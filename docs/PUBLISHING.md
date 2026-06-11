# Publishing

How *The Quiet Game* is built and put online. The book is plain Markdown in `src/`, and
[mdBook](https://rust-lang.github.io/mdBook/) turns it into a static website that GitHub
Pages serves.

## Build locally

You need either the `mdbook` binary (download from the
[mdBook releases](https://github.com/rust-lang/mdBook/releases)) or the Rust toolchain:

```bash
cargo install mdbook        # one-time install

mdbook serve --open         # live preview at http://localhost:3000, auto-reloads
mdbook build                # writes the static site to ./book
```

`./book` is build output and is git-ignored, never commit it.

## Automatic deploy to GitHub Pages

`.github/workflows/deploy.yml` builds the book and publishes it to GitHub Pages on every push
to the **`main`** branch (and on manual dispatch). To turn it on, once:

1. Push this repository to GitHub (`qvisty/litrpg`).
2. In **Settings → Pages**, set **Source = GitHub Actions**.
3. Merge work into `main` (or run the workflow manually from the **Actions** tab).

The published URL will be `https://qvisty.github.io/Litrpg/` (or your custom domain).

> **Troubleshooting, the most likely failure.** If the live site shows a plain white page with
> no menu, or chapters return 404, the Pages **Source** has been set to "Deploy from a branch"
> instead of "GitHub Actions". In that mode GitHub serves a Jekyll render of the repo root (the
> README) rather than the mdBook this workflow builds. Fix it at
> <https://github.com/qvisty/Litrpg/settings/pages>, set **Source = GitHub Actions**, then wait
> about a minute. A stale white page can also be a cached copy, bust it with a fresh private tab
> or a different network. This caught us once and cost real time.

> **Branch policy (author's standing rule):** **always deploy to `main`.** Work lands on
> `main` so the published site is always current. Each work session also leaves behind a
> snapshot **backup branch**. We keep only the **three most recent** backup branches and prune
> older ones. So `main` = the live trunk, and the recent feature/backup branches = rollback
> points.

## Adding a chapter (checklist)

1. Create `src/part-N/chapter-NN.md` (zero-padded).
2. Add a line for it in `src/SUMMARY.md`.
3. Preview with `mdbook serve`.
4. Update the continuity ledger in `docs/STORY_BIBLE.md` if anything new must stay consistent.
5. Commit with a clear message (note any historical facts relied on).
