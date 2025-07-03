# [GitHub Pages Deployment](https://roadmap.sh/projects/ec2-instance)

Write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

The goal of this project is to help you learn the notion of continuous integration and continuous deployment. You will write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.


## Overview

This repository (`gh-deployment-workflow`) contains:
- A minimal `index.html` (“Hello, GitHub Actions!”)  
- A `README.md` explaining the project  
- A GitHub Actions workflow (`deploy.yml`) in `.github/workflows/` that builds and deploys the site to GitHub Pages on every push to `main` **only** if `index.html` was modified.

---

## Requirements

- A GitHub repository named (for example) **`gh-deployment-workflow`**  
- A simple **`index.html`** at the root with your page content  
- A **`.github/workflows/deploy.yml`** defining the deploy workflow  
- Workflow triggers **only** on pushes to `main` that include changes to `index.html`  
- The published site will be available at `https://<username>.github.io/gh-deployment-workflow/`
- Go on the **repo Settings**, **Pages** and select the source as `Github Actions`

---

## Getting Started

1. **Clone** this repo (or create a new one named `gh-deployment-workflow`).
2. Ensure you have an **`index.html`** at the root.
