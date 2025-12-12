# Tatka — GitHub Pages site

This branch contains a minimal static website (index.html + CSS + assets) intended to be published with GitHub Pages.

How to publish
1. Push this branch (e.g. `gh-pages`) to the repository.
2. In GitHub web UI go to Settings → Pages (or Settings → Code and automation → Pages).
3. Under "Build and deployment" choose the branch (e.g. `gh-pages`) and folder ("/ (root)"), then Save.
4. Wait a few minutes for the site to be published. GitHub will show the published site URL in the Pages settings.

Preview locally
- You can preview locally by opening `index.html` in a browser, or run a simple local server:
  - Python 3: `python -m http.server 8000`
  - Then open http://localhost:8000

Notes
- I cannot update repository settings (Pages domain) automatically — you'll need to enable Pages in the repo settings or give me explicit permission and instructions for a settings change.
- If you prefer the site to be published from `main` → `/docs` instead, I can instead create a `docs/` folder on `main`. Tell me which you prefer.