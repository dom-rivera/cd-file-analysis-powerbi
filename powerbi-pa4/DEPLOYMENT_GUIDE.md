# Deployment Guide

Publish this documentation on GitHub in a few steps.

## What's in this folder

```
powerbi-pa4/
├── README.md                      the documentation page (outcomes-based)
├── images/
│   ├── dashboard-overview.png     main Dashboard page
│   └── drillthrough-detail.png    2011 month breakdown (drill-through)
└── DEPLOYMENT_GUIDE.md            this file
```

The two screenshots are already in place and already referenced by the README —
nothing to rename.

## Step 1 — Create the repository

1. Go to github.com and sign in.
2. Click **+** (top-right) → **New repository**.
3. Name it `cd-file-analysis-powerbi`, set it **Public**.
4. Click **Create repository**.

## Step 2 — Upload everything at once

1. On the repo page, click **Add file → Upload files**.
2. Drag in `README.md` and the entire `images/` folder together.
3. Click **Commit changes**.

## Step 3 — Verify

Open the repo's main page. The README should render with both screenshots
inline. A broken image means the filename in `images/` doesn't match the path in
`README.md` — but as shipped, they already match.

## Optional — add the .pbix file

To let others open your live report, drag `Practice Activity 4.pbix` into the
same upload (browser limit is 25 MB per file).

## Optional — a live interactive link

If your Power BI account allows **Publish to web**, paste the public URL near the
top of the README so viewers can click through to the interactive report. Note
this makes the report fully public — only use it for non-sensitive data.

---

Done — your CD File Analysis report is now documented and shareable.
