# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A collection of standalone browser-based games. Each game is a single self-contained HTML file with embedded CSS and JS — no build tools, frameworks, or dependencies.

## Architecture

- **One file per game**: Each `.html` file is a complete game (markup, styles, and logic all inline)
- **No build system**: Files are opened directly in a browser — no bundler, transpiler, or dev server
- **No shared code**: Games are independent; there are no shared libraries or modules between them

## Running

Open any `.html` file directly in a browser. No server required.

## Current Games

- `index.html` — Barrel Shootout (hide-and-shoot game, local 2P or vs AI, 3 HP lives system)
- `connect4.html` — Connect 4
- `magic-chess.html` — Magic Chess

## Workflow

- **Commit and push frequently**: After completing any meaningful unit of work (new feature, bug fix, refactor), commit to Git and push to GitHub immediately. Use clean, descriptive commit messages. Never leave work uncommitted — we must not lose progress.

## Conventions

- Vanilla HTML/CSS/JS only — no external dependencies or CDN imports
- All game state managed in plain JS objects
- CSS-only visuals (no image assets)
- Games support being played on a single device
