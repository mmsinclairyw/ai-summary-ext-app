# ai-summary-ext-app

Chrome extension that summarizes the current page with an LLM

## What it does

- Popup shows a 5-bullet summary
- Manifest V3 service worker, no build step
- Reads the page, extracts main text, sends to your endpoint
- Options page for API base and key

## Usage

```bash
# open any article, click the icon, get a 5-bullet summary
```

## Installation

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   └── usage.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.

## License

MIT licensed, see LICENSE.
