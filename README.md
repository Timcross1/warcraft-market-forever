# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.664.0, installer 1.39.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.39.0 — bundled addon 2.664.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Post and Transit manual ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarket-Tools.zip)
- [Manual bundle with optional Farm, Performance, Hunter Ammo, Post and Transit](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-Addons-2.664.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-Farm-1.8.5.zip)
- [Standalone Hunter Ammo ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-Hunter-1.4.1.zip)
- [Standalone Warcraft Market Post ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-Post-1.2.0.zip)
- [Standalone Warcraft Market Transit ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-Transit-1.1.1.zip)
- [WMF core addon 2.664.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.664.0/WarcraftMarketForever-2.664.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe once to upgrade to Windows companion **1.39.0**; it is required for the new Post file layout and corrected code/feed handling. The EXE fetches the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder, select any optional helpers and click Install/Reinstall addon, then `/reload` in WoW. The companion checks signed main-addon updates and selected Farm, Hunter, Performance, Post and Transit updates, plus current market data. The EXE launcher upgrades the Windows companion itself. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

### Optional downloads from their publishers

- Gathering: [GatherMate2](https://www.curseforge.com/wow/addons/gathermate2/files/all) and [GatherPath Forever](https://www.curseforge.com/wow/addons/gatherpath-forever), which requires GatherMate2.
- Saved containers: [DataStore](https://www.curseforge.com/wow/addons/datastore/files/all) and [DataStore Containers](https://www.curseforge.com/wow/addons/datastore_containers/files/all).
- Navigation: [Waypoint Tracker](https://www.curseforge.com/wow/addons/waypoint-tracker).

Choose the publisher’s WoW Forever files. These tools can be installed separately.

With Windows companion **1.39.0 or newer**, signed automatic addon updates deliver **2.664.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Changes in this release

- **Forever Farm 1.8.5:** Summary, Loot, Current Gold and Auction house window toggles are together at the top of Options > Windows. The auction toggle is fourth. The auction panel has independent title dragging, two-way corner resizing, X-to-hide, saved On/Off and `/wmfg auctions on/off/reset`. A dedicated session-goal area has a taller input and aligned action; the summary goal now wraps text and has space around its progress bar. The Loot header has a native Options cog and always-visible X, with grouped tabs and background dragging at narrow and wide sizes. Saved loot, ledger and preferences are preserved.
- **Warcraft Market Post 1.2.0:** a WMF-owned Inbox, Send composer, Recipients and confirmed Sent Journal replace the native/Mello handoff. Open all and Gold only use server-aware collection, refreshed indices, multiple attachments, bounded waits, failed-envelope isolation and overflow batches. COD and GM mail are excluded; items blocked by full bags remain safely in mail. Compose, icons/tooltips, attachment removal, money/COD and postage remain in WMF. Native delivery and secure transfer confirmation are retained; only confirmed sends enter the journal.
- **Core:** incremental and bounded market/history work, profession quote recovery, clearer Character Shop quantity/confirmation handling, reference metadata and optional provider/route integrations. Native exact-item, price, stock, scope, pending and user-click safeguards remain in place.
- **Installer 1.39.0:** embeds matching WMF 2.664.0, Farm 1.8.5, Post 1.2.0 and existing optional Performance 1.0.0, Hunter Ammo 1.4.1 and Transit 1.1.1. Optional components remain selectable; saved data and newer generated price history are protected.

## Warcraft Market

- Browse Auctions: progressive native results, search/category/rarity/level filters, saved scans, 50 items per logical page, wheel scrolling, native item icons/tooltips and exact-variant price checks.
- Price and supply graphs, dated history, item lookup, saved searches, watchlists and optional alerts. Missing, stale or wrong-market evidence remains explicit.
- My auctions, competition/undercut checks, posting, sales and trading ledgers. Purchases retain fresh exact-stack, funds, scope and pending-action checks; submission is never treated as confirmation. Profession buying avoids redundant quote clicks and requires review for a rise above 10%.
- Character Shop, Disenchant, smelting, crafting and recipe resale research, profession equipment, reputation, quests/material uses, farming and Darkmoon deck research.
- Profession Build: essential materials before optional patterns, saved same-market journeys, background route updates, compact blue controls, profession artwork and a moving scan indicator. Unknown prices never become free ingredients.
- Fishing & Cooking: full-width food table and lake banner, fish/meat/other filters, recipes, skill requirements, locations/coordinates where available, native green food effects, recipe Buy Box links, editable rate assumptions and estimated gold per hour. Reference routes and assumed rates are distinct from measured farming income.
- Market briefing, daily AI commentary and sourced intel. Viewing pages does not issue paid AI requests. Reports and observations keep their true dates and source coverage.
- Responsive layouts, fonts, scaling, panel visibility, graphs and retained account watchlists. New Horizons is the default opening track; saved music/mute choices remain.

## Forever Farm

- Compact session dashboard plus an independently draggable and resizable loot/ledger panel. Native game icons, item rarity and tooltips; fonts, themes, background opacity, sizing, saved positions and mouseover visibility controls.
- Live coins and loot estimates, dynamic gold/hour, best drop, target amount and ETA. Vendor/Market and Every drop/Item totals controls; optional timestamps. Summary opens a separate snapshot while new loot continues to record.
- Loot, purchases/spending, vendor receipts and optional confirmed net auction sales are separate. Bind-on-pickup items use vendor value only.
- Item rows open the WMF graph-only popup with close control; clicking the same item toggles it closed. Session GPH graphs use cumulative session averages sampled every five active minutes, plus the current endpoint, with Clock/elapsed controls. Saved session rows reopen retained graphs.
- Session, dungeon and level ledgers and personal records. Retained summaries include item quantities, values, best gold/hour and gold per level; missing historic events/checkpoints cannot be reconstructed.
- Enemy mouseover shows empirical drop occurrence percentages, sample counts, an observed item loot table and average readable corpse value, including uncollected drops. Partial samples remain labelled incomplete.
- Account-wide observed mob knowledge, character-specific finances and sessions. Optional community sharing defaults No and uses exact cohort identity; local account knowledge remains available across characters.
- Loot notifications have separate coin-sound and short golden-sparkle controls with an editable value threshold, strictly above 1g by default.
- Independent Current Gold wallet with five compact looks, six target-bar styles, target percentage, optional glow/coin effects and explicit hours ETA. Pause state survives reload and is visibly marked.

## Optional companions and updates

The Windows companion has independent Farm, Hunter and Performance choices. Hunter defaults off on fresh installations. Clearing a choice stops managing that addon while preserving its files and settings. Manual users may extract only wanted folders. Mana and Hunter Shot FX are excluded.

Hunter Ammo provides ammunition tracking, compact Auto Shot countdown and Aimed Shot readiness/cast feedback, Frost/Gold bar colours and movable controls. Version 1.4.1 has no projectile or target effects and does not change native missiles.

Performance samples FPS into bounded history, gradually reduces supported scenery settings outside combat under sustained load, restores settings it still owns and cooperatively reduces WMF background work. Its panel shows available native CPU/memory evidence. It does not restart arbitrary addons, force garbage collection/reloads or promise higher FPS in every scene.

The saved Setup.exe resolves the latest Windows MSI. Signed main/code/media, Farm/Performance and Hunter channels use the existing publisher identity; prices refresh independently from validated Blizzard collector exports. Friends receive exports, never the database or credentials. Original dates and newer installed feeds are preserved. WTF/SavedVariables are retained.

Windows EXE/MSI files remain Authenticode unsigned. Addon publisher signatures are separate. Synthetic regression and stress tests do not certify live game-server latency, FPS, another PC's security software or native visual appearance. Load an installed update with `/reload`; open WMF with `/wmf`, Farm with `/wmfg`, Performance with `/wmfp` and Hunter Ammo with `/wmha`.


## Installation and updates

Use WarcraftMarket-Setup.exe for Windows setup; each launch resolves and verifies the latest MSI. Saved older MSI files remain offline versioned installers. For a manual installation, extract the WarcraftMarketForever folder from the versioned ZIP into Interface/AddOns. WarcraftMarketForever.toc must sit directly inside the addon folder. Preserve WTF/SavedVariables and newer generated price files. Then use /reload and /wmf.

Automatic downloads default on for new companion installations and can be disabled. The companion checks at sign-in and hourly while signed in. Download prices now retries price checks; Update addon now checks signed main addon code, selected helper code and market data. The EXE launcher fetches the latest MSI when upgrading the Windows companion itself.

Prices update independently; publishing code does not refresh auction observations. Data retains genuine source dates. Stale/invalid packs are rejected and newer installed observations are preserved. No game password or database credentials are required.

## Removal, privacy and limits

Remove addon moves the folder into WarcraftMarketBackups outside AddOns and keeps WTF settings. Windows Settings > Apps removes the companion and its update task while keeping addon data/backups. Personal inventory, watchlists and receipts remain local. No collector database or private signing key is distributed.

Purchases require a player click and fresh native checks. Recorded asks and estimated profit do not guarantee sales. Synthetic validation does not replace native-client acceptance. The installer targets Windows 10/11 with .NET Framework 4.8.

## Feedback

[Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose) with addon/installer version, market, page, resolution/UI scale, reproduction steps and expected/actual behavior. Remove private information from screenshots.

[Release history](https://github.com/Timcross1/warcraft-market-forever/releases) | [Latest release notes](https://github.com/Timcross1/warcraft-market-forever/releases/latest)
