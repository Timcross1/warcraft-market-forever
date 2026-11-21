# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.650.0, installer 1.31.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.31.0 — bundled addon 2.650.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Manual addon bundle — WMF, Farm and Performance](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.650.0/WarcraftMarketForever-Addons-2.650.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.650.0/WarcraftMarketForever-Farm-1.5.1.zip)
- [WMF core addon 2.650.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.650.0/WarcraftMarketForever-2.650.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe to fetch the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder and click Install/Reinstall addon, then `/reload` in WoW. The companion checks publisher-signed main, Farm and Performance updates plus current market data. The EXE launcher upgrades the Windows companion itself. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

Signed automatic addon updates remain at **2.649.0** pending migration/use of the existing publisher signing key. Use the matching installer or versioned manual ZIP for **2.650.0**. The canonical `WarcraftMarketForever.zip` is the older signed package, not the current manual download.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Price updates and the in-game timestamp

- The Windows companion checks at five past the hour UTC and at sign-in. Installer upgrades realign the existing enabled task and keep automatic updates disabled where already opted out.
- The one-hour source freshness check keeps older downloads from replacing installed history. The collector and public price publisher continue independently.
- The bottom-left footer above CPU and RAM shows the last source check of the selected market loaded in WoW. Hover over the resource readout for the full UTC timestamp. Use `/reload` after new prices land.
- This release is delivered through the installer and manual ZIP. The existing signed automatic addon channel remains at 2.649.0.

## Included features



### Forever Farm 1.5.1 — `/wmfg`



- Live estimated gold/hour, session value, coins, quest gold, loot value, vendor alternative, goal progress and ETA.

- Compact Warcraft-style summary plus independently draggable/resizable loot panel. Native item icons, rarity colours and game tooltips.

- Two clear controls: **Loot: Every drop / Item totals** and **Value: Market / Vendor**. Matching ingredient quantities merge across looter-level link differences, retaining component valuations and named random variants.

- **Summarise loot session** opens a separate scrolling snapshot, with frozen quantities/values and native icons immediately before item names. Live loot continues unchanged.

- Full individual-drop history for new sessions, stored in compact chunks; only two chunks are decoded for scrolling. Older unavailable event details remain explicitly missing.

- **Gold/hour graph** opens the familiar blue native graph at any time: cumulative session-average GPH sampled at five active-minute checkpoints, plus the current/final endpoint. Vendor/Market alternatives, hover details and X; pause/reload/offline time excluded.

- **Ledger > Sessions** keeps one compact persistent row and graph per session, beyond the last 50 detailed item ledgers. Clicking a row opens its graph; later invoice corrections update the original final receipt total. Existing unrecorded checkpoints are not invented.

- All graph samples remain saved; long graphs draw a bounded extrema-preserving projection with every original checkpoint accessible on hover.

- Native fonts, text size, scale, themes, backgrounds and transparent-to-opaque panels; summary/tiny modes and saved positions.

- **Mouseover On/Off** on the loot toolbar; reveal when hovered and fade when idle. Explicit show/hide controls and clear paused status.

- Empty realm names use native normalized-name, CVar or numeric realm identity fallbacks. Unknown-realm samples remain local; no guessed realm or player GUID is uploaded. Missing identity pauses sharing while preserving consent and old records.

- Account-wide observed drop knowledge across characters on the same account; money, purchases and session accounting stay per character.

- Optional community drop sharing defaults to **No**. **Yes** queues only new complete observations after consent; same-realm/faction/build/instance cohorts, deduplication and bounded queues. Save consent with normal /reload or logout for the companion to read it. No old observations are uploaded retroactively.

- Community estimates show sample counts and uncertainty; they are observed player reports, not authoritative game drop chances. Market prices still use the original Blizzard collector.

- GPH graph **Clock / Session elapsed** toggle, with actual recorded checkpoint times. Older missing wall-clock times are explicitly estimated.

- Fixed stale mailbox/trade flags suppressing new loot. Background inbox updates no longer classify ordinary mob drops as mail. Historical unclassified aggregates cannot recreate missing item names.

- Tracking resumes after reload if it was active; a deliberately paused session stays paused. Loading/offline time does not inflate active time.

- Separate loot, unclassified receipts, purchases/spending, vendor sales and optional net auction-sale income. Estimated unsold loot and actual sale receipts are distinct accounting modes.

- Bind on Pickup items use vendor value only in row modes, session totals, gold/hour, mob averages and value alerts; market estimates do not inflate them.

- Session, dungeon-visit and observed-level ledgers; saved totals and personal bests for value, gold/hour, loot/hour and best drop.

- Enemy mouseover estimates include all readable observed corpse contents, including items not picked up. Native corpse sources establish attribution; no target guessing or invented drop tables.

- Observed mob loot tables show native item icons, names, quantities, percentages and hit/sample counts. Stacks, variants and repeat openings do not inflate occurrence counts. Hold Shift for more rows.

- Rates are empirical samples, not guaranteed game drop chances. Missing contents remain partial; unknown historical occurrence rates are not fabricated.

- Click a loot item to open an independent WMF price-history graph with period controls and X. Click the same item again to close it; saved sessions use their own market.

- Dedicated **Alerts** settings: custom minimum gold per item, optional native coin jingle, brief golden sparkles and preview. Default threshold is strictly above 1g per item.

- Bounded reusable rows, two-chunk decode cache, corpse history and particle pool. Detailed event logs and compact session records grow with recorded history; full item ledgers retain the latest 50 sessions. No auction queries, forced reload or forced garbage collection from Farm.



### Warcraft Market Forever 2.650.0 — `/wmf`



- WoW Forever EU Alliance, Horde and Blackwater market scopes using dated exports from the existing Blizzard API collector.

- Browse Auctions with search/category/rarity/level filters, native item tooltips, watch controls, scrolling and up to 50 items per page.

- Saved price, supply, auction and analysis graphs; saved searches, watch lists and local preferences.

- Character Shop recommendations with class, role, level and equipment matching, visible metadata coverage and incremental loading.

- Correct whole-stack commodity sale totals, matching native ITEM_PURCHASED confirmation and duplicate/context guards; unknown outcomes retain their retry lock.

- Profession BUY / Buy next can request a fresh native quote and finish the single clicked batch without repeated checking clicks. A rise above 10% requires review, using the original displayed batch as the baseline; no automatic next purchase.

- Stable three-day briefing work survives minute refreshes. Fresh unchanged API checks can confirm older price points without changing their original observation dates.

- My auctions and posting workflows with confirmed native receipts, exact variant/stack checks, competition evidence and explicit click-to-trade safeguards.

- Sniper and watch alerts; dated asking prices and estimated opportunities remain distinct from proven sales or guaranteed profits.

- Profession Build with main-material-first scanning, optional patterns, cached journeys, shopping/crafting steps, cost summaries and eight profession-specific daytime scenes.

- Materials, profession gear, crafting and conversion research, Disenchant, prospecting/milling research, reputation and farming reference views.

- Market intel and daily commentary views use existing generated feeds; browsing does not request paid AI. Feed source dates and incomplete coverage remain visible.

- Responsive classic/concept layouts, graph visibility controls, standard blue fonts, reusable row/projection caches and background-work pacing.

- New Horizons opening music and selectable sound/animation settings.



### Forever Performance 1.0.0 — `/wmfp`



- Configurable FPS target, fixed-size FPS history and gradual relief tiers for sustained low FPS.

- Supported scenery settings adjust outside combat and restore gradually. Manual changes and other addons' changes are preserved.

- Cooperative WMF background-work budgets and release of completed inactive projections while the market window is hidden.

- On-demand native CPU and memory diagnostics with throttled refresh. It does not enable legacy profiling, unload arbitrary addons, force garbage collection or promise an FPS gain.


## Installation and updates

Use WarcraftMarket-Setup.exe for Windows setup; each launch resolves and verifies the latest MSI. Saved older MSI files remain offline versioned installers. For a manual installation, extract the WarcraftMarketForever folder from the versioned ZIP into Interface/AddOns. WarcraftMarketForever.toc must sit directly inside the addon folder. Preserve WTF/SavedVariables and newer generated price files. Then use /reload and /wmf.

Automatic downloads default on for new companion installations and can be disabled. The companion checks at sign-in and hourly while signed in. Download prices now retries price checks; Update addon now checks signed main, Farm and Performance code and market data. The EXE launcher fetches the latest MSI when upgrading the Windows companion itself.

Prices update independently; publishing code does not refresh auction observations. Data retains genuine source dates. Stale/invalid packs are rejected and newer installed observations are preserved. No game password or database credentials are required.

## Removal, privacy and limits

Remove addon moves the folder into WarcraftMarketBackups outside AddOns and keeps WTF settings. Windows Settings > Apps removes the companion and its update task while keeping addon data/backups. Personal inventory, watchlists and receipts remain local. No collector database or private signing key is distributed.

Purchases require a player click and fresh native checks. Recorded asks and estimated profit do not guarantee sales. Synthetic validation does not replace native-client acceptance. The installer targets Windows 10/11 with .NET Framework 4.8.

## Feedback

[Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose) with addon/installer version, market, page, resolution/UI scale, reproduction steps and expected/actual behavior. Remove private information from screenshots.

[Release history](https://github.com/Timcross1/warcraft-market-forever/releases) | [Latest release notes](https://github.com/Timcross1/warcraft-market-forever/releases/latest)
