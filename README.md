# JDI Key Dates

The JDI Key Dates tracker: one page, `index.html`, that draws the set up and completion key dates for every live site from `data.json` beside it.

- `index.html` — the page. No build step, no dependencies beyond Google Fonts.
- `data.json` — the dates. Rewritten by the hourly Key Dates routine from the sheets in JDI Systems JB › Key Dates › Drop.
- `keydates_site_data.py` — writes `data.json` from the Drop folder on the Mac (the cloud routine does the same from Dropbox).

Hosted at keydates.justdoesit.co.uk.
