# Interconnected Places — Project Template

This is the starter repository for your spatial history project. Everything you need is already here. You will not build this from scratch — you'll swap in your own place.

## What's in here

- **`index.html`** — the map. You edit three small spots inside it (they're marked `EDIT ZONE`).
- **`data.geojson`** — the sample data. You replace this with the file you export from QGIS or geojson.io.
- **`README.md`** — this file. Rewrite it to describe your own project.

## The whole workflow

```
Research  →  QGIS / geojson.io  →  data.geojson  →  GitHub  →  index.html  →  GitHub Pages
```

You make the data, drop it in this folder, and the map reads it. That's it.

## How to make it your map

1. **Export your features** as GeoJSON from QGIS (Week 5–7) or geojson.io. Give every feature a **Name**, **Date**, and **Description** — those are the three columns the popups read.
2. **Rename your export to `data.geojson`** and put it in this folder, replacing the sample.
3. **Open `index.html`** in a text editor (VS Code is free). Change the title in `EDIT ZONE 1` and `EDIT ZONE 2`, and set your map's opening location in `EDIT ZONE 3`.
4. **Preview it.** See the note below — don't just double-click the file.
5. **Push to GitHub and turn on Pages** (Week 8 and Week 12) to get a live public link.

## ⚠️ One thing that trips everyone up

If you **double-click `index.html`** to open it, the map will load but your data probably won't — you'll see a yellow warning box. That's normal and it's not your fault. Browsers block data files from loading off a bare `file://` address.

Two fixes, either works:
- **Install the "Live Server" extension in VS Code**, right-click `index.html`, choose "Open with Live Server." (Best for previewing while you work.)
- **Push to GitHub Pages.** On a real web address, the data loads automatically with no extra steps.

## The data columns (keep these exact)

| Column | What goes in it | Example |
|---|---|---|
| `Name` | What the feature is called | `Fort Pitt` |
| `Date` | When it existed (plain text is fine) | `1761` or `19th century` |
| `Description` | 1–3 sentences of history | `British fort built after...` |

Same three columns for points, lines, and polygons.
