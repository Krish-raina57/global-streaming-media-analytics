# Dashboard Guide

Inventory reconstructed from the supplied Power BI report file (`DVPROJECT.pbix`).

## Page 1: GLOBAL STREAMING OVERVIEW

- **kpi** — Spotify Streams
- **kpi** — YouTube Views
- **kpi** — TikTok Views
- **kpi** — Track Score
- **kpi** — Explicit Track
- **textbox**
- **image**
- **image**
- **image**
- **image**
- **image**

## Page 2: ARTIST PERFORMANCE OVERVIEW

- **slicer** — Artist
- **kpi** — Song Target, Track
- **kpi** — Spotify Streams, Spotify Target
- **kpi** — YouTube Target, YouTube Views
- **kpi** — TikTok Target, TikTok Views
- **kpi** — Track Score, TrackScore Target
- **clusteredBarChart** — Spotify Streams, Track
- **clusteredColumnChart** — Spotify Streams, TikTok Views, Track, YouTube Views
- **textbox**

## Page 3: GLOBAL PLATFORM PERFORMANCE

- **textbox**
- **kpi** — Spotify Streams, Spotify Target
- **kpi** — YouTube Target, YouTube Views
- **kpi** — TikTok Target, TikTok Views
- **clusteredBarChart** — Spotify Streams, TikTok Views, Track, YouTube Views
- **donutChart** — Platform, Spotify Streams, TikTok Views, YouTube Views
- **lineChart** — Date, Spotify Streams, TikTok Views, YouTube Views

## Notes

- The report contains three pages.
- The primary data table is `Most Streamed Spotify Songs 2024`.
- The report also references `Platform Table` for platform-level comparison.
- Artist selection is available on the Artist Performance page.
- The report contains target measures such as `Song Target`, `Spotify Target`, `YouTube Target`, `TikTok Target`, and `TrackScore Target`.
- Exact DAX expressions and source-data provenance have not been documented here because they were not verified from the supplied file.