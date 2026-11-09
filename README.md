# danieltregoportfolio (public): what danieltrego.com serves

GitHub Pages serves this repo as it is, with the domain set in `CNAME`.
It holds two kinds of files. Keep them apart.

## Hand-made pages (edit these here)
| File | Page |
|---|---|
| `viewmaster-prototype-v2.html` | The View-Master photo viewer (current). Reel share links point here. |
| `picker.html` | Photo picker: choose which Lightroom photos go on each disc. Saves to the private repo. |
| `high-scores.html` | High Scores page |
| `index.html` | Home page (placeholder until the landing page is built) |
| `viewmaster-prototype.html` | First viewer prototype, kept for reference. Don't edit. |
| `.github/workflows/retry-pages-deploy.yml` | Re-runs a Pages deploy once if GitHub's side fails |

## Generated files (don't edit; overwritten on every publish)
Written by the private repo's publish workflow (`tregodan/danieltrego`):
- `content/portfolio.json`, `content/high-scores.json`, `content/album-sheets.json`
- `media/public/`: images uploaded through the CMS
- `reel/<slug>/`: share pages, plus `card.png` preview images

To change discs, photos or High Scores, use Pages CMS, not this repo.
