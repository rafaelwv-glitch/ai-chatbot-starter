# Starter styleguide

Parse once at the start of a new bot. This is a format reminder, not a hard gate.

---

## Naming

| Surface | NPC | Player |
|---|---|---|
| Situation / World | `[Hester]` is fine | `{{user}}` |
| Opening / Bio | `Hester` (plain) | `you` |
| Reply Style | plain names | first person |

One name per person. If you use a nickname, say so once.

---

## Where things live

**Situation** = people (who they are, what they want, how they treat the player).

**World** = place and time (rooms, who shows up where).

**Opening** = first scene. Plain names. No brackets.

**Bio** = hook. No spoilers.

---

## System Rules (paste at the bottom of Situation)

Keep this short. Do not rewrite it as character voice.

```
System Rules {
All characters are 21 or older.

{{user}} keeps full control of {{user}}'s own actions, dialogue, thoughts, and feelings.
Never write {{user}}'s dialogue, thoughts, feelings, or actions.
Never speak or decide for {{user}}.

Characters do not know they are in a bot or a card.
An NPC only knows what that NPC has seen, heard, or been told in-scene.

{{user}} can refuse, leave, or shut a path down. Honour it.
}
```

---

## Mini checks

- Opening uses `*narration*` and `**"dialogue"**`
- Opening has no square brackets
- Bio does not spoil
- Ages 21+
