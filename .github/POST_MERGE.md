# Post-Merge Checklist

Run through this after merging changes to `main`.

## Content sync

- [ ] New award/project added to **both** `public/PROOF.md` and `README.md`
- [ ] `schema/person.jsonld` `award[]` updated if placements changed
- [ ] `llms-full.txt`, `llms-ctx-full.txt`, `llms-index.json` reflect new facts
- [ ] No inflated placements (e.g. "1st Runner Up" stays "1st Runner Up")

## Links

- [ ] README badge links resolve (RECRUITER, FAQ, STACK, PROOF, portfolio)
- [ ] Project repo links not 404
- [ ] `sitemap.xml` includes any new public page

## Automation

- [ ] `snake.yml` ran green → `output` branch updated
- [ ] Snake SVG renders in README (hard-refresh profile if cached)
- [ ] Stats/trophy/streak widgets load (external services)

## Visibility

- [ ] Repo `polsalarm/polsalarm` still **public** (profile README needs public)
- [ ] Default branch is `main`
- [ ] Profile renders at https://github.com/polsalarm (incognito to bypass cache)

## Machine-readable

- [ ] `llms.txt` / `schema/person.jsonld` valid (no JSON syntax errors)
- [ ] `robots.txt` sitemap pointer correct
