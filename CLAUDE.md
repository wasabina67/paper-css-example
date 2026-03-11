# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a static HTML demo project using [Paper CSS](https://github.com/cognitom/paper-css) to render print-ready A4 documents in the browser. The page content is a Japanese text about the Sankin-kōtai (参勤交代) system from the Edo period.

## Structure

- `docs/index.html` — Main HTML file; served via GitHub Pages from the `docs/` directory
- `docs/style.css` — Custom styles layered on top of Paper CSS

## How it works

Paper CSS is loaded from CDN (`paper.css`). The `<body>` has class `A4` and content lives inside `<section class="sheet padding-15mm">`. The `@page { size: A4 }` rule in `style.css` controls print sizing.

## Previewing

Open `docs/index.html` directly in a browser — no build step required.
