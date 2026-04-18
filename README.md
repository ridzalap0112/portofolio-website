# Ridzal Ade Putera Portfolio

Personal portfolio website for Ridzal Ade Putera. The site highlights professional experience, skills, selected projects, education, certifications, and contact links.

## Structure

```text
portfolio-website/
  index.html
  assets/
    .gitkeep
  README.md
  .gitignore
  .nojekyll
```

## Run Locally

Open `index.html` directly in a browser.

## Deploy With GitHub Pages

1. Create a new GitHub repository, for example `portfolio-website`.
2. Push this folder to the repository.
3. Open the repository settings on GitHub.
4. Go to **Pages**.
5. Set the source to the `main` branch and the root folder.
6. Save and wait for GitHub Pages to publish the site.

## Notes

- The main page is intentionally a single static HTML file, so it can be hosted without a build step.
- The contact email uses a direct `mailto:` link.
- The photo upload button stores the selected image only in the visitor's browser through `localStorage`.
