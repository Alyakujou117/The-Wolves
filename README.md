# The Wolves — separated HTML, CSS and JavaScript

This project is an extraction of the original **The Wolves.html**, with game code and page content left unchanged. It uses the same script order as the original.

## File structure

- `index.html` — original HTML markup, now referencing external styles and scripts.
- `css/tailwind.css` — original locally embedded Tailwind utility CSS.
- `css/game.css` — original game-specific CSS.
- `js/icons.js` — original SVG icon hydration logic.
- `js/game.js` — original game logic, audio, and embedded data.
- `.nojekyll` — disables Jekyll processing on GitHub Pages.

## GitHub Pages

1. Extract the ZIP. Upload **the contents**, keeping `index.html`, `css`, and `js` in the same relative locations in the GitHub repository.
2. Go to **Settings → Pages**. Select **Deploy from a branch**, choose `main` and `/(root)`. Save.
3. Open the Pages URL. Refresh without cache if you uploaded a previous version.

You can also double-click `index.html` for local play. Google Fonts still require an internet connection, as in the original.

This extraction does not add an online multiplayer backend: all original behavior is retained as-is.
