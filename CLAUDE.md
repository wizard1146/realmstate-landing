# Realmstate site

The landing page at https://realmstate.net. Read `README.md` first.

Identity: **wizard1146** (`yellowhat1146@gmail.com`), SSH host alias `github-wizard1146`. Local git config is set.
Remote: `git@github-wizard1146:wizard1146/realmstate-landing.git` (branch `main`); GitHub Pages serves `main`.

## Rules
- Static only: plain HTML, CSS and JavaScript, no build step, no framework, no runtime dependencies (Google Fonts is
  the one outside asset).
- Read only the game's public API (`https://api.realmstate.net/age`, without credentials). Never sign in here:
  sign-in happens on the game's own address, and play happens at https://play.realmstate.net.
- Naming follows the game: realms > states > houses. Never "kingdoms" or "provinces" as game terms.
- Light and dark themes through the custom properties on `:root`; it must work at phone width with no sideways
  scroll, and by keyboard.
