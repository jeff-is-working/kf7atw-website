# KF7ATW Website — Initial Setup

**Date**: 2026-05-23
**Status**: In progress — awaiting DNS configuration at Cloudflare

## Completed

- Created public repo `jeff-is-working/kf7atw-website`
- Scaffolded Jekyll site with Minima theme
- Pages: Home, About, Projects, Activities + welcome blog post
- GitHub Pages enabled with custom domain `kf7atw.com`
- GitHub Actions workflow for Jekyll build/deploy
- Filed GitHub issue #1 with acceptance criteria
- CNAME file set for `kf7atw.com`

## Pending (Manual Steps)

### Cloudflare DNS Configuration

Log into Cloudflare dashboard for `kf7atw.com` and add these records:

| Type  | Name | Value               | Proxy Status |
|-------|------|---------------------|--------------|
| A     | @    | 185.199.108.153     | DNS only     |
| A     | @    | 185.199.109.153     | DNS only     |
| A     | @    | 185.199.110.153     | DNS only     |
| A     | @    | 185.199.111.153     | DNS only     |
| CNAME | www  | jeff-is-working.github.io | DNS only |

### Cloudflare SSL Settings

- Set SSL/TLS mode to **Full** (not Full Strict)
- Cloudflare proxy must be **OFF** (grey cloud / DNS only) for GitHub Pages HTTPS cert provisioning

### After DNS Propagation

- Verify site loads at https://kf7atw.com
- Enable HTTPS enforcement in GitHub Pages settings
- Close GitHub issue #1

## Next Steps

- Customize Minima theme colors/styling
- Add more project detail pages
- Write blog posts about ongoing ham radio work
- Add QRZ badge or widget
