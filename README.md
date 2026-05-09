# Sesha N. Charla's Resume

This repository contains the LaTeX source code and related documents for my professional resume and portfolio.

## Repository Structure

*   **`SeshaCharla_resume.tex`**: The main LaTeX document that aggregates all sections.
*   **`secs/`**: Directory containing individual modular sections of the resume (e.g., `education.tex`, `experience.tex`, `skills.tex`, `academic.tex`, `honors.tex`).
*   **`ltx_core/`**: A Git submodule containing reusable core LaTeX packages, styling, and custom commands.
*   **`CoverLetters/`**: Directory containing various draft and finalized cover letters.
*   **`portfolio_presentations/`**: Contains presentation slide decks used for interviews and portfolio reviews.
*   **`old_stuff/`**: Archived items, including previous versions of the CV, old cover letters, and outdated presentations.

## Requirements

To build the resume from source, you need a working LaTeX distribution such as TeX Live, MiKTeX, or MacTeX.

## Building the Resume

1.  **Clone the repository along with the submodule:**
    ```bash
    git clone --recurse-submodules <repository-url>
    ```
    *If you have already cloned the repository without the submodule, initialize it using:*
    ```bash
    git submodule update --init --recursive
    ```

2.  **Compile the main document:**
    You can compile the PDF using `pdflatex` (or another preferred engine like `latexmk`):
    ```bash
    pdflatex SeshaCharla_resume.tex
    ```
    *(Run the command a second time if necessary to ensure all layout elements and fonts are processed correctly.)*

The compiled output will be `SeshaCharla_resume.pdf`.
