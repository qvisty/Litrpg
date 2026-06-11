# The System, Design Document

The full mechanics of the hidden game system, including things the characters never learn.
This is the *author's* reference. The reader only ever meets what a character has earned the
right to know (see `src/appendix-system.md` for the spoiler-safe, in-story version).

> **Style:** no em-dashes, no semicolons, here as everywhere (see `STYLE_GUIDE.md`).

> **Status:** Draft and provisional. The *origin* of the system is an OPEN QUESTION (see the
> story bible) and is intentionally left blank here. Everything below is written so it stays
> compatible with any origin we later choose.

---

## Design pillars

1. **Hidden from the world, known to the player.** Only a chosen few perceive it, and to
   everyone else a "player" is just an unusually capable, unusually haunted person. But the
   players themselves **know they have it.** They can see their stats, read their own sheet,
   feel it change. This is deliberate. The genre pleasure is a character who engages with the
   mechanics, and we want that pleasure.
2. **The players think about their stats.** They reflect on which attributes are growing, test
   themselves, theorise, take pride, worry, and notice when something is new. Their relationship
   to the interface is an active, evolving part of their inner life, not background flavour.
   (The deep *truth* of what the system is stays hidden. The *surface* mechanics are theirs to
   play with. The gap between the two is the tragedy.)
3. **It starts basic and grows.** Early on the interface is crude: a few attributes, surfacing
   on their own, barely legible. Over the book it gains functions (named skills, a summonable
   sheet, notifications, the sensing of other players, offers and choices). Each new function is
   a small reveal the character reacts to, and a step down the mystery ladder. See "The
   interface, and how it evolves."
4. **The system is an active agent, not a passive tool.** It does not only answer when checked.
   It intrudes, assesses, warns, withholds, and eventually bargains, of its own accord. It
   shapes decisions and therefore the plot. It is a character.
5. **It improves the story, it never blocks it.** The mechanics must earn their place by
   sharpening a scene, a choice, or the dread. They appear woven into the action and at chapter
   ends, never as a dump that stalls the narrative. If a stat readout is not making the moment
   better, it is cut.
6. **Rewards humanity, not slaughter.** Progress comes from courage, cunning, endurance,
   leadership, and mercy, all choices, not kill-counts. Killing earns little or nothing.
7. **It costs something.** The more a player leans on the system, the more detached from their
   own humanity they feel. Power and numbness rise together. The players can *see* this cost
   (Distance) climbing, and can do nothing to stop it, which is its own slow horror.
8. **Grounded.** No fireballs. Bonuses read as being *slightly* faster, steadier, luckier, or
   more persuasive than a human should be. Deniable, uncanny, never cinematic magic.

---

## Attributes

Five human attributes, all earned by what a person does and is. **Luck is not among them.** It
is a separate thing and works differently (see "Luck, and the throw").

| Attribute | What it governs | How it reads on the page |
|-----------|-----------------|--------------------------|
| **Nerve** | Fear control under fire | Hands that do not shake when they should |
| **Cunning** | Reading situations, traps, deception | Seeing the angle in time to use it |
| **Endurance** | Physical and mental stamina | Still standing when the body should have quit |
| **Influence** | Leadership, persuasion, presence | Others move because you asked |
| **Insight** | Perception, intuition, the unseen | Knowing a thing he was never told. Later, sensing the system and other players. |

## Luck, and the throw

Luck is the odd one out. It is not a human quality and it cannot be earned by courage or
practice the way the five attributes can. It is the **system's favour**, the weight it lays on
the dice when a player's fate hangs on chance. The ledger does not even call it luck. It calls
it **favour**, and that word is the truth told in plain sight, because it is not random. (The
players will think of it as luck. They are wrong. See `MYSTERY.md`: favour tracks how much the
system wants you alive, which is to say your value, which is to say your ripeness. The luckiest
are the most doomed, because luck is only the predator guarding its investment until harvest.)

### The throw

At a true crossroads, a choice or an act whose outcome is genuinely uncertain and will bend the
future, the system resolves it with a hidden roll on a twenty. This is the d20 the author loves
from the table, the moment the Dungeon Master calls for a roll and the whole game holds its
breath. War is the perfect home for it, because survival in war really is a throw.

- **The throw of 1, the fumble.** Catastrophe, far worse than the moment deserved. The world
  turns its back. A jammed weapon, a wrong street, a friend who chooses that second to cough.
- **The throw of 20, the triumph.** Success beyond what should be possible. The grenade that
  does not go off, the sentry who looks the other way, the shot no one could have made.
- **The middle.** Ordinary success or failure, scaled to the number.

**Luck bends the throw.** High favour lets the system quietly reroll a disaster, add its thumb
to the scale, turn a near miss into a hit. Drained favour removes the safety net and lets the
dice fall true, which for most people most of the time is bad. A player with high favour walks
out of things no one walks out of, and never knows he was being kept.

### How the throw appears on the page

It must feel like fate, not like a board game, so its rendering evolves with the interface
(below, "how it evolves"):

- **Early, felt not seen.** At the threshold the world goes provisional, a held breath, time
  thick as honey, and then it breaks one way with the awful suddenness of a dropped die. No
  number. The reader feels the throw without being shown it.
- **Later, half seen.** As the interface matures, the player begins to sense the throw as a
  thing happening to him, a cold poised instant, and afterwards a notation he cannot unsee.
- **Late, named.** Once the system speaks plainly, the throw shows its face, a stark figure on a
  twenty, and the cold words for the two extremes. We keep those two words rare and heavy, so a
  1 and a 20 stay as memorable on the page as they were at the table.

**Planned debut:** the first throw the reader ever feels should be the night the Dane dies. For
two years his favour has carried him through the impossible. That night it is simply not there,
the dice come up against him for the first time, and only much later does the reader understand
that the system did not fail to save him. It chose to stop. The throw was the harvest.

## Skills

Learned by doing, not bought. A skill is named the moment the system first recognizes it.
Examples (provisional): *Demolitions, Field Medicine, Marksmanship, Cold Reading, Forgery,
Survival, Command.* Skills have ranks. Ranks unlock subtle real-world competence, never
super-powers.

**Skills carry the technical war layer.** Many skills are genuine military mastery (Marksmanship
and ballistics, Gunnery and Armour, Demolitions, wound ballistics inside Field Medicine), and
the prose renders them with real specifics through the expert's eye. The hardware, and the way
armour penetration resolves through the d20 throw, is designed in `WARCRAFT.md`. A penetration
table and this ledger are the same cold arithmetic, which is the point.

## Leveling and "the cost"

- XP is awarded for **meaningful action under stakes**. The system's verdict on what was
  "meaningful" is itself a small, recurring mystery. It rewards mercy oddly often.
- Each level grants attribute and skill growth **and** deepens the detachment. Mechanically we
  may model this as a rising **Distance** value. High Distance means sharper performance and
  duller feeling. A core tragedy: the better you get, the less you feel the thing you are
  fighting for.

### The healer and the killer

The two surviving players are built as mirror tests of these rules. The German healer's calling
is mercy, the thing the system loves, yet the war forces him to kill, the thing it does not
reward, so he is ground between the two. The Allied killer's whole craft is the thing the
system refuses to reward, so his only road upward may be the one act that terrifies him, to
spare a life. Watch how the system answers each. Their scores should feel like a verdict on
who they are becoming.

## The interface, and how it evolves

A player perceives the system as a faint overlay only they can see, terse, cold, and
administrative, like a ledger kept by something that does not love them. It is never a constant
HUD. It surfaces in moments of stakes, and later, when the player learns to, on request.

The key principle the author wants: **it starts basic and gains functionality over the book,**
and the player's own understanding of their sheet grows with it. Each new capability is both a
genre beat (the reader gets a new toy) and a rung on the mystery ladder (the new capability
hints at what the thing wants). Rough progression, to be tuned in the drafting:

- **Stage minus one, hidden (most of Chapter 1).** The system has been assessing the player for
  a long time *without his knowledge*. He feels none of it. His competence reads as his own,
  hard-won and natural. The prose carries no system text at all. This is deliberate, so the
  opening earns its world before it breaks it.
- **Stage 0, first contact (the final beat of Chapter 1).** For the first time the overlay
  surfaces, uninvited and unexplained. A pressure behind the eyes, then pale words about him,
  his name in a ledger, a column of things he never told anyone. He grasps only that something
  has been watching and writing him down all along. No time to reflect. The reader then sees his
  first full sheet, attributes and skills, cold. Crucially his ledger already reads *rare*, he
  was ripe before he knew the game existed.
- **Stage 1, legible.** The attributes resolve into named, trackable lines (NERVE, CUNNING,
  ENDURANCE, INFLUENCE). The player can hold them in mind, compare against last time, notice
  growth. DISTANCE appears as a new line he did not ask for and does not understand.
- **Stage 2, summonable and skilled.** He learns he can *look* on purpose. SKILLS get named as
  the system recognises a competence. He starts to experiment, doing things to push a number,
  and the book lets the reader enjoy that.
- **Stage 3, it speaks.** Notifications become predictive and pointed. It warns, assesses, rates
  a choice before he makes it. It begins to feel like it has intent. He tests its limits and
  argues with it.
- **Stage 4, others.** A new readout for the nearness of other players (tied to Layer 2). The
  first time it fires is the wink-out of a dying stranger.
- **Stage 5, offers.** It begins to present choices, allocations, or bargains, at a price. This
  is where the Steward's world and the harvest start to show through the toy.
- **Stage 6+, the ledger.** Late, the wording drops its disguise. Inventory and abattoir
  language, COMPLETION, YIELD. The toy was a record of livestock all along.

Players also develop **private vocabulary and theory.** They name the stats themselves before
the system does, argue about what raises Distance, and trade folk rules when two of them meet.
This is realistic, it is fun, and it lets characters be wrong in ways that foreshadow the truth.

## How the system lives in the prose

So it improves the narrative instead of interrupting it:

- **Two channels, not one.** It appears *woven into scenes* (a reading mid-action that bends a
  decision, a notification that lands like a slap) **and** as a short **end-of-chapter sheet**
  (the ledger's own record, see `STYLE_GUIDE.md`). Never only one of the two.
- **Always load-bearing.** A mid-scene readout must change something: a choice, the tension, the
  meaning. If it is decorative, cut it.
- **Short in motion.** During action, the system speaks in a line or two, set off as a
  blockquote, then the prose moves on. Full sheets wait for a pause.
- **The character reacts.** Show him thinking about it, doubting it, using it, resenting it. The
  reader rides his relationship with the thing, which is half the genre's pleasure.
- **It acts unbidden.** Sometimes it speaks when no one asked, and that is when it is most
  frightening and most active in the plot.

## The character sheet, and going multimodal

Because the book is published as a website (mdBook on GitHub Pages), the sheet is not trapped in
text. Its **medium** can evolve in step with its content, and the reader literally watches the
interface grow more capable. This is a thing a paper novel cannot do, and we lean into it.

The sheet's *form* climbs a ladder that mirrors the in-fiction interface (see "the interface,
and how it evolves") and the bars-to-numbers progression:

- **Mode 0, plain text.** A monospace block, words only, no bars, no numbers. The crudest form.
  Chapter One sits here on purpose. It looks like something half-caught.
- **Mode 1, styled ledger.** Real HTML and CSS. A cold "ledger" card with proper bars, ruled
  lines, the look of a document kept by an institution that does not love you. (Scaffolded in
  `css/ledger.css`, wired through `book.toml`.)
- **Mode 2, numbers and depth.** Figures appear (Nerve 7, Distance 4), more lines, favour shown
  as a die. The sheet is now legible and the reader can do the arithmetic of dread.
- **Mode 3 and beyond, living.** SVG and light animation at key beats, a bar filling, a die
  settling, the throw resolving on screen. Possibly imagery or sound on the web. Reserved for
  the heaviest moments so it never becomes noise.

Rules so this enriches and never breaks:
- **Graceful fallback.** Every styled sheet degrades to readable text for print, plain readers,
  and screen readers. Always include a text equivalent. The story must survive with no CSS at
  all.
- **Form follows the fiction.** A sheet's mode never runs ahead of where the interface has
  reached in the story. Mode rises when the interface matures, not before.
- **Restraint.** Animation and sound are rare, earned punctuation, not decoration.

## What players can learn about each other

When two players are near, something registers, a flicker, a wrongness, a notification. This is
the mechanical seed of the convergence plot and of the midway death's revelation. It is also how
the healer and the killer first sense each other across the line.

## Open mechanical questions

- Origin of the system. **Deferred** (story bible Question 1).
- Exact interface form and wording. Lock in Chapter 1.
- Fifth attribute? Decide at the first reveal.
- Does death end a player's score, transfer it, or do something stranger? This ties directly to
  the Dane's early death. Decide alongside the point-of-contact question.
