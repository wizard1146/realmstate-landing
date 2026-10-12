# Realmstate: the front door

The landing page at **https://realmstate.net**: what Realmstate is, a countdown to the current
age's start (or end), and the way in.

- It's one static page (`index.html`), with no build step and no framework.
- It reads only the game's public API: `GET https://api.realmstate.net/age`. Add `?game=https://...` to the
  address to point it at another game server for a test.
- Its buttons go to the player front end at https://play.realmstate.net and to the
  [wiki](https://wizard1146.github.io/realmstate-wiki/).

## Editing it

Change the files and push to `main`. GitHub Pages serves `main` at realmstate.net (the `CNAME`
file names the domain). To look before pushing, run `python3 -m http.server 8080` here and open
http://localhost:8080.

## The other pieces

| Address | What | Repository |
|---|---|---|
| realmstate.net | This page | `wizard1146/realmstate-landing` |
| play.realmstate.net | The player front end | `wizard1146/realmstate-frontend` |
| api.realmstate.net | The game server: API, sign-in | `wizard1146/realmstate` |
