# Jeffrey Carmichael Portfolio Website

A static, single-page portfolio site built with plain HTML, CSS, and JavaScript. No frameworks, build tools, package managers, or deployment scripts are required.

## Files

- `index.html` — page structure and placeholder content
- `style.css` — site-wide styling and responsive layout
- `script.js` — mobile nav toggle, active nav highlighting, and footer year

## Preview locally

Open `index.html` directly in your browser.

For a slightly more realistic local preview, run a tiny local server from this folder:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Pages deployment

1. Place `index.html`, `style.css`, `script.js`, and this `README.md` in the root of your GitHub repository.
2. Commit and push the files to GitHub.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the branch you want to publish from, usually `main`, and choose the root folder.
6. Save the setting and wait for GitHub Pages to publish the site.

## Replacing placeholders

Search for `PLACEHOLDER` inside `index.html`. The placeholder bullet bars intentionally use visual lines instead of visible text, but each has a nearby HTML comment showing where to add the real bullet copy.

The current dummy asset paths are:

```text
https://jcarmichael.github.io/assets/images/headshot.jpg
https://jcarmichael.github.io/assets/images/logo.png
https://jcarmichael.github.io/assets/resume/Jeffrey-Carmichael-Resume.pdf
```

Update those paths once the final assets are added.
