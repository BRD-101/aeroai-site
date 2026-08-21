---
module: aeroai-site
prefix: —
status: parked
updated: 2026-08-02
vault_note: MASTER_PROJECT_SUMMARY
---

# aeroai-site — status

Public marketing site for aeroAI, `aeroai.ai`. Single-page static site — `index.html` plus three images. Four files total.

**Parked.** Last substantive change was 2026-03-17; 6 commits on `main`. Nothing is broken, it simply has not been touched in months while work went into the products.

## Open

- **Decide whether it stays a single static page.** Bridgeway's site has since
  grown an Insights section fed automatically by `news-content-pipeline`; aeroAI's
  has no equivalent. If aeroAI is the company that sells the software, the
  asymmetry is worth a deliberate decision rather than drift.
- No deployment path recorded here. Bridgeway's site deploys via Cloudflare Pages
  on commit; whether this one does is not written down anywhere.

## How this file is used

Update at session end, then run `python3 ~/dev/_estate/tools/fi_status_rollup.py`.

---

Dated history for this module lives in [`HISTORY.md`](HISTORY.md).
