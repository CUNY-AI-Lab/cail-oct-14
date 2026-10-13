# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

The reveal.js slide deck for the **CUNY AI Lab session on October 14, 2026**
(about 4:15 to 5:20): context from Luke Waltzer and Matthew K. Gold (no slides),
then Stefano Morello, Stephen Zweibel and Zach Muhlbauer, then discussion.
17 slides. It reuses images from the ACH 2026 deck (`../ach-2026`) but not its
theme.

`SLIDES.md` is the manifest (order, sources, open items). Spoken notes are
reveal.js speaker notes inside `index.html`; press `S` to open the speaker view.

## Files

- `index.html` — the deck. Reveal.js 5.1.0 and its notes plugin load from
  jsDelivr. Each slide is a `<section id="…">`.
- `styles.css` — the plain light theme: white, black text, one sans, sizes in pt
  on a 1280×720 slide. Bump the `?v=` on its `<link>` after every edit, or the
  Pages CDN serves the old file.
- `images/` — Sandbox screenshots (`zm-step*`, `owui_*`), the AmigAI figure, and
  `tools/` (Tools page, Agent Studio workspace, Site Studio mock-up).

## Layouts

- `class="opener"` on a section: title slide, section openers, Discussion.
- `.content` holding a `<ul>`: text slide. Keep to four bullets.
- `.side`: bullets left, picture or diagram right.
- `.figure` with an `<img class="shot">`, or an `.r-stack` of images with
  `class="fragment"` for click-through steps.

## Preview and QA

No build step. `python3 -m http.server 8765 --directory .` from this folder,
then open `http://localhost:8765/`. Check overflow with
`node ~/.claude/skills/revealjs/scripts/check-overflow.js index.html`, and look
at a screenshot of every slide and fragment state before pushing.

## Deploy

Live at **https://cuny-ai-lab.github.io/cail-oct-14/** (repo
`CUNY-AI-Lab/cail-oct-14`, GitHub Pages off `main`). Push to `main` and Pages
rebuilds in about a minute.

## House rules

- Plain titles and cue bullets with people or "we" as the subject. No question
  titles, no "What we…" titles, no eyebrow labels.
- Banned words in slide text: `bot`, `chatbot`, `assistant`.
- No student names, emails or personal data on slides.
- Commits: lowercase, detailed, at most 100 characters; never co-author as Claude Code.
