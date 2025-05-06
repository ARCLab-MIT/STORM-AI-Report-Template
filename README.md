# Storm AI Technical Report Template


## Overview  
This repository provides a LaTeX template (`storm-ai_report.cls`) and example driver (`main.tex`) for preparing Phase 2 technical reports in the Storm AI Challenge. It includes predefined boxes for title, authors, abstract, participants, scoring equations, and a structured report outline.

## Features  
- **Custom class** (`storm-ai_report`) optimized for A4, 11 pt  
- **Participant box** environment with `\speaker{…}{…}`  
- **Header** and **abstract** boxes  
- **Preformatted scoring scheme** (Phase I & II metrics)  
- **Report template** sections (Introduction, Data, Methods, Results, etc.)  
- Bibliography support via `biblatex`

## Prerequisites  
- TeX distribution (TeX Live, MiKTeX, etc.)  
- `biblatex` and Biber  
- Standard LaTeX packages: `xcolor`, `hyperref`, `fontawesome`, etc.

## Getting Started  
2. **Edit the driver** (`main.tex`)  
   - Update `\headerbox{== Title ==}`  
   - Set `\authordate{== Team ==}{<Date>}`  
   - Fill in the `participantbox` with your team’s members  
   - Replace placeholder text in `\abstractbox{Abstract}{…}`  
   - Customize or remove example sections as needed  

   👉 **Use [Overleaf](https://www.overleaf.com/)** to edit and compile this report. No local setup is needed or supported.  
   ✅ **Set the compiler to "LuaLaTeX"** under Overleaf’s **Project Settings**.
   
3. **Compile to PDF**  
   On Overleaf, simply click **Recompile**. Make sure **LuaLaTeX** is selected as the compiler.
## Directory Structure
```
├── storm-ai_report.cls     # Custom LaTeX class
├── main.tex               # Example driver with placeholders
├── references.bib         # BibTeX file for citations
├── figures/               # (Optional) images and plots
└── README.md              # This file
```
## Usage Tips  
- **Deadline**: Phase 2 reports are due **May 26, 2025, at 23:59:59 EDT**  
- **Page limit**: Maximum **4 pages**, including figures but excluding references  
- **Bibliography**: Add entries to `references.bib` and cite them using `\cite{...}`  
- **Extending**: You may add custom sections or environments. However, if you remove the scoring equations, **you must include them in an appendix**.

---

For questions, open an issue or contact the Storm AI Challenge Organizers at **ai_challenge@mit.edu**.
