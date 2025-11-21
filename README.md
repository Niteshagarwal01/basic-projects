## Basic Projects — Collection

![Gemini_Generated_Image_gm288dgm288dgm28](https://github.com/user-attachments/assets/bb16c378-fc9f-4c2e-9b11-7ae0576245dd)

This repository contains a set of small, self-contained frontend projects built with plain HTML, CSS, and JavaScript. Each project is in its own folder and can be run by opening the project's `index.html` in a browser or serving the repo with a simple static server.

### Quick links

- `01-quiz-game/` — Quiz Game
- `02-color-palette-generator/` — Color Palette Generator
- `03-drag-and-drop/` — Drag and Drop demo
- `04-expense-tracker/` — Expense Tracker
- `05-bookmark-saver/` — Bookmark Saver
- `06-form-validator/` — Form Validator
- `07-password-generator/` — Password Generator
- `08-todo-app/` — Todo App
- `09-contact-form/` — Contact Form (UI)
- `10-pricing-cards/` — Pricing Cards
- `11-team-members-showcase/` — Team Members Showcase
- `12-recipe-finder/` — Recipe Finder (demo/search UI)
- `13-currency-converter/` — Currency Converter (demo)
- `14-github-finder/` — GitHub Finder (uses GitHub public API)
- `15-404-page/` — 404 Page design
- `16-newsletter-signup/` — Newsletter Signup (UI)

## Project summaries

Below are short descriptions to help you pick what to open.

- 01-quiz-game: A multiple-choice quiz interface. Good for learning DOM updates and timers.
- 02-color-palette-generator: Generate and copy color palettes, typically using color inputs and clipboard APIs.
- 03-drag-and-drop: Demonstrates HTML5 drag-and-drop interactions for rearranging or dropping elements.
- 04-expense-tracker: Simple expense list with add/remove and totals (usually persisted to localStorage).
- 05-bookmark-saver: Save and manage bookmarks locally (UI + localStorage examples).
- 06-form-validator: Client-side form validation examples and patterns.
- 07-password-generator: Random password generation with options (length, character sets).
- 08-todo-app: Classic todo list with add/complete/remove and persistence demonstrations.
- 09-contact-form: Contact form UI. Typically no backend included — you can wire it to a backend or email service.
- 10-pricing-cards: Responsive pricing cards / UI components for marketing pages.
- 11-team-members-showcase: A responsive grid/list to showcase team members or profiles.
- 12-recipe-finder: Search UI for recipes — may include examples of fetching remote APIs. Some demos require an API key depending on implementation.
- 13-currency-converter: Currency conversion UI (may use a public API or sample rates).
- 14-github-finder: Search GitHub users/repos using the GitHub public API (watch for rate limits; no auth in simple demos).
- 15-404-page: A standalone 404 error page design.
- 16-newsletter-signup: A styled newsletter signup form (UI only; no backend by default).

## How to run

The simplest approach is to open a project's `index.html` in your browser. Example (from the project folder):

1. Open the folder for the project you want to try, for example `14-github-finder/`.
2. Double-click `index.html`, or open it from your browser (File → Open File).

If you prefer a local static server (recommended to avoid CORS restrictions for fetch requests), run a small server at the repository root.

For example, with Python (PowerShell):

```powershell
# serve from repository root on port 8000
python -m http.server 8000

# then open http://localhost:8000/14-github-finder/
```

Or use any static server you prefer (Node's `http-server`, Live Server extension in VS Code, etc.).

## File structure

Top-level folders are individual projects. Each project generally contains:

- `index.html` — entry point
- `script.js` — JavaScript (may be named differently or absent)
- `style.css` — styles for the project

Example:

```
basic-projects/
├─ 01-quiz-game/
│  ├─ index.html
│  ├─ script.js
│  └─ style.css
├─ 02-color-palette-generator/
└─ ...
```

## Notes

- Some projects include API calls (recipes, currency, GitHub). These demos may be rate limited or require API keys depending on the implementation. Check the project's `script.js` for details.
- Projects are intentionally small and focused on front-end patterns and DOM manipulation. They're suitable as learning references, starters, or UI snippets to adapt.

## Contribution

Contributions are welcome. If you'd like to:

1. Open an issue describing the improvement or bug.
2. Fork the repo, make your change in a topic branch, and open a pull request with a short description of the fix or feature.

Keep changes small and focused per project.

## License

This collection is provided under the MIT License. You can copy, modify, and use these examples freely. Add attribution if you publish derivative works.

## Contact

If you have questions or suggestions, open an issue in this repository.

---

Enjoy exploring the projects! If you'd like, I can also add short README files inside each project folder with per-project run notes or add a simple index page that links to all projects visually.
