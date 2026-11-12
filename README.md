# Warcraft Market Forever — beta

Auction browsing, saved price history and trading research for **WoW Forever EU**: Alliance, Horde and Blackwater.

**[Download addon](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Beta.zip)** | **[Update prices](https://github.com/Timcross1/warcraft-market-forever/releases/latest/download/WarcraftMarketForever-Prices.zip)** | [Report a problem](https://github.com/Timcross1/warcraft-market-forever/issues/new/choose)

## Current release

**[2.153.0 beta](https://github.com/Timcross1/warcraft-market-forever/releases/tag/v2.153.0-beta.1)** adds a cleaner character shopping layout, small illustrated upgrade arrows, more responsive resizing, improved disenchant scan recovery and clearer buying/posting controls.

[What's changed and release history](CHANGELOG.md) | [All releases](https://github.com/Timcross1/warcraft-market-forever/releases)

## Install

1. Download **WarcraftMarketForever-Beta.zip** from Releases. The automatic Source code ZIP contains documentation, not the addon.
2. Exit WoW. Extract the WarcraftMarketForever folder into `World of Warcraft/_forever_/Interface/AddOns/`.
3. Check that WarcraftMarketForever.toc is immediately inside that folder, without a second nested addon folder.
4. Start WoW, enable the addon and type `/wmf`. Choose your market.
5. Open an auctioneer for live offers and trading. Away from the AH you can view cached prices and trends.

Back up an existing addon before replacing it. Keep WTF and SavedVariables. A code update includes bundled history; reinstall the latest price pack afterwards if your local history was newer.

## Update prices

Download **WarcraftMarketForever-Prices.zip**, extract outside AddOns, run UpdatePriceHistory.cmd and choose your WoW Forever folder. Then type `/reload`. Options > Update price history provides the same instructions. The updater checks hashes, refuses older observations and backs up replaced data.

Updates are manually published during beta. There is no automatic 30-minute publishing service. Observation time, download time and Blizzard publication time are different. Cached prices are not executable live offers.

## First test

- Open away from an auctioneer; inspect cached history and its age.
- Browse without a name, filter Rare, change categories, search Linen Cloth, change pages and select items. Check graph title, item name, unit price and quantity.
- Compare one price against Blizzard's AH and record the time; offers may change between requests.
- Start/stop scans and switch tabs during a scan. Report freezes and cold versus repeated load times.
- Hover several rows and scroll quickly. Default hover uses a lightweight card; hold Shift before hovering for full Blizzard details and other addons' tooltip additions.
- Test your usual screen resolution and UI scale for clipping.
- Add/remove a watch alert, check gear against equipped items and capture a bank snapshot. Each character needs its own capture; missing data means unknown.
- If you choose to trade, use a tiny amount of your own gold. Check item, quantity, unit/total price, receipt, posting state and ledger. Each transaction requires your click. A listing is not a completed profitable sale.
- Reinstall the price pack and verify preferences/watch alerts survive.

## Known limits

**AI is optional and unconfigured in this beta.** No API key or hosted AI endpoint is supplied. Ask AI needs a separately configured local helper. The owner's 30p/day allowance is not a shared multi-user budget.

No third-party personal-use BiS dataset or regional sales dataset is included. Missing guides, sales estimates or long history stay unavailable. Gear scores are not simulated percentage DPS gains. Suffix variants may lack comparable evidence. Low supply does not prove demand. Disenchant yields are estimates. Conservative profit is not a sale probability; Blackwater commission remains unverified against native receipts.

Character data and trading records remain in local SavedVariables. No automatic purchases or telemetry are configured. Collector databases, backend credentials and personal data are not distributed. Font licences and media attribution remain in the addon ZIP.

## Feedback

Use Issues. Include version, market, class/spec/level, screen resolution/UI scale, affected tab, steps, expected versus actual results and any error. For slowness include cold/repeat timing and performance panel values. For prices include item ID/variant, unit versus stack price, quantity and timestamp. Crop private chat/names from screenshots.
