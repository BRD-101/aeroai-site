---
module: aeroai-site
type: history
status: append-only
---

# aeroai-site — history

Dated record, newest first. Split out of `STATUS.md` on 2026-08-20 so the
state file stays small. **Append only — never rewrite an entry.**
`STATUS.md` is what is true now; this is how it got that way.

## 2026-08-27 — first article published; deploy path confirmed

Content Desk's aeroAI publish had returned 502 since 08-23. Cause: GitHub 403,
the desk's fine-grained PAT covered `bridgewayaerotech-site` only. BRD added
this repo with Contents: write; the desk then committed `assets/blog/posts.json`
(1 news) and Cloudflare Pages served it within 30 s. Status flipped from
"parked" to active.

## Recent

- **2026-03-17** — hero brightened (opacity .85, lighter overlay gradients). Last
  commit.

