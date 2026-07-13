# HurryApp — Find a throne. Fast. 🧻

Community map of usable public bathrooms, rated in toilet-paper rolls by people
who were there in their darkest hour.

- `index.html` — the whole app (Leaflet + CARTO map, live data from Supabase)
- Data: Supabase Postgres, exposed read-only through the `map_thrones` view (no PII)
- Phase 2: writes (rate/add thrones) with Supabase Auth, photo gallery

*Make your shitting great again.*
