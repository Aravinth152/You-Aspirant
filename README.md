# Karka AI & Tech Academy

A static landing page for Karka AI & Tech Academy, built with HTML and Tailwind CSS utility classes.

## Project structure

- `index.html` — complete page that can be opened directly in a browser
- `components/` — reusable HTML fragments corresponding to page sections
- `assets/images/` — local images and site assets

The component files are reference fragments; browsers do not import them automatically. When editing a fragment, copy the updated section into `index.html` as well.

## Run locally

Open `index.html` in a modern browser with an internet connection. Tailwind CSS and Font Awesome are loaded from CDNs.

## Forms

The consultation and newsletter forms are demo-only. They use browser validation and show a confirmation message, but do not submit, send, log, or store information. Connect a backend or form provider before using them to collect leads.

## Publish with GitHub Pages

This is a static site and can be published from the repository root:

1. Push the project to a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.

The page uses external CDN and Unsplash resources, so those resources require network access when the published site is viewed.
