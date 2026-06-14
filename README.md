# MindStock website

Static support / marketing / legal site for the MindStock app, served via GitHub Pages
at **https://mindstock.zazavoxbox.com**.

Pages: `index.html` (landing), `support.html`, `privacy.html`, `terms.html`.

## Publish (GitHub Pages)
1. Create a GitHub repo and push this folder.
2. Repo → Settings → Pages → Source: `main` branch, root (`/`).
3. DNS: add a CNAME record `mindstock` → `<your-github-username>.github.io` in the
   zazavoxbox.com DNS zone. (The `CNAME` file here sets the custom domain.)
4. Enable "Enforce HTTPS" in Pages once the certificate is issued.
