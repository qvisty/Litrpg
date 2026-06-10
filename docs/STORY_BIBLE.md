# Story Bible — *The Quiet Game* (working title)

The single source of truth for the book. Read this before writing or editing any chapter.
Everything here is a decision we have made together, or an **OPEN QUESTION** still waiting on
the author. Keep this file honest — when the story changes, change this first.

---

## ✅ Locked decisions

| Decision | Choice |
|----------|--------|
| **Language** | English |
| **Genre** | Grounded WWII LitRPG — a *hidden* system inside the real war |
| **Speculative element** | A secret RPG-like "score" only a few people can see. No magic, no monsters. |
| **System crunch** | Medium — clear stats, skills and levels, but never at the cost of the story |
| **Tone** | Dark & realistic. The war's horror is taken seriously; power-fantasy is kept on a leash. |
| **Structure** | Multiple POV protagonists who each discover the system independently and slowly converge |
| **Cast size** | **Three** POV protagonists across the book, but only ever **two alive at once** — always one on each side, enemies from the start (the Allied killer replaces the dead Dane opposite the German). |
| **The pairing** | **Across enemy lines** — an Allied/Danish player and a Wehrmacht (German) soldier, each only dimly aware the other exists. The most morally complex option; sharpens the "rewards humanity, not killing" core. |
| **The German's job** | A **medic / Sanitäter (field medical orderly)** or field doctor — a *healer*. His ethical engine: the war forces this life-saver into *necessary killing*, which the system answers wrongly/coldly. (Doctor vs. front-line Sanitäter still TBD.) |
| **The third protagonist** | A **hardened Allied killer** (sniper/commando) who steps in after the Dane dies — the direct mirror/inversion of the German healer. The killer vs. the healer. |
| **The gut-punch** | **One of the two POV protagonists actually dies partway through** — a deliberate, rare move. Their death is the doorway into the larger mystery. |
| **Who dies** | **The Dane (the Allied protagonist).** The bold misdirection: the reader is led to believe the Dane is *the* hero (most page-time, classic hero's arc) — then he dies, and the **German** turns out to be the true throughline all along. Flips the reader's sympathy onto "the enemy." |
| **When the death lands** | **Early and unexpected — a shock.** He dies before the reader is ready: abrupt, almost meaningless, the way war actually is. Sets the tone instantly (no one is safe; the system never makes death cheap) and hands the book to the German sooner. |
| **Publishing** | Both: Markdown source in `src/` **and** a generated GitHub Pages site (mdBook) |
| **Branch / deploy policy** | **Always deploy to `main`** (it is the live trunk). Each session leaves a snapshot **backup branch**; keep only the **three most recent**, prune older. |

### The core engine of the system (locked in concept)

The system rewards **real skill and human choice — not killing.** You gain ground for
courage, cunning, leadership, endurance, for saving someone when running would be easier.
But there is a **price**: the more you lean on the system, the more detached you feel from
your own humanity. That tension is the dark heart of the book. (Full mechanics: `SYSTEM.md`.)

### Why "one of them sees the other" matters

The system is not given to one person. A small number of people across the war each discover
the same hidden interface, each believing they are alone. This gives us:
- freedom to portray the whole war (different fronts, sides, years) without stretching one
  character past belief;
- a built-in mystery engine (who made it? why these people? what happens if two meet?);
- a natural convergence as the system pulls them toward one another.

---

## ❓ OPEN QUESTIONS — waiting on the author

These are the next decisions. Nothing downstream gets written until they're settled.

*(Resolved — pairing, who dies, and when — moved up to "Locked decisions".)*

1. **The origin mystery.** *Deliberately deferred — the author has a plot conversation they
   want to have first.* Do NOT lock the system's origin (sci-fi? divine? unknown? ambiguous?)
   until that conversation happens. Build everything else so it stays compatible with any
   answer.

2. **The two characters' specifics.** Names, ages, exact fronts and the moment each discovers
   the system. (Flows out of the origin conversation — the Dane needs enough life for his
   early death to hurt; the German needs room to become the true lead.)

3. **The point of contact.** Since the Dane dies *early*, how do the two ever "touch"? Do they
   meet once before he dies? Does the German only sense the Dane's score wink out? This is the
   hinge between Act-structure and the mystery — settle it alongside Q1.

4. **Final title.** "The Quiet Game" is a working title only.

---

## Protagonists

Three POV protagonists across the book, but only ever **two alive at once** — always one on
each side, enemies from the start. The Dane opens opposite the German, dies early, and the
hardened Allied killer steps into the empty chair to become the German's new opposite number.

> **The thematic spine:** the war is fought between a man whose calling is to **heal** and a
> man whose trade is to **kill** — and the hidden system rewards *humanity, not killing*. So
> the healer is punished by the very thing that should reward him (war forces him to kill),
> and the killer's path to growth may be the hardest thing imaginable for him: to spare, to
> save. The system is the cruel mirror that makes each man the other's inverse.

### Protagonist A — The Dane *(name TBD)*
- **Role in the misdirection:** seems-to-be-the-hero → **dies early & unexpectedly**
- **Side:** Allied (Danish — resistance / in Allied service, specifics TBD)
- Front & years: TBD
- Want / Need: TBD
- Relationship to the system: a player; his early death is the reader's first proof that the
  score does not keep anyone safe — and possibly the German's first awareness of another player.
- Arc: cut brutally short — that is the point.

### Protagonist B — The German *(name TBD)* — **true throughline**
- **Role:** the real protagonist, revealed once the Dane dies
- **Side:** Wehrmacht
- **Job:** a **medic / field medical orderly (Sanitäter)** or field doctor — a *healer*. (Exact
  rank/role TBD: front-line Sanitäter vs. Truppenarzt/doctor.)
- **Core dilemma:** his whole identity is saving lives, yet the war forces him into *necessary
  killing*. Each kill wounds him — and the system's response to it is wrong/cold, deepening the
  horror. The "Distance" cost is doubly cruel on a man made of care: the better he gets, the
  number he grows to the compassion he's fighting to keep.
- Want / Need / Arc: TBD
- Relationship to the system: a player; feelings TBD (likely shame, bargaining, dread).

### Protagonist C — The hardened Allied killer *(name TBD)*
- **Role:** enters around/after the Dane's death; becomes the German's new opposite number
- **Side:** Allied (sniper or commando — a man whose **trade is killing**). Nationality/front TBD.
- **Function:** the direct mirror/inversion of the German healer. Possible arc: the killer who
  must learn to spare or save. Likely also a system-player (→ the two converge). TBD.
- Want / Need / Arc: TBD

---

## The world & the war (anchors)

A running list of the real historical anchors we commit to, so chapters stay consistent.
Add dates, operations, places and facts here as they're used, with a source note when it
matters. *(Empty until drafting begins.)*

| Date | Event / place | Used in | Note |
|------|---------------|---------|------|

---

## Structure & roadmap

- **Part One — The Score Begins:** establish both protagonists, their fronts, and the first
  contact with the system. Plant the misdirection.
- **Part Two — *TBD***
- **(more parts as the plan firms up)**

The death of the POV protagonist is the hinge the structure turns on; its placement (Open
Question 3) decides where the Part breaks fall.

---

## Continuity ledger

Track anything that must stay consistent: names, dates, who-knows-what-about-the-system, and
each protagonist's current stats/skills. *(Empty until drafting begins.)*
