# ICPC India Prelims 2026 Ranklist

A filterable dashboard for the tentative ICPC India Prelims 2026 ranklist (3,610 teams, 389 colleges).

**Live site:** [https://YOUR-USERNAME.github.io/YOUR-REPO/](https://github.com/Eshitanagaria/icpc-india-prelims-2026)

## Features

- Search by team, college or username
- Filter by problems solved, college, institute type (IIT, NIT, IIIT, Other), rank range, penalty and individual problems
- Institute topper tag, college rank for every other team, and a "top N from each college" filter
- Sort by rank, problems solved, time, penalty, team or college
- Light and dark mode, works on phones

## How it works

Everything is in one static file, `index.html`. The ranklist is embedded in the page, so there is no build step and no server.

## Notes

- This is an unofficial dashboard built from the tentative ranklist released by ICPC India. Check the official ICPC India site for final results.
- Tied teams share a rank. College rank is the number of better-ranked teams from the same college, plus one.
- College names that differed only in spelling or capitalisation were merged. Institute type is read from the college name.
