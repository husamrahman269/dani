# Contributing

Thanks for your interest in contributing to DANI!

## Ways to contribute

- **Bug reports** — open an issue describing what happened, what you expected, and your browser/OS
- **Algorithm improvements** — the JS port aims for fidelity to the 1987 BASIC original; changes that improve fidelity are very welcome
- **UI enhancements** — new colour themes, accessibility improvements, mobile layout fixes
- **Historical research** — corrections or additions to the documentation about the original program or Sean Davidson's work

## Ground rules

1. Keep `index.html` self-contained — no build step, no bundler, no npm
2. The core `DANI` module must remain a faithful port of the BASIC algorithm
3. New UI features go in the UI Controller section, not in the DANI module
4. Test in Firefox and Chrome before submitting a PR

## Submitting a pull request

1. Fork the repository
2. Create a branch: `git checkout -b your-feature-name`
3. Make your changes
4. Open a pull request with a clear description of what changed and why

## Code style

- Vanilla JS, no frameworks
- Comments referencing original BASIC line numbers are encouraged (e.g. `// line 770-780`)
- Keep the single-file constraint — everything in `index.html`
