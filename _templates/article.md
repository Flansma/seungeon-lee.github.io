---
# Location: _publications/YYYY-MM-DD-slug.md
# Auto-generates: /publications/<slug>/ page, ScholarlyArticle JSON-LD with DOI/PubMed/PMC,
# citation_* meta (Google Scholar), breadcrumb, sitemap, feed.
# layout is auto-set via _config.yml defaults.

# --- Required ---
title: "Paper Title"
date: YYYY-MM-DD
venue: "Journal of ..."
authors:
  - First Author
  - Seungeon Lee
  - Last Author
type: article                 # article / conference

# --- Optional: status (omit when published) ---
# status: submitted           # submitted / under review / in press

# --- Optional: identifiers (improve Scholar/Knowledge Graph linkage) ---
# doi: 10.xxxx/xxxxx          # → JSON-LD identifier (DOI), citation_doi
# pubmed: https://pubmed.ncbi.nlm.nih.gov/XXXXX/
# pmc: https://pmc.ncbi.nlm.nih.gov/articles/PMCXXXXXX/
# pdf_url: https://...        # → citation_pdf_url

# --- Optional: presentation ---
# featured: true              # show in SELECTED PUBLICATIONS on homepage
# image: /assets/img/publications/filename.jpg
# note: "Author's note about the publication."

# --- Optional: extra buttons on detail page ---
# links:
#   - label: Lab page
#     url: https://...
---

(Optional Markdown body — abstract or notes shown on the detail page.)
