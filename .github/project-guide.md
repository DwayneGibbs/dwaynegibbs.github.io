# Project Guide

This personal portfolio and resume site is built with Jekyll and hosted on GitHub Pages.

## Customize your content

The basic site content can be edited in these files:

- `_config.yml` - name, tagline, description, email, and GitHub/LinkedIn usernames.
- `_data/experience.yml` - work history and timeline entries.
- `_data/education.yml` - education entries.
- `_data/achievements.yml` - certifications and other achievements.
- `_data/projects.yml` - current and previous projects (`status: current | previous`).
- `_data/skills.yml` - grouped skill tags.
- `index.html` - hero summary and about paragraph.
- `assets/resume/2026 Resume dhgibbs.pdf` - resume PDF linked from the "Download Resume" button.

## Run locally

Requires Ruby and Bundler.

```powershell
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploy

GitHub Pages builds the site automatically from the `main` branch using Jekyll. Push changes to `main`.
In repository Settings > Pages, set the source to "Deploy from a branch" > `main` / `(root)`.
