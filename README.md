# Roberto Board

A kanban-style task tracker for all our projects. Roberto maintains this as he works.

## Purpose

Track tasks across all projects with:
- Status flow: Backlog → Todo → In Progress → Done
- Token usage per task
- Time spent per task

## How It Works

- `data.json` — the source of truth (Roberto updates this)
- `index.html` — the UI (open in browser or serve locally)

## Running

```bash
cd projects/roberto-board
npx serve .
# or
python -m http.server 8080
```

Then open http://localhost:8080 (or the port shown).
