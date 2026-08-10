---
title: 5A Scholarly Search
---

# 5A Scholarly Search

A university scholarly-database and search platform for managing and analysing academic papers and research data.

## Technical approach

- **Back end:** Python and Flask
- **Front end:** React, TypeScript, and Vite
- **Document processing:** PyMuPDF
- **Analysis and visualisation:** scikit-learn and Matplotlib
- **Tooling:** `uv` for Python dependencies and `pnpm` for JavaScript dependencies

## Functional scope

The application provides a web interface for browsing and searching academic documents. It includes a PDF-ingestion and processing pipeline, scaffolding for machine-learning-assisted analysis, and data-visualisation components. Configuration is supplied through environment variables in `.env` files.

## Engineering focus

The project uses separate Python and JavaScript dependency-management workflows. That structure keeps the Flask service and React interface independently reproducible while they work together as one application.
