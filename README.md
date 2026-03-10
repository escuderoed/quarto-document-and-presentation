# Quarto Document and Presentation

This repository showcases a **Quarto-based workflow** used to generate both an **HTML document** and an **HTML presentation** from source files.

The project was developed as an exploration of Quarto beyond dashboards, using a course-based exercise as a starting point and adapting it into a more practical reporting workflow.

## Why this project matters

This project highlights how code-driven publishing can be used to create:

- **Structured HTML documents**
- **Presentation-ready HTML slides**
- **Reusable styling with custom CSS**
- **Clean and shareable outputs from a single tool**

It is a small but practical example of how Quarto can support analytical communication in both document and presentation formats.

## Repository contents

This repository includes:

- `cyclistic-presentation.qmd` — Quarto source for the HTML presentation
- `cyclistic-document.qmd` — Quarto source for the HTML document
- `reveal_refined.css` — Custom CSS file used to style the presentation
- `styles.css` — Custom CSS file used to style the HTML document
- Rendered HTML outputs in the `output/` folder

## Project structure

```text
.
├─ README.md
├─ .gitignore
├─ cyclistic-presentation.qmd
├─ `cyclistic-document.qmd`
├─ reveal_refined.css
├─ styles.css
└─ output/
   ├─ cyclistic-presentation.html
   └─ cyclistic-document.html
