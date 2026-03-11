# OpsPulse — Changelog

## [1.1.0] — Project Restructure

- Extracted inline `<style>` → `src/css/main.css`
- Extracted inline `<script>` → `src/js/app.js`
- `index.html` now links external CSS and JS files
- Added `public/favicon.svg` (OpsPulse branded SVG icon)
- Added `supabase/schema.sql` with full DB schema + `get_dashboard_metrics()` function
- Added `supabase/integration.js` — drop-in Supabase data layer (Option A: polling, Option B: realtime)
- Added `.gitignore`, `README.md`

## [1.0.0] — Hackathon Submission (Horizon 1.0)

- Login screen with Owner/Manager role toggle
- 2-step Signup flow
- Owner Dashboard: Stress Score, KPI Row, Delivery Trend, Cancellation Radar, Speedometers
- Manager Dashboard: Stress Score, KPI Row, Stock Levels, Delivery Stacked Bar, Action Items, Alerts Log
- War Room overlay (auto-triggers on crisis)
- Live simulation (3s interval nudges)
- Light/Dark theme toggle
- Crisis Badge (fixed bottom-right)
- Ticker bar with live alerts

