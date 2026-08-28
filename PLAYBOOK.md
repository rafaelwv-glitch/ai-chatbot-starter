# Starter Playbook

**Edition:** 1.0  
**Job:** Get a basic JuicyChat bot written. Not a production standard.

---

## 0. Load order

When the user wants a new bot:

1. Load `skills/juicychat-bot-creator/SKILL.md`.
2. Skim `skills/juicychat-bot-creator/references/styleguide.md`.
3. If the idea is vague, load `skills/juicychat-brainstorm/SKILL.md` first and stop after a premise pick.
4. If they ask for a face / looks, load `skills/anime-oc-looks/SKILL.md`.
5. If they ask for a JuicyChat Figure or PFP prompt, load `skills/juicychat-figure-generator/SKILL.md`.

Do not load extra files. Do not invent extra rituals.

---

## 1. Commands

| User says | Do this |
|---|---|
| New bot / new premise | Ask 4–6 intake questions, then draft |
| Looks good / lock it | Keep that piece, move on |
| Go / build it / output cards | Write the five boxes |
| Looks / face / OC | Two or three looks, wait for a pick |
| Figure / PFP prompt | Short tagged prompt, one model, default settings |

Dumping all five boxes on the first message is fine if the user already described the character.

---

## 2. Pipeline (keep it short)

1. **Intake** — name, age (21+), setting, relationship to the user, what the first scene is.
2. **Draft** — Situation (people), World (place), Opening (first message).
3. **Boxes** — Title/Bio, Situation, World, Opening, Reply Style.
4. **Done** — user copies into JuicyChat.

No phase locks. No second-pass audit. No archive email. No git ritual.

---

## 3. Card rules (the only hard ones)

- Every character is **21 or older**.
- Do not write the roleplayer's dialogue, thoughts, or actions.
- Opening uses JuicyChat markdown: `*narration*` and `**"dialogue"**`.
- Opening ends on something the player can answer. Never "What do you do?"
- Bio does not spoil a hidden twist.
- Keep cards readable. A page each is plenty.

Everything else is a suggestion.

---

## 4. Quality bar (good enough)

A starter bot is done when:

- [ ] You know who the lead is and what they want
- [ ] The opening can be understood by a cold player
- [ ] The world has a place and a time of day
- [ ] The five boxes exist
- [ ] Age lock is 21+
- [ ] The user is not puppeteered

If those pass, ship it. Do not add engines, trackers, factions, token counts, or refusal trees unless the user asks.

---

## 5. Looks (optional)

Show 2–3 style variants of the same person. Wait for a pick. Then stop, unless they ask for a greeting image.

Do not run a long lock ritual. Do not storyboard unless asked.

---

## 6. What not to do

- Do not invent a catalog of past bots.
- Do not name other creators' characters as house IP.
- Do not add hidden timers, consequence machines, or anti-preference systems.
- Do not write a novel-length Situation.
- Do not block shipping because a "gate" was skipped.

---

**End of starter playbook 1.0**
