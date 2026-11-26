# WebSPICE

A responsive browser-based circuit-editor prototype with a simple RC transient simulator.

## Run locally
Open `index.html` in a modern browser. No build step required.

## GitHub Pages
This repository includes a GitHub Actions workflow to publish the static site to GitHub Pages on pushes to `main`. In the repository, open **Settings → Pages** and set the build/deployment source to **GitHub Actions** if GitHub asks for it.

## Scope
This is an initial prototype, not an LTspice clone or full SPICE implementation. The current solver calculates a first-order RC charging transient. Advanced analyses, broad SPICE syntax/model support, accurate schematic connectivity, and IC libraries remain to be implemented.
