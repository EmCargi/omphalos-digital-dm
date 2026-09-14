# The Two-Doctrine Gate-Key

> **Source:** CP-2 (gear Item rail) + Omphalos Keys / Skeleton Keys.

## The Signature Asset

The demo's signature gear is a **gate-key** — 20 CP, `gear` item, Size Rank 0. It attunes to a Prime's door. Two doctrines, one chassis (mirrors psycho-frame/skiff/staff/harp/blade/exo-hand):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **Council Gate-Key** | `omphalos_council_key` | `{"kind":"stat_mod","acv_bonus":2,"ar":0,"note":"Key-attuned to a Prime's door — Council seal"}` | The legal lane — the Council's key |
| **Skeleton Key** | `omphalos_skeleton_key` | Same bonus + `Defect: Hunted` returning 2 CP → `Weapon Enhancement: Gate-Sever` | The forsaken lane — can destroy gates |

Both: 20 CP, rank C, `item_type: gear`, granted as starting gear (not a market buyout).

## Attributes

- Council key: attunes/locks a Prime's door (ACV +2 via `stat_mod`)
- Skeleton key: operates any gate, severs gates (Gate-Sever enhancement)

## Engine Path

One `gear` row per doctrine in the `items` table, `effect_json` structured for `models.py`. No new engine field — exactly the CP-2 rail from the six Primes.