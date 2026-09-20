# JTS tools

Single-file HTML apps. No build step. Drag any folder onto Netlify (or open the file directly) and it runs.

| App | File | Notes |
| --- | --- | --- |
| Sales Scoreboard | `index.html.html` | Team sales scoreboard |
| Load Board | `load-board/index.html` | Load board · load builder · load tender sheet · shippers & receivers directory. Persists to `localStorage`; the Refresh button and the `storage` event pick up changes from other tabs. |

## Load Board — customizing

Company name, phone and email live in the `COMPANY` block at the top of the script in `load-board/index.html`.
Demo data loads on first run; it is replaced by whatever the team saves.
