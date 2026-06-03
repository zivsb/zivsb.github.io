# zivsb.github.io

My personal homepage — a dark, cobalt, glitch-tinged take on "antiquity ÷ protocol,"
built as a single static page. Lives at <https://zivsb.github.io>.

## Contents

- `index.html` — the whole site (HTML + CSS + a little JS, no build step)
- `sat-wire.json` — a satellite mesh processed into feature-edge wireframe +
  point cloud, rendered live in WebGL (Three.js) as a glowing relay node that
  routes packets along its edges
- `email.gif` — my email rendered as an animated image so it never appears as
  scrapable text anywhere in the source
- `favicon.ico` / `favicon.png` — cobalt "Z" mark
- `Ziv_Weissman_CV.pdf` — CV, linked from the page

## Notes

- The top bar runs a real speed test (measured throughput to the host) and shows
  the visitor's public IP as a faux shell prompt.
- The visitor counter uses [counterapi.dev](https://counterapi.dev) so it works
  on static hosting.
- Three.js is loaded from a CDN via an import map.

## Branches

- `main` — the live site (this design).
- `legacy-web1.0` — the previous maximalist Web 1.0 / Y2K version.
- `aesthetic-v2` — the lab branch where this design was prototyped (oracle /
  perspective / signal / orbital explorations).
