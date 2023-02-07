# Wissenschaftliches Arbeiten an Lehrstuhl und Juniorprofessur für Kommunikationswissenschaft der FAU Erlangen Nürnberg

## Link to page
You can view the page [here](https://faucommsci.github.io/wissenschaftliches_arbeiten/leitfaden_book/index.html)

## Notes for editing these documents
- The css theme is in the folder "theme", the file is named "theme.scss"
    - **List of custom classes**:
        - `.download`: Add this class to a  `<span>` or `<a>` tag to get a download button after the text. 
        - `.box`: Place text within a `<div>` Use to get text formatted like a figure, e.g. for APA-examples
        . `.notes`: Makes text for notes smaller below a figure or table, adds "Hinweis. " in bold
        - Please update this list with any new, non-cosmetic classes you add.
    - Headings at level 4 (h4) automatically get a dot placed after them and following paragraphs continue on the same line.
- All images for the "leitfaden_book"-output are located in the "leitfaden/img"-folder. Please store all images there or in sub-folders of this folder
- Rendering:
    - **To render all output formats write in the terminal (not console): `quarto render`**
    - This is tested in RStudio opening the project-file "wissenschaftliches_arbeiten.Rproj" and using the terminal to render. Other methods may lead to issues with relative paths.
