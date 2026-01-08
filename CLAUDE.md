# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a performance management training repository containing documentation and training materials in Markdown format.

The purpose of the project is to create an online website with text, visual, and auditory components - as well as interactive graphics and exercises - to train state government employees on performance management concepts and skills.

## Development

This site uses MkDocs with Material theme. To preview locally:

```bash
# First time setup
pip install -r requirements.txt

# Start local server (does not affect public site)
mkdocs serve
```

Then open http://localhost:8000/

To deploy to GitHub Pages:
```bash
mkdocs gh-deploy
```

## Repository Structure

- `index.md` - Home page and table of contents
- `modules/` - Training module content
- `mkdocs.yml` - MkDocs site configuration

## Content Guidelines

- Training materials use Markdown with embedded HTML/CSS/JS for interactive elements
- Interactive components (quizzes, diagrams) are self-contained with scoped styles
- Navigation is configured in `mkdocs.yml` under the `nav` section
