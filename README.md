# Scopecraft

Scopecraft is a standalone, browser-based research-scope and agent-handoff builder. It turns one topic into a consistent thesis, capability chain, scope guard, comparison matrix, evidence standard, update review, and reusable agent prompt.

## Use

Open `index.html` directly, or run:

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173>.

1. Replace the title with the topic or domain.
2. Select **Adapt whole document** to propagate it through the brief.
3. Edit any field in place. Changes autosave in the browser.
4. Use **Build + copy prompt**, **Download filled HTML**, or **Print / PDF**.

Scopecraft has no build step, runtime dependencies, analytics, or network calls.

## Development

The app is a single self-contained HTML file. Validate it with any HTML parser and exercise it in a modern browser.

## License

MIT
