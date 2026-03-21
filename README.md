# Static Website Project

This repository contains a static website based on a Tooplate template. I updated the content, added a GitHub Actions workflow, and deployed the site with GitHub Pages.

## Live Links

- Live website: https://adahmo.github.io/github-Action-proj2/
- Repository: https://github.com/adahmo/github-Action-proj2

## Overview

This project covers three tasks:

1. Update a static frontend project.
2. Add a CI/CD workflow with GitHub Actions.
3. Prepare the repository for review with screenshots.

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Bootstrap
- jQuery
- Git and GitHub
- GitHub Actions
- GitHub Pages

## CI/CD Workflow Summary

Workflow file: [.github/workflows/ci-cd.yml](.github/workflows/ci-cd.yml)

The workflow does three things:

1. Triggered by push events and manual workflow dispatch.
2. Checks that the required static site files and folders exist.
3. Deploys the site to GitHub Pages from the default branch.

## Repository Structure

```text
.
|-- .github/
|   `-- workflows/
|       `-- ci-cd.yml
|-- css/
|-- font-awesome-4.5.0/
|-- img/
|-- js/
|-- slick/
|-- docs/
|   |-- screenshots/
|   |   `-- README.md
|-- ABOUT THIS TEMPLATE.txt
|-- index.html
`-- README.md
```

## Local Run Instructions

Option 1

1. Clone the repository.
2. Open index.html in a browser.

Option 2

1. Start a simple local server from the project root:
   ```bash
   python -m http.server 8080
   ```
2. Open http://localhost:8080

## Screenshots

Add screenshots to [docs/screenshots](docs/screenshots) with the exact filenames below:

1. 01-live-homepage-hero.png
2. 02-live-project-highlights.png
3. 03-actions-success-run.png
4. 04-pages-deployment-environment.png
5. 05-repository-file-structure.png
6. 06-mobile-responsive-view.png
7. 07-linkedin-featured-section.png

After you add the files, the image sections below will render automatically.

### Screenshot 1: Live Homepage Hero

![Live homepage hero](docs/screenshots/01-live-homepage-hero.png)

### Screenshot 2: Project Highlights Section

![Project highlights section](docs/screenshots/02-live-project-highlights.png)

### Screenshot 3: GitHub Actions Successful Run

![GitHub Actions successful run](docs/screenshots/03-actions-success-run.png)

### Screenshot 4: GitHub Pages Deployment Environment

![Pages deployment environment](docs/screenshots/04-pages-deployment-environment.png)

### Screenshot 5: Repository File Structure

![Repository file structure](docs/screenshots/05-repository-file-structure.png)

### Screenshot 6: Mobile Responsive View

![Mobile responsive view](docs/screenshots/06-mobile-responsive-view.png)

### Screenshot 7: LinkedIn Featured Section

![LinkedIn featured section](docs/screenshots/07-linkedin-featured-section.png)

## Review Order

1. Open the live website.
2. Review the workflow in [.github/workflows/ci-cd.yml](.github/workflows/ci-cd.yml).
3. Check the Actions tab for deployment runs.
4. Read this README.

## Notes

- Base design source: Tooplate template (Individual - Template 2096).
- Original template notice is retained in [ABOUT THIS TEMPLATE.txt](ABOUT THIS TEMPLATE.txt).
- Changes in this repository focus on content updates, deployment workflow, and project documentation.

## Before Sharing

1. Add your screenshots to [docs/screenshots](docs/screenshots).
2. Confirm all screenshot previews render in this README.
3. Pin this repository in your GitHub profile.
