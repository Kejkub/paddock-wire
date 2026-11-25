# Paddock Wire

A fan-made F1 media portal built from your **F1 Manager 2024** career save. Load your `.sav` file and get news articles, a fake X/Twitter feed, results, stats, academies and the next-season grid, all wrapped around your own season.

**Live version:** https://kejkub.github.io/paddock-wire/

> **Version 0.5.1 (early access).** This is an early version and may contain bugs. Bug reports and ideas are very welcome: [open an issue](https://github.com/Kejkub/paddock-wire/issues) or write to the author on Discord.

## What it does

- **Paddock News**: front page and article list with categories such as race reports, qualifying, car analysis, title fight, transfers, rumours, throwbacks, fun facts, academy profiles and F2/F3 coverage.
- **Paddock X**: a Twitter-style feed with official team and series accounts, journalists and fans. It has threads, polls and replies, and you can post your own and get reactions. New in 0.5.0: the **Paddock Radio** account posts 1 to 3 team radio dialogues (driver and race engineer) after every Grand Prix, team accounts post **anniversaries** of milestones from their history, and the F1 account summarises the grid for next season after the transfer posts. Driver names in posts open their stats.
- **Results**: every round of F1, F2 and F3, race and sprint, with driver and team standings.
- **Stats Corner**: driver and team tables, cumulative points chart (points or championship position, with a tooltip for every round), results map, head-to-head between team-mates, car strength versus expectations and engine suppliers.
- **Team, Academy and Grid**: rosters with reserves and juniors, academy history season by season, and the next-season grid based on contracts. A team profile always shows the full line-up for next season. The driver comparison has a new picker with search.
- **Customisation**: your own team names, logos, car images and colour palettes, plus settings export and import. New in 0.5.1: a **Logo instead of the car** option that shows team logos instead of cars (handy when replaying older seasons), and six new colour themes (Midnight blue, Forest, Sunset, Violet night, Mono blue, Cream).
- **Languages**: English (default) and Polish interface.
- **Help built in**: a Wiki describing every tab and option, a Changelog with the history of changes, and a short "What's new" window on the first visit after an update.

## How to use it

1. Open the live version in your browser.
2. Load your F1 Manager 2024 `.sav` file.
3. (Optional) Open **Settings** and connect an AI provider with your own API key to generate full articles and posts.
4. Browse the portal. After new races, load an updated save and use **Update data**.

### No-AI mode

If you don't want to use an API key, switch on **No-AI mode** in Settings. In this mode the portal builds article headlines from templates only. There is no full article text and no journalist or fan posts, while official-account posts (including Paddock Radio and anniversaries) are assembled as usual.

## Privacy

Paddock Wire is a single static HTML file with no backend. Your save data and settings are stored only in your browser's localStorage. If you use an AI provider, your API key stays in your browser and is sent only to the provider you chose.

The hosted version counts anonymous page visits with [GoatCounter](https://www.goatcounter.com/), which uses no cookies and collects no personal data. It does not see your save file or what you do in the program.

## Technical notes

- One `index.html` file, vanilla JavaScript, no build step, no install.
- Works in current desktop browsers.
- Because data is stored per web address, data saved in a local copy of the file will not appear on the hosted version. Use settings export and import to move it.

## Feedback and contact

- Bugs and suggestions: [GitHub Issues](https://github.com/Kejkub/paddock-wire/issues). Please include the logs from **Settings → Diagnostics** and never paste your API key.
- Questions and contact with the author: [Discord](https://discord.com/users/414150520899502082).

## Support

Paddock Wire is free. If you like it, you can support its development with a voluntary donation on [Ko-fi](https://ko-fi.com/kakub). A donation gives no extra features or access.

## Disclaimer

This is an unofficial, non-commercial fan project. It is not affiliated with, endorsed by or connected to Formula 1, the FIA, any F1, F2 or F3 team, or the developers or publishers of F1 Manager 2024. All names, logos and trademarks belong to their respective owners.

## License

All rights reserved unless stated otherwise.
