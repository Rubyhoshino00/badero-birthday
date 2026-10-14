# Moonlit Chapter 25 — For Bader

An anime-inspired interactive birthday visual novel for Bader's 25th birthday on 18 November, made by Mira. It includes visible anime artwork, dialogue, branching choices, a story log, restart/replay, and a personalized birthday ending.

## Publish/update on GitHub Pages

1. Open your existing GitHub repository.
2. Upload and replace `index.html`, `style.css`, `script.js`, and `README.md`.
3. Upload the complete `assets` folder with all five images. Keep the folder name exactly `assets`.
4. Commit the changes to the `main` branch.
5. In **Settings → Pages**, keep **Deploy from a branch**, branch `main`, folder `/(root)`.
6. Wait for the Actions deployment to finish, then refresh your Pages URL.

## Files
- `index.html` — game screens and UI
- `style.css` — responsive anime visual-novel styling
- `script.js` — story nodes, branches, choices, log, replay and ending
- `assets/` — scene artwork used by the game

No build step or external framework is required. The game runs as a static GitHub Pages site.
