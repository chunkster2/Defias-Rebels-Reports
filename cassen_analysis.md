# Cassen Tank Death Analysis — March 22 to April 22, 2026

## TL;DR
**It's primarily a healing problem, not a Cassen problem.** The spike in deaths correlates directly with healer roster changes — specifically Frothy's absence and deteriorating heal coordination in Kara. A secondary factor is Cassen experimenting with Justicar spec on Mag (bad call, died 63s in).

---

## The Data

### Deaths By Week
| Date | Deaths | Boss | Trash | Notes |
|------|--------|------|-------|-------|
| Mar 3 | 0 | 0 | 0 | Clean week |
| Mar 10 | 0 | 0 | 0 | Clean week |
| Mar 24 | 2 | 2 | 0 | HKM wipes (7s and 13s in) |
| Mar 31 | 1 | 1 | 0 | Mag wipe |
| **Apr 7** | **0** | **0** | **0** | **Last clean week** |
| **Apr 14** | **11** | **4** | **7** | **Spike — Kara trash + Nightbane/Prince** |
| **Apr 21** | **9** | **4** | **5** | **Still bad — Kara trash + boss deaths** |

The jump from 0 deaths (Apr 7) to 11 deaths (Apr 14) and 9 deaths (Apr 21) is stark.

---

## Root Cause #1: Frothy Is Gone (Apr 21)

Frothy (Resto Druid) was consistently the **#1 healer on Cassen** in every single 25-man raid from March 3 through April 14:

| Date | Frothy HPS on Cassen (Gruul) | Present? |
|------|------------------------------|----------|
| Mar 10 | 560 HPS | ✅ |
| Mar 24 | 403 HPS | ✅ |
| Mar 31 | 405 HPS | ✅ |
| Apr 7 | 481 HPS | ✅ |
| Apr 14 | 421 HPS | ✅ |
| **Apr 21** | **N/A** | **❌ MISSING** |

On Apr 21, Frothy was **not in the raid at all**. That's 400-560 HPS of dedicated tank healing just gone. The remaining healers partially compensated but not enough — Cassen died on Mag at 63 seconds (previously surviving full fights), died on Attumen 22s in, and died on Netherspite.

---

## Root Cause #2: Kara Healing Coordination Collapsed

This is where the trash deaths come from. Comparing **identical trash types** between good weeks and bad:

### Ghostly Steward Pulls
| Date | DTPS | Dharkon Healing | Cassen Died? |
|------|------|-----------------|--------------|
| Mar 31 | 394 | 30,649 | No |
| Mar 31 | 910 | 18,792 | No |
| **Apr 21** | **477** | **2,136** | **YES** |
| **Apr 21** | **1,689** | **12,223** | **YES** |

On Apr 21, fight 23: Cassen took 477 DTPS (less damage than the Mar 31 pulls) but Dharkon only healed 2,136 total in 31 seconds. That's **87 HPS on a tank pulling 477 DTPS.** On Mar 31 equivalent pulls, Dharkon pumped 18-30K.

### Phantom Stagehand
| Date | DTPS | Dharkon Healing | Died? |
|------|------|-----------------|-------|
| Mar 31 | 940 | 24,283 | No |
| **Apr 21** | **854** | **9,895** | **YES** |

Same pattern: less damage taken, way less healing received.

### Why the healing dropped with MORE healers present:
- **Mar 31 Kara:** Dharkon (3.8M effective, **34% overheal**)
- **Apr 21 Kara:** Dharkon (3.4M effective, **42% overheal**), Krektt (485K, 38% OH), Hopped (397K, **53% OH**)

More healers but worse results. Dharkon's overheal went from 34% → 42%, and Hopped is running **53% overheal**. Classic healer coordination problem: everyone assumes someone else has the tank, heals land simultaneously creating overheal spikes, then there are gaps where nobody is casting on Cassen.

---

## Minor Factor: Cassen's Justicar Experiment (Apr 21)

On Apr 21 Magtheridon, Cassen swapped to **Justicar spec** (offensive prot variant). Results:
- Died **63 seconds** into the fight (previously surviving full 300+ second kills)
- Parsed **30.8%** (vs 91-93% as Protection in previous weeks)
- DPS while alive was ~1028 (higher than usual ~700), confirming offensive play

This was a bad call. Justicar on Mag without Frothy backing him up = dead tank. But this only accounts for 1 of his 9 deaths that week.

---

## What It's NOT: Gear/Survivability

Cassen's defensive stats are **stable across weeks.** Gruul melee comparison:

| Date | Avg Hit | Dodge% | Parry% | Block% | Total Avoid |
|------|---------|--------|--------|--------|-------------|
| Mar 10 | 3,941 | 19.4% | 18.3% | 45.2% | 43.0% |
| Mar 24 | 2,936 | 20.0% | 17.8% | 45.6% | 50.0% |
| Apr 7 | 4,391 | 16.4% | 15.1% | 56.2% | 34.2% |
| Apr 14 | 5,071 | 22.1% | 16.2% | 44.1% | 45.6% |
| Apr 21 | 4,024 | 19.7% | 15.8% | 43.4% | 43.4% |

No meaningful degradation. His ilvl has been stable (113-115). He's not swapping to DPS gear for general tanking — the avoidance/block numbers are consistent.

---

## Recommendations

1. **Get Frothy back.** This is the #1 priority. Frothy was the anchor of Cassen's healing, consistently providing 400-560 HPS of dedicated tank throughput. If Frothy is gone long-term, you need an equally dedicated tank healer replacement.

2. **Fix Kara healer assignments.** Having 3 healers with no clear tank-healing assignment is worse than 2 healers where one is locked on the tank. Assign one healer (Dharkon?) as the primary tank healer who does NOT leave Cassen to snipe raid damage.

3. **Tell Cassen to shelve Justicar for Mag.** It's not the right fight for it, especially without Frothy's safety net. If he wants to parse-chase on Mag, he needs the healing support to match.

4. **The healer overheal problem needs addressing.** 53% overheal from Hopped and 42% from Dharkon means wasted GCDs and mana. Better coordination = more efficient healing = fewer tank deaths.
