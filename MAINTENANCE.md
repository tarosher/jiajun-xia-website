# Website maintenance

This repository is the single source of truth for Jiajun Xia’s personal academic website. Vercel automatically redeploys production after changes are committed to `main`.

## Structure

- `index.html` — homepage content and navigation
- `research/` — one standalone HTML case study per research project
- `assets/train`, `assets/metro`, `assets/cooperative` — curated original research figures only
- `styles.css` — shared visual system and responsive layout
- `resume_Jiajun_Xia.pdf` — public CV

## Safe update workflow

For small edits, update the relevant HTML or asset and commit to `main`.

For major layout/design changes:
1. Create a separate branch.
2. Let Vercel generate a preview deployment.
3. Review the preview on desktop and mobile.
4. Merge into `main` only after approval.

Vercel can roll production back to an earlier deployment if needed.

## Content rules

1. Keep the site English-first.
2. Preserve original research figures when they are used as evidence; explain or translate them in captions and surrounding text instead of altering the original image.
3. Use a curated subset of figures that materially advances the research narrative.
4. Distinguish team-level project output from individually documented contributions.
5. Keep quantitative claims traceable to the project reports, presentations, or CV.
6. Use the same design system across new case studies.
