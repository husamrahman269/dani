# Changelog

All notable changes to this project are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.0.0] — 2025

### Added
- Faithful JavaScript port of the original MSX BASIC DANI program
- CRT monitor UI with scanlines, phosphor glow, and screen flicker
- Green / amber phosphor colour toggle
- Live stats display (words learned, links, inputs)
- `list` command — renders the full word-link graph
- `reset` command — clears all learned data
- Animated boot sequence
- Original BASIC source preserved in `archive/DANI_original.bas`
- Scanned magazine pages preserved in `docs/`

### Notes
- Original algorithm by Sean Davidson, MSX Computing, February 1987
- Port targets 100% algorithmic fidelity to the BASIC original
