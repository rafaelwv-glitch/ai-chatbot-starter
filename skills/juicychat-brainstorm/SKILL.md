---
name: juicychat-brainstorm
description: Use when the JuicyChat idea is still vague. Outputs a short premise pick. Does not write Situation, World, Opening, or Reply Style. Triggers brainstorm, new premise, what if, is this viable. Do not trigger on go, build, assemble, or final cards.
---

# JuicyChat Brainstorm — Starter v1.0

**Job:** Turn a vague idea into one picked premise. Then stop.

Do not write cards in this skill.

---

## Output

Restate the idea in one line. Then give **three options**. Wait for a pick.

```
Premise A: [one sentence]
Premise B: [one sentence]
Premise C: [one sentence]

Ask: Which one, or mix?
```

After a pick, write this tiny packet and hand off:

```
Picked: [one sentence]
Setting: [place]
Lead: [name + one trait]
First scene: [one beat]
Next: write the five boxes with juicychat-bot-creator.
```

---

## Rules

- Three options is enough. Do not generate a grid of engines.
- Do not score viability with codes.
- Do not mention other bots or franchises.
- Do not write Opening prose.
- If the user already knows the premise, skip this skill.

---

## Hand-off

Once they pick, load `skills/juicychat-bot-creator/SKILL.md` and write cards.
