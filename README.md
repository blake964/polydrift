# PolyDrift — PolyTrack-style Drift / Handbrake Demo

A standalone browser racing demo inspired by the clean low-poly look and controls of PolyTrack.

## Features

- Low-poly 3D circuit
- Arcade drift physics
- Handbrake on **Space** that reduces lateral rear grip and increases rotation
- WASD / Arrow-key steering
- R to reset
- Speed, timer, lap and drift HUD
- Static-site friendly for GitHub Pages

## Run locally

Open `index.html` in a modern browser. If your browser blocks modules from `file://`, use any small local web server, e.g. VS Code Live Server.

## Publish on GitHub Pages

Upload `index.html` and this README to a GitHub repository. Then enable:

`Settings → Pages → Deploy from a branch → main / root`

The page is designed to work without a build step.

## Attribution / relationship to PolyTrack

This is an independent implementation inspired by PolyTrack's low-poly racing presentation and general keyboard-control style. It does not include PolyTrack's original bundled game files or original assets.

PolyTrack is a game by Kodub. The public PolyTrack community also provides modding/decompilation resources; see the official/community repositories for the original project's licensing and modding guidance.

## Third-party dependency

Three.js is loaded from jsDelivr at runtime:

https://cdn.jsdelivr.net/npm/three@0.160.0/build/three.module.js

For a fully offline build, download the same Three.js module and change the import URL in `index.html`.
