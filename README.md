# CoinTicker × BingX — firmware releases

Release builds for the CoinTicker × BingX desk ticker. The tickers check this repo's latest
release on power-up and install updates from Menu → Firmware.

Each release holds:

- `firmware.bin` — the ESP32 application image
- `manifest.json` — version, size, SHA-256 and an ECDSA P-256 signature over them

A ticker installs only a signed build newer than its own. Sources are not published here.
