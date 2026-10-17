# Shobin Sam S — Portfolio

A responsive, static portfolio for AI/ML engineering work. No build tools, paid API, account system, or server-side application is needed.

## Recommended public home: GitHub Pages

Use the repository **ShobinSamS.github.io** in your GitHub account. Its user-site address will be **https://shobinsams.github.io/** after GitHub Pages is enabled and deployment succeeds. That address is a proposed destination, not a claim that it is already live.

1. Create a public repository named `ShobinSamS.github.io` in the `ShobinSamS` account. If it already exists, preserve its existing content and merge this portfolio deliberately.
2. Upload the **contents of `dist/`** to the repository root. `index.html` must be at the root, alongside `styles.css`, `app.js`, `.nojekyll`, and `assets/`.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then save.
4. Wait for the deployment to succeed. Use the URL displayed in Pages settings.
5. Add the live portfolio URL to your LinkedIn contact details, GitHub profile, Naukri profile, and resume.

GitHub Pages documentation:
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

The accompanying `Shobin_Sam_Portfolio_GitHub_Pages.zip` has the publishing files at its root; extract it before uploading. No Sites identity or Git credentials are included in that ZIP.

## Edit the portfolio

- `dist/index.html`: biography, project descriptions, experience, certifications, links.
- `dist/styles.css`: colors, type, layout, responsive rules.
- `dist/app.js`: mobile menu and copy-email interaction.
- `dist/assets/cortexops-overview.png`: actual CortexOps project screenshot.
- `dist/assets/shobin-sam-resume.pdf`: the latest PDF supplied in this chat, exported before the subsequent LaTeX spacing adjustment. Replace it with the newly exported final resume when ready.

The CortexOps screenshot and case study describe a local demonstration with synthetic operational data. The TCS ticket figure describes workflow volume; the portfolio does not claim an automated resolution rate or a completed launch of the ongoing project. The Azure entry refers to the credential earned in 2025.

## Preview locally

From the `dist` directory:

```text
python -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000 in a browser. Press Ctrl+C in the terminal when finished.

## Sites preview

The private Sites deployment is a review copy. The source checkout's `.openai/hosting.json` is for that deployment and is not required for GitHub Pages. Keep the public GitHub Pages files and any later edits in version control.
