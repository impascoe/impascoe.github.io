---
title: My Projects
hide:
  - navigation
  - toc
---

# Projects

Here are some of the key projects I've worked on. Each represents different aspects of my skills and interests in software development.

---

## 5A Scholarly Search
A university scholarly database and search platform for managing and analyzing academic papers and research data.

**Technologies Used:**

- Python (Flask backend)
- React + TypeScript + Vite (frontend)
- PyMuPDF (PDF parsing)
- scikit-learn (machine learning tooling)
- Matplotlib (data visualization)
- uv (Python environment & dependency management)
- pnpm (JavaScript dependency management)

**Key Features:**

- Web interface for browsing and searching academic documents
- PDF ingestion and processing pipeline
- Machine learning-assisted analysis scaffolding
- Data visualization components
- Environment-driven configuration via `.env`
- Dual ecosystem dependency management (Python + JS)

---

## Zirconium (.zr)

**Repository:** [impascoe/Zirconium](https://github.com/impascoe/Zirconium)

An experimental, pre‑alpha programming language implemented in Zig. Current focus is a minimal end-to-end frontend pipeline (tokenizer → parser → AST + debug output) for very small function-based programs.

**Technologies Used:**

- Zig
- Compiler front-end design (tokenizer, parser, AST)
- Custom CLI tooling
- Early unit tests

**Current Capabilities:**

- Tokenizes identifiers, unsigned integer literals, and basic symbols
- Parses simple function declarations (`func <name>() <return_type> { ... }`)
- Supports return statements with integer literals
- Builds an AST and prints a debug representation
- Basic parser tests via `zig build test`

**Planned / Roadmap Highlights:**

- Expression grammar (arithmetic)
- Function parameters
- Better error diagnostics with source spans
- Symbol table & basic type system scaffold
- Tree-walk interpreter prototype
- Improved memory management (arena allocation)

**Why It Matters:**

It is a learning and exploration vehicle for language design, parsing strategies, diagnostics, and future experimentation with execution models (interpreter, VM, or code generation).

---

## WeatherWise CLI 

**Repository:** [impascoe/weatherwise-cli](https://github.com/impascoe/weatherwise-cli)

A university project for a weather data and analysis project combining Python, weather APIs, data visualization, and AI-assisted development workflows.

**Technologies Used:**

- Python
- Jupyter Notebook / JupyterLab
- OpenWeatherMap API
- Plotly (visualizations)
- Local AI tooling (Ollama integration)
- Standard Python packaging & requirements management

**Key Features:**

- Ready-to-run `starter_notebook.ipynb` for iterative development
- Structured assignment scaffold with reflection and submission folders
- Weather data retrieval via OpenWeatherMap
- Data visualization capability (e.g. Plotly integration)
- Optional AI-assisted experimentation (via local Ollama instance)
- Clear environment setup instructions for local or Colab workflows

**Folder Highlights:**

- `starter_notebook.ipynb` – Main interactive analysis environment
- `ASSIGNMENT.md` – Specification / guidance
- `ai-conversations/` – Space to store AI interaction transcripts
- `submission/reflection.md` – Reflection artifact

**Usage Flow Overview:**

1. Install dependencies from `requirements.txt`
2. Supply an OpenWeatherMap API key (env var or inline)
3. Launch Jupyter (local or Colab)
4. Run cells to fetch, explore, and visualize weather data

**Educational Value:**

Encourages disciplined, reproducible exploratory workflows while integrating modern tooling (APIs + AI) into a lightweight academic or prototype project setting.

---

## Online Will-Producing Website
A collaborative project focused on developing a web platform for creating legal wills online.

**Technologies Used:**

- React.js (Frontend)
- Golang (API Development)
- Database Integration
- User Authentication

**Key Features:**

- Document generation system
- Secure data handling
- User-friendly interface
- Legal compliance

---

## Donation Tracking Application

A web application for tracking donations made to Australian charitable organizations.

**Technologies Used:**

- Python (API Development)
- NoSQL Database
- Web Frontend
- Data Visualization

**Key Features:**

- Donation analytics
- Organization profiles
- Reporting system
- User account management

---

## Smash Return

A mobile idle game with the inspiration from keyboard keys.

**Technologies Used:**

- Kotlin (Android Development)
- Game Development
- Mobile App Design

---

## ZMM 2.0 (Archived)

**Repository:** [impascoe/zmm-2.0](https://github.com/impascoe/zmm-2.0)

A modern personal C compiler written in Zig for educational purposes.

**Technologies Used:**

- Zig Programming Language
- Compiler Design

**Key Features:**

- Lexical analysis
- Syntax parsing
- Compiles to x86-64 assembly

---

## Dotfiles

**Repository:** [impascoe/dotfiles](https://github.com/impascoe/dotfiles)

My personal configuration files for development environments.

**Technologies Used:**

- Shell Scripting
- Linux Configuration
- Development Environment Setup

**Key Features:**

- Customized development environment
- Productivity enhancements
- Cross-platform configurations

---

## Other Projects

I'm constantly working on new ideas and contributing to various development initiatives. Check out my [GitHub profile](https://github.com/impascoe) for the latest updates on what I'm building.

---

Interested in collaborating on a project? [Contact me](mailto:isaacmpascoe@gmail.com)!
