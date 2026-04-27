---
# Location: _preprints/YYYY-MM-DD-slug.md
# Auto-generates: /preprints/<slug>/ page, ScholarlyArticle JSON-LD (Preprint status) with arXiv,
# citation_* meta (Google Scholar), breadcrumb, sitemap, feed.
# layout is auto-set via _config.yml defaults.

# --- Required ---
title: "Paper Title"
date: YYYY-MM-DD
venue: arXiv                  # arXiv / bioRxiv / chemRxiv / etc.
authors:
  - Seungeon Lee
  - Co-author
type: preprint

# --- Recommended (one of these for the link to the preprint server) ---
link: https://arxiv.org/abs/XXXX.XXXXX
# arxiv_id is auto-detected from `link` when it's an arXiv URL; set explicitly to override.
# arxiv_id: "XXXX.XXXXX"

# --- Optional ---
# pdf_url: https://...        # → citation_pdf_url
# featured: true              # show in SELECTED on homepage
# image: /assets/img/preprints/filename.jpg
---

(Optional Markdown body — abstract.)
