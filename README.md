# 💿 Omphalos: The Council Chamber — Game Disc for Chronos Core

*The BESM Anime Multiverse hub — the secret chamber of seven doors and seven thrones where the Prime gatekeepers meet. Deadlocked since Ozymandius vanished, with Bazaroth's rogue member growing in the vacuum.*

> **Source:** BESM 4e Chapter 14 (Anime Multiverse) — First-party canon, no third-party IP.
> All content authored from the canon hooks. Regenerable via the Chronos engine.

---

## 🎮 Boot (when ready)

```text
/setting besm_omphalos       # swap discs in the TUI
/roster                      # Seat column
/module council_of_omphalos.json             # default starter module
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_omphalos` in `config/settings.json` → `council_of_omphalos.json` |
| **2 · Module** | ✅ `modules/council_of_omphalos.json` (validator-passed) |
| **3 · Roster** | ✅ Starter characters authored (`Characters/`, 50 CP, `besm_omphalos`) |
| **4 · Economy** | ✅ Seed catalog + chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–5 wired via Chronos Core engine.

## 🗂️ Structure

```
omphalos-digital-dm/
├── README.md               ← this home page
├── Characters/             ← PC/NPC sheets (besm_omphalos)
├── data/                   ← roster DB + catalog
├── Factions/               ← organizations & groups
├── Locations/              ← region & landmark sheets
├── Mechanics/              ← system rules & supplements
├── modules/                ← playable labyrinth modules
├── scripts/                ← import/parser utilities
└── World/                  ← lore vault
```

---

*Disc for the Chronos Core console. Swap via `/setting besm_omphalos`.*
