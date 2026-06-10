# The Quiet Game

*A grounded WWII LitRPG. Working title.*

A war novel with a secret. No magic, no monsters. The Second World War unfolds exactly
as it did, except that a handful of people, scattered across the fronts, each discover a
hidden system that quietly measures and rewards real human qualities: nerve, cunning,
endurance, the choice to save someone when running would be easier. Each believes they
are the only one. None of them know who is keeping score, or why.

This repository is both the **source** of the book (plain Markdown, one file per chapter)
and the **published site** (a clean, searchable reading experience via
[mdBook](https://rust-lang.github.io/mdBook/) deployed to GitHub Pages).

## Read it

Once GitHub Pages is enabled, the latest version is published automatically. See
[`docs/PUBLISHING.md`](docs/PUBLISHING.md) for how the site is built and deployed.

## Repository layout

| Path | What it holds |
|------|---------------|
| `src/` | The book itself, one Markdown file per chapter |
| `src/SUMMARY.md` | The table of contents (mdBook reads this to order chapters) |
| `book.toml` | mdBook configuration (title, theme, build options) |
| `docs/STORY_BIBLE.md` | The master plan: premise, characters, the system, tone, continuity |
| `docs/STYLE_GUIDE.md` | Prose, tense, POV and formatting conventions for consistency |
| `docs/SYSTEM.md` | The rules of the hidden game system (stats, skills, costs) |
| `docs/PUBLISHING.md` | How to build locally and how the GitHub Pages deploy works |
| `.github/workflows/deploy.yml` | CI that builds the book and publishes to GitHub Pages |

## Status

🚧 **In planning & early drafting.** The publishing pipeline and story bible are in place.
Chapters are written into `src/` as the plan is locked. Open creative decisions are tracked
at the top of `docs/STORY_BIBLE.md`.

## Build locally

```bash
# Install mdBook (requires Rust toolchain), or download a release binary
cargo install mdbook

# Live-preview while writing (auto-reloads in the browser)
mdbook serve --open

# Produce the static site into ./book
mdbook build
```

## A note on the subject

This is fiction set against a real war in which real people suffered. It aims to treat
that weight honestly: the enemy is human, atrocity is never "loot," and the game system
never makes the cost of war cheap. That seriousness is the point of the story, not a
constraint on it.
