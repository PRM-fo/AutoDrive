# AutoDrive Lab

Chaos in. Decisions out. An interactive 3D explainer and driving game about self-driving cars.

## Files
- `index.html`: the 3D scroll tour (Tesla and AVs, computer vision, sensor fusion, path planning, decision making)
- `game.html`: "Try it yourself", a drivable simulator with warning, auto-brake, auto-steer, lane keeping and a high score

Both are single, self-contained files. The only outside resources are three.js (r128) and the Archivo font, loaded from CDNs, so the page needs an internet connection.

## Run locally
Open `index.html` in a browser. (Or run `python3 -m http.server` in this folder and visit http://localhost:8000.)

## Host it for free
- **Netlify:** go to app.netlify.com/drop and drag this folder onto the page.
- **GitHub Pages:** push these files to a repo, then Settings > Pages > deploy from the main branch.
- **Vercel:** run `npx vercel` in this folder.

## Controls (game)
W gas, S or Space brake, A/D or arrow keys steer, T toggles the safety assist. Touch buttons appear on phones.
