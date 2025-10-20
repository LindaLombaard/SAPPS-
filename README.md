```markdown
## Mobile / GitHub Pages (short notes)

- This repository can be published via GitHub Pages from the repository root (branch: main).
- Ensure an index.html file is present at the repository root. The site root URL will be:
  `https://<your-username>.github.io/<repo-name>/` (for example: `https://LindaLombaard.github.io/SAPPS-/`).

Recommended changes (already prepared above):
- Add `<meta name="viewport" content="width=device-width, initial-scale=1">` inside the `<head>` of index.html.
- Add `mobile.css` to the repo and include `<link rel="stylesheet" href="mobile.css">` in index.html (or merge rules into your existing CSS).

Quick mobile testing checklist:
1. Confirm viewport meta tag is present.
2. Confirm images and iframes are responsive (they should not overflow on small screens).
3. Test on a narrow viewport (e.g., 360x800) and on larger screens to confirm layout adapts.
4. Test on iOS Safari and Android Chrome for spacing and touch targets.

If you prefer a CSS framework, consider adding a lightweight CDN (e.g., Bootstrap or a utility-first CSS) — but the above adds minimal, dependency-free responsive behavior.