# Keyword Research Framework

My end-to-end keyword research process, from raw ideas to a prioritized target list. Built for service businesses and local SEO, but the framework works for any niche.

## The process

See [playbook.md](playbook.md) for the full step-by-step method. In short:

1. **Ideas first** — brainstorm seed keywords and angles before opening any tool. The best keywords come from understanding the customer's language, not from autocomplete alone.
2. **Expand** — Google Keyword Planner, Keywords Everywhere, Google Trends, People Also Ask, and competitor gap analysis.
3. **Classify intent** — every keyword gets one intent label: informational, commercial, transactional, or local. Intent decides the page type.
4. **SERP analysis** — manually open the top 10 for each shortlisted keyword. Check: who ranks (brands vs small sites), content type, content quality, and whether an AI Overview dominates the results.
5. **Competition check** — Moz DA/KD and Ahrefs DR on the ranking domains. Weak domains in the top 10 mean the keyword is winnable.
6. **Prioritize** — score each keyword on volume, difficulty, intent value, and business fit. Target the high-volume, weak-competition overlaps first.

## Templates

- `templates/keyword-template.csv` — blank tracking sheet with columns: `keyword, volume, KD, intent, priority, notes`
- `templates/keyword-template-filled-example.csv` — a filled example for a local plumbing business

## CSV columns

| Column   | Meaning                                                        |
|----------|----------------------------------------------------------------|
| keyword  | The exact keyword                                              |
| volume   | Monthly search volume (note the country)                       |
| KD       | Keyword difficulty, 0 to 100 (note which tool)                 |
| intent   | informational, commercial, transactional, or local             |
| priority | P1 (target now), P2 (next), P3 (later)                         |
| notes    | SERP observations, competitor notes                            |

## Rules I follow

- Never target a keyword without checking the live SERP first. Metrics lie, the SERP does not.
- One page per intent. If two keywords share intent and the SERP looks the same, they belong on one page.
- AI Overviews change the math: if an overview answers the whole query above the fold, informational keywords need a different angle or they get deprioritized.
- Recheck quarterly. SERPs shift, competitors publish, new features appear.

## License

MIT
