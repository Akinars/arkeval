# arkeval.com

Personal site for Alana R. Kinarsky, PhD (ARK Evaluation).
Hosted on **GitHub Pages** from the `main` branch. Pushing to `main` publishes
live at https://arkeval.com within a few minutes.

## Files
- `index.html` — the whole site (one hand-maintained, mobile-responsive page).
- `assets/` — logo and portrait images (kept optimized/small for fast loading).
- `CNAME` — the custom domain (`arkeval.com`). Do not delete.

## ⚠️ Important: do NOT upload the design-tool "Bundle" export over index.html
On 2026-09-30 a design-tool **"Bundle/Download" export** was uploaded as
`index.html`. That kind of file:
- has **no mobile layout** → the site got cut off and broke on iPhone,
- is **~2 MB** (this version is ~35 KB) → slow to load on phones,
- uses the browser-tab title "Bundled Page".

If you redesign in the design tool, **edit `index.html` directly** here, or have
the export **re-compiled to plain static HTML** before publishing — don't drop
the raw bundle in. The top of `index.html` has a matching warning comment.

## To update
- Small text/content tweaks: edit `index.html` and push to `main`.
- New images: add to `assets/` (keep them small — resize before committing).
