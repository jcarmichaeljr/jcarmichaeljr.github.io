# Jeffrey Carmichael Portfolio Website

A static, single-page portfolio website built with plain HTML, CSS, and JavaScript. No frameworks, build tools, package managers, or backend services are required.

## Files

- `index.html` — site structure and placeholder content
- `style.css` — responsive layout, typography, light/dark theme styling
- `script.js` — mobile nav, active section highlighting, dark-mode toggle, image fallback handling

## Local preview

Open `index.html` directly in a browser, or run a simple local server from the project folder:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Pages deployment

1. Create a GitHub repository named `jcarmichael.github.io`, or use your existing Pages repository.
2. Put `index.html`, `style.css`, and `script.js` in the repository root.
3. Add your final assets later using this structure:

```text
assets/
  images/
    headshot.jpg
    contact-headshot.jpg
    rit-logo.png
  resume/
    Jeffrey-Carmichael-Resume.pdf
```

4. Commit and push the files to the main branch.
5. In GitHub, go to **Settings → Pages** and confirm the source is set to deploy from the branch root.

## Placeholder content

Search the code for `PLACEHOLDER` to find bullets and bio text that should be replaced later. The project titled `xxx` is intentionally preserved for future updates.

## Notes

The image and resume links currently point to `https://jcarmichael.github.io/assets/...`. If you host this repository under a different GitHub Pages domain or project path, update those URLs accordingly.
