# PhD Research Masterbook

## Project Structure
- `main.tex`: Primary document that compiles the entire masterbook
- `config.tex`: Global configuration and package imports
- `chapters/`: Individual chapter files
- `bibliography/`: BibTeX reference files
- `images/`: Figures and visualizations
- `appendices/`: Additional supporting materials

## Setup Instructions
1. Ensure you have a full LaTeX distribution installed (e.g., TeX Live)
2. Use a LaTeX editor like TeXstudio or VS Code with LaTeX Workshop extension
3. Compile using `pdflatex` or `latexmk`

## Recommended Workflow
- Update individual chapter files as your research progresses
- Maintain a consistent commit history in your version control system
- Regularly backup your bibliography and research notes

## Compilation
```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Tips
- Use `\todo{}` for tracking pending tasks
- Update bibliography regularly
- Keep your file structure organized