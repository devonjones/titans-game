---
tags:
  - Reference
  - Spells
---
# Spell Descriptions

## Instructions for Claude

When told to read this file and follow its instructions, do the following:

### Step 1: Scan All Spell Files
Search the character folder for **all directories** matching spell-level naming patterns (e.g. `0th*`, `1st*`, `2nd*`, `3rd*`, `4th*`, `5th*`, etc. through `9th*`). New directories may be added as the character levels up.

Each `.md` file in these directories is a spell. Read every spell file.

### Step 2: Find Checked Descriptions
In each spell file, look for **Flavor Text Options** sections containing checkboxes.
- `- [x]` = **Used at the table.** This description has been played.
- `- [ ]` = **Available.** Don't touch these.

### Step 3: Process Used Descriptions
For each checked description (`- [x]`):
1. **Log it** in the Used Descriptions section below (under the appropriate spell heading), noting which session it was used in if known.
2. **Remove the checked entry** from the spell file.
3. **Generate a new replacement description** and add it as an unchecked entry (`- [ ]`) in the spell file.
4. The new description should be **shaped by the tone, imagery, and phrasing of the used description**. Over time, this means the generated descriptions drift toward what actually happens at the table.

### Step 4: Update Combat Logs
Each spell file should have a **Combat Log** table at the bottom. For every spell cast during a session, add a row to that table. If the table doesn't exist yet, create it.

Format:
```
**Combat Log:**

| Session | Slot | Type | Target | Roll | Result |
|---------|------|------|--------|------|--------|
| [[Session XX - Name\|SXX]] | 1st | Lightning | Target description | Hit/Miss/Crit | Damage/Kill/etc |
```

- **Session:** Link to the session, with a short alias (S01, S02, etc.)
- **Slot:** What level slot was used (1st, 2nd, etc.), or "Cantrip"
- **Type:** Damage type or effect
- **Target:** Brief description of who/what was targeted
- **Roll:** Hit, Miss, Crit, or Auto (for saves)
- **Result:** What happened - damage dealt, kill, saved, etc.

If the session notes don't contain enough detail to fill in the roll and result, **ask the player** what happened.

### Step 5: Don't Invent From Nothing
- Only generate new descriptions for spells that have at least one used description logged below. The used descriptions set the tone.
- If a spell has never been cast (no entries in Used Descriptions below), leave it alone.

### Style Notes
- Cael doesn't "cast spells" - he releases pressure, calls the strike, becomes the wind, makes the air snap.
- Descriptions should be short and punchy - what it looks like, what it sounds like, what happens to the target.
- Include intimidation/voice lines where natural. Cael talks during combat.
- Lightning is his default element. Salt, static, ozone, and thunder are recurring sensory details.
- Descriptions should vary - don't repeat the same phrasing across entries for the same spell.

---

## Used Descriptions Log

### Chromatic Orb (1st Level Evocation)

- **Session 2 - Riverdale Tavern:** Cael holds a ball of lightning between his hands, arcing. He flings it at the bandit who seizes and drops to the floor, a smoking corpse.
