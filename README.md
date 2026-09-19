# RelicJack

### The Arcane Tables · Offline Edition

> Developed By Daniel Lantz, Designed by Gabriel Cram.

**Relicjack** is a single-file fantasy blackjack roguelite. Build a passive relic loadout, wager gold across five-round runs, unlock elemental casinos, collect rare artifacts, and climb through a local-only progression system.

> Designed to run completely offline in a browser — including school Chromebooks.

---

## ✦ Play It

No installation, account, server, or internet connection is required.

1. Download or clone this repository.
2. Open [`index.html`](./index.html) in Chrome, Edge, or another modern browser.
3. Your progress saves automatically in that browser.

For the best experience, use the GitHub-ready `index.html` at the repository root.

---

## 🎴 The Game Loop

1. Claim the one-time **Welcome Crate**.
2. Build a loadout from your unlocked relics.
3. Enter a five-round blackjack run.
4. Place wagers with gold, then Hit, Stand, or Double.
5. Earn gold, XP, relics, quest rewards, and casino progress.
6. Defeat casinos to unlock more elemental relic Orders.

Your goal is to become a legendary Cardwright by conquering the Elemental Casino Atlas and building powerful relic combinations.

---

## 🗝 Main Features

### Fantasy Blackjack

- Five-round casino runs with elemental themes.
- Gold wagering, animated chip stacks, blackjack actions, and dealer rules.
- Adaptive casino wager limits that rise as progression advances.
- Wins, pushes, double-downs, bust protection, resonance, and relic effects.

### Relic Collection

- **100 elemental Orders** with a huge collection of relics.
- Rarity tiers: **C, R, SR, SSR, UR, and HR**.
- Relics can reach **Level X** through duplicate discoveries and gold upgrades.
- Elemental Bonds reward compatible loadout combinations.
- Full relic Library, filters, Collection Map, branch focus, lore details, and set progress.

### Passive Loadouts

- Start with one visible relic slot and unlock up to five permanent passive slots in the Forge.
- Every equipped relic affects the full run.
- Loadouts cannot contain duplicate relics.
- Imbued relics receive a visual glow and a small power increase.

### Casino Atlas

- Begin at the **Fire Casino**.
- Win five perfect five-round games to defeat a casino and unlock the next Order.
- Each casino has its own dealer, atmosphere, fair table rule, and wager limits.
- The Dealer Journal records the keepers of the tables.

### Forge & Cases

- Open animated cases containing one, three, six, or ten relic rolls.
- Case reels reveal each relic one at a time.
- Unlockable elemental cases only draw from available casino Orders.
- The **Archive Case** can draw from the full non-Founder collection.
- Welcome Crate, rank caches, and special rewards use the same reel ceremony.

### Archive Artifacts

The **Unfiled Five** are permanent, unfusable, Hyper Rare Archive relics:

- Anarchist’s Archived Accord
- The Ashen Index
- The Null Curator’s Key
- The Obsidian Errata
- The Last Black Catalogue

They are level X on discovery, have decaying-black visuals, and can be toggled through the local Admin Console for testing.

### Progression

- Persistent gold, relic vault, casino unlocks, quests, deeds, rank, XP, and uptime.
- Daily login blessings and daily/weekly quests.
- Hall of Deeds achievements and full-set completion rewards.
- Level rewards, Cardwright’s Caches, Run Ledger, and Arcane Chronicle update history.

---

## 📜 Pages

| Page | Purpose |
| --- | --- |
| **Tavern** | Home, rank, daily rewards, quick status, and Chronicle summary. |
| **Loadout & Start** | Equip relic slots, inspect bonds, and begin a run. |
| **Casino Atlas** | View casino progression, dealer rules, and unlocked Orders. |
| **Forge** | Open cases, buy slot unlocks, and use cosmetic upgrades. |
| **Fusion Crucible** | Combine eligible Level X base relics into hybrid artifacts. |
| **Quest Hall** | Claim Daily Decrees and Weekly Chronicles. |
| **Relic Library** | Browse, filter, inspect, and equip the full collection. |
| **Hall of Deeds** | Track achievements and set-completion rewards. |
| **Run Ledger** | Review saved activity and recent progression. |
| **Arcane Chronicle** | Read versioned update records. |
| **Grimoire** | Read the full in-game guide. |
| **Rune Seals** | Redeem game codes and access the local Admin Console. |

---

## 💾 Saving & Offline Play

Relicjack stores progress in the browser’s **local storage**. This means:

- Progress persists after closing or refreshing the tab.
- The game works offline after the HTML file is available on the device.
- Progress is specific to the browser and device being used.
- Clearing browser site data/local storage will erase the save.

If a reload happens during a blackjack hand, the game safely returns the player to the Tavern rather than trying to reconstruct an incomplete hand.

---

## 📁 Project Structure

```text
.
├── index.html                 # GitHub-ready game file
├── README.md                  # Project documentation
└── outputs/
    └── relicjack.html         # Local working copy
```

---

## ⚙️ Technical Notes

- Built with vanilla **HTML, CSS, and JavaScript**.
- No packages, build system, online API, or asset downloads are required.
- All visuals, animations, interface styling, relic rendering, and game systems are bundled into one HTML file.

---

## ✨ Current Version

**v6.6 — The Unfiled Five**

The Archive set expanded with four new permanent HR artifacts, Archive collection progress, special case eligibility, effects, and unified Admin Console controls.

---

## License

This project is a personal game project. Add a license file before redistributing or accepting contributions.
