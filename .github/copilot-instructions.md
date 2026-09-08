# Copilot Instructions

## Workspace Purpose

This repository is Dwayne Gibbs' personal portfolio and resume website. It is a single-page Jekyll site deployed by GitHub Pages from the `main` branch.

## Technology and Structure

- Use Jekyll and Liquid conventions compatible with GitHub Pages.
- `_layouts/default.html` provides the page shell.
- `_includes/head.html`, `_includes/header.html`, and `_includes/footer.html` contain shared markup.
- `assets/css/main.scss` imports the partials in `_sass/`.
- `assets/js/main.js` contains client-side behavior.
- Keep the existing clean, minimal, light visual style and single-page anchor navigation.

## Content Ownership

Prefer content changes in the data and configuration files rather than hard-coding entries in templates:

- `_config.yml`: site identity, biography metadata, and social links.
- `_data/experience.yml`: work-history timeline.
- `_data/achievements.yml`: certifications and achievements.
- `_data/projects.yml`: portfolio projects; use `status: current` or `status: previous`.
- `_data/skills.yml`: grouped skills.
- `index.html`: hero summary and about copy.

## Editing Guidelines

- Keep changes focused and preserve the existing Jekyll data schema and Liquid patterns.
- Use ASCII text unless existing content requires otherwise.
- Do not edit generated `_site/` files; update source files and let Jekyll rebuild them.
- Do not add a GitHub Actions deployment workflow: GitHub Pages builds this repository natively.
- For visual changes, preserve responsive behavior and the established component styles.

## Validation

- When Ruby and Bundler are available, validate site changes with `bundle exec jekyll serve` or `bundle exec jekyll build`.
- Ruby/Bundler may not be installed locally, so report that limitation when a Jekyll build cannot run.
