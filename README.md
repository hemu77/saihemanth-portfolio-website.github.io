# saihemanth-portfolio-website.github.io

This repository contains a simple static personal portfolio website built with HTML and CSS.

## Site Structure

The site is organized as a small multi-page static website:

- `index.html`: landing page with profile intro and social links
- `about.html`: background/about page
- `project.html`: project-links page
- `assets/css/style.css`: shared styling
- `assets/css/about.css`: styling for the about page
- `assets/css/project.css`: styling for the projects page

## What The Site Shows

The current site presents:

- a short personal introduction
- links to GitHub, email, and Instagram
- an about page with background details
- a projects page linking out to selected work and profiles

## Local Preview

Because this is a plain static site, you can preview it locally with any simple web server. For example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` in a browser from the repository root.

## Notes

- This repo is static only. There is no build step or framework dependency.
- Some page metadata and template remnants suggest the site was adapted from an earlier template, which is normal for a small personal site.
