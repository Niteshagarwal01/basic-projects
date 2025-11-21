# GitHub Finder

Short description

A small app that searches GitHub users or repositories using the GitHub public API. Useful to demonstrate fetch, async handling, and rendering remote results.

Files

- `index.html` — entry point
- `script.js` — fetch and render logic
- `style.css` — styles

How to run

1. Open `index.html` in your browser, or run a local static server to avoid CORS issues when making API requests.

2. The app uses GitHub's public API; unauthenticated requests are rate-limited. If you plan to use it heavily, consider authenticating requests with a personal access token.

Notes

- Check `script.js` for the specific endpoints used (users vs search). Don't commit personal tokens to the repository.
