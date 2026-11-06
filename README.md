# Adoption page

`index.html` is the whole page: the text, the styling and the small script that holds the site addresses. Edit it in a code editor (VS Code) or in TextEdit set to plain text (Format > Make Plain Text before opening the file). Do not save it from TextEdit in its default rich-text mode: that rewrites the file with TextEdit's own styling and loses the design.

Live at https://adopt.abigailhaddad.com (Cloudflare Pages project `adopt`). A push to `main` that changes `index.html` deploys it through `.github/workflows/deploy.yml`, which needs the repo secrets `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID`.

Preview with `python3 -m http.server` in this folder.
