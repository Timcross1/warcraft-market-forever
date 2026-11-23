# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.661.0, installer 1.36.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.36.0 — bundled addon 2.661.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Manual addon bundle — WMF, Farm, Hunter and Performance](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.661.0/WarcraftMarketForever-Addons-2.661.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.661.0/WarcraftMarketForever-Farm-1.8.2.zip)
- [Standalone Hunter Ammo ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.661.0/WarcraftMarketForever-Hunter-1.4.1.zip)
- [WMF core addon 2.661.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.661.0/WarcraftMarketForever-2.661.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe to fetch the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder and click Install/Reinstall addon, then `/reload` in WoW. The companion checks publisher-signed main, Farm, Hunter and Performance updates plus current market data. The EXE launcher upgrades the Windows companion itself. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

Signed automatic addon updates deliver **2.661.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Fishing & Cooking

A full-width food table with a responsive panoramic banner, recipe ingredients, farming locations and coordinates, Auction House prices and estimated gold per hour. Food effects appear in tooltip green, including both the Intellect and kill XP bonuses on Roast Raptor. Hover a food for game details. **Buy recipe** opens the existing Buy Box for eligible recipes. **Back** returns to the previous view.

The release also corrects the posting error when choosing to use a recommendation override. Hunter Ammo 1.4.1 keeps the Auto Shot countdown and Aimed Shot marker, with the projectile and target effects removed. The full manual bundle and installer include Forever Farm 1.8.2, Hunter Ammo 1.4.1 and Forever Performance 1.0.0.

## Choose which addons to install

In the Windows companion, tick any of **Forever Farm**, **Hunter Ammo** and **Performance** before choosing **Install addon** or **Update addon now**. Hunter starts unchecked on new installs. Existing Hunter installations remain selected on upgrade if companion updates were enabled. Clearing a checkbox stops managing that addon and keeps its installed files and saved settings. Manual ZIP users can extract only the addon folders they want.


## Installation and updates

Use WarcraftMarket-Setup.exe for Windows setup; each launch resolves and verifies the latest MSI. Saved older MSI files remain offline versioned installers. For a manual installation, extract the WarcraftMarketForever folder from the versioned ZIP into Interface/AddOns. WarcraftMarketForever.toc must sit directly inside the addon folder. Preserve WTF/SavedVariables and newer generated price files. Then use /reload and /wmf.

Automatic downloads default on for new companion installations and can be disabled. The companion checks at sign-in and hourly while signed in. Download prices now retries price checks; Update addon now checks signed main, Farm, Hunter and Performance code and market data. The EXE launcher fetches the latest MSI when upgrading the Windows companion itself.

Prices update independently; publishing code does not refresh auction observations. Data retains genuine source dates. Stale/invalid packs are rejected and newer installed observations are preserved. No game password or database credentials are required.

## Removal, privacy and limits

Remove addon moves the folder into WarcraftMarketBackups outside AddOns and keeps WTF settings. Windows Settings > Apps removes the companion and its update task while keeping addon data/backups. Personal inventory, watchlists and receipts remain local. No collector database or private signing key is distributed.

Purchases require a player click and fresh native checks. Recorded asks and estimated profit do not guarantee sales. Synthetic validation does not replace native-client acceptance. The installer targets Windows 10/11 with .NET Framework 4.8.

## Feedback

[Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose) with addon/installer version, market, page, resolution/UI scale, reproduction steps and expected/actual behavior. Remove private information from screenshots.

[Release history](https://github.com/Timcross1/warcraft-market-forever/releases) | [Latest release notes](https://github.com/Timcross1/warcraft-market-forever/releases/latest)
