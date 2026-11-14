# Warcraft Market Forever

Auction browsing, price history and trading tools for WoW Forever EU: Alliance, Horde and Blackwater. For players across classes and levels, whether browsing gear, gathering materials or managing auctions.

**[Download the complete package](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever.zip)** | [Latest release notes](https://github.com/Timcross1/warcraft-market-forever/releases/latest) | [Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose)

## Included

- Addon **2.477.0**, bundled price history, music and media.
- Windows setup wizard and optional price-update companion.
- Manual-install folder and **START HERE.txt** instructions.
- Character Shop, price-tier comparisons and 1/3/7/28-day history charts.
- Resizable layouts, saved filters and auction scanning controls.

The original download address is unchanged. GitHub Source code archives contain repository documentation; use the complete package above to install the addon.

## Windows installation

1. Download **WarcraftMarketForever.zip**, right-click it and choose **Extract All**.
2. Open **WarcraftMarket-Setup-Test.msi** from the extracted folder.
3. Open **Warcraft Market** from Start. Select the game folder containing **Wow.exe** and click **Install addon**.
4. In WoW, type `/reload`, then `/wmf`, and choose the appropriate market. **WoW can stay open; no game restart is needed.**
5. Visit an auctioneer for live offers and trading. Recorded history can be viewed away from the auction house.

**The Windows companion is an unsigned test build. Publisher signing is pending.** Windows may show an unverified-publisher warning. Do not disable Windows security. Windows 10/11 with .NET Framework 4.8 is the intended platform; clean-machine acceptance testing remains pending.

For manual installation, copy **Manual install/WarcraftMarketForever** into the game's **Interface/AddOns** folder. Ensure **WarcraftMarketForever.toc** is directly inside it, without another nested addon folder. Back up an existing addon and preserve WTF/SavedVariables. Use `/reload` afterwards.

## Optional price updates

Automatic downloads are **off by default**. The companion offers **Check prices now**, the last successful price check, and controls to enable or disable hourly updates while signed in to Windows. Downloads use public GitHub price files; no game password, account sign-in or database credentials are required. No PowerShell steps are needed for the new setup.

Bundled history remains the dated 12 November snapshot. Publishing a new installer does not refresh auction observations. Live auction scans provide current offers. The companion rejects stale or invalid downloads and preserves newer installed prices; if the publisher has not refreshed the feed, it reports this and keeps existing data. Type `/reload` after a successful update.

The separate [price-data download](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip) remains available for existing installations. It is not required for initial setup.

## Removal and privacy

**Remove addon** in the companion moves the addon into **WarcraftMarketBackups**, outside AddOns, and preserves saved settings. Removing the companion through **Windows Settings > Apps** stops its scheduled updates but keeps the addon, backups and settings. To remove both, remove the addon in the companion first.

No collector database, credentials, personal inventory, watchlists or trade receipts are bundled. Personal records remain in local SavedVariables. Purchases require an explicit player click. Media attribution and font licences are retained.

## Verification and limits

The Windows companion passed **19 automated checks**, including installation logic, upgrades, hash and freshness validation, interrupted-update rollback and preservation of saved settings. The addon previously passed **41 focused suites on Lua 5.1 and Lua 5.4**. These checks do not replace real Windows installer, scheduled-update or live auction-house testing.

AI is optional and unconfigured; no shared service or API key is supplied. Missing history remains unavailable. Gear scores are not simulated damage gains, estimated profits do not guarantee sales, and Blackwater fees still require native-receipt verification.

## Feedback

Check shopping results against the current character's class, level and usable equipment. Try search, filters, saved rules, chart periods and window sizes. Compare item, quantity, unit price and total with the native auction interface before a purchase.

When reporting a problem, include addon version, market, affected page, screen resolution/UI scale, steps to reproduce and expected versus actual behavior. Include class/level only when relevant, and item IDs or timestamps for pricing issues. Remove private chat and personal details from screenshots.

[Release history](CHANGELOG.md) | [All downloads](https://github.com/Timcross1/warcraft-market-forever/releases)
