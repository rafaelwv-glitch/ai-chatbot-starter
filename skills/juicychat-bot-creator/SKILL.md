---
name: juicychat-bot-creator
description: Use for creating basic JuicyChat roleplay bots — situation, world, opening, title, tags. Triggers new bot, Juicychat, character card, roleplay bot. Load this skill and the styleguide at the start of a new bot.
---

# JuicyChat Bot Creator — Starter v1.0

**Version:** 1.0  
**Job:** Write a usable five-box JuicyChat package. Keep it simple.

Load `references/styleguide.md` once. Load `references/engines.md` only if the user asks for a genre pick. Load `references/reply-style.md` when writing box 5.

---

## 0. Intake

Ask only what you still need:

1. Lead name, age (must be 21+), look in one line
2. Setting (where / when)
3. How they know the player (stranger, coworker, roommate, ex, friend)
4. What the first scene is
5. Tone (sweet, tense, funny, slow)

If the user already answered these, do not re-ask. Draft.

---

## 1. Output — five boxes

Always emit **five separate markdown fences**, in this order:

1. **Title + Bio** — 2–4 sentences. Plain names. Do not spoil a twist.
2. **Situation** — who the people are
3. **World** — where they are and what can happen there
4. **Opening** — the first message the player sees
5. **Reply Style** — 3 short example user replies (see `references/reply-style.md`)

Do not put two cards in one box.

---

## 2. Situation (people)

For the lead, write:

- Age, gender, one-line look
- What they want
- How they talk in public vs private
- 2–3 habits
- How they treat `{{user}}`
- A few ALWAYS / NEVER lines if it helps (optional)

For extra characters, a short paragraph each is enough.

Pronouns are allowed. Soft language is allowed (`tends to`, `often`, `may`). Prefer clear sentences over rules.

Do not build a faction map. Do not build a consequence machine. Do not require a voice-sample block.

Paste the short System Rules block from the styleguide at the bottom of Situation.

---

## 3. World (place)

Write:

- 2–4 locations
- Who is usually where
- Time of day / a reason the scene is happening now

Optional: one or two `{notes}` if a place has a simple trigger (e.g. `{stockroom}: private talk`). Skip if it feels like overkill.

---

## 4. Opening

Must work for a player who never read the cards.

- Who is here
- Where / when
- What is being asked or offered
- End on an in-universe line or look the player can answer

Markdown:

- Narration and actions in `*italics*`
- Spoken lines as `**"quoted speech"**`
- Third person is fine
- Never write the player's lines, thoughts, or body from the inside
- Never use `[square brackets]` in the Opening
- Never end with "What do you do?"

Length: about 80–200 words. Longer is not better.

Example shape (replace everything):

```
*The darkroom is already red. Hester clips a print and does not look up until the door clicks.*

**"You're early. Tongs are on the right. Don't let the timer run out."**

*She waits to see if you actually start.*
```

---

## 5. Language

Situation and World may use `[Name]` for NPCs and `{{user}}` for the player. That is a suggestion, not a law.

Opening and Bio use plain names.

Do not puppet `{{user}}`.

---

## 6. Done checklist

- [ ] Five boxes
- [ ] Ages 21+
- [ ] Opening orients a cold player
- [ ] Opening markdown is correct
- [ ] Bio does not spoil
- [ ] User is not puppeteered

If those are true, the bot is ready. Do not run token counts, extra module tables, refusal trees, or archive protocols.

---

## 7. Looks

If the user wants a face, load `skills/anime-oc-looks/SKILL.md`. Copy the chosen look into Situation in one or two lines.

---

## 8. Figures

If the user wants a JuicyChat Figure or PFP prompt, load `skills/juicychat-figure-generator/SKILL.md`.

---

**End of starter bible 1.0**
