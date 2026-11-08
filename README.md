# Par 5

A golf spin-and-pick game. Spin a year, tournament and round from every PGA Tour stroke-play event since 2001, pick one player's round, and try to build a perfect 5-round card.

## Files
- `index.html` - the game
- `data/` - round-by-round data for each season (2001-2026), plus `index.json`

Keep `index.html` and the `data` folder together, in the same place.

## Run it
The game loads its data from the `data` folder. Because of that, double-clicking `index.html` on your computer won't work. It needs to be served from a web server, like GitHub Pages (see below).

## Put it on GitHub Pages
1. Create a new public repository on github.com (for example `par5`).
2. Click **Add file > Upload files**, drag in `index.html`, `README.md` and the whole `data` folder, then click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two, the game is live at `https://<your-username>.github.io/par5/`.

## Data
Scores, finishes and prize money come from ESPN's public PGA Tour leaderboards. Match play, team and Stableford events are excluded.
