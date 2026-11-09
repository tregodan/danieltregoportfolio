# danieltregoportfolio (public): what danieltrego.com serves

GitHub Pages serves this repo as it is, with the domain set in `CNAME`.
**Don't edit pages here.** Almost everything is copied or generated from the private repo
[`tregodan/danieltrego`](https://github.com/tregodan/danieltrego) by its publish workflow, and gets overwritten on every publish.

| Path | Comes from |
|---|---|
| `*.html` (viewer, picker, high scores, home) | `danieltrego/site/` (edit it there) |
| `content/*.json` | Built from Pages CMS and Lightroom data |
| `media/public/` | Images uploaded through Pages CMS |
| `reel/<slug>/` | Generated share pages and `card.png` previews |

Only these belong to this repo itself:
- `CNAME`: the custom domain
- `.github/workflows/retry-pages-deploy.yml`: re-runs a Pages deploy once if GitHub's side fails
- this README
