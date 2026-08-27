---
module: aeroai-site
prefix: —
status: active — AI newsfeed live, fed by Content Desk since 2026-08-27
updated: 2026-08-27
vault_note: MASTER_PROJECT_SUMMARY
---

# aeroai-site — status

Public marketing site for aeroAI, `aeroai.ai`. Static: `index.html`, `article.html`,
three images, and `assets/blog/posts.json`, which is **written by Content Desk**
(news-content-pipeline Module 5A) on every publish to the aeroAI target.

**Deploy path:** Git-connected Cloudflare Pages — push to `main` = live in ~30 s.
Clean URLs are on (`article.html` → `/article`). Confirmed 2026-08-27 by watching
the first Content Desk commit go live.

**AI newsfeed** (three across + headline ticker, PR #1 merged 2026-08-23) renders
`posts.json`; section and nav link stay hidden while the file is empty. First
article published 2026-08-27 13:41 UTC — until then every publish had failed
because the desk's GitHub PAT had no Contents write on this repo (fixed by BRD
at github.com the same day).

## Open

- ~~Decide whether it stays a single static page~~ — resolved by the newsfeed
  (08-23) and the first publish (08-27). Editorial/opinion columns: the desk
  only drafts those for BAT sections today; whether aeroAI gets its own is open.
- Landing shows the top 3 by relevance (`AEROAI_LANDING_COUNT`); with one
  article live the grid is mostly empty — publish AI_TECH drafts from the desk.

## How this file is used

Update at session end, then run `python3 ~/dev/_estate/tools/fi_status_rollup.py`.

---

Dated history for this module lives in [`HISTORY.md`](HISTORY.md).
