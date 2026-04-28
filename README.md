# Flightradar24 Crowdsourced Aircraft Database

Sharded by ICAO 24-bit hex prefix (first 2 chars).
- Files: 115 shards in `aircraft/`
- Format: `{ "hex": [reg, msn, built, type] }`
- Total entries: 500689
- License: CC0

## CDN access
`https://cdn.jsdelivr.net/gh/joniasus/fr24-aircraft-db-@main/aircraft/<prefix>.json`
