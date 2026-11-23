# Market Hours — Trading Session Dashboard

A responsive, dark-themed trading session dashboard with live clocks for New York, the United Kingdom, and India.

## Deploy
- **GitHub:** Create a repository, upload the contents of this ZIP, and commit.
- **Vercel:** Import that GitHub repository. Framework preset: **Other**. Build command: leave blank. Output directory: `.`. Then Deploy.
- You can also drag the project folder into a static hosting provider that supports direct uploads.

No build step, API key, database, or environment variables are required.

## Schedule
The event labels and IST times are based on the handwritten reference:
- 03:30 — Forex open
- 04:30 — Futures open
- 12:30 — UK killzone
- 13:30 — UK open
- 17:30 — NY pre-market
- 18:30 — NY open
- Hourly NY session markers through 00:30
- 02:30 — Forex close reference

The New York and UK times are calculated from `America/New_York` and `Europe/London` using the browser's timezone database, so daylight-saving changes are handled automatically. The highlighted row and “Happening now” panel follow the current IST time.

**Important:** Please verify the handwritten event times before relying on them for trading. This is a time-reference tool, not financial advice or a broker/exchange feed.
