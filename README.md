# Swim Meets Thailand

Public results website for Thai swim meets: swimmer profiles, personal bests, rankings, national and age-group records, head-to-head comparisons and printable reports.

Live site: https://pakornsnl-smt.github.io/swimmer-database/

## How it is updated

Results are uploaded and checked by the meet operator's staff in the staff app. After each meet, staff press **Publish public data** in the staff app's Manage tab and upload the downloaded `public.json` into the `data` folder of this repository (replace the old file). The site updates within a minute or two.

## Privacy

`data/public.json` contains only what the public site shows: names, gender, birth year, club, nationality, results, meets, records and points base times. Citizen IDs, passport numbers, full birth dates and staff settings are never included. Never upload a staff **backup** file here: it contains private data.

## Files

- `index.html` — the website (no build step).
- `data/public.json` — the published results.
