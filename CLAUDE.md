# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A static site (plain HTML and CSS) for a Danish hotdogs business plan. There is no build step, package manager, linter, or test suite; preview by opening `index.html` (the home page) in a browser. `dog.html` is the sausage suppliers page; `menu.html`, `costs.html`, `location.html` and `marketing.html` are placeholder section pages linked from the home page. Shared styles belong in `style.css`, not inline in the HTML.

## Code style

Always use named exports, never default exports.

## Deployment

GitHub Pages serves the root of `main` at https://sternnn.github.io/danishhotdogs/ (main page: `index.html`, served at the site root). A change goes live only once it is merged into `main`.

## Workflow

Changes are made on the `localdev` branch and merged into `main` through GitHub pull requests (remote: `sternnn/danishhotdogs`).

The codebase is hosted on GitHub and Claude is allowed to use it via the `gh` CLI (creating pull requests, pushing branches, and similar).
