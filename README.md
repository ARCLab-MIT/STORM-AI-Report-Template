# Storm AI Technical Report Template


## Overview  
This repository provides a LaTeX template (`storm-ai_report.cls`) and example driver (`main.tex`) for preparing Phase 2 technical reports in the Storm AI Challenge. It includes predefined boxes for title, authors, abstract, participants, scoring equations, and a structured report outline.

## Getting Started  
1. **Clone or use this template repository**
   - Click the "Use this template" button on GitHub to create your own repository based on this template
   - Alternatively, you can clone the repository directly using:
     ```
     git clone https://github.com/ARCLab-MIT/STORM-AI-Report-Template.git
     ```
   - **Import to Overleaf**: 
     - Go to [Overleaf](https://www.overleaf.com/)
     - Click "New Project" → "Import from GitHub"
     - Connect your GitHub account if prompted
     - Select this repository from the list
     - Select LuaLaTex as the compiler in the side menu.

2. **Edit the driver** (`main.tex`)  
   - Update `\headerbox{== Title ==}`  
   - Set `\authordate{== Team ==}{<Date>}`  
   - Fill in the `participantbox` with your team's members  
   - Replace placeholder text in `\abstractbox{Abstract}{…}`  
   - Customize or remove example sections as needed  

   👉 **Use [Overleaf](https://www.overleaf.com/)** to edit and compile this report. No local setup is needed or supported.  
   ✅ **Set the compiler to "LuaLaTeX"** under Overleaf's **Project Settings**.
   
3. **Compile to PDF**  
   On Overleaf, simply click **Recompile**. Make sure **LuaLaTeX** is selected as the compiler.
## Directory Structure
```
├── storm-ai_report.cls            # Custom LaTeX class (not necessary to modify)
├── main.tex                       # Example driver with placeholders
├── references.bib                 # BibTeX file where you should add you citations
├── STORM_AI_Report_Template.pdf   # Template rendered
├── figures/                       # (Optional) images and plots you want to add
└── README.md                      # This file
```
## Usage Tips  
- **Deadline**: Phase 2 reports are due **May 26, 2025, at 23:59:59 EDT**  
- **Page limit**: Maximum **4 pages**, including figures but excluding references  
- **Bibliography**: Add entries to `references.bib` and cite them using `\cite{...}`  
- **Extending**: You may add custom sections or environments.

---

For questions, open an issue or contact the Storm AI Challenge Organizers at **ai_challenge@mit.edu**.
