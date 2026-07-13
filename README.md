# Clubhouse — Score Tracker

A mobile-friendly golf / pitch & putt scorecard app. Add courses (hole-by-hole par and optional distance), add golfers, play a round with up to 4 golfers on one scorecard, and review stats and hole-by-hole difficulty rankings.

All data is stored locally in your phone/browser's storage (`localStorage`) — nothing is sent to a server, so it works fully offline once loaded. Data is per-browser, so if you clear your browser data or switch phones/browsers you'll need to re-enter your courses and golfers.

## Deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `golf-tracker`).
2. Upload `index.html` to the root of the repo.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. GitHub will give you a URL like `https://<your-username>.github.io/golf-tracker/`. Open it on your phone and add it to your home screen for quick access on the course.

## Using it

- **Courses tab** — add a course, pick 9 or 18 holes, then set par (required) and distance in metres (optional) for every hole. Pitch & putt holes default to par 3.
- **Golfers tab** — add the names of everyone who plays.
- **Round tab** — pick a date, course, and up to 4 golfers (they become A/B/C/D in the order you tap them). Tap "Build Scorecard" to get a single-page card with a column per golfer, front/back subtotals and a running total. Tap "Save Round" when you're done (or partway through, if you want).
- **Stats tab** — pick a golfer to see rounds played, best round per course, and a hole-by-hole average with a difficulty rank (1 = hardest, highest average over par; highest number = easiest) for each course they've played.
- **History tab** — every saved round, sorted by date, with a full scorecard on tap and the option to delete it.
