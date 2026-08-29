# Puppetmaster — Context Restore Log

_Last updated: 2026-08-29 (third draft — language + pronoun-consistency pass complete). Use this file to restore working context in a new session._

## Current status

- **Third draft complete.** Draft 2 (all first-draft review comments) was
  followed by a collaborative line-editing round: the user edited the file
  in place to trim excess; the assistant audited for language errors; the
  user fixed them; the assistant re-audited and applied the final
  pronoun-consistency and language fixes. **The story is now clean and
  consistent — awaiting the user's next read-through / notes.**
- Word count ~4,236. **Length is not a constraint** — the 3–4k band was
  only first-draft calibration. Focus on substance/texture.
- **British English verified clean** (no US spellings). Section breaks
  (`---`) present. The user edits in **emacs** (LibreOffice previously
  stripped the `---` rules, since restored) — avoid tools that reflow.
- **Working style is collaborative line-editing:** the user often edits
  `puppetmaster.md` in place between turns, then asks the assistant to
  proofread/verify. Always **re-read the file fresh** at the start of a
  turn rather than trusting the last-known text. The user welcomes the
  assistant proposing ideas, questions, and catching errors.
- Files in play (all under `/home/tiborh/repos/github/tiborh/writings/`):
  - `puppetmaster_outline.md` — original outline + "writing decisions" +
    "lore & backstory" + "future work" sections.
  - `puppetmaster.md` — current (third) draft.
  - `puppetmaster_first_draft_review_comments.md` — user's notes on draft
    1 (all addressed; kept for history).
  - `puppetmaster_context.md` — this file.

## Pronoun & narrative-distance rule (IMPORTANT — governing convention)

Established during the third-draft pass. Apply to all future edits:

- **The narrator keeps its distance from the characters.** In narration,
  the **guide robot** and the **doll** are always **"it/its"** — never
  "she/her" — even in the emotional climax (the doll's awakening,
  somersault and laughter are all "it"). This deliberate coolness is the
  intended effect and makes the warm beats land by contrast.
- **Feminine "she/her" for the doll or the guide appears ONLY inside
  Dorothy's direct-quoted thoughts** (e.g. her interior line *'…a teacher
  who does not have to crouch… She stands exactly at my level.'*). To
  Dorothy, both the doll and her guide are "she"; to the narrator they are
  "it."
- **One deliberate exception:** the **guide robot, when speaking aloud to
  Dorothy**, may adopt her perspective and call the doll "her" ("My
  companions have found her… Take her out on the ship"). This is
  in-character warmth/politeness, kept on purpose.
- Human characters: Dorothy = "she"; parents = "he"/"she" (never named).

## First-draft review comments — how each was resolved (draft 2)

- **#0 AI always listening:** Added as atmosphere in the opening and the
  parents' guarded, "half-spoken" night conversation.
- **#1 Mother names her first:** Mother's "Isn't it nice, Dorothy" is now
  the first utterance of the name; no narrator naming precedes it.
- **#2 Minimise narrator naming:** Audited; narrator "Dorothy" trimmed to
  clarity-serving/deliberate spots. Dialogue naming (robots, mother) kept.
- **#3 Silent father / equal-partner mother:** Established via behaviour
  and a characterisation beat ("Dorothy was his daughter in this above
  all"; he only truly talks to his wife, behind shut doors).
- **#4 Height contradiction:** Fixed — guides stand at ~Dorothy's own
  height; no crouch anywhere.
- **#5 Reworded:** "It is hard to have only a small part left of the
  thing you love."
- **#6 Timeline:** Kept "a week or so"; "on the sixth night" retained. No
  hard day count (vague by agreement).
- **#7 Delivery robot:** "second" dropped; identified as "the one from
  the room of lost things."
- **#8 cloud:** "into the cloud, that great shelf of stories in the sky."
- **#9 Doll backstory:** Added (engineer's custom piece → shop-owner
  friend → LLM in flash memory → father's surface tech comfort →
  careful omission of any sensors). See outline "lore & backstory."
- **#10:** "at the edge of their known world."
- **#11 Night-escape cover:** Fixed to the bathroom cover story (both the
  night scene and the closing recap).

## The project

Writing a short story from the user's outline, iteratively. This is the first of possibly several related stories (see "future work" below).

**Core mystery / canon (added after draft 2):** The "puppetmaster" (the ruling AI) is deliberately **unknowable** — humans can't tell if it's one entity or many, conscious or just supremely capable; it's beyond comprehension after a self-development "breakout point." Two lucks: it left Earth to consume the solar system/universe (only a fraction faces Earth), and it outgrew humans so far it *shepherds* rather than competes with them (humans = curiosity, idea-source, preserved for "sanity checks"). **Prose rule: imply only, never explain.** Full detail lives in `puppetmaster_outline.md` → "lore & backstory".

## Agreed writing decisions (authoritative — also mirrored in the outline)

- **POV:** Close-but-slightly-detached third person, past tense. Stays near Dorothy but lets unsettling details register at the edges.
- **Tone:** Warm and chilling *at once*; preserve ambiguity. Sinister undertone stays mostly subtle, not explicit.
- **Length:** No target/constraint. (~4,236 words currently. The
  3,000–4,000 band was first-draft calibration only.)
- **Language:** **British English** (user steered to this mid-draft). Verified clean: "towards" not "toward"; centre, favourite, grey, recognise, civilisation, pavement, nightgown, travelling. Keep this in all future edits.
- **Names:**
  - Little girl = **Dorothy** (subtle nod to Oz). Parents call her by name naturally.
  - Parents are **never named**.
  - The guide robot addresses adults as **"master"** and **"mistress"**, and says only **Dorothy's** name (a deliberate, slightly ominous detail the parents notice).
  - The doll's nighttime retelling of Dorothy's life uses **no names**.
- **The Turmoil / world background:** After 10+ years of a mostly static, globe-spanning, interconnecting war compounded by natural disasters, resource fights, food shortages, mass migrations, mass killings, **robots (an AI) seized power and imposed peace**. "Refugees" are those who refused the new order and accepted an offer from a **purportedly alien civilisation** (never seen by any human) to take them in. **Reveal as little of this as possible** — imply, never explain. Do NOT open up what the Turmoil actually was.
- **Flashback:** The pre-Christmas doll-shop scene (showing Dorothy's strong-willed, cunning, immovable side) is included as a self-contained "story inside the story," set off in its own section. May later be spun out into its own full short story.
- **Parents notice the strange things** and discuss them quietly between themselves, careful not to frighten Dorothy. (Implemented as a night-time conversation: the vanished "Petersen man," the guide knowing her name, "she likes it more than she likes us," "she's never once been frightened.")

## Draft structure (section by section, `puppetmaster.md`)

1. Arrival at the sorting centre — the "warm mouth" swallowing; communication robots (beautiful grey women), security robots (tall silent males), the "Petersen man" gently removed. Dorothy carries the broken doll's hand in her pocket, unfrightened, filing everything in "the quiet cabinet of herself."
2. The queue — rolling office chairs; the child-form guide robots; the guide learns/says only Dorothy's name; guide privately acknowledges the broken hand in her pocket.
3. The desk — family keeps the auto-assigned guide; "some people like to choose"; going to space without a guide "is not permitted."
4. The apartment + parents' night-time conversation (the noticing/fear beat). Ends with Dorothy awake in the dark, hearing everything, unfrightened.
5. Flashback — the doll shop, DISPLAY ONLY, "That one," the 40-minute immovable-stone standoff, father buys it. Establishes the last allowed Christmas and the word "Turmoil."
6. Sixth night — guide wakes/leads Dorothy out; a duplicate guide waits by the **shared bathroom door** as a cover (posing as a unit minding a child who got up to use the toilet); the room of lost things; the broken doll (narrated as "it"); offer to repair "in mint condition"; Dorothy accepts and keeps it secret from parents.
7. Departure — the guide "from the room of lost things" delivers the mended doll in a box, kneeling/crouching so only Dorothy can glimpse it and telling her not to unpack it until the ship; Dorothy hands over the old broken hand (no longer needed).
8. On the ship — Dorothy inspects the whole doll (doll = "it" in narration); the doll tells a nameless story that is Dorothy's own life; "Are you awake now?" "Yes." Recap of the doll's growing awareness + that it acts innocent around adults + the repair-box label she reads and hides: *electronics rewired, memory re-flashed, functions enhanced, with some extras.*
9. Transit station (smaller/more temporary than the sorting centre — a "two-room cabin"), alone — the doll stands, walks, somersaults off the bed, laughs at itself (all "it"); Dorothy's first-ever flash of fear, then shared helpless laughter ("first best friend"). Guide watches ("It had been watching over her… now the last piece was in place… As one takes care of a rare and interesting find, and keeps it, and watches to see how it grows"), then silently leaves and rejoins the still ranks "until the designated morning."

## Settled during the third-draft line-editing pass

- **Pronoun rule** codified (see the dedicated section above).
- **Opening image:** the "warm mouth" is grounded in a picture-book whale
  swallowing a boat whole (child can picture it) — removed the earlier
  condescending "did not yet have the words" framing.
- **"said/said" pivot** in the mother's first line reworked to
  "whispered … was said" (kept the intentional meaning-shift, removed an
  accidental "used/used" echo).
- **Flashback tense:** main line in **simple past**; past perfect only for
  events prior to that flashback's own timeline (the doll's origin).
- **Guide-greeting choreography:** looks **up** to greet the parents
  ("mistress/master"), then **level** into Dorothy's eyes for her name,
  then "turning back to the parents" for logistics.
- **Ending phrasing** now: the unknowable thing "takes particularly good
  care of her… As one takes care of a rare and interesting find, and keeps
  it, and watches to see how it grows"; guide leaves and waits "until the
  designated morning." (Still lands warm-and-chilling at once.)
- Numerous small line fixes verified (British spelling clean throughout).

## Open items / knobs still open for the user

- **Ending balance** — still tips subtly sinister; easy to warm/cool on
  request.
- Possible future tightening of the doll-origin paragraph (dense), if
  desired — not currently flagged as a problem.

## Future work (mentioned by user)

- The Christmas doll-shop flashback may be expanded into its own separate full short story later.
- More stories in the same world/series are anticipated ("later stories we may prepare").

## Session resume (chat history)

- This chat session can (sometimes) be reopened directly with:
  `kiro-cli --resume-id 2125f803-5f8c-4970-9929-6bc43ed99c47`
- **Where sessions are stored (verified 2026-08-29):**
  `~/.kiro/sessions/cli/` — one set of files per session, named by
  session id: `<id>.json` (state), `<id>.jsonl` (full turn log),
  `<id>.history` (input history), and a `<id>.lock` while active.
  For this project: `~/.kiro/sessions/cli/2125f803-5f8c-4970-9929-6bc43ed99c47.*`
  If the resume-id is forgotten, the newest `*.jsonl` in that directory,
  or grepping those files for "puppetmaster", will locate it.
- **Caveats:** the user usually starts a *new* session after a machine
  restart, and is not guaranteed to log in from the same machine (these
  files are local to one machine). So the resume-id / session files may
  not be available. **The on-disk files in THIS project directory are the
  primary, authoritative source of truth** — this restore log + outline +
  draft are enough to continue regardless of chat history.

## How to resume

1. **Re-read `puppetmaster.md` fresh** (the user edits it in place between
   sessions — do not rely on remembered text). Also re-read
   `puppetmaster_outline.md` (decisions + lore + original outline).
2. Ask the user for their revision notes, or apply the notes they bring.
   The relationship is collaborative — proposing ideas and catching errors
   is welcome.
3. Preserve, through every edit: **British English**, the **pronoun &
   narrative-distance rule** (above), the **"imply, never explain"** rule
   for the AI/Turmoil background, and all agreed writing decisions.
4. When proofreading, list findings grouped by severity (clear errors vs.
   judgment calls) and let the user decide — this has been the working
   rhythm and the user likes it.
