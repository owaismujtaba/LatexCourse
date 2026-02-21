# LaTeX Advanced Course Portfolio

This repository contains a collection of LaTeX projects developed as part of an advanced course. The portfolio showcases various typesetting techniques, ranging from basic formatting to complex academic poster designs.

## Project Structure

- **[Basics/](file:///home/owais/Desktop/LatexCourse/Basics/)**: An introductory guide demonstrating core LaTeX features, including:
    - Text styles (bold, italic, small caps).
    - Font family manipulations.
    - Text rotation and color boxes.
    - Mathematical typesetting and framed environments.
- **[poster/](file:///home/owais/Desktop/LatexCourse/poster/)**: A research poster (A0 size) titled *"Fragmentation Dynamics in Global Trade: G7 vs. BRICS+"*.
    - Uses the `beamerposter` package.
    - Features data-driven visualizations of trade decoupling and network modularity.
    - Implements advanced layout techniques with `tcolorbox` and `multicol`.
- **[presentations/](file:///home/owais/Desktop/LatexCourse/presentations/)**: Beamer slides for project presentations.
- **[Biblo/](file:///home/owais/Desktop/LatexCourse/Biblo/)**: Directory for managing bibliography files and references.

## Getting Started

### Prerequisites

You need a LaTeX distribution installed on your system (e.g., TeX Live, MiKTeX).

### Compilation

To compile the documents, use `pdflatex`. For example, to build the poster:

```bash
cd poster
pdflatex poster.tex
```

For documents with bibliographies, remember to run `bibtex` between `pdflatex` passes.

## Author
**Owais Mujtaba Khanday**  
Network Science & Geopolitics Department