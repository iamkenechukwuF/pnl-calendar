# PnL Calendar

A simple, visual trading journal that shows your daily profit and loss at a glance, like a GitHub contribution graph but for your trading performance.

Single HTML file. No frameworks, no build step, no account, no server. Your data stays in your own browser.

## Features

**Calendar**
- Color-coded days: green for winning days, red for losing days, with intensity based on size
- Tap any day to log a result (+ / -), add an optional note (setup, pair, mistake, lesson), edit, or delete it
- Monthly summary: total PnL, win rate, average win, average loss
- Current win/loss streak indicator
- Month navigation, with today highlighted

**Analytics dashboard**
- Equity curve
- Trades logged, win rate, profit factor, and expectancy per day
- Best and worst day, longest winning and losing streaks
- Average result by day of the week
- Monthly totals for the last 6 months

**Other**
- 12 currency symbols, including USD, EUR, GBP, and NGN (display only, values are not converted)
- Export and import backups as a JSON file
- Mobile-first layout with a dark theme

## Try It

Open `index.html` in any modern browser. On a Mac:

```bash
git clone https://github.com/iamkenechukwuF/pnl-calendar.git
cd pnl-calendar
open index.html
```

To use it on your phone, turn on GitHub Pages (Settings, then Pages, deploy from the `main` branch) and open the link it gives you. You can add it to your home screen from the browser's share menu.

## Your Data and Backups

Entries are saved in your browser's `localStorage`. That means:

- Data is private and never leaves your device
- Data is tied to one browser on one device
- Clearing site data or browser history can erase it

Use the menu (☰) and choose **Export backup** to download a JSON file, and **Import backup** to restore it or move to another device. Importing merges with what you already have, and matching days are overwritten. Export regularly.

## Tech

- HTML, CSS, and vanilla JavaScript
- `localStorage` for persistence
- Inline SVG for the equity curve

## Roadmap

- Per-trade entries instead of one result per day
- CSV export
- Tags for setups and pairs
- Weekly and yearly views
- Installable app (PWA) with offline support

## Disclaimer

This is a personal journaling tool, not financial advice.

## Author

[@iamkenechukwuF](https://github.com/iamkenechukwuF)
