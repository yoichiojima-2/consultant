# Changelog

## 1.2.0 — 2026-08-20

### New

- **Unit Economics framework (LTV / CAC / payback)** in `finance.md` — core metrics with formulas, healthy/warning thresholds, a worked subscription example, limitations, and framework combinations. Indexed in SKILL.md with a new quick-selection entry: *"Is this business model viable? Are customers profitable?"*

### Improved

- **Better triggering** — the skill description now covers the ways people actually ask for this help (business plan reviews, prioritization, executive summaries, case interview prep), so the skill activates even when no framework or the word "consulting" is mentioned.
- **Effort calibration** — new first guideline in "How to Consult": a quick question gets a focused answer built on one well-chosen framework; the full engagement flow is reserved for `/consult` and explicit deep dives.
- **Deliverables can be written to files** — `Write` added to the skill's allowed tools, so "offer a deliverable" (filled SWOT report, business case, project charter…) can actually produce a file.
- **Navigable Framework Index** — the alphabetical index in SKILL.md now links every framework directly to its reference file instead of naming an abstract category.
- **Refreshed market-sizing anchors** — US population (340M), households (132M), and GDP ($29T) updated in `cases.md`.

### Fixed

- **Divergent duplication of the Complete Consulting Flow** — the flow existed in both SKILL.md (11 steps) and `problem-solving.md` (12 steps, drifted). SKILL.md is now the single source of truth; `problem-solving.md` points to it.

### Docs

- **Improved README** (#7) — contributed by @webbrain-one.

## 1.1.0

- Added slash commands: `/consult` (full engagement flow), `/analyze` (PESTEL → 5 Forces → SWOT/3C), `/case-practice` (mock case interview with scoring).
- Added the "How to Consult" behavior guide to SKILL.md.
- Added CI validation for plugin manifests and relative markdown links.

## 1.0.1

- Fixed plugin install failure on older Claude Code versions: marketplace source path must start with `./`.
- Synced `plugin.json` and `marketplace.json` versions.

## 1.0.0

- Initial release: 50+ consulting frameworks across problem-solving, strategy, cases, business design, projects & change, finance, and operations, with ready-to-use templates.
