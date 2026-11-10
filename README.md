pose-harvester-lite

A tiny browser prototype that demonstrates the workflow: discover downloadable CSV/JSON pose files (simulated), download and parse them, validate schema (required keys/columns and numeric ranges), log provenance, and produce a compact report for inspection. No network calls are made — two sample files are embedded. Open index.html in a modern browser.

Limitations: This is a demo. Replace the simulatedFetcher() with real fetch() calls and add robust crawling, robots checks, and rate limiting before use on the web.