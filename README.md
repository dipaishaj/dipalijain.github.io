# Teaching Portfolio (GitHub Pages) — v2

This is a refreshed scaffold for a **teaching portfolio** hosted on GitHub Pages, with your uploaded artifacts pre-linked.

## Quick Start
1. Copy all files into your `dipalijain.github.io` repo (or a dedicated repo if you prefer).
2. Commit & push to `main`.
3. In GitHub: **Settings → Pages → Source = Deploy from a branch → Branch: `main`**.
4. Replace placeholders in `/assets/` with your real files (keep names the same to preserve links):
   - Teaching_Statement.pdf
   - Fundamentals_Syllabus.pdf
   - UTD_Fall2023_Evals.pdf
   - headshot.png
   - eval_summary.png
   - (Recognition letters / certificates if you have scans)

## Where your uploaded files went
- IoT_Syllabus_2016.pdf
- IoT_Syllabus_Revision_2020.pdf
- IoT_Lab_Manual.pdf
- IoT_Weather_Project.pptx

## Switching themes
Default is **Minimal**. To try **Cayman**, change `_config.yml`:
```
theme: jekyll-theme-cayman
```

## If your repo already has files
**Option A (safe):** Make a backup branch before replacing.
```
git checkout -b backup-pre-teaching-site
git push -u origin backup-pre-teaching-site
```
Then replace files on `main`, commit, and push.

**Option B (side-by-side):** Keep your current homepage and link to these pages.
- Add a link to `/teaching.html` from your main `index.md`.
