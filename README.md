# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater.

<!-- WMF_CURRENT_RELEASE -->
## Current downloads: addon 2.594.0, installer 1.19.0

- [Windows installer 1.19.0 — bundled addon 2.594.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarket-Setup.msi)
- [Manual addon 2.594.0 ZIP](https://github.com/Timcross1/warcraft-market-forever/releases/download/v2.594.0/WarcraftMarketForever-2.594.0.zip)
- [Current price pack](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)
- [Versions and channel status](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/ReleaseInfo.json)

Run the matching installer upgrade, open Warcraft Market, choose the game folder and click Install/Reinstall addon, then `/reload` in WoW. The companion does not update its own Windows EXE through Update addon now. Preserve WTF/SavedVariables and newer generated prices. WoW can stay open.

Signed automatic addon updates deliver **2.594.0**.

The Windows MSI/EXE is Authenticode unsigned. If security software blocks it, use the manual ZIP; do not disable protection. Addon signatures are separate from Windows signing.
<!-- /WMF_CURRENT_RELEASE -->

## New in 2.594.0

Includes a soft golden graph flow that follows the trend, configurable Full / Reduced / Off animations, scan shimmer, new-result highlights, fresh watch-eye pulses, confirmed purchase/post feedback, button fades and price-change cues. Choose Options > Colour theme > Time of day for optional dark dawn/day/dusk/night surfaces following the game clock. Layout, saved lists and financial colour meanings are preserved.

## Market research features

Market price now uses outlier-filtered real asking history, retains dated fallback values and grows to a rolling 14-day reference. Graph cards include an Auctions tab showing checked pricing tiers. Browse and Item lookup offer an experimental Price / supply column preset; it is descriptive, not a validated forecast. Saved watch lists and manual targets are preserved.

## Included

Auction browsing, Character Shop, price and quantity history, saved searches, Sniper, crafting and conversion research, watchlists, posting and auction management. Media attribution and font licences remain in the distribution. GitHub Source code archives contain distribution documentation; install the actual ZIP/MSI above.

## Installation and updates

Download WarcraftMarket-Setup.msi directly for Windows setup. For a manual installation, extract the WarcraftMarketForever folder from the versioned ZIP into Interface/AddOns. WarcraftMarketForever.toc must sit directly inside the addon folder. Preserve WTF/SavedVariables and newer generated price files. Then use /reload and /wmf.

Automatic downloads default on for new companion installations and can be disabled. The companion checks at sign-in and hourly while signed in. Download prices now retries price checks; Update addon now uses only publisher-signed code. Upgrading the Windows companion itself requires the current MSI.

Prices update independently; publishing code does not refresh auction observations. Data retains genuine source dates. Stale/invalid packs are rejected and newer installed observations are preserved. No game password or database credentials are required.

## Removal, privacy and limits

Remove addon moves the folder into WarcraftMarketBackups outside AddOns and keeps WTF settings. Windows Settings > Apps removes the companion and its update task while keeping addon data/backups. Personal inventory, watchlists and receipts remain local. No collector database or private signing key is distributed.

Purchases require a player click and fresh native checks. Recorded asks and estimated profit do not guarantee sales. Synthetic validation does not replace native-client acceptance. The installer targets Windows 10/11 with .NET Framework 4.8.

## Feedback

[Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose) with addon/installer version, market, page, resolution/UI scale, reproduction steps and expected/actual behavior. Remove private information from screenshots.

[Release history](https://github.com/Timcross1/warcraft-market-forever/releases) | [Latest release notes](https://github.com/Timcross1/warcraft-market-forever/releases/latest)

Installer 1.19.0 fixes the addon download-size limit. Existing companion users should reinstall the latest MSI; addon code and market prices continue to update separately.

## Code, prices and media updates

Companion 1.19.0 checks signed component hashes and downloads only changed code or media. All artwork/audio retains its original bytes and quality. Prices are published and downloaded separately. Install the current MSI once to enable components; older companions still use the signed full addon ZIP. Full manual installs include one bundled price snapshot and preserve WTF/SavedVariables. The retired PriceUpdates shell helper is replaced by the companion’s Download prices now action.
