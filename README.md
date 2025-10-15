# Harshit Jain — GitHub Pages Site

This is a simple, professional single‑page portfolio you can deploy on GitHub Pages in minutes.

## How to deploy
1. Create a new repository named **`<your-username>.github.io`**.
2. Upload the files from this folder to the repo root (index.html, styles.css, assets/ etc.).
3. Commit to the **default branch** (usually `main`). GitHub Pages should auto‑publish within a minute.
   - If it doesn’t: go to **Settings → Pages** and set **Source: Deploy from a branch**, **Branch: `main` / root**.
4. Visit `https://<your-username>.github.io` to see your site live.

## Customization
- Replace `assets/profile.jpg`, the project images, and `assets/HarshitJain_Resume.pdf`.
- Update all links (LinkedIn, Scholar, ORCID, Email).
- Edit text content in **index.html** — search for placeholder words like “ABB”, “CMU”, etc.
- Colors and layout live in **styles.css**.

## Tips
- To use a custom domain: in **Settings → Pages** add your domain, then create a DNS `CNAME` to `<your-username>.github.io`.
- Add analytics (e.g., Plausible) by pasting the script in `<head>` of `index.html`.
- Keep images under ~300KB for fast loads.
