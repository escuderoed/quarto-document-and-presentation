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
├─ cyclistic-document.qmd
├─ reveal_refined.css
├─ styles.css
└─ output/
   ├─ cyclistic-presentation.html
   └─ cyclistic-document.html
```
## Tools used

- **Quarto**
- **R**
- **HTML**
- **Custom CSS**
- **Markdown-based technical writing**

## Data source

The analysis is based on the public Divvy trip history dataset.

The raw data files are **not included in this repository** in order to keep the project lightweight and focused on the reporting workflow.

Source: `https://divvy-tripdata.s3.amazonaws.com/index.html`

## How to render

Make sure Quarto is installed, then run:

```bash
quarto render cyclistic-presentation.qmd
quarto render cyclistic-document.qmd
```

## Notes

Part of the motivation for this project came from a learning exercise, but the repository is presented here as a practical example of using Quarto for reproducible documents and presentations.

## Author

Eduardo García Escudero
