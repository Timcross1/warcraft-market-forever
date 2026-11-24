# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.665.0, installer 1.40.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.40.0 — bundled addon 2.665.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Post and Transit manual ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarket-Tools.zip)
- [Complete manual addon bundle with optional helpers](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Addons-2.665.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Farm-1.8.12.zip)
- [Standalone Hunter Ammo ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Hunter-1.4.1.zip)
- [Standalone Warcraft Market Post ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Post-1.3.3.zip)
- [Standalone Warcraft Market Transit ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Transit-1.1.1.zip)
- [Standalone Forever Quest ZIP (manual optional addon)](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Quest-1.1.0.zip)
- [Standalone Forever Bank ZIP (manual optional addon)](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-Bank-1.0.0.zip)
- [WMF core addon 2.665.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.665.0/WarcraftMarketForever-2.665.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe once to upgrade to Windows companion **1.40.0**, which bundles addon **2.665.0** and its matching managed helpers. The EXE fetches the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder, select optional helpers and click Install/Reinstall addon, then `/reload` in WoW. The companion checks signed main-addon updates and selected Farm, Hunter, Performance, Post and Transit updates, plus current market data. Quest and Bank are separate optional manual addons in the complete ZIP. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

### Optional downloads from their publishers

- Gathering: [GatherMate2](https://www.curseforge.com/wow/addons/gathermate2/files/all) and [GatherPath Forever](https://www.curseforge.com/wow/addons/gatherpath-forever), which requires GatherMate2.
- Saved containers: [DataStore](https://www.curseforge.com/wow/addons/datastore/files/all) and [DataStore Containers](https://www.curseforge.com/wow/addons/datastore_containers/files/all).
- Navigation: [Waypoint Tracker](https://www.curseforge.com/wow/addons/waypoint-tracker).

Choose the publisher’s WoW Forever files. These tools can be installed separately.

With Windows companion **1.40.0 or newer**, signed automatic addon updates deliver **2.665.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Changes in 2.665.0 / Windows 1.40.0

- **Forever Farm 1.8.12:** Current Gold has independent width/height, compact coin art, one-row Target/ETA, saved 8-24 wallet text size and separate 4-32 px bar thickness. Its title matches the Forever Farm title's font and visible size, including independent Summary scaling. Look cycles all five appearances with one click. Settings open one panel at a time with Back/X; positions, custom sizes and values are retained. Summary and Loot snap with a slim gap, including different scales. Existing optional auction-house window remains independently movable/resizable and controlled under Windows.
- **Post 1.3.3:** permanent account address book, manually added full names, optional notes, known alts and confirmed send journal. `/wmpost addressbook` saves contacts away from a mailbox. The native Forever blank-realm identity case is handled using the exact native realm/shard identifier. Reply-driven Open all advances on server replies, with bounded waits, safeguards and accurate payment accounting. Payment glow and wallet coin animation/jingle remain optional. Hovering the Post launcher shows the addon version.
- **WMF 2.665.0:** ledger graph date controls use explicit date windows, and Profession Build includes learning/recipe-source references, including skill-cap progression. Existing exact-market, source-date and purchase-confirmation safeguards remain.
- **Forever Quest 1.1.0 and Bank 1.0.0:** available as optional manual addon folders and standalone ZIPs. These two extras are not yet managed by the Windows companion; copy only the folders you want from the complete ZIP. New addon discovery may need a normal game restart. Existing addons load changes with `/reload`.
- **Windows 1.40.0:** matching core 2.665.0 and updated Farm/Post bundles. Managed Farm, Performance, Hunter Ammo, Post and Transit remain selectable. Existing data, preferences and newer generated feeds are preserved. Mana and Hunter Shot FX remain excluded.

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

## Warcraft Market Post 1.3.3

- Own Inbox, Send composer, Recipients and Sent Journal, with native icons/tooltips and game delivery confirmation. Native/Mello visual panels stay suppressed while the mailbox controller remains active.
- Open all / Gold only, progress, Stop, multiple attachments, overflow batches, refreshed indices, bounded reply recovery and per-envelope failure isolation. COD/GM exclusions and bag-full handling retain undeliverable items safely in mail.
- Bag item search, one-stack or matching-stack attachment selection, removal, postage, money/COD and explicit per-send review. Pending guards prevent duplicate submission; journal records distinguish confirmed sends from attempts.
- Account address book, captured alts/previous recipients, manual Add name and notes. Contact editing works away from mailboxes and never sends mail. Saved variables and receipts survive addon updates.
- Optional glowing payment rows; verified incoming gold updates Current Gold with optional coin jingles/animation using actual wallet changes.

## Forever Quest 1.1.0 (optional manual addon)

- Completed turn-ins with green native completion ticks, quest icons/tooltips, completion times and recorded quest XP. Imports available historical completed quest IDs; missing old XP is not invented.
- Session and recorded totals, total observed XP, quest XP, XP/hour and native level progress. Optional periodic XP/hour flashes; movable/resizable window, appearance/visibility controls, pause and retained character data.

## Forever Bank 1.0.0 (optional manual addon)

- Independent replacement bank window with native item controls, icons/tooltips, search, filters, grid/list layouts and appearance options.
- Saved, dated read-only character bank snapshots and ownership; absence of a snapshot is unknown. Live bank actions require the bank to be open and retain native safeguards.

## Other optional helpers and updates

- Hunter Ammo 1.4.1: ammunition count, compact Auto Shot countdown, Aimed Shot readiness/cast feedback, Frost/Gold colours and movable controls. No projectile or target effects.
- Performance 1.0.0: bounded FPS samples, gradual supported scenery adjustment outside combat, restoration of settings it still owns and cooperative WMF background-work reduction. Native CPU/memory evidence is shown when available; no promised FPS gain, forced collection or forced reload.
- Transit 1.1.1: retained route/transport assistance and matching optional signed tool delivery.
- The Windows companion manages Farm, Performance, Hunter Ammo, Post and Transit. Quest and Bank are manual optional extras. Removing a managed choice preserves its installed files/settings.
- The existing signing identity protects main/code/media, Farm/Performance, Hunter and Post/Transit channels. Prices refresh independently from validated Blizzard collector exports with their real dates. Friends receive exports, never the collector database or credentials.
- Windows EXE/MSI files remain Authenticode unsigned. Saved variables and newer generated observations are preserved. Synthetic tests do not establish native visual appearance, server latency or live FPS.

Open WMF with `/wmf`, Farm with `/wmfg`, Performance with `/wmfp`, Hunter Ammo with `/wmha`, Post with `/wmpost`, Quest with `/wmquest`, and Bank with `/wmbank`.


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
