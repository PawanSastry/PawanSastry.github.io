# pawansastry.github.io

Personal website of Pawan Sastry, Senior Product Manager.

Live at https://pawansastry.github.io. Deployed to GitHub Pages by the workflow in `.github/workflows/deploy.yml` on every push to `main`.

## What's here

| Path | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts in one file |
| `logos/` | Company logos for the experience timeline and discipline drawers |
| `Pawan_Sastry_Resume.pdf` | Downloadable resume (no phone numbers) |
| `portrait.webp` | Portrait image |
| `.github/workflows/deploy.yml` | Deploys the repo to GitHub Pages |

The page has a strict Content Security Policy that lists a SHA-256 hash for each inline `<script>`. After changing any script, recompute those hashes in the `<meta>` tag or the script will not run.

## Changelog

### 2026-11-01: Major overhaul

- Rebuilt the page layout and visual design, with light and dark themes.
- Added Expertise: four disciplines (AI-enabled, Analytics, Platform and Tech PM), each opening a right-hand drawer.
- Added Impact cards and a Selected work showcase with Challenge, Approach and Outcome tabs.
- Replaced the resume section with a horizontal experience timeline using company logos.
- Rebuilt Recommendations as an auto-scrolling carousel with five recommenders, a pause control and a pop-up showing each full recommendation.
- Added an Off stage section and a contact panel with icon actions for email, copying the address and LinkedIn.
- Added a phone-free resume download and LinkedIn, GitHub and Medium icons in the top bar.
- Removed the LinkedIn button from the hero to reduce repetition.

### Earlier

- Added a LinkedIn recommendations slider above the resume section.
- Redesigned the site with expertise, domains, a Medium link and security headers.
- Added the personal website and GitHub Pages deploy workflow.
