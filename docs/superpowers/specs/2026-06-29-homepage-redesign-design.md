# Homepage Redesign — Design Spec

**Date:** 2026-06-29
**Goal:** Completely refactor the homepage of `zhiqi-li.github.io` into a modern-minimalist, high-end editorial design.

## Decisions (confirmed)

- **Visual base:** Light editorial — near-white warm background, near-black text, generous whitespace, hairline dividers. (Apple / Linear / Vercel register.)
- **Build approach:** Bespoke standalone layout. New `_layouts/home.html` + new `assets/css/home.css`, fully detached from the minimal-mistakes theme. Existing `_sass/` left untouched for any other pages.
- **Headline type:** Large sans-serif (Inter), oversized with tight letter-spacing. Body also Inter. Dates/metadata in a monospace face for editorial-tech contrast.
- **Accent color:** Pure neutral graphite gray (no NVIDIA green). Accent used only on link hover, active nav item, and the hiring callout dot.
- **Entrance animation:** Yes — a simple, tasteful fade/rise-in on scroll. Keep it subtle.
- **Dark mode:** No.

## Layout

Single centered column, content max-width ~720px, large side margins.

1. **Sticky top nav** — translucent frosted bar: name on the left; `About / News / Papers / Awards` anchors + social icons on the right. Smooth-scroll to anchors; active section highlighted.
2. **Hero** — oversized name, role line ("Research Scientist"), `NVIDIA Research · Singapore`, one-line tagline, small refined avatar, minimal social icon row.
3. **About** — intro prose.
4. **News** — timeline list: monospace date column + content.
5. **Publications** — image-left / text-right refined cards, subtle shadow + hover lift, small badge tags (Arxiv etc.). Google Scholar citation count preserved.
6. **Honors & Awards** — date-column clean list.
7. **Education** — date-column clean list.
8. **Footer** — `© 2026 Zhiqi Li` + email.

### Hiring callout
Redesign the garish red banner into a tasteful highlighted card: hairline border, a pulsing graphite dot, restrained copy.

## Content

All existing content preserved verbatim (About, hiring note, News items, the Eagle 2 publication, Honors, Education). This is a re-typesetting, not a content edit.

## Technical notes

- `about.md` front matter: `layout: home` (was `default`).
- New layout has its own `<head>`: viewport/SEO meta, Google Fonts (Inter + a mono), academicons CSS for the social/scholar icons, `home.css`, and the Google Scholar stats fetch.
- **Rewrite the Google Scholar fetch in vanilla JS** (current version depends on jQuery via `main.min.js`, which the new layout will not load). Preserve `show_paper_citations` / `total_cit` behavior.
- Do not set `<base target="_blank">` globally (breaks anchor smooth-scroll); open external links in new tabs selectively if desired.
- Must build cleanly under GitHub Pages / Jekyll `--safe`.

## Out of scope

- Other pages / the global theme.
- Dark mode.
- Editing the substance of any content.
