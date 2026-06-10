# Publishing

How *The Quiet Game* is built and put online. The book is plain Markdown in `src/`;
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

`./book` is build output and is git-ignored — never commit it.

## Automatic deploy to GitHub Pages

`.github/workflows/deploy.yml` builds the book and publishes it to GitHub Pages on every push
to the **`main`** branch (and on manual dispatch). To turn it on, once:

1. Push this repository to GitHub (`qvisty/litrpg`).
2. In **Settings → Pages**, set **Source = GitHub Actions**.
3. Merge work into `main` (or run the workflow manually from the **Actions** tab).

The published URL will be `https://qvisty.github.io/litrpg/` (or your custom domain).

> **Note:** drafting happens on the `claude/litrog-book-github-dpns3l` branch. The deploy
> targets `main`, so the public site only updates when work is merged there — handy for
> keeping rough drafts off the live site. If you'd like the draft branch to publish to a
> preview instead, say so and the workflow can be adjusted.

## Adding a chapter (checklist)

1. Create `src/part-N/chapter-NN.md` (zero-padded).
2. Add a line for it in `src/SUMMARY.md`.
3. Preview with `mdbook serve`.
4. Update the continuity ledger in `docs/STORY_BIBLE.md` if anything new must stay consistent.
5. Commit with a clear message (note any historical facts relied on).
