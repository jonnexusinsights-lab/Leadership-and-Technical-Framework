# Leadership and Technical Framework

This repository contains the source code for the **Management Technical Knowledge Framework (MTKF)**, **Leadership Skills Framework**, and **Standard Operating Procedures (SOP)**.

## Project Structure

The project is structured as a modular LaTeX document:

- **`main.tex`**: The root document file.
- **`config/preamble.tex`**: LaTeX configuration and packages.
- **`chapters/`**: Content files.
  - **`mtkf/`**: Management Technical Knowledge Framework chapters.
  - **`leadership.tex`**: Leadership Skills Framework wrapper.
  - **`sop.tex`**: Standard Operating Procedure wrapper.
- **`references.bib`**: Bibliography data.

## Compilation

To compile the document, you need a LaTeX distribution (like MiKTeX or TeX Live) and `latexmk`.

Run the following command in the root directory:

```bash
latexmk -pdf main.tex
```

This will generate `main.pdf`.

## Frameworks Included

1.  **Management Technical Knowledge Framework (MTKF)**
    - AI & Machine Learning
    - Data & Analytics
    - Software Engineering
    - Integration & Synergy
    - Management Tools
    - Validation

2.  **Leadership Skills Framework**
    - (In development)

3.  **Standard Operating Procedure**
    - (In development)
