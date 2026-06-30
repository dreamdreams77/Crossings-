# Crossing Problems

A logic puzzle game. Ten problems, one river, a Rubik's cube, and a fidget mode for when you just need something for your hands.

No accounts. No tracking. No backend. It's a single HTML file that runs entirely in the browser.

## Play it

**Live:** once deployed, this will be at `https://<your-username>.github.io/<repo-name>/`

**Locally:** just open `index.html` in any browser. No build step, no install.

## What's inside

- 10 logic and philosophy puzzles — river crossings, probability, paradoxes, infinity
- A fully playable, scrambled Rubik's cube (real face-rotation logic, not a gimmick)
- A 6-mode fidget tool: spinner, click cube, infinity cube, pop it, slider, spin ring

Every puzzle reveals something after it's solved — not a "congratulations," just a thought.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (public)
2. Upload `index.html` (and this `README.md`) to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select the `main` branch and `/ (root)` folder
5. Save — GitHub will give you a URL in a minute or two, usually `https://<username>.github.io/<repo-name>/`

That's the whole deployment. No npm install, no build pipeline, nothing else needed.

## Tech

Single-file HTML/CSS/JS. No external dependencies except two Google Fonts (Press Start 2P, JetBrains Mono) loaded over CDN. Works offline once cached.
