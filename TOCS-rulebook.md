# Tactical Operations Combat System (TOCS) – 2026 Version

### Creator Note
TOCS is meant to be a realistic, medium-speed tactical system. These rules are just a baseline that may be changed upon. GMs should adjust for campaign era, technology, and desired lethality. Players make tactical decisions under pressure. Anything not covered in this version is up to the GM or whatever version you are using.

---

## 1. The Health System

### 1.1 Health Thresholds
- **Complete Maximum HP:** 65 (absolute human limit)
- **Normal Maximum HP:** 40–50
- **Shock** (< 15 HP): Lose the weapon's flat "to hit" bonus. (e.g., 1d20 + 4 + DEX becomes 1d20 + DEX)
- **Crippled** (1–5 HP): Movement near zero. Cannot use main weapons. Disadvantage on all rolls.
- **Bleedout** (0 to -9 HP): Down, making death saving throws.
- **Dead** (-10 HP or lower): Instant death. No saves.

### 1.2 Death Saving Throws
On your turn while in Bleedout, spend your entire turn rolling 1d20 + DEX + CON (Max total modifier +6 to saving throw):
- **Nat 1:** Take 4 damage. If current HP is -5 or lower, you die instantly.
- **2–9:** Take 2 damage.
- **10–19:** Heal 1–2 HP (GM sets exact value based on campaign lethality).
- **Nat 20:** Instantly heal to 1 HP, even from -9.

---

## 2. Environmental/Combat Factors (Modifiers)

In short, this is every modifier for spotting (To-Spot), hitting (To-Hit), and damage bonuses or nerfs. To get each modifier for spotting, hitting, or damage, add/subtract the number for each relevant subsection (only listed for the modifier type).

You may stack one modifier from each subsection below, but never two from the same subsection.

### 2.1 Lighting — To-Hit
| Condition | Normal | NVGs | Thermals |
|---|---|---|---|
| Day | +0 | -4 | +2 |
| Sunrise/Sunset | -1 | -8 | +2 |
| Night ('High' Light) | -1 | +2 | +2 |
| Night (Low Light) | -3 | +3 | +2 |
| Night (Darkness) | -8 | +4 | +2 |

### 2.2 Lighting — To-Spot
| Condition | Normal | NVGs | Thermals |
|---|---|---|---|
| Day | +0 | -6 | +3 |
| Sunrise/Sunset | +0 | -8 | +3 |
| Night ('High' Light) | -2 | +3 | +4 |
| Night (Low Light) | -4 | +4 | +4 |
| Night (Darkness) | -6 | +6 | +4 |

### 2.3 Weather — To-Hit
| Condition | Normal | NVGs | Thermals |
|---|---|---|---|
| Light Rain/Snow | +0 | +0 | +0 |
| Medium Rain | -3 | -1 | -2 |
| Heavy Rain | -4 | -3 | -4 |
| Medium Snow | -2 | -1 | -1 |
| Heavy Snow | -5 | -3 | -2 |
| Heavy Snow & Rain | -7 | -5 | -3 |

### 2.4 Weather — To-Spot
| Condition | Normal | NVGs | Thermals |
|---|---|---|---|
| Light Rain/Snow | +0 | +0 | +1 |
| Medium Rain | -2 | +0 | +1 |
| Heavy Rain | -5 | -2 | -3 |
| Medium Snow | -1 | +0 | +1 |
| Heavy Snow | -4 | -2 | -3 |
| Heavy Snow & Rain | -11 | -9 | -8 |

### 2.5 Cover
| Cover Type | AC Bonus | To-Spot |
|---|---|---|
| Fully Out of Cover | +0 | +0 |
| Partly in Cover (low) | +4 | -1 |
| Partly in Cover (high) | +6 | -3 |
| Unsafe Cover | +5 | -3 |
| Full Cover | +25 (or more) | Cannot spot. |

**Blind fire rule** (shooting from Full Cover): If you want to shoot from full cover (cannot be an enclosed vehicle/fully inside), your weapon's flat to-hit bonus is removed and you also roll with disadvantage.

### 2.6 Distance
| Range | To-Hit | To-Spot |
|---|---|---|
| 100–200m | +0 | +0 |
| 200–300m | -1 | +0 |
| 300–400m | -2 | -1 |
| 400–500m | -4 | -3 |
| 500–600m | -6 | -6 |
| 600–700m | -8 | -9 |
| 700–800m | -8, disadvantage | -14 |
| 800–900m+ | -10, disadvantage | -19 |

---

## 3. Gunplay & Damage

**Headshots (all weapons):** Triggered on a natural 20, OR a total to-hit of 36+ after modifiers (AP round bonus doesn't count toward this total). Destroys any headgear worn (thermals, NVGs, etc.) in addition to dealing full damage.

**Shotgun Point-Blank Rule:** A headshot with a shotgun at under 1.5m is an instant kill regardless of HP.

### 3.1 Weapon Classes (Flat bonus depends on attachments/quality)
| Class | To Hit | Damage | Headshot Damage |
|---|---|---|---|
| Pistols | 1d20 + Flat(0–5) + DEX | 2d6 or 2d8 + Flat(2–3) | 2d20+20+Flat(2–3) |
| Rifles | 1d20 + Flat(2–8) + DEX | 2d(8–12) + Flat(3–5) | 2d20+20+Flat(3–5) |
| Snipers | 1d20 + Flat(1–8) + DEX | 2d10 to 2d20 + Flat(4–5) | 2d20+20+Flat(4–5) |
| Full-Auto | 1d20 + Flat(1–8) + DEX | 2d8+Flat(3–4) to 3d12+Flat(3–4) | 2d20+20+Flat(3–4) |
| Shotguns | 1d20 + DEX (-1 to -20 beyond 2m) | 4d8+4 to 5d10+4 | Normal shotgun damage unless point-blank (instant kill) |

### 3.2 Recoil / Multiple Shots
At the end of your turn, your recoil is reset.
- Shot 1: Normal
- Shot 2: Normal
- Shot 3: -1 to hit
- Shot 4: -2 to hit, disadvantage
- Shot 5 to 7: -4 to hit, disadvantage
- Shot 7+: -7 to hit, super disadvantage/disadvantage²

---

## 4. Turn Economy (TP System)

2 Turn Points (TP) per turn. A Bonus Action grants +1 TP (3 total). This system is only active **in combat**.

After 1 TP has been used by the first attacker (even if they still have 1–2 TP left), the other player/NPC gets **0.5 TP to use instantly**. If they don't use this, it does not get added on when it's their turn.

*(This is just a baseline for the GM to add onto.)*

| Cost | Action |
|---|---|
| 0.25 TP | Fire (1 shot) · Pick up a small item · Move in/out of cover · "Reset" recoil |
| 0.5 TP | Reload · Throw a grenade · Move 5m · Question GM for context/info (think of it as a quick scan; only for things between 0–100m) · Interact with an item/object |
| 1 TP | Scan/look around, not from full cover (opposed stealth [DEX] vs. perception [WIS]) · Switch weapons |
| 2 TP | Move a large object · Run 24m (opposed stealth [DEX] vs. perception [WIS+2]) · Move an ally at -9 to 0 HP, 15m (2 TP if ally is at 1–5 HP) |
| 3 TP | Heal another character (see Section 7) · Plant explosives |
| 4 TP | Heal yourself (Trained Operator+) |
| 6 TP | Heal yourself (Civilian/Untrained) |

---

## 5. Armor Class (AC) & Armor Piercing Rounds (AP)

| Armor | AC Range | AP Bonus |
|---|---|---|
| Unarmored | 7–11 | +0 hit / +2 dmg |
| Light | 12–16 | +2 hit / +2 dmg |
| Medium | 17–23 | +5 hit / +1 dmg |
| Heavy | 24–28 | +7 hit / +1 dmg |
| Unarmored Vehicle | 29–32 | +10 hit / +0 dmg |
| Armored Vehicle | 33–75 | +10 hit / -5 dmg |

---

## 6. Gameplay

### 6.1 Stat Modifiers
| Score | Modifier |
|---|---|
| 20 | +5 |
| 18–19 | +4 |
| 16–17 | +3 |
| 14–15 | +2 |
| 12–13 | +1 |
| 9–11 | +0 |
| 6–8 | -1 |
| 3–5 | -3 |
| 1–2 | -7 |

### 6.2 Minimum & Maximum Stats (Recommended for balancing)
- **Strength (STR):** 9 to 17
- **Dexterity (DEX):** 8 to 18
- **Constitution (CON):** 9 to 18
- **Intelligence (INT):** 6 to 16
- **Wisdom (WIS):** 6 to 16
- **Charisma (CHA):** 3 to 16

If you've rolled for one of these stats and it is either higher or lower than the allowed minimum/maximum, you may roll again and pick the number in range for that stat. If both your first and second roll don't fit in the range, you may pick either number.

### 6.3 Shot Placement

Shot placement allows a player/enemy to choose where to shoot at an enemy/vehicle/item. This can only be used once per turn (the 0.5 TP reaction window doesn't count) due to it bypassing headshots.

At distances of less than 1 meter, choosing where to shoot at an enemy rolls **Opposed vs. Attacker and Attacked**. Both characters roll 1d20+STR+DEX. The attacker gets a +2 to this. If the attacker rolls higher, their shot lands wherever they want it. This only applies if the attacker is targeting an instant-kill area (neck, head, heart, etc.) — targeting something like the legs does not count.

- Shooting between 1 and 7.5 meters: **-1 to hit.**
- Shooting between 7.5 and 200 meters: **-3 to hit** (rifle/sniper rifle only), plus an extra 0.5 TP.
- Shooting between 200 and 400 meters: **-5 to hit**, plus an extra 0.5 TP.
- Shooting 400m to 1km: **-10 to hit** (sniper/long-range rifle only), plus 1 full TP.

| Range | Placement Allowed | To-Hit Penalty | Notes |
|---|---|---|---|
| 0–1m (CQB/CQC) | Yes | +0 | See paragraph above. |
| 1–7.5m (CQB) | Yes | -1 | None. |
| 7.5–200m | Yes | -3 | Costs an extra 0.5 TP (total 0.75). |
| 200–400m | Yes | -5 | Costs an extra 0.5 TP (total 0.75). |
| 400m–1km | Yes | -10 | See paragraph above. |
| 1km+ | No | +0 | None. |

### 6.4 Mastery
Sustained use of a weapon type/tool grants a permanent +1 to +6 to-hit/use progression bonus.

---

## 7. Medical Training & Supplies

**Tiers:** Civilian/Untrained → Trained Operator (TCCC) → Doctor/Real Medic → Field Medic → Combat Medic (most combat-effective).

### 7.1 Small Medical Kit
| Tier | In-Combat | Out-of-Combat |
|---|---|---|
| Civilian | 3 TP, 1d4 HP + stabilize | 1d6 HP |
| Trained Operator | 3 TP, 1d4+1 HP + stabilize | 1d8+1 HP |
| Doctor | 2 TP, 1d6 HP + stabilize | 1d10+2 HP |
| Field Medic | 2 TP, 1d6+2 HP + stabilize | 1d10+4 HP |
| Combat Medic | 1.5 TP, 1d8+4 HP + stabilize | 1d12+4 HP |

### 7.2 Medium Medical Kit
| Tier | In-Combat | Out-of-Combat |
|---|---|---|
| Civilian | 5 TP, 1d8+2 HP | 2d8+2 HP |
| Trained Operator | 4 TP, 2d6+4 HP | 3d6+4 HP |
| Doctor | 5 TP, 2d8+6 HP | ⅓ Max HP + 5 |
| Field Medic | 4 TP, 3d6+4 HP | ⅓ Max HP + 8 |
| Combat Medic | 3 TP, 3d8+6 HP | ⅓ Max HP + 10 |

### 7.3 Large Medical Kit
| Tier | In-Combat | Out-of-Combat |
|---|---|---|
| Civilian | 5 TP, 1d8+2 HP. Unable to fully use. | 40% Max HP (round up). Unable to fully use. |
| Trained Operator | 8 TP, 2d12+4 HP | 50% Max HP (round up) |
| Doctor | 6 TP, 3d10+8 HP | 90% Max HP (round up) |
| Field Medic | 5 TP, 3d12+6 HP | 80% Max HP (round up) |
| Combat Medic | 5 TP, 4d10+10 HP | 70% Max HP (round up) |

### 7.4 Medical Items
- **Painkillers:** Shock threshold drops from 15 to 5 for 2 rounds.
- **Morphine Auto-Injector:** Immediately stabilizes, sets HP to 5. At the end of the next turn, HP drops to 1 unless healed above 5 or damaged further.
- **Splint** (Trained Operator+): While at 1–5 HP, ignores the Crippled movement restriction. Lasts until healed above 5 HP or 3 rounds, whichever comes first.

---

## 8. Explosives

Anyone in range rolls a saving throw; damage scales with distance band. These damage & range stats may change by extreme amounts for the type of weapon/explosive device.

| Type | Radius | Full / Half / Quarter Damage Bands |
|---|---|---|
| Small/Light (grenades, AP mines) | 3m | 0–1m / 1–2m / 2–3m |
| Medium (RPG, vehicle mines, breaching charge) | 6m | 0–2m / 2–4m / 4–6m |
| Large/Heavy (AT mines, tank/mortar rounds) | 7.5m | 0–2.5m / 2.5–5m / 5–7.5m |

- **8.1 Small/Light:** Save 1d20+DEX vs 12. Fail: 2d20+15 dmg. Success: 1d20+5 dmg.
- **8.2 Medium:** Save 1d20+DEX vs 15. Fail: 1d20+45 dmg. Success: 2d20+10 dmg.
- **8.3 Large/Heavy:** Save 1d20 vs 20 (no DEX). Fail: 3d20+75 dmg. Success: 5d20+40 dmg.

---

## 9. CQC & CQB (Close-Quarters Combat/Battle)

**CQB Range Definition:** Any engagement under 5 meters is considered CQB range. At this range, the Distance modifiers in Section 2.6 don't apply — use the modifiers below instead.

### 9.1 CQB Weapon Modifiers
- **Pistols/Shotguns:** No penalty. Built for close range.
- **Rifles/Full-Auto:** -2 to hit (unwieldy at grappling distance), but +1 damage die if it connects.
- **Snipers:** -6 to hit, or the GM may rule the shot isn't possible without repositioning.

### 9.2 Melee Combat
**To Hit:** 1d20 + STR modifier (Section 6.1) + Weapon Mastery bonus if applicable to melee.

**Damage:**
- Unarmed: 1d4 + STR
- Melee weapon (knife, tomahawk, etc.): 1d8 + STR
- Improvised weapon: 1d6 + STR

No Flat bonus — melee doesn't get the "+Flat" attachment-style bonus guns do, since there's no equivalent to optics/barrels here.

### 9.3 Grapple/Disarm (Opposed Roll)
Instead of a flat DC, grappling and disarming are opposed rolls against the target's own d20 + STR (or DEX, attacker's choice which stat the target defends with — grip strength vs. agility):
- **Grapple:** Win the opposed roll to restrain the target. A grappled target can't use Main Weapons (same restriction as Crippled) and only pistols/melee are usable until they break free (their turn, opposed STR check to escape).
- **Disarm:** Win an opposed roll to knock a weapon out of a target's hands. Costs 1 TP.

### 9.4 CQB & Cover Interaction
Full Cover's +25 AC doesn't apply against melee/grapple attempts — you can't out-AC someone who's already inside your cover with you. Partial cover bonuses (low/high) still apply as normal, representing awkward positioning rather than protection from range.

---

## 10. Vehicles

Vehicles use the same to-hit/AC math as personnel combat, but track Vehicle HP separately from crew HP (crew inside are protected by the vehicle's armor rating until it's disabled — see 10.4).

**Note:** Weak spots (e.g., front glass, car door on an unarmored vehicle) may count as unsafe cover for crew.

### 10.1 Vehicle Classes
| Class | AC (from Sec. 5) | Vehicle HP | Notes |
|---|---|---|---|
| Unarmored/Civilian | 29–32 | 80–120 | Standard market vehicles — sedans, trucks, SUVs. No mounted weapons. |
| Armored/Civilian | 33–45 | 120–180 | Custom or rare armored civilian vehicles. Glass/tires often have separate, lower AC (GM discretion). |
| Unarmored/Military | 29–34 | 100–150 | Jeeps, transport trucks. Uncommon in modern combat. May mount a mid weapon (see 10.3). |
| Armored/Military | 40–55 | 200–350 | APCs, IFVs. Can mount medium-to-heavy weapons. |
| Tanks | 60–75 | 400–600 | Immune to small arms and AP rounds below Medium Explosive tier (Sec. 8.2) entirely — no roll needed, damage is 0. |
| Planes/Aircraft | Varies (see 10.5) | 150–500+ | AC driven by maneuverability, not plating. |

### 10.2 Damaging Vehicles
- Small arms (Pistols, Rifles, Full-Auto, Shotguns) can only damage Unarmored/Civilian and Unarmored/Military vehicles normally. Against anything Armored or higher, small arms deal 0 damage unless firing AP rounds (Sec. 5) at exposed weak points (GM discretion — viewports, tires, hatches).
- Explosives (Sec. 8) are the primary tool against Armored vehicles and up. Use the vehicle's AC as the save DC modifier context; damage is rolled as normal per explosive tier.
- **Called shots to weak points** (tires, viewports, engine block): -6 to hit, but bypasses armor rating entirely and deals damage as if the vehicle were Unarmored.

### 10.3 Mounted Weapons
Vehicle-mounted weapons (turret guns, coaxial MGs, cannons) don't use a character's DEX — they use the gunner's DEX or a flat vehicle-weapon bonus (GM's call, +2 to +6 depending on stabilization tech), and ignore personnel Recoil penalties (Sec. 3.2) since mounts are stabilized. The TP cost to fire a mounted weapon is the same as firing any weapon (0.25 TP), but traversing/aiming a slow turret may cost an additional 0.75 TP at GM discretion.

### 10.4 Crew & Passengers
While a vehicle has Vehicle HP remaining, occupants cannot be targeted directly except by called shots at weak points (10.2) or explosives that exceed the vehicle's blast threshold.

When Vehicle HP hits 0, the vehicle is disabled (not necessarily destroyed) — occupants become directly targetable, and a follow-up explosive/incendiary hit can trigger a secondary explosion (GM discretion; suggest reusing the Medium Explosive table from Sec. 8.2 for anyone still inside/adjacent).

### 10.5 Aircraft (Special Case)
Planes don't use static AC — their defense comes from altitude, speed, and evasion:
- **Base AC** starts at the Armored/Military range (40–55) and adjusts with an opposed Piloting check (pilot's DEX + Mastery vs. attacker's to-hit) representing evasive maneuvers.
- Ground-based small arms and even most mounted weapons cannot effectively target aircraft above low altitude — this requires dedicated AA weapons or air-to-air weapons, handled as their own weapon category if your campaign needs them (left to GM to statblock based on era/setting).
