# dwaynegibbs.github.io

Personal portfolio / resume site built with Jekyll, hosted on GitHub Pages.

## Customize your content

All editable content lives in `_data/` and `_config.yml` — no HTML editing required for the basics:

- `_config.yml` — name, tagline, description, email, GitHub/LinkedIn usernames.
- `_data/experience.yml` — work history / timeline entries.
- `_data/achievements.yml` — certifications and other achievements.
- `_data/projects.yml` — current and previous projects (`status: current | previous`).
- `_data/skills.yml` — grouped skill tags.
- `index.html` — hero summary and about paragraph.
- `assets/resume/2026 Resume dhgibbs.pdf` — resume PDF linked from the "Download Resume" button.

## Run locally

Requires Ruby + Bundler.

```powershell
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## Deploy

GitHub Pages builds this automatically from the `main` branch using Jekyll — just push to `main`.
Repo Settings > Pages should have source set to "Deploy from a branch" > `main` / `(root)`.
