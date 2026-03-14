# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static tribute/memorial website for Cushion (cushion.ai), a fintech company founded in 2016 and acquired by LendingClub in April 2025. The site is a single `index.html` file (~500 lines) containing all HTML, CSS, and JavaScript inline.

## Architecture

- **Single-file site**: Everything lives in `index.html` — no build tools, bundlers, or dependencies
- **CSS**: Inline `<style>` block using CSS custom properties (`:root` variables) for theming
- **Fonts**: Google Fonts (Syne for headings, DM Sans for body text)
- **Responsive**: Mobile breakpoints at 768px and 480px
- **Interactivity**: Vanilla JS for scroll-reveal animations and timeline tab switching

## Design System

Key CSS custom properties:
- `--bg: #07191a`, `--bg2: #0d2325` (dark backgrounds)
- `--teal: #33C5C8`, `--green: #5fe3a1` (accent colors)
- `--text: #e8f0ef`, `--muted: #6e9896`
- `--grad: linear-gradient(120deg, #33C5C8, #5fe3a1)` (gradient accent)

## Development

Open `index.html` directly in a browser. No server or build step required.
