# Paddock Wire

A fan-made F1 media portal built from your **F1 Manager 2024** career save. Load your `.sav` file and get news articles, a fake X/Twitter feed, results, stats, academies and the next-season grid, all wrapped around your own season.

**Live version:** https://kejkub.github.io/paddock-wire/

> Status: work in progress. Feedback and ideas are very welcome (open an issue).

## What it does

- **Paddock News**: front page and article list with categories such as race reports, qualifying, car analysis, title fight, transfers, rumours, throwbacks, fun facts, academy profiles and F2/F3 coverage.
- **Paddock X**: a Twitter-style feed with official team and series accounts, journalists and fans. It has threads, polls and replies, and you can post your own and get reactions.
- **Results**: every round of F1, F2 and F3, race and sprint, with driver and team standings.
- **Stats Corner**: driver and team tables, cumulative points chart, results map, head-to-head between team-mates, car strength versus expectations and engine suppliers.
- **Team, Academy and Grid**: rosters with reserves and juniors, academy history season by season, and the next-season grid based on contracts.
- **Customisation**: your own team names, logos, car images and colour palettes, plus settings export and import.
- **Languages**: Polish and English interface.

## How to use it

1. Open the live version in your browser.
2. Load your F1 Manager 2024 `.sav` file.
3. (Optional) Open **Settings** and connect an AI provider with your own API key to generate full articles and posts.
4. Browse the portal. After new races, load an updated save and use **Update data**.

### No-AI mode

If you don't want to use an API key, switch on **No-AI mode** in Settings. In this mode the portal builds article headlines from templates only. There is no full article text and no journalist or fan posts, while official-account posts are assembled as usual.

## Privacy

Paddock Wire is a single static HTML file with no backend. Your save data and settings are stored only in your browser's localStorage. If you use an AI provider, your API key stays in your browser and is sent only to the provider you chose.

## Technical notes

- One `index.html` file, vanilla JavaScript, no build step, no install.
- Works in current desktop browsers.
- Because data is stored per web address, data saved in a local copy of the file will not appear on the hosted version. Use settings export and import to move it.

## Disclaimer

This is an unofficial, non-commercial fan project. It is not affiliated with, endorsed by or connected to Formula 1, the FIA, any F1, F2 or F3 team, or the developers or publishers of F1 Manager 2024. All names, logos and trademarks belong to their respective owners.

## License

All rights reserved unless stated otherwise.
