# QotW Rankings

Pairwise FFA ELO rankings for **QotW (Qube of the Week)** — the Thursday Zeepkist cup hosted by [lillyfenn](https://www.twitch.tv/lillyfenn).

Live page: https://aizpunr.github.io/qube-rankings/

## What it tracks

Per-cup elimination-bracket placements aggregated into a single ELO over time. Each cup, every pair of attendees plays a "match" by cup placement (lower = win, ties draw). Rating updates via standard ELO with K=12 (K=24 during a player's first 5 cups).

Player history (click any row in Rankings):

- Rating arc across cups, podium-colored dots
- Per-cup table (cup #, date, map, finishing position, rating after the cup)

Events tab: every cup, sortable by date / SOF / lobby size, click to see full final standings.

## Data source

Source files (per-cup markdown, build script, xlsx) live in the working folder, not this repo. This repo holds the published page + the prebuilt `qube.json` only.
