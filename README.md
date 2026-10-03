# Masarif legal pages

Static pages for the Masarif Android app: landing page, Privacy Policy, and Terms & Conditions. Served with GitHub Pages from the root of the `main` branch.

## Publish

1. Create an empty **public** repository on GitHub named `masarif` (no README).
2. From this folder:

   ```bash
   git remote add origin https://github.com/<your-username>/masarif.git
   git push -u origin main
   ```

3. On GitHub open the repository's Settings → Pages, set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.

After a minute or two the pages are live at:

- `https://<your-username>.github.io/masarif/`
- `https://<your-username>.github.io/masarif/privacy.html` (use this as the privacy policy URL in Play Console)
- `https://<your-username>.github.io/masarif/terms.html`

## Updating

Edit the HTML, change the "Effective" date at the top of the page, commit, and push.
