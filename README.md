# From the Mayflower to the Midwest — Konecny Genealogy

This repo is a GitHub Pages site for publishing the Konecny / Wood family history.
It ships with an initial outline and an easy structure for adding people, lines,
and research notes over time.

## Quick start

1. Create a new GitHub repository and upload the contents of this ZIP.
2. In **Settings → Pages**, set:
   - **Build and deployment**: Deploy from branch
   - **Branch**: `main` / `/ (root)` (or default branch you use)
3. Your site will publish at `https://<your-username>.github.io/<repo>/`.

## How to update

- Add a new person: put a Markdown file in `_people/` (e.g., `_people/franklin-wood.md`).
- Add a lineage write-up: a Markdown file in `_lines/`.
- Add a research note: a Markdown file in `_notes/`.
- Upload images to `assets/images/` and docs to `assets/docs/`.
- Create simple pages in `outline/`, `research/`, or `sources/` folders.

Front matter example for a person:

```yaml
---
layout: default
title: Franklin Wood (1921–2013)
tags: [Wood, Franklin line]
---

Content goes here...
```