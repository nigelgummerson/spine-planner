# AGENTS.md — spine-planner-old-redirect

## Project Overview

Minimal redirect stub. Publishes a single `index.html` that issues a meta-refresh to `https://plan.skeletalsurgery.com/spine/` — the current home of the Spinal Instrumentation Plan & Record tool. Exists purely so that the legacy GitHub Pages URL (`nigelgummerson/spine-planner`) keeps forwarding users and search engines to the current site.

## Structure

```
products/spine-planner-old-redirect/
├── index.html      # <meta http-equiv="refresh" content="0;url=https://plan.skeletalsurgery.com/spine/">
├── AGENTS.md       # This file
├── CLAUDE.md       # Session history
└── .git/
```

No build step. No dependencies. No JavaScript. This is intentionally the smallest possible project.

## Do Not

- Add features, styles, or analytics to `index.html` — it is a redirect, not a page.
- Point the redirect somewhere other than `plan.skeletalsurgery.com/spine/`.
- Turn this into a second landing page — that role belongs to `skeletalsurgery-landing/`.

## Deployment

GitHub Pages from `nigelgummerson/spine-planner` (repo name retained for historical URL continuity, despite the name collision with the active dev repo `spine-planner-dev`).

## AI Collaboration

- **AGENTS.md** — this file.
- **CLAUDE.md** — session history.
- Read `CLAUDE.md` for current state before making changes.

## Done when

type: area
status: draft
review: annually, while the old URL may be bookmarked

<!-- Drafted 2026-07-30 from this project's own PROJECT-GUIDE.md entry.
     Correct it and delete the `status: draft` line when you next work here.
     Format: tools/project-index/STATE-FORMAT.md -->
