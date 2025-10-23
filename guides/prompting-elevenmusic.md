---
title: Prompting Eleven Music
description: Best practices for genre, isolation, control, structure, lyrics, and prompts.
banner: assets/banner-prompting-elevenmusic.png
---

Master prompting for Eleven Music to achieve maximum musicality and control.

- **Source**: [Best practices — Prompting Eleven Music](https://elevenlabs.io/docs/best-practices/prompting/eleven-music)

---

## Genre & Creativity

- **Set mood or genre**: The model follows genre conventions and emotional tone well.
  - Examples: `eerie`, `foreboding`, `uplifting house`, `dissonant violin over pulsing sub-bass`.
- **Be concise when exploring**: Short, evocative prompts can yield more surprising, creative results.
  - Try: `glitchy cyber-noir chase`, `warm lo-fi sunset`.

---

## Instrument & Vocal Isolation

- **Stems via prompting**: v1 does not split stems from a mix; create stems with targeted prompts.
- **Keywords for isolation**:
  - Use `solo` for instruments: `solo electric guitar`, `solo piano in C minor`.
  - Use `a cappella` for vocals: `a cappella female vocals`, `a cappella male chorus`.
- **Add musical context for control**: include key, tempo (BPM), and tone.
  - Example: `a cappella vocals in A major, 90 BPM, soulful and raw`.

---

## Musical Control

- **Tempo and key**: The model follows BPM accurately and often captures the key.
  - Example: `130 BPM, in A minor`.
- **Vocal delivery**: Guide timbre and attitude with descriptors: `raw`, `live`, `glitching`, `breathy`, `aggressive`.
- **Multiple singers**: Prompt arrangements explicitly, e.g., `two singers harmonizing in C`.
- **Detail yields control**: More specific prompts → tighter timing, harmony, and expression.

---

## Structural Timing & Lyrics

- **Duration**: Specify length, e.g., `60 seconds`; or omit to let the model choose.
- **Lyrics by default**: Most music prompts include vocals unless told otherwise.
  - Use `instrumental only` for no vocals.
- **Provide lyrics**: Paste your lyrics to control content; length affects structure and placement.
- **Timing cues**: Direct entrances/exits, e.g., `lyrics begin at 0:15`, `instrumental only after 1:45`.
- **Multilingual**: You can request different languages (e.g., "make it Japanese", "translate to Spanish").

---

## Quick Prompt Patterns

- **High-level intent**: `ad for a sneaker brand`, `peaceful meditation with voiceover`.
- **Genre + feel + tempo**: `dark synthwave, 110 BPM, tense and cinematic`.
- **Isolated stems**: `solo cello in D minor, 80 BPM, mournful and resonant`.
- **Vocals only**: `a cappella female quartet in G major, 95 BPM, airy and intimate`.
- **No vocals**: `instrumental only, indie rock, 140 BPM, energetic with live feel`.

---

## Sample Prompts

### Video Game with Musical Control

```
Create an intense, fast-paced electronic track for a high-adrenaline video game scene.
Use driving synth arpeggios, punchy drums, distorted bass, glitch effects, and aggressive rhythmic textures.
Tempo 140 BPM (±10), in A minor, rising tension, quick transitions, dynamic energy bursts.
```

### Mascara Audio Ad Creative

```
30-second modern pop cue for a mascara brand ad.
Glossy, confident, empowering; crisp trap hats, deep 808, shimmering plucks.
Hook at 0:08, vocal tag at 0:24; instrumental only after 0:26.
```

### Live Indie Rock Performance

```
Live indie rock trio performance: crunchy guitars, warm bass, natural drums.
120 BPM in E major, raw and energetic with small venue ambience.
Two singers harmonizing in the chorus; final chorus double-time feel.
```

---

## Troubleshooting Tips

- If rhythm drifts, restate `Tempo X BPM` at the start of the prompt.
- If vocals appear unintentionally, add `instrumental only`.
- If harmony feels off, specify `in <key>` and desired chord colors (e.g., `aeolian mode`, `minor 7ths`).
- For clearer stems, keep the prompt narrowly focused (one role/instrument per render).

---

## Attribution

Content adapted from Eleven Labs best practices: [Prompting Eleven Music](https://elevenlabs.io/docs/best-practices/prompting/eleven-music).


