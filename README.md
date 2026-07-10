# Logan Manuola — Portfolio

Data analytics portfolio: Power BI dashboards, baseball analytics, and web-based data exploration.

Live site: **https://manuola11.github.io**

## Projects

- **Does Humidity Affect Offensive Performance in MLB?** — an OLS regression study (built
  in Excel) of whether ballpark humidity moves team wOBA across all 30 MLB teams, 2021–24.
- **Greenscapes — End-to-End Power BI Project** — three Power BI dashboards over 52 job IDs
  covering service-line optimization, crew productivity, and client concentration.
- **MLB Pitch Analytics Platform** *(in progress)* — a Statcast pitch-analytics platform
  (Python/FastAPI/DuckDB + React) surfacing whiff rates, two-pitch sequences, and
  pitcher–batter matchup edges. An equal collaboration; code at
  [N-Rossi/Python-MLB-Whiff_Percentage](https://github.com/N-Rossi/Python-MLB-Whiff_Percentage).

## A note on the Power BI dashboards

The Greenscapes dashboards were built in **Power BI Desktop**. There is no live
interactive embed on the site because my Microsoft account is a **school tenant with
"Publish to web" disabled by the administrator** — a common restriction that I can't
override without an organizational or Pro work account.

So the dashboards are shared two ways:

1. **Screenshots** of each dashboard on the
   [Greenscapes project page](projects/greenscapes.html).
2. **The original `.pbix` file** at
   [`assets/files/greenscapes.pbix`](assets/files/greenscapes.pbix), which anyone can
   download and open in **Power BI Desktop** (free, Windows) to inspect the data model,
   DAX measures, and interact with the report directly.

## Repository layout

```
index.html            Landing page
projects/             One page per project
assets/images/        Dashboard screenshots and figures
assets/files/         Downloadable source files (e.g. greenscapes.pbix)
assets/pdfs/          Supporting documents
styles.css            Site styles
script.js             Small helpers
```
