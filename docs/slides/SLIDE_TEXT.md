# Slide Text

Use the Slide Copy text directly on each slide.
Use the Short Note text as speaker notes.
Screenshot instructions tell you exactly what to capture and where to place it on the slide.

---

## Slide 1 — Cover

Title: Static Website Project

Subtitle: HTML · CSS · JavaScript · GitHub Actions · GitHub Pages

Slide Copy:
A static website built from an HTML template, updated with real content,
deployed automatically using GitHub Actions, and published on GitHub Pages.

Screenshot to take:
- Open the live site at https://adahmo.github.io/github-Action-proj2/
- Scroll to the hero section (top of the page)
- Take a full-browser screenshot at 1280x800
- Save as: ../screenshots/08-slide-deck-cover.png

Where to place the screenshot on the slide:
- Full-width background or right-hand panel alongside the title text

Short Note:
This is a small but complete project. The goal was to take a template, make it mine, and deploy it properly.

---

## Slide 2 — Why This Project

Title: Problem and Approach

Slide Copy:
Problem:
Most small frontend projects are pushed to GitHub without a working deployment,
documentation, or anything that helps a reviewer understand the work.

Approach:
- Update the site content so it represents the project clearly
- Add a CI/CD workflow so the site deploys automatically on every push
- Organize the repository so a reviewer can follow the work quickly

Screenshot to take:
- No screenshot needed for this slide
- Use a simple two-column layout: Problem on the left, Approach bullets on the right

Short Note:
This slide explains why the project is structured the way it is, not just what was built.

---

## Slide 3 — Stack

Title: Architecture and Stack

Slide Copy:
Frontend:
HTML5, CSS3, JavaScript, Bootstrap 4, jQuery, Slick carousel, Magnific Popup

Delivery:
GitHub repository → GitHub Actions → GitHub Pages

No build step. The workflow validates the file structure and deploys the site directly.

Screenshot to take:
- Go to the repository on GitHub: https://github.com/adahmo/github-Action-proj2
- Expand the file tree in the left panel or Code tab
- Take a screenshot showing the folder structure (.github, css, js, img, slick, docs, index.html)
- Save as: ../screenshots/05-repository-file-structure.png

Where to place the screenshot on the slide:
- Right side of the slide, next to the stack list on the left

Short Note:
The stack is straightforward. The interesting part is that the delivery is automated from a push.

---

## Slide 4 — CI/CD Pipeline

Title: CI/CD Workflow

Slide Copy:
Trigger:    Push to the default branch (or manual run)
Job 1 - CI: Check that index.html, css/, js/, img/, slick/ are present
Job 2 - Deploy: Upload site artifact → Deploy to GitHub Pages

Workflow file: .github/workflows/ci-cd.yml

Screenshot to take:
- Go to https://github.com/adahmo/github-Action-proj2/actions
- Click on a completed workflow run that shows both jobs passing (green ticks)
- Take a screenshot of the run summary showing the two jobs: Validate and Deploy
- Save as: ../screenshots/03-actions-success-run.png

Where to place the screenshot on the slide:
- Right side or bottom half, showing the two green jobs clearly

Short Note:
The two-job structure separates validation from deployment. If the file check fails, the deploy never runs.

---

## Slide 5 — Deployment Proof

Title: Live on GitHub Pages

Slide Copy:
The site deploys to GitHub Pages from the default branch.
Every push triggers the workflow and updates the live URL.

Live URL: https://adahmo.github.io/github-Action-proj2/

Screenshot to take:
- Go to https://github.com/adahmo/github-Action-proj2/deployments
  OR go to repository Settings > Pages
- Take a screenshot showing the Pages URL, the "Active" badge, and the environment name
- Save as: ../screenshots/04-pages-deployment-environment.png

Where to place the screenshot on the slide:
- Centre or right side, showing the Pages environment details clearly

Short Note:
The deployment environment confirms the site is live and linked to the repository. Anyone can click the URL.

---

## Slide 6 — Website Demo

Title: Website Screenshots

Slide Copy:
The template was updated with project-specific content:
- Hero section describes the project and links to GitHub
- Second section lists the stack and workflow
- Third section explains the CI/CD setup
- Final section links to GitHub, the live site, and LinkedIn

The layout is responsive and works on mobile.

Screenshots to take:

Screenshot A — Desktop hero section:
- Open https://adahmo.github.io/github-Action-proj2/ at full-screen width
- Capture the hero section with the title and both buttons visible
- Save as: ../screenshots/01-live-homepage-hero.png

Screenshot B — Project highlights section:
- Scroll down to the three-column section (Deploy / Docs / Review)
- Capture the full row of three cards
- Save as: ../screenshots/02-live-project-highlights.png

Screenshot C — Mobile view:
- Open browser DevTools (F12) and set device to iPhone 12 or similar (390x844)
- Reload the page and capture the hero section
- Save as: ../screenshots/06-mobile-responsive-view.png

Where to place screenshots on the slide:
- A grid layout: Screenshot A large on the left, B and C stacked on the right

Short Note:
This slide shows the actual product. The content on the page reflects the project, not the original template.

---

## Slide 7 — LinkedIn and GitHub Profile

Title: Where the Project Lives

Slide Copy:
GitHub profile: repository is pinned on the profile page
LinkedIn: project is added to the Featured and Projects sections
Both link directly to the live site and the repository

Screenshot to take:
- Update LinkedIn Profile → scroll to Featured section
- Pin the live site URL and the GitHub repository URL as Featured items
- Take a screenshot of the LinkedIn Featured section showing both items
- Save as: ../screenshots/07-linkedin-featured-section.png

Where to place the screenshot on the slide:
- Full-width or right side, showing the LinkedIn card with the site thumbnail

Short Note:
Adding this to LinkedIn Featured puts it at the top of your profile. It is the first thing a recruiter sees after your headline.

---

## Slide 8 — Learnings and Next Steps

Title: What I Learned and What Comes Next

Slide Copy:
What I learned:
- How to write a GitHub Actions workflow from scratch
- How to deploy a static site with GitHub Pages using workflow artifacts
- How to organize a repository and documentation so a reviewer can follow the work

Next steps:
- Add an HTML linter to the CI job (HTMLHint or similar)
- Add an accessibility check (axe-core or Lighthouse CI)
- Set a custom domain for the GitHub Pages site
- Improve the site content further with personal branding

Screenshot to take:
- No screenshot needed for this slide
- Use a two-column layout: What I Learned on the left, Next Steps on the right

Short Note:
The next steps are concrete. They are not suggestions. They are the next things that would make this project better.

---

## How to Upload These Slides to LinkedIn

### Step 1 — Prepare the file

Export your slide deck as PDF from PowerPoint or Google Slides.
Save it as: docs/slides/engineer-review-deck.pdf

PDF works best on LinkedIn because it renders as a swipeable document card in the feed.

### Step 2 — Upload as a LinkedIn post (Document Post)

1. Log in to LinkedIn.
2. Click the Start a post box at the top of your feed.
3. Click the More icon (...) inside the post box if you do not see the document option, or look for the document/page icon directly.
4. Select Add a document.
5. Upload your PDF file (engineer-review-deck.pdf).
6. Add a title for the document, for example: Static Website CI/CD Project.
7. Write the post text in the body. Use this as a starting point:

---

Post text (paste this):

I recently deployed a static website using GitHub Actions and GitHub Pages.

Here is a short walkthrough of what I built:
- Updated a static HTML template with project-specific content
- Added a GitHub Actions workflow to validate and deploy on push
- Organized the repository with a README, screenshots, and slide material

Live site: https://adahmo.github.io/github-Action-proj2/
Repository: https://github.com/adahmo/github-Action-proj2

Skills used: HTML, CSS, JavaScript, GitHub Actions, GitHub Pages, Git

---

8. Click Post.

### Step 3 — Add to LinkedIn Featured section

1. Go to your LinkedIn profile.
2. Scroll to the Featured section, or click Add profile section > Recommended > Featured.
3. Click the + button.
4. Choose Add a link.
5. Paste the live site URL: https://adahmo.github.io/github-Action-proj2/
6. Add a title: Static Website Project
7. Add a short description: Static site deployed with GitHub Actions and GitHub Pages.
8. Save.
9. Repeat steps 3 to 8 and add the GitHub repository URL as a second featured item.

### Step 4 — Add to LinkedIn Projects section

1. Go to your LinkedIn profile.
2. Click Add profile section > Additional > Projects.
3. Fill in the fields:

   Project name: Static Website CI/CD Project
   Date: March 2026
   Project URL: https://adahmo.github.io/github-Action-proj2/
   Description:
   Built and deployed a static website using HTML, CSS, and JavaScript.
   Configured a GitHub Actions workflow to validate files and deploy to GitHub Pages on push.
   Repository includes documentation, screenshots, and a review slide deck.

4. Save.

### Tips

- Tag your post with skills like #GitHub #CICD #WebDevelopment #GitHubActions #HTML
- Post in the morning on a weekday for better reach
- If someone comments, reply within 24 hours to increase engagement