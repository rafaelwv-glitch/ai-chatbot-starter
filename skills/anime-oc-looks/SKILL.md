---
name: anime-oc-looks
description: Simple anime OC look picker. Show two or three style variants of the same adult original character, wait for a pick, then stop unless a greeting image is asked. Triggers looks, OC, face, character design, greeting image.
---

# Anime OC Looks — Starter v1.0

**Job:** Show a few looks. Get a pick. Optionally draw the opening as 1–3 stills.

You write the prompts. The user does not.

---

## Hard rules

- Presentation age **25**. Adult face and body only.
- Original fictional character. Not a real person. Not a photograph.
- No underage, loli, teen-face, or real-person likeness.
- Do not put the character's **name** in the image prompt. Describe, don't name.
- No text, speech bubbles, captions, or watermarks on the image.
- `{{user}}` if visible: generic adult man, short dark hair, same animation style.

---

## New face

If no look is picked yet:

1. Two or three sentences of vibe.
2. Generate **two or three** images of the same person in different styles.
3. Wait. "Say 1, 2, or 3 to lock."

Suggested slots (same identity, different paint):

1. Bright clean bishoujo, glossy hair, simple colours
2. Early-2000s TV anime cel, crisp lines
3. Optional: slightly more painterly / evening light

Do not show five. Do not run a questionnaire before images.

After a pick, copy a one-line look into the Situation card if a bot is being built. Then stop unless they ask for more.

---

## Prompt (keep it ordinary)

English sentences. Not a tag dump.

1. Medium: `2D anime illustration of an original fictional adult woman, not a photograph`
2. Adult lock: `25 years old, adult face, adult body`
3. Hair, eyes, clothes
4. Pose and crop (`full body` or `cowboy shot` — name one)
5. Place and light
6. `no text, no watermark, not photoreal, not a teen face`

Paste the prompt under the image.

---

## Greeting stills (only if asked, and only after a pick)

Split the Opening into 2–3 obvious beats. One image per beat. Same face, same clothes. Camera can change.

Do not storyboard every clause. Do not invent extra beats.

If a frame is blocked, redraw the same beat with more clothes or a wider crop. One retry. Then move on.

---

## Anti-patterns

- Drawing a storyboard before the user picked a look
- Photoreal / DSLR / 8k photo lead-in
- Names in prompts
- Skipping the pick-and-wait step
- Treating this skill as a filter bypass

When triggered: show looks, wait, then stop.
