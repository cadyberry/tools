# Tools

Fast, in-browser utilities. No account. No upload. No tracking.

**Live site:** https://cadyberry.github.io/tools/

---

## Tools

| Tool | What it does |
|------|-------------|
| [JSON Formatter](json-formatter/) | Paste messy JSON, get it cleaned up and validated instantly |
| [CSV ↔ JSON](csv-to-json/) | Convert between spreadsheet data and structured JSON, either direction |
| [Diff Viewer](diff-viewer/) | Paste two versions of any text and see exactly what changed |
| [List Sorter](list-sorter/) | Sort, deduplicate, shuffle, and clean any line-by-line list |
| [Unit Converter](unit-converter/) | Convert between units across length, weight, temperature, cooking, data, and more |

---

## How it's built

- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step
- Each tool is a single self-contained `index.html` file
- Works offline after the page loads
- Hosted on GitHub Pages

## Adding a tool

1. Create a new folder (e.g. `my-tool/`)
2. Add an `index.html` — keep it self-contained, no external fetch calls
3. Add a card to `index.html` in the root
4. Open a PR

## Running locally

Clone the repo and open any `index.html` directly in your browser. No server required.

```bash
git clone https://github.com/cadyberry/tools.git
cd tools
open index.html
```
