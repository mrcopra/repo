# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project — plain HTML, CSS, and vanilla JavaScript with no build tooling, package manager, or framework. There is no compilation, bundling, or transpilation step.

## Repository State

The repository currently contains only `README.md`. The previous main file (`index.html`) was deleted in the most recent commit. Prior versions of the site (visible in git history) were AI-generated single-page websites (e.g. a Retro Gaming Store, a Coffee Shop) consisting of self-contained HTML files with inline `<style>` and `<script>` blocks.

## Development Workflow

- **Viewing the site**: Open `index.html` directly in a browser — no server required for basic static content. If the page loads external resources or uses `fetch`, run a simple local server:
  ```sh
  python3 -m http.server 8080
  ```
- **No linting, testing, or build commands** are configured in this repo.

## Conventions from Prior Code

- All CSS and JavaScript were written inline within the single `index.html` file (no separate `.css` or `.js` files).
- Layout used Flexbox with media queries for responsiveness.
- No external JS libraries or CSS frameworks were used.
- Commits following the pattern `auto: site update` or `AI Auto-Update` indicate this repo has been used for AI-driven iterative site generation.
