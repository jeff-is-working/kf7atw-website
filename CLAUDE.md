# KF7ATW Ham Radio Website

Personal ham radio website for callsign KF7ATW, hosted on GitHub Pages at kf7atw.com.

## Tech Stack

- **Framework**: Jekyll (GitHub Pages native)
- **Theme**: Minima
- **Hosting**: GitHub Pages
- **Domain**: kf7atw.com (DNS at Cloudflare)
- **Repo**: jeff-is-working/kf7atw-website (public)

## Local Development

```bash
bundle install
bundle exec jekyll serve
# Site available at http://localhost:4000
```

## Deployment

Merging to `main` makes GitHub Pages build and deploy automatically. Agents do not push to `main`, merge, or complete PRs; the user pushes and merges.

## Structure

```
_posts/          # Blog posts (YYYY-MM-DD-title.md)
_config.yml      # Jekyll configuration
assets/          # CSS, images, static files
docs/status/     # Session status files
```

## Workflow

1. Plan changes, file an ADO work item in project `personal-projects` (User Story or Bug; never open GitHub issues)
2. Create feature branch
3. Test locally with `bundle exec jekyll serve`
4. Commit, open a PR to main, and give the user the push command; the user pushes and merges, then verifies the deploy
