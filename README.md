# Global Streaming Media Analytics Dashboard

An interactive Power BI report exploring streaming performance across Spotify, YouTube, and TikTok using the `Most Streamed Spotify Songs 2024` dataset.

## Dashboard pages

### 1. Global Streaming Overview
High-level KPI cards covering platform engagement and track-level performance, including Spotify streams, YouTube views, TikTok views, track score, and explicit-track information.

### 2. Artist Performance Overview
An artist slicer, KPI cards, and track-level comparisons. The report includes Spotify stream performance by track and a comparison of YouTube views, Spotify streams, and TikTok views across tracks.

### 3. Global Platform Performance
Cross-platform KPI cards and visual comparisons of engagement across Spotify, YouTube, and TikTok. Includes a platform breakdown and a date-based trend visual.

## Tools
- Microsoft Power BI
- Power Query (data preparation, if used in the original report)
- DAX measures and KPI targets (target measures are present in the report model)

## Files
- `dashboard/DVPROJECT.pbix` — original Power BI report.
- `assets/` — image resources embedded in the report.
- `docs/dashboard-guide.md` — page-by-page guide and report inventory.

## How to open
1. Install Microsoft Power BI Desktop.
2. Open `dashboard/DVPROJECT.pbix`.
3. Use the page tabs to navigate the three report pages.
4. Use the artist slicer and report interactions to explore the data.

## Scope and data notes
This repository packages the supplied Power BI report. The report metadata identifies the primary table as `Most Streamed Spotify Songs 2024` and includes a separate `Platform Table` used in platform analysis.

The source dataset file, its license/provenance, and the detailed transformation history were not supplied separately. This README therefore does not claim a specific row count, data-cleaning workflow, DAX formula, or numerical business finding that cannot be verified from the report metadata alone.

## Repository structure
```text
global-streaming-media-analytics/
├── README.md
├── dashboard/
│   └── DVPROJECT.pbix
├── docs/
│   └── dashboard-guide.md
└── assets/
```
