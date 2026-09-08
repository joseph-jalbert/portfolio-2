# Company logos

Drop a logo file per role/project in here and it'll pick up automatically —
each entry's `<img class="role-mark-logo">` `src` in [index.html](../index.html)
already points at one of these filenames:

Jobs:
- `people-inc-logo.png` — People.inc
- `onestudyteam-logo.png` — OneStudyTeam
- `x-team-logo.png` — X-Team
- `adweek-logo.png` — Adweek
- `morgan-morgan-logo.png` — Morgan & Morgan
- `moxie-media-group-logo.png` — Moxie Media Group

Side Projects:
- `side-project-1-logo.png` — ColorTabs
- `tech-for-campaigns-logo.png` — Tech for Campaigns

Rename the `src` values in index.html if you'd rather use different filenames.

Tips:
- Square images work best, roughly 200×200px.
- PNG or SVG with a transparent background looks cleanest against the tile's
  background color.
- If a file is missing or fails to load, the tile automatically falls back to
  the colored initials placeholder — nothing else needs to change.
