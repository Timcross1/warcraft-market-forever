# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.663.0, installer 1.38.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.38.0 — bundled addon 2.663.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Post and Transit manual ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarket-Tools.zip)
- [Manual bundle with optional Farm, Performance, Hunter Ammo, Post and Transit](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-Addons-2.663.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-Farm-1.8.3.zip)
- [Standalone Hunter Ammo ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-Hunter-1.4.1.zip)
- [Standalone Warcraft Market Post ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-Post-1.1.0.zip)
- [Standalone Warcraft Market Transit ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-Transit-1.1.1.zip)
- [WMF core addon 2.663.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.663.0/WarcraftMarketForever-2.663.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe to fetch the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder, select any optional helpers and click Install/Reinstall addon, then `/reload` in WoW. The companion checks signed main-addon updates and selected Farm, Hunter, Performance, Post and Transit updates, plus current market data. The EXE launcher upgrades the Windows companion itself. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

### Optional downloads from their publishers

- Gathering: [GatherMate2](https://www.curseforge.com/wow/addons/gathermate2/files/all) and [GatherPath Forever](https://www.curseforge.com/wow/addons/gatherpath-forever), which requires GatherMate2.
- Saved containers: [DataStore](https://www.curseforge.com/wow/addons/datastore/files/all) and [DataStore Containers](https://www.curseforge.com/wow/addons/datastore_containers/files/all).
- Navigation: [Waypoint Tracker](https://www.curseforge.com/wow/addons/waypoint-tracker).

Choose the publisher’s WoW Forever files. These tools can be installed separately.

Signed automatic addon updates deliver **2.663.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Changes in 2.663.0

- **Forever Farm** shows pending Auction House sales below the summary. Confirmed sales can play the coin jingle and animate the sales window. Set **Include** to **On** to count verified, uncollected proceeds in Current Gold and its target. You can resize the summary, Loot and pending-sales windows independently.
- **Warcraft Market Post** adds a Post tab to the native mailbox with Quick Send, remembered recipients and a sent journal. Review the draft in WoW's Send Mail pane before sending.
- **Companion tools** in Warcraft Market Options opens installed helpers. GatherMate2 can supply gathering routes, DataStore Containers can show saved alt stock, and Fishing & Cooking coordinates can open an available waypoint provider.
- **Windows manager** lets you choose Farm, Performance, Hunter Ammo, Post and Transit individually.
- **Market pages** reduce repeat work when opening the dashboard and price trends, and reuse profession material lookups.


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
