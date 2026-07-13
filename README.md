# KamtexSolar Prototype Website

Static prototype site for Kamtex Solar (off-grid B2B solar, Singapore). No build step: plain HTML/CSS/JS.

- `index.html` - home (hero, trust band, stats, about, industries, custom solutions, case-study teasers, testimonials, history, maintenance)
- `case-studies.html` - 11 case studies with photo carousels and challenge/solution flippers
- `products.html` - product catalogue categories
- `quote.html` - multi-step quote request form (composes an email to kamtex@kamtexindustries.com)
- `assets/` - logo and photos extracted from the Kamtex pitch and monthly case-study decks

## Local preview

From this folder, run:

```
python -m http.server 8741
```

then open `localhost:8741` in a browser.

## Editing

Edit any file, then:

```
git add -A
git commit -m "describe change"
git push
```

GitHub Pages redeploys automatically within a minute or two.

## Notes

- Content pending from William: MCSS Type A-D specs, owner bio/photo, certifications, client photo/name permissions (PSA, MINDEF, CAG).
- Build log and decisions: Notion page "Kamtex Solar Website - Build Log & Decisions".
