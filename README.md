# UUID/GUID Generator

Generate random UUIDs for development, testing, and databases.

Live: <https://crusher-labs.github.io/uuid-generator/>

## What it does

Generate random UUIDs for development, testing, and databases.

## Privacy

This tool runs entirely in your browser. There is no server. No data is uploaded, no telemetry, no analytics. The only network requests fired are the page-load fetches for the framework's CSS / JS (from `cdn.jsdelivr.net` and `fonts.googleapis.com` / `fonts.gstatic.com`); your inputs and outputs never leave the tab.

## Framework / hosting

- Static HTML / CSS / JS deployed via GitHub Pages from this repo's `main` branch.
- UI chrome is the published `crusher-ui-kit@0.1.6` static contract — see the workspace `CLAUDE.md` for the contract details.

## Development

- Open `index.html` directly in a browser. No build, no dependencies.
- Or serve the parent workspace via the hub's preview server: `cd ../../tools-hub && npm run preview` then visit `http://127.0.0.1:8723/utility-tools/uuid-generator/`.

## License

MIT.
