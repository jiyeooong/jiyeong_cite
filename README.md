# Jiyeong Kim — Academic Homepage

Personal academic website of Jiyeong Kim, built with the
[al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

- **Live site:** https://jiyeooong.github.io/jiyeong_cite
- **Content to edit:**
  - `_pages/about.md` — bio, profile photo, affiliation
  - `_bibliography/papers.bib` — publications
  - `_news/` — news / announcements
  - `_data/cv.yml` — CV (education, experience, awards)
  - `_data/socials.yml` — email, GitHub, Google Scholar links
  - `_config.yml` — site title, name, URL

## Deployment

Pushing to `main` triggers the `Deploy site` GitHub Action, which builds the
site and publishes it to the `gh-pages` branch. In **Settings → Pages**, set the
source to the `gh-pages` branch.

## Local development (optional)

Requires Ruby 3.x, Bundler, and Node 20:

```bash
bundle install
npm install
bundle exec jekyll serve
```

Then open http://localhost:4000/jiyeong_cite/.
