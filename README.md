# Utility Bench

A single-file, interactive learning tool for Tailwind CSS — 43 hands-on stations covering the full utility catalog, from basic spacing to arbitrary values, with a live code editor, real-time preview, instant class-by-class explanations, and a searchable cheat sheet.

**Category:** Education / Developer Tools

**Live site:** https://islandcoder3.github.io/tailwind-workshop/

**Built with:** HTML, CSS, JavaScript

## About

Built as a hands-on alternative to reading Tailwind docs. Every station gives you real HTML to edit, a live rendered preview, and a "bill of materials" panel that decodes every class in your code into plain English as you type. Stations are grouped into 43 lessons across 16 chapters, ordered by how often each pattern actually comes up in real projects — essentials first, edge cases and reference material last. A separate cheat sheet page rounds it out with a searchable, click-to-copy reference covering both the taught curriculum and the full Tailwind color palette.

## Features

- Browsable, tiered curriculum (Essential → Common → Advanced → Rare & Reference)
- Live HTML editor with syntax highlighting and VS Code-style autocomplete for tags and Tailwind classes
- Real-time rendered preview via the Tailwind CDN
- Class-by-class decoder with hover-to-trace highlighting
- Per-station validation with hints
- Searchable cheat sheet with click-to-copy class chips, plus a full 22-family × 11-shade color palette reference
- Progress saved automatically across sessions (with a `localStorage` fallback so it persists on any deployed site, not just inside Claude)

## Tech Stack

Vanilla HTML, CSS, and JavaScript — no frameworks or build tools required to run it.
