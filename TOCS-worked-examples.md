# TOCS — Worked Examples

A companion to the main rulebook. Each example walks through a full roll, start to finish, so players and GMs can see how the modifiers actually stack in practice.

---

## Character Sheet Template

```
Name: First, Code/middle, Last.
Age: ()
Gender: F/M

Current Health points: ()
Maximum Health points: ()
Armor Class (number and type): ()
Medical Tier: ()

Strength (STR): ()
Dexterity (DEX): ()
Constitution (CON): ()
Intelligence (INT): ()
Wisdom (WIS): ()
Charisma (CHA): ()

Main weapon (damage & to-hit): ()

Secondary weapon (damage & to-hit): ()

Weapon/Tool Mastery: ()

Skill(s)/Passive(s): ()

Appearance: ()

Personality: ()

Background: ()

Extras:
```

---

## Sample Character — "Reyes"

- **Name:** Reyes, R
- **Age:** N/A
- **Gender:** Male
- **Current HP:** 46
- **Maximum HP:** 46
- **Armor Class:** 20, Medium armor
- **Medical Tier:** Trained Operator
- **STR:** 12 (+1)
- **DEX:** 14 (+2)
- **CON:** 13 (+1)
- **INT / WIS / CHA:** N/A
- **Main weapon:** M4 — Damage: 2d10+3, To-Hit: 1d20+5+2 (1d20+7)
- **Secondary weapon:** N/A
- **Weapon/Tool Mastery:** Rifle +1
- **Skills/Passives:** None

---

## Example 1 — Spotting a Target (Section 2.2 / 2.4 / 2.5)

**Scene:** Reyes is scanning at Night (Low Light), Light Rain, target is 450m out and partly in low cover.

| Source | Modifier |
|---|---|
| Lighting — Night (Low Light), Normal | -4 |
| Weather — Light Rain, Normal | +0 |
| Distance — 400–500m, To-Spot | -3 |
| Cover — Partly in Cover (low), To-Spot | -1 |
| **Total To-Spot Modifier** | **-8** |

Reyes rolls **1d20 - 8**. Say the die comes up 15 → total **7**. This is checked against the target's opposed stealth (DEX) roll, as defined in Section 4.

*Once Reyes spots the target, no further Spot rolls are needed unless the target breaks line of sight, moves to a new range band, or conditions change.*

---

## Example 2 — Taking the Shot (Section 3.1 / 2.6)

Same scene, now Reyes fires at the spotted target (400-500m, Night Low Light, Light Rain, no NVGs/thermals).

| Source | Modifier |
|---|---|
| Lighting — Night (Low Light), Normal | -3 |
| Weather — Light Rain, Normal | +0 |
| Distance — 400–500m, To-Hit | -4 |
| Attachments (Flat) | +5 |
| DEX | +2 |
| Rifle Mastery I | +1 |
| **Total To-Hit Modifier** | **+1** |

Reyes rolls **1d20 + 1**. A 19 → total **20**, hitting the target's AC. Damage: **2d10 + 5** (Flat bonus applies to damage too, per weapon's Flat stat).

---

## Example 3 — Multiple Shots & Recoil (Section 3.2)

Reyes decides to burst-fire 4 shots this turn at the same target (no new Spot roll needed — already spotted).

| Shot # | Recoil Modifier | Effective To-Hit |
|---|---|---|
| 1 | +0 | +1 (from Example 2) |
| 2 | +0 | +1 |
| 3 | -1 | +0 |
| 4 | -2, disadvantage | -1, disadvantage |

TP Cost: 4 shots × 0.25 TP = **1 TP total**.

---

## Example 4 — Getting Hit & Health Thresholds (Section 1.1)

Reyes is hit for 34 damage on a 46 Max HP pool. New HP: **12**.

Since 12 HP is under the Shock threshold (15), Reyes now loses the weapon's flat "to hit" bonus on all future rolls until healed back above 15 — the +5 Flat attachment bonus from Example 2 would no longer apply.

---

## Example 5 — Going Down & Death Saves (Section 1.2)

Reyes takes another hit, dropping to **-4 HP** (Bleedout Zone). On Reyes's next turn, the entire turn is spent rolling a death save:

**1d20 + DEX (2) + CON (1)**, capped at +6 total modifier — here the raw total is only +3, so the cap doesn't come into play.

Roll: **14** → total **17**. Since 17 falls in the 10–19 band, Reyes heals 1–2 HP (GM's call) and stays in the Bleedout Zone, alive for another round.

---

## Example 6 — Medical Kit Use (Section 7.1)

An ally with Field Medic training rushes over and uses a Small Medical Kit on Reyes, who is still down.

**In-Combat cost:** 1.5 TP (per the current Small Kit table — Field Medic actually lists 2 TP; adjust per your live table). **Healing:** 1d6+2 HP, and Reyes is stabilized (no longer needs to roll death saves).

Roll: **4** → Reyes heals **6 HP**, moving from -4 HP to +2 HP — out of Bleedout, into the Crippled threshold (1-5 HP).

---

## Example 7 — CQC Engagement (Section 9)

Reyes rounds a corner into a target at 3 meters — CQB range, no Distance modifier from Section 2.6 applies.

Using the M4 (a Rifle) inside CQB range: **-2 to hit**, but **+1 damage die** if it connects.

| Source | Modifier |
|---|---|
| Attachments (Flat) | +5 |
| DEX | +2 |
| Rifle Mastery I | +1 |
| CQB Rifle Penalty | -2 |
| **Total To-Hit** | **+6** |

If it connects: damage becomes **3d10 + 5** instead of the normal 2d10+5.

---

## Example 8 — Explosive Resolution (Section 8)

A grenade (Small/Light) lands 1.5m from Reyes — inside the 1-2m half-damage band.

**Save:** 1d20 + DEX (2) vs DC 12. Roll: 8 → total **10**. Success.

**Success damage:** 1d20+5. Roll: 11 → **16 damage** applied.

---

## Example 9 — Vehicle Engagement (Section 10)

Reyes fires small arms (Rifle, AP rounds) at an Armored/Military vehicle (AC 40-55).

Per 10.2: small arms deal 0 damage against Armored-tier vehicles or higher **unless** targeting an exposed weak point.

Reyes instead calls a shot at the vehicle's viewport: **-6 to hit**, but on a hit, damage is resolved as if the vehicle were Unarmored — full rifle damage applies (2d10+5), rather than being reduced to 0.

---

*These are illustrative baselines only — GMs should adjust exact rolled outcomes, opposed stealth values, and edge-case rulings (weak point locations, etc.) to fit their table.*
