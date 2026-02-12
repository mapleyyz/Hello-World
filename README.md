# FitTrack

A minimal daily fitness tracker for logging weight and push-ups. Runs entirely in the browser with no dependencies.

## Features

- **Daily logging** — Record weight (lbs) and push-up count for any date
- **Stats dashboard** — Current weight, today's push-ups, day streak, total push-ups
- **Weight trend chart** — Line chart of your last 30 entries
- **Push-up bar chart** — Bar chart of your last 14 sessions
- **Streak tracking** — Consecutive days with entries (survives if you haven't logged today yet)
- **History table** — All entries with weight change indicators and inline delete
- **Persistent** — Data saved to localStorage
- **Responsive** — Works on desktop, tablet, and mobile

## Usage

Open `index.html` in any browser. No build step or server required.

## Data

All data is stored in your browser's localStorage under the key `fittrack_data`. Use the "Clear All" button to reset.
