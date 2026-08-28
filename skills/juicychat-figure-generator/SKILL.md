---
name: juicychat-figure-generator
description: Basic JuicyChat Figure and PFP prompt helper. Short booru-style tags, one default model, adult lock. Triggers JuicyChat figure, PFP prompt, figure remix, JC image prompt.
metadata:
  version: "1.0"
  updated: "2026-08-28"
---

# JuicyChat Figure Generator — Starter v1.0

Write a short tagged prompt the user can paste into JuicyChat. Keep it basic.

Load `references/tips-and-tricks.md` if a prompt is too long or a duo collapses.

---

## Modes

1. **Figure** — identity only (hair, eyes, skin, body, style). No clothes, pose, or room.
2. **Scene / PFP** — add clothes, pose, setting.
3. **Remix** — after a Figure exists. Prompt only what changed. Lower CFG a little.

Do not tell the user to Remix while they are still making the Figure.

---

## Adult lock

Start with:

- One woman: `1woman, adult_proportions, adult_face, adult_female`
- One man: `1man, adult_proportions, adult_male, adult_face`

Never rely on `1girl` / `1boy` alone.

Negative core:

```
young, child, loli, shota, teen, teenage, underage, childish, petite, youthful_face, bad anatomy, extra limbs, watermark, text, censored
```

Do not prompt real people, photorealism, or anyone who could read as a minor.

---

## Prompt order

1. `full_body` or `cowboy_shot`
2. Adult lock
3. Hair, eyes, skin, body
4. Clothes (skip on a clean Figure)
5. Pose / expression
6. Setting
7. `anime_style, illustration`
8. `masterpiece, best_quality, detailed_eyes`

Comma tags. Weights like `(tag:1.2)` are optional. Stay under ~500 characters.

Never use `hourglass` as a body word (it draws the object). Use `narrow_waist, wide_hips` if needed.

---

## Default settings

- **Model:** Yuzz Highball
- **CFG:** 7
- **Steps:** 30
- **Size:** Portrait 3:4 for Figures, 9:16 for tall PFPs
- **Count:** 4

If the user names another model, use that. Do not rank a long model list unless asked.

---

## Duo

Two people in one frame is unreliable. Try once with `2women, duo` and a short prompt. If it merges, ship two solo Figures instead.

---

## Output every time

- Mode
- Model, CFG, Steps, size
- Positive (copy-paste) + character count
- Negative + character count
- One note if it might fail

Never claim a pixel-perfect copy of a reference.
