# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

The reveal.js slide deck for the **CUNY AI Lab session on October 14, 2026**
(about 4:15 to 5:20): context from Luke Waltzer and Matthew K. Gold (no slides),
then Stefano Morello, Stephen Zweibel and Zach Muhlbauer, then discussion.
22 slides. It reuses images from the ACH 2026 deck (`../ach-2026`) and a
light version of its cali-narst look.

`SLIDES.md` is the manifest (order, sources, open items). Spoken notes are
reveal.js speaker notes inside `index.html`; press `S` to open the speaker view.

## Files

- `index.html` — the deck. Reveal.js 5.1.0 and its notes plugin load from
  jsDelivr. Each slide is a `<section>` with no `id`, so URLs use slide numbers
  (`#/3`, one-based, matching the on-screen counter). Adding an `id` would put
  that name in the URL instead.
- `styles.css` — the light theme: Newsreader headings, IBM Plex Sans text, arrow
  bullets, light gray cards, and a presenter accent set by a class on each
  section (`stefano`, `steve`, `zach`). The accents are the ACH pastels
  darkened to at least 5:1 contrast on white. Sizes in pt on a 1280×720 slide. Bump the `?v=` on its `<link>` after every edit, or the
  Pages CDN serves the old file.
- `images/` — Sandbox screenshots (`zm-step*`, `owui_*`), the AmigAI figure, and
  `tools/` (Tools page, Agent Studio workspace, Site Studio mock-up), and
  `access/` (application form, admin and instructor screens; sample data, see
  `SLIDES.md`).

## Layouts

- `class="opener"` on a section, with a `.card` inside: title slide, section
  openers, Discussion. The presenter name is `<p class="name">`.
- `.card` holding an `<h2>` and a `<ul>`: text slide. Keep to four bullets.
- `.principles` (a `<dl>` in a `.card`, slide 3): the website's four guiding
  principles as `<dt>`, what the Lab does about each as `<dd>`.
- `.side`: bullets left, picture or diagram right.
- `.hosts` (slides 5 and 6): inline SVGs of where the tools run and of the
  local pipeline. Navy boxes are run
  by the Lab; solid lines go through the Gateway, dashed ones straight to a
  provider.
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

- Plain titles and cue bullets with people or "we" as the subject, never an
  object doing something. No question titles, no "How we…" or "What we…"
  titles, no eyebrow labels.
- Banned words in slide text: `bot`, `chatbot`, `assistant`.
- No student names, emails or personal data on slides.
- Commits: lowercase, detailed, at most 100 characters; never co-author as Claude Code.
