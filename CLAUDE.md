# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A static site (plain HTML and CSS) for a Danish hotdogs business plan. There is no build step, package manager, linter, or test suite; preview by opening `dog.html` in a browser. Shared styles belong in `style.css`, not inline in the HTML.

## Deployment

GitHub Pages serves the root of `main` at https://sternnn.github.io/danishhotdogs/ (main page: `dog.html`). A change goes live only once it is merged into `main`.

## Workflow

Changes are made on the `localdev` branch and merged into `main` through GitHub pull requests (remote: `sternnn/danishhotdogs`).

The codebase is hosted on GitHub and Claude is allowed to use it via the `gh` CLI (creating pull requests, pushing branches, and similar).
