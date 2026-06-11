# Dask DataFrame: A Practical Guide

A Quarto-based blog covering Dask DataFrame for scalable, parallel data processing in Python.

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
├── _quarto.yml              # Quarto site configuration
├── index.qmd                # Landing page
├── blog.qmd                 # Blog listing page
├── styles.scss              # Custom styles
├── posts/
│   └── dask-dataframe/
│       ├── index.qmd        # Main blog post
│       └── images/          # Screenshots and figures
├── .github/
│   └── workflows/
│       └── publish.yml      # GitHub Actions deployment
└── .nojekyll                # Disables Jekyll on GitHub Pages
```

## Author

Sumanjali
