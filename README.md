# Personal site (GitHub Pages + Jekyll Collections)

이 리포는 GitHub Pages(Jekyll) 기반 개인 홈페이지입니다. 실적은 컬렉션으로 폴더/개별 파일로 관리합니다.

## Update content (실적 추가/수정)

다음 폴더에 파일을 추가하면 자동 반영됩니다. 파일명은 `YYYY-MM-DD-slug.md` 권장.

- `_publications/` — 저널 논문(게시/게재승인/투고중)
- `_preprints/` — 프리프린트(arXiv 등)
- `_talks/` — 학회/세미나 발표
- `_awards/` — 수상

Front Matter 예시:

```yaml
---
title: "논문 또는 발표 제목"
date: 2026-01-10
venue: "학술지/학회명 등"
authors:
  - First Author
  - Second Author
type: article   # article | preprint | talk | award
# 선택 항목
status: submitted
doi: 10.xxxx/xxxxx    # 또는 link:
link: https://example.com
links:
  - label: PDF
    url: https://...
featured: true        # 대표 실적 카드에 노출
---
```

푸시 후 1–2분 내 GitHub Pages가 자동 빌드됩니다.

## Deployment (GitHub Pages)

- Settings → Pages → Source: `Deploy from a branch`
- Branch: `main` / `(root)` 선택 → 저장

## Notes

- BibTeX: `/publications.bib`
- .DS_Store는 `.gitignore`로 제외됨
