# Floresta GUI (v0)

This repo contains **GUI design concepts + artifacts** for the Floresta project.

It’s meant to keep UI work **separate** from the core node implementation repo, so reviews stay focused and lightweight.

## What’s inside
- Figma links to frames/screens
- Exported screenshots (optional, for quick review)
- Design notes (states, components, IA)
- GitHub Issues used as the main review + feedback workflow

## Design goals (v0)
- Desktop-first GUI that remains **responsive** on resize
- Friendly language + clear explanation of node concepts
- Consistent state system across screens:
  **READY / LOADING / EMPTY / ERROR / LOCKED**
- Avoid overdesign: only reflect current Floresta capabilities

## How review works
- One **umbrella issue** is the index for the whole v0 design.
- Each screen gets its own issue for scoped feedback.

Start here:
- **Design Index (Umbrella Issue):** #<ADD_UMBRELLA_ISSUE_NUMBER_AFTER_CREATION>

## Figma
All frame links are tracked here:
- `design/figma-links.md`

## Status
Designed so far (v0):
- Setup Wizard (Network / Storage / Fast Start / Services / Review)
- Overview
- Sync

## Notes
This repo is design-first for now. If/when implementation begins (e.g., Slint), we can add:
- `/prototype/` for UI code
- component specs and tokens
