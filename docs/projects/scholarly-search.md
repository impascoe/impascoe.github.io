---
title: Scholarly Searcher
---

# Scholarly Searcher

[Repository: impascoe/scholarly-searcher](https://github.com/impascoe/scholarly-searcher)

A Flask dashboard for managing and analysing academic papers and research data.

## Technical approach

- **Back end:** Python and Flask
- **Front end:** React, TypeScript, and Vite
- **Document processing:** PyMuPDF
- **Analysis and visualisation:** scikit-learn and Matplotlib
- **Tooling:** `uv` for Python dependencies and `pnpm` for JavaScript dependencies

## Functional scope

The application provides a web interface for browsing and searching academic documents. It includes a PDF-ingestion and processing pipeline, scaffolding for machine-learning-assisted analysis, and data-visualisation components. Configuration is supplied through environment variables in `.env` files.

## Engineering focus

Python and JavaScript dependencies are managed separately. The Flask service and React interface can therefore be installed and run through their own package workflows.
