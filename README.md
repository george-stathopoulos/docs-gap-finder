# Docs Gap Finder

Find the questions your documentation does not answer yet, ticket by ticket. A Chrome/Edge extension for Zendesk plus a small web app. No AI: matching is deterministic word comparison, and ticket text never leaves your browser.

- 🌐 Website: https://george-stathopoulos.github.io/docs-gap-finder/
- 🚀 App: https://support-docs-gap-finder.george-stathopoulos.workers.dev/
- 📖 Guides: [docs/](docs/getting-started.md)

This repository holds the website and the user guides. The app and extension source is kept in a separate private repository.

## Guides
1. [Getting started](docs/getting-started.md) · 2. [Indexing](docs/indexing.md) · 3. [The extension](docs/extension.md) · 4. [Scanning a ticket](docs/scanning.md) · 5. [How matching works](docs/matching.md) · 6. [Status icon](docs/status-icon.md) · 7. [Training](docs/training.md) · 8. [Findings](docs/findings.md) · 9. [Team](docs/team.md) · 10. [Privacy](docs/privacy.md) · 11. [Troubleshooting](docs/troubleshooting.md) · 12. [Glossary](docs/glossary.md)

## Build the website
```
npm install
npm run build   # website/dist
```
Publishing to GitHub Pages: `bin/publish-site.sh` (only when intended).
