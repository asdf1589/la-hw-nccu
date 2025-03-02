# Linear Algebra Homework

This project contains LaTeX files for linear algebra homework assignments. Below is a brief overview of the project structure and instructions on how to compile the documents.

## Project Structure

- **src/**: Contains all the LaTeX source files.
  - **main.tex**: The main LaTeX document that includes the preamble and references to the sections.
  - **sections/**: Directory containing individual sections of the homework.
    - **introduction.tex**: Introduction section.
    - **chapter1.tex**: Content for Chapter 1.
    - **chapter2.tex**: Content for Chapter 2.
    - **conclusion.tex**: Conclusion section.
- **images/**: Directory for storing images or figures used in the LaTeX document.
- **bibliography.bib**: Bibliography entries in BibTeX format for citations.

## Compilation Instructions

To compile the LaTeX documents, follow these steps:

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Open a terminal and navigate to the `src` directory.
3. Run the following command to compile the main document:
   ```
   pdflatex main.tex
   ```
4. If you have citations, run:
   ```
   bibtex main
   ```
5. Finally, run `pdflatex main.tex` twice more to ensure all references are updated.

## Additional Information

Feel free to add any images to the `images` directory and reference them in the LaTeX files as needed. Make sure to update the `bibliography.bib` file with any new references you use in your homework.