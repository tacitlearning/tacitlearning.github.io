# Tacit Learning Website

This repo is configured as a GitHub Pages **user site** (tacitlearning.github.io) using the **Minimal Mistakes** Jekyll theme.

## Pages
- Home: `index.md` (splash layout with big buttons)
- Project Management: `_pages/project-management.md`
- Artificial Intelligence: `_pages/artificial-intelligence.md`
- Data Analytics: `_pages/data-analytics.md`
- Contact Us: `_pages/contact.md`

## Navigation
Top navigation is defined in `_data/navigation.yml`.

## Run locally
1. Install Ruby + Bundler
2. `bundle install`
3. `bundle exec jekyll serve`
4. Open http://localhost:4000

## Deploy
Commit/push to `main`. In GitHub: **Settings → Pages** → Deploy from branch → `main` + `/ (root)`.
