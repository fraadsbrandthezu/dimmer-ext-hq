# dimmer-ext-hq

Chrome extension that tracks reading time per tab

## Highlights

- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Popup shows today's total focus time

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT. Do whatever you want.
