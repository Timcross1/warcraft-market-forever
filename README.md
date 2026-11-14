# Warcraft Market Forever

Auction browsing and trading research for WoW Forever EU: Alliance, Horde and Blackwater.

**[Download addon 2.473.0](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever.zip)** | [Release notes](https://github.com/Timcross1/warcraft-market-forever/releases/tag/v2.473.0) | [Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose)

## Latest update — 14 November 2026

**Laptop resize fix:** releasing the resize handle now keeps your chosen size. Width and height are saved for reopening/reload. New installs default to nearly the full screen width, while fitting the available height. Tooltips use available side space or overlay inside the edge without shrinking the window.

- Character Shop replaces Character Outfitter, with corrected low-level gear recommendations and audited controls.
- Green price tiers, seven-day price comparisons, 1/3/7/28-day charts and one Buyout action.
- Applied price-gap rules persist; disabled fields are greyed out.
- Vendor scans retain result order and avoid repeated full sorting; Smelting rescans on opening.
- Improved scan controls, header alignment, compact restocking and purchase feedback.
- Original melody retained with orchestral strings.

## One complete download

WarcraftMarketForever.zip includes the addon, bundled price history, music and Windows price-update tools. Extract the ZIP and read **START-HERE.txt**. No separate price pack download is needed for setup.

## Install on another laptop

1. Download **WarcraftMarketForever.zip**. GitHub Source code archives contain documentation, not the addon.
2. Close WoW. Extract WarcraftMarketForever into `World of Warcraft/_forever_/Interface/AddOns/`.
3. Check WarcraftMarketForever.toc is directly inside that folder, without a second nested folder.
4. Start WoW, enable the addon and type `/wmf`. Check version **2.473.0** and choose your market.
5. Open an auctioneer for live offers and trading. Cached history can be viewed away from the auction house.

Back up any existing addon. Keep WTF and SavedVariables. Personal preferences, watchlists and trade records are not bundled: transfer your own SavedVariables separately with WoW closed on both machines if you want matching settings. Back up the destination first.

## Prices

For automatic downloads, run **PriceUpdates/EnableHourlyDBSync.cmd** from the extracted complete package after installing the addon, then choose your WoW Forever folder. This registers a Windows task for your account: immediately, at sign-in and hourly. Keep PriceUpdates outside AddOns. In WoW, use Options > Blizzard DB sync > Sync to load downloaded prices (UI reload). The manual updater is also included in PriceUpdates.

The separate data-only pack below is optional for existing installations:

[Download the data-only update](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip), extract outside AddOns and run UpdatePriceHistory.cmd. Select the WoW Forever folder, then `/reload`. The updater checks hashes, refuses older observations and backs up replaced data.

This release retains the verified 12 November snapshot: 18,699 records across three markets. Code publication does not refresh observation times. Optional SyncPriceHistory and EnableHourlyDBSync helpers download published packs; they do not run a collector or make upstream data fresh. Live AH scans provide current offers. Reapply a newer price pack after replacing addon files if needed.

## Laptop test checklist

- On the level-14 priest, open Character Shop > Weapons, compare Show: Recommended with Show: Usable, and check search, category/rarity filters, sorting and selection.
- Apply custom Price gap rules; close/reopen, then reload and confirm they remain. Check green tiers, chart periods and column readability.
- Run Vendor profit and watch whether discovered deals stay visible. Reopen Smelting and check it scans.
- Try smaller window sizes and your normal UI scale; report clipped text and cold versus repeat load times.
- Listen to the original melody with strings; check phrasing and loop transitions.
- Compare item, unit price, quantity and total with the native AH. If trading, check the receipt and ledger using a small amount of your own gold. Every transaction requires your click.

## Validation and known limits

The latest local review passed 13 targeted suites on both Lua 5.1 and 5.4. This publication passed 13 packaging/updater tests, ZIP/TOC checks, compilation of every packaged Lua file on both runtimes, and the latest music hash check. These are offline checks; native visuals, audio and live auction behaviour still need laptop testing.

Disenchant Beep/Continuous still share Sniper handlers; independent settings need further work. AI is optional and unconfigured; no shared service or API key is supplied. No personal-use BiS or regional sales dataset is distributed. Missing long history remains unavailable. Scores are not simulated damage gains; estimated profits are not guaranteed sales. Blackwater fees remain unverified against native receipts.

No collector database, credentials, personal inventory, watchlist or trade receipts are included. Personal records remain in local SavedVariables. No automatic purchases or telemetry are configured. Media attribution and font licences are retained in the ZIP.

## Feedback

Use Issues with version, market, class/level, screen resolution/UI scale, affected tab, exact steps and expected versus actual result. Include timestamps and item/variant IDs for price issues. Remove private chat from screenshots.

[Earlier release history](CHANGELOG.md) | [All releases](https://github.com/Timcross1/warcraft-market-forever/releases)
