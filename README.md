# getmiw.github.io

Public GitHub Pages repository for the MiW project.

## Purpose

This repository hosts MiW public pages:

- Product landing page
- Privacy policy and compliance pages

## Public URLs

- Site: https://getmiw.github.io/
- Privacy Policy: https://getmiw.github.io/privacy-policy/

## Structure

- `index.html`: MiW landing page.
- `assets/brand/miw-logo-temporary.svg`: temporary logo used in the landing header.
- `assets/brand/favicon.svg`: favicon used by the landing page.
- `assets/screenshots/`: app screenshots used in the landing page.
- `privacy-policy/index.html`: privacy policy content.

## Landing page highlights

- Bilingual content with EN and PT-BR toggle.
- Messaging focused on core positioning: offline-first, totally free, and open source.
- Uses screenshots from the app for product communication.
- Uses MiW design system color tokens and typography direction.

## How to update pages

### Landing page

1. Edit `index.html`.
2. Commit and push to the repository default branch.
3. Wait for the GitHub Pages automatic deployment.

### Privacy Policy

1. Edit `privacy-policy/index.html`.
2. Commit and push to the repository default branch.
3. Wait for the GitHub Pages automatic deployment.

## Local preview (optional)

From this repository root:

```bash
python3 -m http.server 8080
```

Open in your browser:

- http://localhost:8080/
- http://localhost:8080/privacy-policy/

## License and trademark

- Code and content related to the MiW app follow the policies from the main repository:
  https://github.com/woliveiras/miw
- MiW name, logo, and brand identity follow the Trademark Policy from the main repository.
