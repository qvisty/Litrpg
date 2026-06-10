# Style Guide

Conventions that keep every chapter feeling like one book. Update as we settle preferences.

## Voice & prose
- **Tone:** dark, grounded, restrained. Understatement over melodrama. The war does the
  heavy lifting; we don't editorialize the horror, we report it and let it land.
- **Tense:** past tense. **POV:** third person limited, one protagonist per chapter (or clearly
  marked scene). Never head-hop inside a scene.
- **Sentences:** lean. Short for fear and violence; longer for stillness and memory.
- **Research honesty:** real dates, places, kit and operations stay accurate. When unsure,
  flag it in the chapter's commit message rather than inventing silently.

## POV rotation
- Label each chapter with whose POV it is (in the bible's continuity ledger, not on the page).
- Hold the **misdirection**: early on, weight page-time and heroic framing toward the
  protagonist who will die, so the loss lands.

## Rendering the system on the page
- The system is **diegetic and sparse.** It appears in moments of stakes, not constantly.
- Present system text as a blockquote so it reads as an intrusion into the prose:

  > **NERVE** holds. *(+1)*
  > A thing you did not ask for has decided that mattered.

- Cold, administrative, slightly inhuman wording. Never chirpy gamer-speak.
- Numbers appear only when they sharpen the moment. No stat-block dumps mid-scene; if a full
  status is shown, keep it short and put it at a natural pause.

## Formatting (mdBook / Markdown)
- One chapter per file under `src/part-N/chapter-NN.md`. Zero-pad numbers (`chapter-03.md`).
- Every new chapter gets a line in `src/SUMMARY.md` — mdBook only includes what's listed.
- Chapter heading is a single `# Chapter N` (optionally `# Chapter N — Title`).
- Scene breaks: a centered `* * *` (literally `<p style="text-align:center">* * *</p>` or a
  Markdown `---` if a harder break is wanted).
- Keep Danish/German/Russian phrases italicized; translate or gloss in-line when meaning
  matters to the reader.

## Naming & consistency
- Lock each character's name, rank and spelling in the story bible the first time they appear.
- British vs American English: pick one per the book's language setting (English) — default to
  **British** spelling for the European theatre flavour unless the author prefers American.
