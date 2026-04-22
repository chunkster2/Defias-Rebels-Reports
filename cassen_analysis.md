# Cassen Tank Death Analysis — Feb 22 to Apr 22, 2026

**Guild:** Nightslayer-US | **Tank:** Cassen (Protection Paladin) | **Content:** TBC Phase 1 (Gruul/Mag 25-man, Karazhan 10-man)

---

## TL;DR

**Cassen has never been properly defense capped and takes crushing blows on 30-65% of boss melee hits that land.** He also swaps gear 5-7 times per raid night, trading defense for spell damage on "easier" bosses. The recent death spike (0 deaths → 11 → 9) is caused by the combination of: (1) increasingly aggressive gear swaps sacrificing survivability, (2) Frothy (his best healer) disappearing from the raid, and (3) Kara healing coordination collapsing. All three hit at once.

---

## 1. Defense Cap / Crit Immunity

**Cassen needs 490 defense skill (5.6% crit reduction) to be crit immune vs level 73 raid bosses. He has never consistently hit this threshold.**

### Crit Immunity by Week — 25-Man Boss Gear

| Date | Spec | Def Rating | Def Skill | Resil | Crit Red | Immune? | Margin |
|------|------|-----------|-----------|-------|----------|---------|--------|
| Feb 22 | 0/44/17 | 280 | 488.1 | 0 | 5.53% | **NO** | -0.07% |
| Feb 24 | 0/44/17 | 269 | 483.5 | 0 | 5.34% | **NO** | -0.26% |
| Mar 3 | 0/44/17 | 253 | 476.8 | 0 | 5.07% | **NO** | -0.53% |
| Mar 10 | 0/40/21 | 252 | 476.3 | 11 | 5.33% | **NO** | -0.27% |
| Mar 24 | 0/31/30 | 283 | 489.4 | 0 | 5.58% | **NO** | -0.02% |
| Mar 31 | 0/31/30 | 283 | 489.4 | 0 | 5.58% | **NO** | -0.02% |
| Apr 7 | 0/31/30 | 264 | 481.4 | 11 | 5.53% | **NO** | -0.07% |
| Apr 14 (Mag) | 0/31/30 | 283 | 489.4 | 0 | 5.58% | **NO** | -0.02% |
| Apr 14 (Gruul) | 0/31/30 | 264 | 481.4 | 11 | 5.53% | **NO** | -0.07% |
| Apr 21 (25-man) | 0/31/30 | 264 | 481.4 | 11 | 5.53% | **NO** | -0.07% |

**He's crit immune on exactly 2 types of encounters:** HKM on Apr 14 (5.87%, +0.27%) and Prince/Netherspite on Apr 14 (5.91%, +0.31%) — because he swaps to max defense gear for those specific fights.

### Empirical Boss Crits Received

| Date | Boss Melee Swings | Crits | Crit Rate (of landed) |
|------|-------------------|-------|----------------------|
| Feb 22 | 865 | 0 | 0% |
| Feb 24 | 898 | 0 | 0% |
| Mar 3 | 230 | 0 | 0% |
| Mar 10 | 189 | 0 | 0% |
| Mar 24 | 239 | **1** (Mag: 10,068 dmg) | 3.3% |
| Mar 31 | 995 | **1** (Opera: 2,891) | 1.3% |
| Apr 7 | 195 | 0 | 0% |
| Apr 14 | 1012 | 0 | 0% |
| Apr 21 | 679 | **1** (Gruul: 5,451) | 1.1% |

Being 0.02-0.27% below cap means crits are rare but they DO happen. A 10,068 Mag crit is potentially lethal.

---

## 2. Crushing Blows — The Bigger Problem

**This is worse than the crit situation.** Paladins need miss + dodge + parry + block ≥ 102.4% to push crushing blows off the combat table. Cassen is running 86-96% table coverage, leaving a 6-16% window for crushing blows.

### Gruul Combat Table Breakdown

| Date | Swings | Miss | Dodge | Parry | Block | Table% | Gap | Crushes | Crush% (of landed) |
|------|--------|------|-------|-------|-------|--------|-----|---------|-------------------|
| Mar 10 | 93 | 5.4% | 19.4% | 18.3% | 45.2% | 88.2% | -14.2% | 4 | 36% |
| Mar 24 | 90 | 12.2% | 20.0% | 17.8% | 45.6% | 95.6% | -6.8% | 3 | 75% |
| Mar 31 | 78 | 12.8% | 11.5% | 16.7% | 51.3% | 92.3% | -10.1% | 6 | **100%** |
| Apr 7 | 73 | 2.7% | 16.4% | 15.1% | 56.2% | 90.4% | -12.0% | 4 | 57% |
| Apr 14 | 68 | 7.4% | 22.1% | 16.2% | 44.1% | 89.7% | -12.7% | 6 | **86%** |
| Apr 21 | 76 | 7.9% | 19.7% | 15.8% | 43.4% | 86.8% | -15.6% | 4 | 40% |

**On Mar 31, 100% of Gruul melee hits that landed were crushing blows.** On Apr 14, 86%. These crushing blows hit for 3,000-12,000+ damage.

### All Boss Crushing Blow Rates

| Date | Boss Crush Rate (of landed) | Sample |
|------|----------------------------|--------|
| Feb 22 | 33% | 30 crushes in 521 swings |
| Feb 24 | 26% | 25 in 898 |
| Mar 3 | 25% | 8 in 230 |
| Mar 10 | 44% | 8 in 189 |
| Mar 24 | 47% | 14 in 239 |
| Mar 31 | 53% | 50 in 995 |
| Apr 7 | **64%** | 16 in 195 |
| Apr 14 | **50%** | 46 in 1012 |
| Apr 21 | 30% | 26 in 679 |

Crushing blows are the **single biggest source of spike damage** on Cassen. When a Mag crushing blow hits for 10,343 or 12,054, that's more than half a tank's health pool in one swing.

---

## 3. The Gear Swapping Problem

Cassen carries multiple gear sets and swaps between every boss fight, trading defense and stamina for spell power (threat). This is common for farm content prot paladins, but **his swaps are getting more aggressive**.

### Apr 21 Gear Set Breakdown (by boss)

| Boss | Def Rating | Def Skill | Crit Immune? | Stamina | Spell Power | Key Swaps |
|------|-----------|-----------|-------------|---------|-------------|-----------|
| Mag/HKM/Gruul | 264 | 481.4 | NO (-0.07%) | 468 | 569 | Base 25-man set |
| Attumen | 244 | 473.0 | NO (-0.40%) | 468 | 649 | -Devilshark Cape +Shadow-Cloak, -Archmage +Magus-Blade |
| Moroes | 264 | 481.4 | NO (-0.07%) | 471 | 613 | Cloak back |
| Maiden | 248 | 474.6 | NO (-0.34%) | 456 | 639 | -Barbed Choker +Brooch of Fury |
| **Curator** | **303** | **497.8** | **YES (+0.59%)** | **486** | **441** | Full tank set (dodge trinket + block trinket + defense ring) |
| Illhoof | 228 | 466.2 | NO (-0.67%) | 453 | **675** | Stripped 5 slots for threat |
| Shade of Aran | 209 | 458.2 | NO (-0.99%) | 438 | **717** | Also swapped shield for SP shield |
| **Netherspite** ✗✓ | 228 | 466.2 | NO (-0.67%) | 453 | **675** | Threat gear on a hard-hitting boss → WIPED |
| Prince | 303 | 497.8 | YES (+0.31%) | 484 | 495 | Back to full tank set |

**Key observations:**
- His max defense set (303 rating) IS crit immune. He knows how to be capped — he chooses not to be.
- He only puts on full defense for Curator and Prince. Everything else gets threat gear.
- **Netherspite in threat gear was a wipe.** He re-killed it in the same gear set.
- On Shade of Aran he dropped to 209 defense rating (458 skill) — nearly 1% below crit cap. He even swapped his Aldori Legacy Defender (19 def, 5279 armor) for Triptych Shield of the Ancients (0 def, +42 SP). That's trading a tank shield for a spell damage shield.

### Talent Spec Evolution

| Dates | Spec | Notable |
|-------|------|---------|
| Feb 22 - Mar 3 | 0/44/17 | Deep prot. Has Ardent Defender (passive damage reduction <35% HP) |
| Mar 10 | 0/40/21 | Dropped 4 prot for ret |
| Mar 24 onward | **0/31/30** | Lost Ardent Defender, lost Reckoning, invested heavily in Ret tree for threat |

Dropping from 44 to 31 prot points means **losing Ardent Defender**, the passive that reduces damage taken when below 35% HP. This is a critical safety net for spike damage — exactly the kind of damage that kills tanks.

---

## 4. The Healing Collapse (Apr 14 + Apr 21)

### Frothy Disappears

**Frothy** (Resto Druid) was the #1 healer on Cassen for every 25-man raid from Mar 3 through Apr 14 (400-560 HPS during boss fights). **Frothy was completely absent on Apr 21.**

| Date | Frothy Present? | Frothy HPS on Cassen (Gruul) |
|------|----------------|------------------------------|
| Mar 10 | ✅ | 560 |
| Mar 24 | ✅ | 403 |
| Mar 31 | ✅ | 405 |
| Apr 7 | ✅ | 481 |
| Apr 14 | ✅ | 421 |
| **Apr 21** | **❌** | **N/A** |

### Kara Healing Coordination Broke

Identical trash types, dramatically different healing output on Cassen:

| Trash Type | Date | DTPS | Dharkon Healing | Died? |
|------------|------|------|-----------------|-------|
| Ghostly Steward | Mar 31 | 394 | 30,649 | No |
| Ghostly Steward | Mar 31 | 910 | 18,792 | No |
| **Ghostly Steward** | **Apr 21** | **477** | **2,136** | **YES** |
| **Ghostly Steward** | **Apr 21** | **1,689** | **12,223** | **YES** |
| Phantom Stagehand | Mar 31 | 940 | 24,283 | No |
| **Phantom Stagehand** | **Apr 21** | **854** | **9,895** | **YES** |

Less damage taken, way less healing received. Dharkon's overheal went from 34% → 42% (Kara overall), and Hopped runs 53% overheal — classic "everyone assumes someone else has the tank" coordination failure.

---

## 5. Deaths Timeline

| Date | Deaths | Boss | Trash | Notes |
|------|--------|------|-------|-------|
| Feb 22 | 7 | 4 | 3 | Early progression, expected |
| Feb 24 | 12 | 6 | 6 | Still learning |
| Mar 3 | 0 | 0 | 0 | |
| Mar 10 | 0 | 0 | 0 | |
| Mar 24 | 2 | 2 | 0 | HKM wipes (died 7s and 13s in) |
| Mar 31 | 1 | 1 | 0 | Mag wipe |
| Apr 7 | 0 | 0 | 0 | Last clean week |
| **Apr 14** | **11** | **4** | **7** | Prince wipes, Kara trash deaths |
| **Apr 21** | **9** | **4** | **5** | Frothy absent, Netherspite wipe, trash deaths |

---

## 6. Consumables

| Date | Consumable | Type |
|------|-----------|------|
| Apr 7 (clean) | Flask of Blinding Light | Flask (persists through death) |
| Apr 14 (bad) | Adept's Elixir + Elixir of Draenic Wisdom | Elixirs (lost on death, cheaper) |
| Apr 21 (bad) | Flask of Blinding Light | Flask |

Not a major factor, but Apr 14's elixir downgrade is notable — each death costs him his consumable buffs.

---

## Root Cause Summary (Ranked)

### 1. **Crushing blows (structural, ongoing)**
Cassen has NEVER been crush immune. 30-65% of boss melee hits that land are crushing blows dealing 3,000-12,000+ damage. This is the fundamental survivability hole. A prot paladin needs Holy Shield block coverage + enough avoidance/block to push the combat table to 102.4%. He's running 86-96%.

### 2. **Increasingly aggressive gear swapping (getting worse)**
He swaps gear 5-7 times per Kara clear, dropping defense by 20-95 rating between bosses. On Apr 21, he tanked Netherspite (a hard-hitting boss) in threat gear with only 228 defense rating and wiped. His Shade of Aran gear has 209 defense rating and swaps his tank shield for a spell damage shield.

### 3. **Not crit immune (structural, ongoing)**
His primary 25-man gear set sits at 481-489 defense skill (needs 490). Crits are rare (1 every ~500 boss swings) but devastating when they land — a 10,068 Mag crit is potentially lethal combined with a crushing blow.

### 4. **Lost Ardent Defender (talent respec)**
From Mar 24 onward, he respecced from 0/44/17 to 0/31/30, losing Ardent Defender — the passive that reduces damage taken below 35% HP. This was his safety net against spike damage. Gone.

### 5. **Frothy gone (Apr 21)**
His best healer (400-560 HPS dedicated tank healing) was absent on the worst week.

### 6. **Kara healing coordination collapse (Apr 14+)**
More healers with worse results. Dharkon's overheal went up, Hopped runs 53% overheal. Healing gaps on trash pulls dropped from consistent tank healing to sporadic coverage.

---

## Recommendations

1. **Hit the defense cap.** He needs 490 defense skill minimum for every boss fight. His full defense set already hits 497.8 — he just needs to stop stripping it for threat on bosses that can kill him. At minimum: Violet Signet of the Great Protector (19 def) + Barbed Choker (16 def) should be non-negotiable.

2. **Address crushing blows.** This requires:
   - Higher block rating on gear (he's running 56-122, needs more)
   - 100% Holy Shield uptime (needs mana sustain)
   - Consider Libram of Repentance (+42 block rating) as his default libram, not just for Curator/Prince
   - The block trinkets (Figurine of the Colossus, Styleen's Impeding Scarab) should be used more broadly

3. **Get Ardent Defender back.** A 0/40/21 or 0/44/17 spec gives the passive damage reduction safety net. The ret tree threat from 0/31/30 isn't worth dying for on farm content.

4. **Get Frothy back or assign a dedicated tank healer.** Frothy was the anchor. If they're gone, someone needs to be explicitly assigned as the primary Cassen healer.

5. **Kara healing assignments need to be explicit.** One healer locked on tank, period. The "everyone snipe heals" approach is killing Cassen on trash.

6. **If Cassen wants to gear for threat, he needs the healing support to match.** Threat gear on a tank who takes crushing blows requires healer buy-in. That means discussing it with healers, not just silently swapping rings between pulls.
