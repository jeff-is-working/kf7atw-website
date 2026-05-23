# KF7ATW Website — Initial Setup

**Date**: 2026-05-23
**Status**: Complete — live at https://kf7atw.com

## Completed

- Created public repo `jeff-is-working/kf7atw-website`
- Scaffolded Jekyll site with Minima theme
- Pages: Home, About, Projects, Activities + welcome blog post
- GitHub Pages enabled with custom domain `kf7atw.com`
- GitHub Actions workflow for Jekyll build/deploy
- Filed GitHub issue #1 with acceptance criteria
- CNAME file set for `kf7atw.com`
- Cloudflare DNS configured via API (4x A records + www CNAME, DNS only)
- Cloudflare SSL set to Full mode
- HTTPS cert provisioned and enforcement enabled
- Custom design: PNW steel-blue + copper palette adapted from C6S website
  - Dark navy header/footer with copper accent border
  - Inter + JetBrains Mono typography
  - Card components, dark code blocks, oscilloscope-green syntax highlighting
  - WCAG AAA contrast ratios
- Cloudflare API token stored in Key Vault as `cloudflare-global-dns-api-key`

## Next Steps

- Add detailed project pages with links to repos
- Write blog posts about ham radio activities and projects
- Add QRZ badge or widget
- Customize further (photos, grid locator map, equipment list)
