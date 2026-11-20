# Hempenology website
Static site (HTML/CSS/vanilla JS). 7 pages + 404, sitemap.xml, robots.txt.
## Deploy
1. Back up the current repo (`ahoychefahoy-cmc`) first: copy the existing index.html, styles.css, script.js and old ZIP into a `/_backup` folder or a git branch.
2. Copy this folder's contents into the repo root, commit and push to `main`.
3. Cloudflare Pages: build command none, output directory `/`. Domain hempenology.com is already attached.
## Still required
- Original botanical artwork and boxed H logo files: `assets/images/botanical.svg` is a generated swirl stand-in (the original textured artwork was only seen in a screenshot); replace it (keep the filename or update `.hero` in styles.css).
- Real product photography (image areas are marked) and product details.
- Contact form: none configured, so Contact uses mailto links. Add a form service (e.g. Formspree) if wanted.
- Optional: SoundCloud embed players; fonts load from Google Fonts (self-host into assets/fonts for full independence).
