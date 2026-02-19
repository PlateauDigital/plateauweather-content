# Plateau Weather Content

Weather updates for the Sammamish Plateau area. See [PlateauWeather.com](https://plateauweather.com).

## Creating Posts

Use the `new-post` script to create a new post with front-matter pre-filled:

```bash
# New post with current timestamp
./new-post

# Backfill a post (defaults to 8pm)
./new-post 2026-02-17

# Backfill with specific time
./new-post "2026-02-17 19:30:00"
```

Posts are created in `posts/` as `YYYY-MM-DD.md`. If a post for that date already exists, it appends the time: `YYYY-MM-DD-HHMM.md`.
