# Dask DataFrame: A Practical Guide

A single-page site covering Dask DataFrame for scalable, parallel data processing in Python.

## What This Covers

- **Installation and setup** of Dask
- **Key features**: parallel computing, out-of-core processing, lazy evaluation, task scheduling
- **Hands-on examples** using a million-row sales dataset (loading, statistics, sorting, grouping, handling missing data)
- **Practical use cases** for data analysis, ML preprocessing, and real-time processing

## Live Site

[https://suma2006.github.io/Dask-dataframe/](https://suma2006.github.io/Dask-dataframe/)

## Tech Stack

- [Quarto](https://quarto.org/) for static site generation
- Python / [Dask](https://www.dask.org/) for code examples
- GitHub Pages for hosting
- GitHub Actions for automated deployment

## Local Development

Make sure [Quarto](https://quarto.org/docs/get-started/) is installed, then:

```bash
# Preview with live reload
quarto preview

# Build the site
quarto render
```

The rendered output goes to the `docs/` directory.

## Project Structure

```
.
├── _quarto.yml       # Quarto site configuration
├── index.qmd         # Main content (the entire site)
├── images/           # Screenshots and figures
├── styles.scss       # Custom styles
├── .github/
│   └── workflows/
│       └── publish.yml   # GitHub Actions deployment
└── .nojekyll         # Disables Jekyll on GitHub Pages
```

## Author

Sumanjali
