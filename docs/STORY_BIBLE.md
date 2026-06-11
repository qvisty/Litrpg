# Story Bible: *The Quiet Game* (working title)

The single source of truth for the book. Read this before writing or editing any chapter.
Everything here is either a decision we have made together, or an **OPEN QUESTION** still
waiting on the author. Keep this file honest. When the story changes, change this first.

---

## House style (always)

Two hard rules for every word in this repository, prose and docs alike:

1. **No em-dashes** (the long dash). Use commas, full stops, colons, or parentheses, or
   restructure the sentence.
2. **No semicolons.** Use a full stop and a new sentence, or a comma, instead.

Full conventions live in `STYLE_GUIDE.md`.

---

## Locked decisions

| Decision | Choice |
|----------|--------|
| **Language** | English |
| **Genre** | Grounded WWII LitRPG, a *hidden* system inside the real war |
| **Speculative element** | A secret RPG-like "score" only a few people can see. No magic, no monsters. |
| **System crunch** | Medium. Clear stats, skills and levels, but never at the cost of the story. |
| **Tone** | Dark and realistic. The war's horror is taken seriously. Power-fantasy is kept on a leash. |
| **Structure** | Multiple POV protagonists who each discover the system independently and slowly converge. |
| **Cast size** | **Three** POV protagonists across the book, but only ever **two alive at once**, always one on each side, enemies from the start. The Allied killer replaces the dead Dane opposite the German. |
| **The pairing** | **Across enemy lines.** An Allied/Danish player and a Wehrmacht (German) soldier, each only dimly aware the other exists. The most morally complex option, and it sharpens the "rewards humanity, not killing" core. |
| **The German's job** | A **medic, or Sanitäter (field medical orderly), or field doctor**, a *healer*. His ethical engine: the war forces this life-saver into *necessary killing*, which the system answers wrongly and coldly. (Doctor versus front-line Sanitäter still TBD.) |
| **The third protagonist** | A **hardened Allied killer**, the morally darkest of the three, who steps in after the Dane dies. **Specialisation: sniper.** The direct mirror and inversion of the German healer, the killer against the healer. A sniper's trade is *distance*, which is also the system's name for the loss of humanity, so he begins already hollow and therefore safe. |
| **The killer is also a player** | Yes. The healer and the killer are **two players on opposite sides**, drawn inevitably toward each other. They may be the only two people alive who can understand each other's curse, and still they are enemies. This is the engine of the convergence mystery. |
| **The gut-punch** | **One of the two opening POV protagonists actually dies partway through**, a deliberate, rare move. The death is the doorway into the larger mystery. |
| **Who dies** | **The Dane (the Allied protagonist).** The bold misdirection: the reader is led to believe the Dane is *the* hero (most page-time, classic hero's arc), then he dies, and the **German** turns out to be the true throughline all along. It flips the reader's sympathy onto "the enemy." |
| **When the death lands** | **Early and unexpected, a shock.** He dies before the reader is ready: abrupt, almost meaningless, the way war actually is. It sets the tone instantly (no one is safe, the system never makes death cheap) and hands the book to the German sooner. |
| **Publishing** | Both: Markdown source in `src/` **and** a generated GitHub Pages site (mdBook). |
| **Branch / deploy policy** | **Always deploy to `main`** (it is the live trunk). Each session leaves a snapshot **backup branch**. Keep only the **three most recent**, prune older. |

### The core engine of the system (locked in concept)

The system rewards **real skill and human choice, not killing.** You gain ground for courage,
cunning, leadership, endurance, and for saving someone when running would be easier. But there
is a **price**: the more you lean on the system, the more detached you feel from your own
humanity. That tension is the dark heart of the book. Full mechanics live in `SYSTEM.md`.

### Why "one of them sees the other" matters

The system is not given to one person. A small number of people across the war each discover
the same hidden interface, each believing they are alone. This gives us:

- freedom to portray the whole war (different fronts, sides, years) without stretching one
  character past belief,
- a built-in mystery engine (who made it, why these people, what happens if two meet),
- a natural convergence as the system pulls the players toward one another.

---

## OPEN QUESTIONS, waiting on the author

These are the next decisions. Nothing downstream gets written until they are settled.

1. **The origin mystery.** **Architecture now locked.** The full layered truth, the reveal
   ladder, and the Part One seed map live in `MYSTERY.md` (author-only, full spoilers). What
   remains open there is tuning, not structure: the deepest nature of *It* (kept dark on
   purpose), the "third way" out of the final trap, and a few texture choices. The one thing
   every chapter must respect from day one: **the system feeds on humanity, and the Dane's
   early death is a harvest, planted to pay off at the floor of the book.**

2. **The three characters' specifics.** Names, ages, exact fronts, and the moment each
   discovers the system. The Dane needs enough life for his early death to hurt. The German
   needs room to become the true lead. The killer needs a trade (sniper or commando) and a
   nationality and front that can plausibly collide with a German medic.

3. **The point of contact.** Because the Dane dies *early*, how do the players ever "touch"?
   Does the German sense the Dane's score wink out at the moment of death? How and when do the
   German and the killer first register each other? This hinge ties straight into the mystery,
   so settle it alongside Question 1.

4. **Final title.** "The Quiet Game" is a working title only.

---

## Protagonists

Three POV protagonists across the book, but only ever **two alive at once**, always one on
each side, enemies from the start. The Dane opens opposite the German, dies early, and the
hardened Allied killer steps into the empty chair to become the German's new opposite number.

> **The thematic spine:** the war is fought between a man whose calling is to **heal** and a
> man whose trade is to **kill**, and the hidden system rewards *humanity, not killing*. So the
> healer is punished by the very thing that should reward him (war forces him to kill), and the
> killer's path to growth may be the hardest thing imaginable for him, to spare, to save. The
> system is the cruel mirror that makes each man the other's inverse. And both men carry it,
> which means each may be the only one who could ever understand the other.

*(All names and fronts below are proposals, easy to rename. They are concrete so drafting can
begin.)*

### Protagonist A: Aksel Holt, the Dane
- **Role in the misdirection:** seems-to-be-the-hero, then **dies early and unexpectedly**.
- **Side:** Danish resistance, Copenhagen.
- **Front and years:** occupied Copenhagen, autumn 1943. The real backdrop is the collapse of
  the policy of cooperation in August 1943 and the attempted deportation of Danish Jews in
  October 1943, a moment of genuine moral extremity, perfect ground for the system.
- Want and Need: TBD, but he is brave, decent, and good at this, the kind of man the reader
  roots for instantly.
- Relationship to the system: a player, and unknown to himself the **furthest along of anyone**.
  He is **assessed for two years without ever knowing it**, and only at the very end of his
  first chapter does the overlay surface and reveal that a count has been kept on him all along.
  He has no time to understand it. His ledger already reads *rare*. The high score reads as
  triumph. It is ripeness. (See `MYSTERY.md`, Layer 6.)
- Arc: cut brutally short. That is the point. His death is a **harvest**, planted from Chapter 1.

### Protagonist B: Jonas Keller, the German, the **true throughline**
- **Role:** the real protagonist, revealed once Aksel dies.
- **Side:** Wehrmacht.
- **Job:** a **Sanitäter (front-line medical orderly)**, a healer.
- **Front and years:** posted to the garrison in occupied Copenhagen in 1943 (so he and Aksel
  are enemies in the same city), then transferred to France and the Normandy meat-grinder in
  1944, where the war forces him to kill and where he meets the Allied killer.
- **Name note:** *Jonas* carries the Jonah resonance on purpose, the man swallowed whole. Keep
  it subtle. It is a common German name and never remarked on in the text.
- **Core dilemma:** his whole identity is saving lives, yet the war forces him into *necessary
  killing*. Each kill wounds him, and the system's response to it is wrong and cold, which
  deepens the horror. The "Distance" cost is doubly cruel on a man made of care. The better he
  gets, the number he grows to the compassion he is fighting to keep. He is the perfect
  specimen, being fattened (Layer 6).
- Want, Need, Arc: TBD.
- Relationship to the system: a player. Feelings TBD (likely shame, bargaining, dread). His
  first awareness of another player is feeling Aksel's score wink out at the instant of death.

### Protagonist C: Jack Mercer, the hardened Allied killer (the "villain" of the three)
- **Role:** enters after Aksel dies, becomes Jonas's new opposite number. The morally darkest of
  the three protagonists, the one the reader is meant to recoil from before they understand him.
- **Side:** British, Normandy and north-west Europe, 1944 onward.
- **Specialisation: sniper.** This is his whole craft and his whole identity. He kills at
  distance, never close, the target an object in a lens, no eye met, no name known. He is good
  at it the way Aksel was good at the resistance, the best anyone has seen.
- **The distance resonance (core to his design):** a sniper's trade *is* distance, and the
  system's price is named **Distance**, the loss of one's own humanity. So Mercer begins
  already hollowed out, maximally detached, and that is exactly why the harvest cannot touch
  him. His arc toward mercy is an arc toward *closing the distance*, becoming human again, and
  so becoming ripe. The safest man alive, for as long as he stays behind the glass.
- **Function:** the direct mirror and inversion of the German healer. The killer who must learn
  to spare or to save, and whose growth toward mercy is also his road to the harvest.
- **Name note:** *Mercer* buries the word *mercy*, the thing that will both save and doom him.
- **System:** **also a player.** While he stays a pure instrument of killing he scores almost
  nothing, which is exactly why he survives. The two converge across enemy lines, two men who
  share the one secret no one else would believe, and who are still sworn to kill each other.
- Want, Need, Arc: TBD.

### Recurring: the Steward *(name TBD)*
The human face that serves It (see `MYSTERY.md`). Appears **early in Copenhagen**, warm and
helpful, with one detail wrong. We do not know what he is for a long time.

---

## The world and the war (anchors)

A running list of the real historical anchors we commit to, so chapters stay consistent. Add
dates, operations, places and facts here as they are used, with a source note when it matters.
*(Empty until drafting begins.)*

| Date | Event / place | Used in | Note |
|------|---------------|---------|------|

---

## Structure and roadmap

- **Part One, The Score Begins:** establish the Dane and the German, their fronts, and the
  first contact with the system. Plant the misdirection, weighting heroic framing toward the
  Dane. Kill him early and without warning.
- **After the death:** the book passes to the German. The hardened Allied killer enters as the
  new opposite number, and we learn he too is a player.
- **Later parts:** TBD, building toward the convergence of healer and killer and the origin
  mystery.

The Dane's early death is the hinge the structure turns on. Because it lands early, Part One is
short and brutal, and the true shape of the book reveals itself only once he is gone.

---

## Continuity ledger

Track anything that must stay consistent: names, dates, who knows what about the system, and
each protagonist's current stats and skills. *(Empty until drafting begins.)*
