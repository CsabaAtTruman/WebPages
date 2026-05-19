# AGENTS.md

- This repo contains only two self-contained static HTML files served by GitHub Pages.
- `truman_data_invitation_202605.html` is the only file to edit during development.
- Do not touch `index.html` unless the user explicitly अनुमति/permits it for promotion or another direct request.
- `index.html` is the approved production copy; when promoted, copy the working file over it so both files match.
- Before overwriting `index.html`, save the previous version as `last_index.html`.
- There is no local build, test, lint, or typecheck workflow in the repo. Verify changes by opening the HTML in a browser and checking desktop plus mobile layout.
- Preserve the inline CSS structure, the viewport meta tag, and the `@media (max-width: 540px)` rule; they are what keep the invitation usable on small screens.
- The page depends on Google Fonts (`Playfair Display` and `DM Sans`), so avoid removing those links unless you are intentionally changing the design.
