# Kaiju ASCII Art — Variants

Compare these on GitHub (they're in fenced code blocks so spacing is
preserved). Each is built around a single center axis so the top and
bottom halves line up. They're intentionally more compact than the
first attempt — less empty interior space.

## Lessons learned (verified on GitHub)

- **Pure ASCII line art aligns reliably** everywhere.
- **Braille dot art works too** — variant H rendered cleanly and stayed
  aligned in a GitHub screenshot, so Braille is a viable style here.
- **Wide, spacious designs drift and look sparse.** The very first
  attempt (large, lots of interior gaps) leaned/misaligned; compact
  designs with a single center axis hold up much better.
- **Never mix double-width CJK glyphs inside ASCII art** — it breaks
  column alignment. Keep kanji on their own line (see below).
- **Kanji title line balances above a spaced Latin caption.** Placing
  `怪 獣 8 号` above `K A I J U` works, but kanji are double-width so
  centering is by eye, not character count. Final balance in
  `kaiju_no8_alternatives.md` used **8 leading spaces** for the kanji
  line vs the caption — confirmed in both a text editor and on GitHub.
- **Chosen for the document: variant A** (horned skull mask, ASCII).

---

## Variant A — Compact head (small, dense)

```
    /\_/\
   ( o.o )
  __\~~~/__
 /  |   |  \
(   |K-8|   )
 \__|___|__/
   /_/ \_\
```

---

## Variant B — Roaring face (medium, symmetrical)

```
     .---.
    / o o \
   |  \_/  |
   |  |||  |
  _\__|_|__/_
 /   K - 8   \
 \___________/
   ||     ||
```

---

## Variant C — Full-body stomper (compact, centered)

```
      .-"-.
     / o o \
    |  \_/  |
   _|__|_|__|_
  /  \ K-8 /  \
 |    \___/    |
  \___/   \___/
   |_|     |_|
```

---

## Variant D — Minimalist crest / logo style

```
   __/\__
  '-.  .-'    K A I J U
    |  |         No. 8
  .-'  '-.
   \_||_/
```

---

## Variant E — Chunky monster (solid, little whitespace)

```
   ▄███▄
  █ o o █
  █  ▼  █
 ▄█▀███▀█▄
 █  K-8  █
 ▀█▄███▄█▀
   █   █
```

(Note: Variant E uses block-drawing characters; it looks bold but
depends on the font. Test how it renders for you.)

---

## Variant F — Wide low-profile beast

```
    ___/\___/\___
   /   o    o    \
  |      \/\/      |
   \  <  K-8  >   /
    \____/\____/
     /  /  \  \
```

---

Pick whichever feels right (or mix elements — e.g. face from B with
legs from C) and I'll drop it into `kaiju_no8_alternatives.md`.

---

# Dot-Style Variants (inspired by emojicombos.com)

The reference page (https://emojicombos.com/Kaiju-No-8-ascii-art) is
built almost entirely from **Braille dot art** — Unicode Braille
patterns (⣿ ⠿ ⢰ …) used like grayscale pixels. Below are a few pieces
in that spirit.

**Caution:** Braille dot art can drift on GitHub. Braille glyphs are
nominally monospace, but many fonts render them at slightly different
widths than ASCII, so alignment is less reliable than the pure-ASCII
variants above. Test how these look for you before committing.

---

## Variant G — Dotted / stippled kaiju head (light shading)

```
      .:::::.
    .:'  _  ':.
   ::  .' '.  ::
   :: ( o o ) ::
    ':.  ^  .:'
   .::'\WWW/':::.
  ::: . K-8 . :::
   ':::.....:::'
     '::: :::'
    .-'     '-.
```

---

## Variant H — Braille blob kaiju (small)

```
⠀⠀⢀⣤⣶⣶⣤⡀⠀⠀
⠀⣰⣿⠟⠻⠟⢿⣿⣆⠀
⢠⣿⡏⢰⡆⢰⡆⢹⣿⡄
⢸⣿⡇⠈⠛⠛⠁⢸⣿⡇
⠸⣿⣷⣄⠈⠁⣠⣾⣿⠇
⠀⠹⣿⣿⣿⣿⣿⣿⠏⠀
⠀⠀⠈⠛⠿⠿⠛⠁⠀⠀
```

(Braille art — best viewed in a font with even Braille spacing.)

---

## Variant I — ASCII "dot texture" kaiju (safer than Braille)

Uses only ASCII punctuation to get a stippled look, so it keeps
alignment everywhere:

```
      ..:*#*:..
    .:*#=---=#*:.
   :*=  o   o  =*:
  :#=    ...    =#:
  :#=  \VVVVV/  =#:
   :*=  K - 8  =*:
    ':*#=---=#*:'
       ':***:'
     .:*     *:.
    (___)   (___)
```

---

If one of the dotted styles reads well after you screenshot it, I'll
place it in `kaiju_no8_alternatives.md`. Otherwise I'd recommend the
pure-ASCII options for guaranteed alignment.
