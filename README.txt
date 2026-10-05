# Charades Time — Installable Web App

## What is in this folder?

- `index.html` — the actual game
- `manifest.webmanifest` — tells phones/computers that this is an app
- `sw.js` — lets the game keep working offline after it has been opened once
- `icon-192.png` and `icon-512.png` — the app icon

## Publishing it with GitHub Pages

1. Create a free GitHub account at https://github.com if you do not already have one.
2. Create a new repository named `charades`.
3. Set the repository to Public.
4. Upload ALL five files in this folder.
5. In the repository, open Settings → Pages.
6. Under "Build and deployment", choose "Deploy from a branch".
7. Choose the `main` branch and `/ (root)`, then Save.
8. Wait a minute or two.
9. GitHub will give you a web address ending in `/charades/`.

Open that address on your phone/tablet in Chrome and choose:
⋮ → Add to Home screen

The result is a Charades icon that opens the game like an app.

Each device keeps its own players, settings, and game state. Nothing in this app requires a server or shared database.
