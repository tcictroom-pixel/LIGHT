# LIGHT Project

This repository contains the LIGHT website and supporting content files.

## Custom Copilot Agent

The workspace includes a custom agent for GitHub Copilot Chat:

- `LIGHT Project Assistant` — defined in `.github/agents/light-project.agent.md`

### Purpose

- Improve HTML page structure, accessibility, and copy quality
- Review and refine text in `YEAR1.txt`, `YEAR2.txt`, and `YEAR3.txt`
- Keep suggestions focused on the workspace

### How to use

Open GitHub Copilot Chat in this repository and select the `LIGHT Project Assistant` agent for website or content-related tasks.

## Publishing

A GitHub Actions workflow has been added at `.github/workflows/publish-pages.yml`. After pushing changes to the `main` branch, GitHub Pages will deploy the repository root as a static website.
