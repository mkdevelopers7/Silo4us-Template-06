# Local preview for this static site

This folder contains the built site (HTML, CSS, JS under `/_next/static`). Do NOT open `index.html` with `file://` because the site uses root-absolute paths (e.g. `/_next/...`). Instead serve the folder over HTTP.

Quick start (choose one):

- Windows (double-click): run `start-server.bat`.
- Windows PowerShell: run `.
start-server.ps1`.
- Python (cross-platform):

```bash
python -m http.server 3000
```

- Node (if you prefer):

```bash
npx serve -s . -l 3000
```

Then open:

http://localhost:3000

If the page is still broken, tell me what you see (console errors or 404s) and I will fix paths or make them relative.
