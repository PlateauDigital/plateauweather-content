# Plateau Weather Content

Weather updates for the Sammamish Plateau area. See [PlateauWeather.com](https://plateauweather.com).

## Creating Posts

### From a laptop

Use the `new-post` script to create a new post with front-matter pre-filled:

```bash
# New post with current timestamp
./new-post

# Backfill a post (defaults to 8pm)
./new-post 2026-02-17

# Backfill with specific time
./new-post "2026-02-17 19:30:00"
```

### From a phone or browser

Use the **New Post** workflow under **Actions**:

1. Go to **Actions → New Post → Run workflow**
2. Paste your post content into the **Post content** field
3. Optionally fill in **Date override** (e.g. `2026-02-17` or `2026-02-17 19:30:00`) — leave blank to use the current Pacific time
4. Click **Run workflow**

The workflow commits and pushes the new post automatically.

---

Posts are created in `posts/` as `YYYY-MM-DD.md`. If a post for that date already exists, it appends the time: `YYYY-MM-DD-HHMM.md`.
