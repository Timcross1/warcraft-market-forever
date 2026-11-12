# Release history

This records public downloads and the main changes between them. Development build numbers are grouped below; they were not all separate GitHub releases.

## 2.153.0 beta — 12 November 2026

Published as `v2.153.0-beta.1`. Includes the changes since the previous public release, plus the latest character layout.

### Character shopping
- Filters sit on the left, with buying and confirmed purchase details across the top.
- Rows stay inside the window when the sidebar changes the table width.
- More space below the heading; Reset and Price details removed from this page.
- Illustrated button icons and quieter green, blue and orange upgrade arrows.
- Improvement labels are New slot, Improvement and Major upgrade. Exact score changes remain on hover; a score is not a percentage damage gain.
- Guide and usability information remain separate from auction availability.

### Scanning and responsiveness
- Window resizing batches repeated redraws and finishes with one final cached paint.
- Disenchant scans retain results after interruptions and retry stalled discovery within bounded limits.
- Scanning Auction House shows progress and clearly labels incomplete coverage.
- One scan control per page where a scanner bar already provides Start/Stop.
- Purple/green magical scanner styling, with more consistent heading and filter spacing.

### Tables, buying and posting
- Equal-height price and stock charts in Item lookup.
- Narrower Material, Bandage and Bar name columns leave room for other values.
- Materials can be filtered by Group; selectors support All/None.
- Confirmed purchases show the actual item, quantity and paid price in a compact receipt.
- Posting has a prominent scan action and clearly grouped auction settings.
- Posting comparisons and selected-row layout were improved.
- My auctions places cancellation with the other controls and removes its name search.

### Market research
- Category summaries explain price and supply changes in plainer language.
- Market niches has more space around its controls.
- Optional niche AI can review a bounded shortlist through a separately configured local helper. The public download includes no shared AI service or key.

### Development milestones included
- 2.153: character layout, bounded rows and quieter illustrated upgrade indicators.
- 2.152: responsive window resizing.
- 2.149–2.151: heading gaps, equal charts and duplicate scan removal.
- 2.144–2.148: disenchant recovery, one scanner, narrower conversion columns and material groups.
- 2.132–2.143: scanning coverage and progress, purchase receipts, posting/character workspaces, clearer market summaries and optional niche AI.
- Earlier internal builds since the first public beta also improved filtering, buying safeguards, saved price evidence and page performance.

### Validation
139 Lua suites passed under Lua 5.1 and Lua 5.4: 278 successful executions. Distribution checks verify TOC dependencies, asset integrity, clean optional feeds, checksums and matching bundled/data-only history. Native visual and performance acceptance remains incomplete.

## Previous public release: v2.58.0-beta.1 — 12 November 2026

[Original release](https://github.com/Timcross1/warcraft-market-forever/releases/tag/v2.58.0-beta.1).

The original release notes covered lightweight hover cards, skipping intermediate cards during rapid scrolling, Shift for full native tooltips, and reserved tooltip space. The original notes reported 202 Lua executions and 10 packaging/updater checks.

Addon and price assets were subsequently refreshed under that existing tag without a corresponding versioned release entry. Those updates do not represent separate historical releases. From 2.153.0 onward, a new versioned release preserves the previous download and notes.
