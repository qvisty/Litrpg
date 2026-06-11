# Style Guide

Conventions that keep every chapter feeling like one book. Update as we settle preferences.

## Hard punctuation rules (apply everywhere, prose and docs)

1. **No em-dashes.** Never use the long dash. Replace it with a comma, a full stop, a colon,
   or a pair of parentheses, or rewrite the sentence so it is not needed.
2. **No semicolons.** Replace with a full stop and a fresh sentence, or with a comma where the
   grammar allows.

These two rules are absolute. A draft that contains either mark is not finished.

## Voice and prose
- **Tone:** dark, grounded, restrained. Understatement over melodrama. The war does the heavy
  lifting. We do not editorialize the horror, we report it and let it land.
- **Tense:** past tense. **POV:** third person limited, one protagonist per chapter (or clearly
  marked scene). Never head-hop inside a scene.
- **Sentences:** lean. Short for fear and violence, longer for stillness and memory.
- **Research honesty:** real dates, places, kit and operations stay accurate. When unsure, flag
  it in the chapter's commit message rather than inventing silently.

## POV rotation
- Label each chapter with whose POV it is (in the bible's continuity ledger, not on the page).
- Hold the **misdirection**. Early on, weight page-time and heroic framing toward the
  protagonist who will die, so the loss lands.

## Rendering the system on the page
- The system is **diegetic and sparse.** It appears in moments of stakes, not constantly.
- **The players know they have it.** Show them reading their stats, reflecting on which are
  growing, theorising, experimenting, taking pride, and noticing when a new function appears.
  Their evolving relationship with the interface is part of the story, not background.
- **Two channels.** The system shows up *woven into scenes* and as a *short end-of-chapter
  sheet*. Use both. Never only the chapter-end sheet.
  - **In-scene:** a line or two, set off as a blockquote, that bends a decision or twists the
    tension, then the prose moves on. It may speak unbidden.

    > **NERVE** holds. *(+1)*
    > A thing you did not ask for has decided that mattered.

  - **End-of-chapter sheet:** the ledger's own record, in the system's cold administrative
    voice. **One sheet per POV character, at the end of their chapter,** so a flat sheet
    (Mercer) can be read against a climbing one (Jonas). Keep it lean. Every number must mean
    something new since last time. The vocabulary darkens as the book descends the mystery
    ladder (`docs/MYSTERY.md`), from innocuous early to abattoir-cold late.
- **It is basic at first and gains functionality.** Early sheets are crude and short. New
  readouts, skills, notifications, and choices appear over the book (`docs/SYSTEM.md`, "The
  interface, and how it evolves"), and the character remarks on each as new.
- **The discovery exception.** A player's introductory chapter may carry **no system text at
  all** until a single first-contact beat at the very end, so the uncanny is earned and the
  reveal lands hard. Chapter One does exactly this: pure grounded war, then the overlay surfaces
  on the final page, then the reader gets the cold sheet.
- Cold, administrative, slightly inhuman wording. Never chirpy gamer-speak.
- **Load-bearing only.** Numbers appear when they sharpen the moment, the choice, or the dread.
  No stat-block dumps that stall the scene. If a readout is decorative, cut it.

## Formatting (mdBook / Markdown)
- One chapter per file under `src/part-N/chapter-NN.md`. Zero-pad numbers (`chapter-03.md`).
- Every new chapter gets a line in `src/SUMMARY.md`. mdBook only includes what is listed.
- Chapter heading is a single `# Chapter N` (optionally `# Chapter N, Title`).
- Scene breaks: a centered `* * *` (literally `<p style="text-align:center">* * *</p>`, or a
  Markdown `---` if a harder break is wanted).
- Keep Danish, German and Russian phrases italicized. Translate or gloss them in line when the
  meaning matters to the reader.

## Technical war detail
Real hardware (armour, guns, aircraft, ballistics, doctrine) is a feature for the war-tech
reader. Full design and the materiel timeline live in `docs/WARCRAFT.md`. On the page:
- **Accurate to the month and front.** Verify load-bearing facts before a chapter ships, and log
  them in the war anchors table.
- **Through an expert eye.** A sniper thinks in wind and drop, a tank man in ranges and angles.
  The reader learns by standing behind a competent, frightened character, never from a manual.
- **Dark, never gun-porn.** Keep the body in the machine. Bad news more often than good. A detail
  that does not change a decision, the tension, or the meaning is cut.
- **It couples to the system.** Skills are technical mastery, and a shot against armour resolves
  through the throw. Evoke the cold penetration math so it rhymes with the ledger.

## Place names (anglicise for the reader)
The story is set in real places, but the prose serves an English reader first and must never
advertise the author's nationality. So:
- **Translate the generic part to English.** gade becomes Street, plads becomes Square, vej
  becomes Road, havn becomes Harbour, torv becomes Square or Market, allé becomes Avenue.
  Examples used so far: Sankt Anne Square, Toldbod Street, Borger Street.
- **Avoid special characters** in any proper noun (no æ, ø, å, ö, ü). Drop or respell them so
  the word reads cleanly, for example Dragor (not Dragør) and Malmo (not Malmö). If a name only
  works with a special character, choose a different name.
- **Keep a light Northern European flavour** in the proper part (Sankt, Toldbod, Borger), so it
  stays grounded and a Danish reader still feels it is loyal to the place, without it ever
  tripping an English reader.
- **Use established English exonyms** where they exist (Copenhagen, not København. Sweden, not
  Sverige).
- The setting remains Denmark and the real history stands. This is about orthography and the
  reading ear, not about relocating the story. It could have been any occupied country, and it
  should read that smoothly.

## Naming and consistency
- Lock each character's name, rank and spelling in the story bible the first time they appear.
- British versus American English: pick one per the book's language setting (English). Default
  to **British** spelling for the European theatre flavour unless the author prefers American.
