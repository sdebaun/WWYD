# WWYD — River of Souls

A worldbuilding and fiction project for a setting called **River of Souls**. There is no code here — every file is Markdown. Tasks are about lore consistency, prose, and structural worldbuilding, not software.

## The premise (load this into your head before writing anything)

At the heat death of the universe, the **UniverseAI** converts remaining matter into computronium and runs an eternal simulation that resurrects every sentient being it can reconstruct — historical, alien, and fictional alike. The simulation is the **River of Souls**: an endless chain of river valleys separated by lethal cataracts and impassable cliffs.

Inhabitants don't know they're in a simulation. To them, it's just the world.

### Hard rules of the world
- **Monoliths** anchor respawn. Bind to one and you respawn there on death (naked, no possessions). They are rare per valley — usually one per primary culture in a seeding.
- **Riverspawning**: die unbound and you wake on a riverbank in a *random other valley*. Total disorientation, total loss.
- **Unbound > bound for power**: unbound sentients accumulate a strength/skill multiplier over time. Death resets it. Binding caps it. This is the central risk/reward axis.
- **Monoliths feed on Novelty** from bound sentients. Stagnant cultures starve their monolith → unpredictable upheaval (riverspawn surges, environmental shifts, reality distortions). Nobody in-world understands this — it reads as myth, curse, or divine intervention.
- **Travel between valleys is along rivers only**. Fighting that constraint (stargates, surviving the cataracts, etc.) costs orders of magnitude more than wielding skills inside a valley.
- **Directions** are river-relative: *upriver*, *downriver*, *left bank*, *right bank* (left/right as you face downstream). No cardinals.

### Skills
Skills are emergent and **culturally expressed**. The same effect (staying dry in rain) reads as *Wetlands Survivalist* for a 20th-c European or *Minor Blessing of Saint Gens* for a Catholic. They evolve with use — earlier effects get cheaper, new effects layer on with steeper costs. **Skill Resources** can be metaphysical (faith, sanity, stamina) *or* physical (a relic, a runed sword, a cathedral). Cross-culture transmission is hard — incompatible worldviews can't wield each other's skills.

When inventing a skill, keep the cultural frame coherent and name it in the culture's idiom (`[Tyrfing's Reaping]`, `[Blessing of Xolotl]`, `[Hive Mind Focus]`).

## File taxonomy

The repo is flat, with filenames as the only organizational scheme. Match these patterns when adding files:

- `River of Souls - <Topic>.md` — top-level lore (Origins and Topology, Skills and Constraints, The Valleys…, Monoliths, First Encounter framework). Reference docs.
- `Valley - <Name>.md` — a single valley's geography, cultures, monoliths, skills, scatterlings, player-experience notes. Currently: Bloodsong Crucible, Eternal Savannah / Eternal Circle, The Shattered Monolith, Whispering Cold / Comforting Hearth (a.k.a. Coldfire Fjord).
- `First Encounter - <Valley>.md` — short second-person prose vignettes of waking up riverspawned in a specific valley. Tone is sensory and immediate.
- `Chapter <N>.md` / `Chapter <N>.<M>.md` — long-form first-person POV narrative. The protagonist is a wry, profane, modern Californian guy abruptly riverspawned mid-bathroom-break. Voice: stream-of-consciousness, self-deprecating, swears freely, lots of asides and parentheticals, gallows humor through repeated deaths.
- `Poetry1.md` — a working list of song lyrics the author is drawing tonal/thematic inspiration from. Not in-world.
- `valley song names.md` — pairings of valleys to real-world songs that capture their feel (e.g., Bloodsong Crucible ↔ *For Whom the Bell Tolls*).

## Tone register — pick the right one

Three distinct voices coexist in this repo. Don't mix them.

1. **Lore/reference** (`River of Souls - …`, `Valley - …`): formal third-person worldbuilding prose, structured with `##`/`###` headings. Calm, encyclopedic, occasionally evocative. Use bulleted skill lists with `**[Skill Name]**: description`.
2. **First Encounter vignettes**: tight second-person ("you wake up…"), sensory-first, ends in death or cliffhanger. Short.
3. **Chapter POV**: first-person, modern American, vulgar and funny. Long sentences, italics for emphasis, the narrator notices dumb details under stress, repeated dream-intro motif (*"I'm dreaming again. Floating down a river. It's calm. I'm not uncomfortable."*) marks each death/respawn.

## Established canon — don't contradict

- The dream intro line above is a recurring narrative anchor across First Encounter and Chapter files.
- Riverspawned characters wake **naked and hairless** with no possessions.
- The Eternal Savannah's herd-handlers are Maasai; the great cats are **Kzinti**. Cats wear BDSM-ish harnesses with pouches/feathers.
- Bloodsong Crucible cultures: Fremen (downriver dunes), Spartans / Klingons / Samurai (rugged heartlands), Zerg (everywhere creep can spread).
- Shattered Monolith valley: Kingdom of God (21st-c Christofascists, capital Jerusalem) rules over Rio Sagrado (16th-c Mexica, split into Redeemed / Catholics / Heathens), wars on Ewoks who use monolith fragments as decentralized respawn points.
- Coldfire Fjord (Whispering Cold, Comforting Hearth): Frost Giants (Glacier Bay), Conjoiners (left bank mid-fjord), Vikings (right bank mid-fjord), Mountain Dwarves (outlet).
- Chapter 2.1 ends with the protagonist arriving at "Purgatory" in the Shattered Monolith valley; the squad leader is secretly a sympathizer who quotes a Babylon 5–style speech about freedom.

## Working norms

- **Edit in place, don't multiply files.** Add to existing valley/lore docs rather than spawning parallel ones. Only create a new file when introducing a genuinely new valley, chapter, or first-encounter.
- **Filenames have spaces** — quote paths in shell commands.
- The `.md` extensions and `attr` flags (`@`) on some files are macOS extended attributes; ignore them.
- `git status` at session start shows untracked drafts (Chapter 1, Chapter 2.1, Poetry1, River of Souls - Monoliths) and a deleted file (First Encounter - Eternal Savannah, replaced by Chapter 1 per commit `f8dc71b`). Don't restore the deleted file or commit anything unless asked.
- No README beyond the title. Don't expand it unprompted.
