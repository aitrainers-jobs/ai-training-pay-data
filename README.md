# AI training jobs: pay and hiring data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23596529.svg)](https://doi.org/10.5281/zenodo.23596529)

Hourly pay and open roles for AI training work, by field, platform, country and language.

Aggregate tables on paid AI training work (data annotation, AI evaluation, RLHF, expert and language roles) compiled by aitrainers.jobs from the job boards of 60+ platforms, including Mercor, Outlier, micro1, Alignerr, Turing, Handshake AI and DataAnnotation. Figures as of 2026-10-23.

Pay is in US dollars per hour. Only postings that state an hourly rate count; each distinct posting counts once; "up to" ceilings and paid research studies are left out; a range counts at its midpoint. Method: https://aitrainers.jobs/methodology

The tables contain no personal data and no job listings, only counts and percentiles. Live versions, rebuilt hourly: https://aitrainers.jobs/open-data

## Files

| File | Rows | Contents |
|---|---|---|
| `pay-by-field.csv` | 15 | Hourly pay by field of work |
| `pay-by-platform.csv` | 15 | Hourly pay by platform |
| `pay-by-country.csv` | 15 | Hourly pay by country a role is open to (worldwide roles not included) |
| `pay-by-language.csv` | 15 | Hourly pay for roles that need a language other than English |
| `trends/open-roles.csv` | 72 | Open roles over time (all roles, and the same platforms since day one) |
| `trends/open-roles-by-field.csv` | 72 | Open roles by field over time |
| `trends/open-roles-by-platform.csv` | 72 | Open roles by platform over time |
| `trends/pay.csv` | 4 | Hourly pay over time: median, quartiles and 90th percentile |
| `trends/pay-transparency.csv` | 39 | Share of roles that state pay, by platform |
| `trends/market-turnover.csv` | 27 | Roles added and closed by platform, latest period |
| `trends/hiring.csv` | 3 | Roles opened and closed each day |
| `trends/coverage-changes.csv` | 4 | When platforms were added to the tracker |

Pay tables have these columns: the group key and label, `open_roles` (roles listed), `distinct_rated_postings` (postings that state an hourly rate, each counted once), then `median_usd_hr`, `p25_usd_hr`, `p75_usd_hr`, `p90_usd_hr` and `max_usd_hr`. Groups with too few rated postings are left out.

## Licence and credit

Creative Commons Attribution 4.0 International (CC BY 4.0). Please credit:

> aitrainers.jobs (2026). AI training jobs: pay and hiring data [Data set]. https://aitrainers.jobs/open-data

## Versions

Each version is a release tagged with its date (for example `v2026-10-23`), archived on Zenodo with its own DOI; [doi.org/10.5281/zenodo.23596529](https://doi.org/10.5281/zenodo.23596529) always points to the newest. The tables on https://aitrainers.jobs/open-data are rebuilt hourly; this repository holds monthly snapshots.
