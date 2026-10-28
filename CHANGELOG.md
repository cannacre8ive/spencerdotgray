# Changelog

## [1.1.0] - 2026-10-28

### Changed
- Readability redesign to match the Skeptic's Deck: warm paper default theme (ink #14120e, cobalt #2448d8) replaces the dark/violet default; the dark theme is now an opt-in toggle with its own high-contrast palette.
- Typefaces: Archivo (display and labels) and Inter (body) replace Bodoni Moda, Schibsted Grotesk and Spline Sans Mono. Labels raised from 10–12px to 13px; body from 17px to 18px.
- Hero blob recolored to cobalt and luminance-clamped per theme so the name keeps ≥ 4.5:1 contrast over it.
- Theme preference key renamed to `sg-theme-v2` so returning visitors start on the new default.

### Not yet refreshed
- `documentation/assets` screenshots and the social preview still show the 1.0 look.

## [1.0.0] - 2026-10-24

### Added
- GitHub release documentation and original-source checksum.
- Browser screenshots and 1200 × 630 social preview.
- Canonical URL, Open Graph/Twitter metadata, robots policy, sitemap and favicon.
- Static Vercel deployment configuration.

### Changed
- Declared English document language and added a descriptive page title.

### Verified
- Public production URL and sharing assets, responsive Chrome layouts and core interactions.
- Refreshed repository screenshots from the production site.
