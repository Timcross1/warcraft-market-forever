# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.654.0, installer 1.35.0

- [Always-current Windows installer EXE](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.exe)
- [Windows installer 1.35.0 — bundled addon 2.654.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Manual addon bundle — WMF, Farm, Hunter and Performance](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.654.0/WarcraftMarketForever-Addons-2.654.0.zip)
- [Standalone Forever Farm ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.654.0/WarcraftMarketForever-Farm-1.8.2.zip)
- [Standalone Hunter Ammo ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.654.0/WarcraftMarketForever-Hunter-1.4.0.zip)
- [WMF core addon 2.654.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.654.0/WarcraftMarketForever-2.654.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run WarcraftMarket-Setup.exe to fetch the latest MSI even from an older saved launcher. After the MSI upgrade, open Warcraft Market, choose the game folder and click Install/Reinstall addon, then `/reload` in WoW. The companion checks publisher-signed main, Farm, Hunter and Performance updates plus current market data. The EXE launcher upgrades the Windows companion itself. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

Signed automatic addon updates deliver **2.654.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

Forever Farm 1.8.2: original compact wallet views, continuous gold/blue/silver glowing target styles, explicit hours ETA, independent resizing, Shift-click options, and all received gold with the optional income-mode toggle. Graph resizing/sorting and genuine market source dates are retained.

Hunter Ammo 1.4.0: one compact Auto Shot countdown bar and Aimed ready mark/cooldown/cast timer, without help rows. Frost/Gold themes pair the bar with original matching ice/gold arrow art and trails; Up direction and Shift-click options remain. Unknown native spell data shows -- and never fabricates readiness. No automatic casts.

Installer 1.35.0 bundles Farm, Hunter and Performance. Main, Farm/Performance and the separate Hunter update channel all use the existing publisher verification identity. The old Farm/Performance companion ZIP layout remains unchanged, so older managers can still update Farm. Run the always-current EXE once to upgrade an old Windows manager to Hunter-capable 1.35.0. The complete manual ZIP and separate Farm/Hunter ZIPs are also available. Windows EXE/MSI remain Authenticode unsigned; addon-channel signatures are separate. No collector/database/schedule changes; WoW can stay open. Native rendering/timing acceptance awaits /reload.


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
