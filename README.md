# CAM Modern LaTeX Project

This repository contains a LaTeX project for creating documents using the `cam-modern` class. Below are the instructions to set up the environment and compile the document.

## Prerequisites

Ensure the following tools are installed on your system:

1. **Tectonic**: A modern LaTeX compiler.
   - Installation: Follow the instructions at [Tectonic Installation](https://tectonic-typesetting.github.io/en-US/install.html).

2. **Biber**: A bibliography processor required for `biblatex`.
   - Installation: Download the latest version from the [Biber GitHub Releases](https://github.com/plk/biber/releases) and follow the installation instructions.

## Files in the Repository

- `main.tex`: The main LaTeX file.
- `CAM-MODERN.cls`: The class file for the document.
- `bibliography_zotero.bib`: The bibliography file.
- `ucam-logo-colour-preferred.eps`: An EPS file used in the document.

## Compilation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/p3jitnath/cam-modern.git
   cd cam-modern
   ```

2. Compile the document using Tectonic:
   ```bash
   tectonic main.tex
   ```

3. If the bibliography is not processed, run Biber:
   ```bash
   biber main
   ```

4. Recompile the document with Tectonic:
   ```bash
   tectonic main.tex
   ```

5. The output PDF will be generated as `main.pdf`.

## Notes

- Ensure that `biber` is in your system's PATH.
- If you encounter any issues, verify that all required packages are included in the LaTeX file.

## License

This project is based on the `CUP-JNL-DTM` class and follows the same licensing terms, which is the Creative Commons CC BY 4.0 license. The template is derived from the [CUP Data Template](https://www.overleaf.com/latex/templates/cup-data-template/kwrskzvmfxbq). Please refer to the original license of `CUP-JNL-DTM` for details.