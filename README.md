# pvp-cockpit-studio

Studio-facing copies of the Voodoo Midcore PvP Cockpit, one folder per game, served with GitHub Pages:

- `castle-rivals-cockpit/` — Castle Rivals × Salt Castle → https://bu-fanchen-maker.github.io/pvp-cockpit-studio/castle-rivals-cockpit/
- `tribal-clash-cockpit/` — Tribal Clash × Beijing Duotai → https://bu-fanchen-maker.github.io/pvp-cockpit-studio/tribal-clash-cockpit/ (opens in Chinese; EN | 中文 toggle in the header)

Each folder holds `index.html` (same code as the internal cockpit, built with `build_page.py --studio <game> --passphrase …`) and the game's data as `*.json.enc` — AES-GCM encrypted, decrypted in the browser after the passphrase prompt. No plain data is stored in this repo. Refreshed daily by the cockpit refresh task.
