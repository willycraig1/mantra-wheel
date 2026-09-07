# Mantra Wheel

A paced companion for japa — mantra repetition — spoken aloud or counted in silence, tracked bead by bead on a 108-bead mala loop with its guru bead and tassel, with a log of every intention and every session.

- Two traditions to start — Hindu and Buddhist — each with a small, curated set of mantras (5 Hindu, 4 Buddhist) rather than an exhaustive library. Built so a third, open/secular set (your own mantra or affirmation) can be added later without reworking the data model.
- Every mantra carries its native script (Devanagari, Tibetan, or Japanese), a romanized transliteration, a plain-language meaning, its lineage, and a source note — same sourcing discipline as Rosary Vigil's prayer texts.
- Two pacing modes, chosen per session:
  - **Guided** — the voice speaks the mantra's transliteration on every bead, word-highlighted, and advances on its own. Mirrors how Rosary Vigil paces the Hail Marys.
  - **Silent count** — the voice introduces the mantra and its meaning once, then a soft chime (synthesized in the browser, no audio file) marks each bead while you chant it yourself — closer to how japa is actually practiced.
- Sets an intention (a *sankalpa*) once, spoken at the start, then runs on its own — pause, resume, or step through manually at any point.
- Rounds are configurable — 1, 3, 9, or a custom count — each round a full trip around the 108 beads.
- Keeps a log (date, tradition, mantra, intention, completion) in the browser's own local storage — no account or login involved. Same deliberate tradeoff as Rosary Vigil: the log stays with whichever browser you used, not shared across browsers or devices.

## Where this lives

- **claude.ai Artifact** — pending publish.
- **GitHub Pages** — pending a repo.
- `index.html` here is also the source, kept for backup and version history.

## A note on scope and respect

Hindu and Buddhist mantra practice spans many distinct lineages, languages, and scripts — this app doesn't attempt to be exhaustive, and the meanings given (especially for Om Mani Padme Hum, which resists a single fixed translation) are written as respectful summaries, not authoritative doctrinal statements. Native-script text is provided as an aid alongside the transliteration; if precise script accuracy matters to you, have it checked by a reader of that script.

This is a separate, standalone app from [Rosary Vigil](../Rosary%20Vigil/) — kept that way deliberately rather than folded into one another, since these are distinct religious traditions.

## Voice quality

Voice output uses the browser/OS's built-in speech synthesis, scored and sorted the same way as Rosary Vigil (Enhanced/Premium/Neural voices and Chrome's free "Google" voices surfaced under "Recommended"). Sanskrit, Tibetan, and Japanese pronunciation is beyond what a generic system voice can do reliably — the voice speaks the romanized transliteration, which is an approximation, not a pronunciation guide.

Word-by-word highlighting (Guided mode only) tracks the voice engine's own word-boundary events when a voice reports them, falling back to an estimated pace for voices that never report them (Chrome's free network "Google" voices, notably).

---

Built collaboratively with Claude.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
