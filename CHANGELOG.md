# Changelog

Versions follow the git tags of the repository.

## [1.0.0] - 2026-11-23

Version used for the synthetic pools of the article *Synthetic Handwriting for HTR Fine-Tuning: Controlled Evaluation
Across Languages, Domains and Data Sizes*.

### Added
- `--text-lines` mode in `build_dataset.py`: one sample per non-empty line of an external corpus, without sentence
  splitting or word-count filtering, for synthetic data with a domain-matched vocabulary (12f0918).
- `--unique-texts` flag: each text is rendered with a single random font, which maximizes text diversity (bcb9707).
- `CITATION.cff`, `.zenodo.json` and this changelog.

### Fixed
- Automatic calculation of `max_articles` with `--unique-texts`, and the doubled `output_` prefix of output folders
  (85593a0).

### Changed
- `.gitignore`: font selections, previews, aborted outputs and backups are never versioned (7dd0be4, 6c978d9).

## [0.1.0] - 2026-04-07

First tagged version.
