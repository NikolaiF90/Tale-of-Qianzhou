# v1.0.1 — Locations Update

**Date:** 2026-08-31

## What changed
- Adjusted `x`/`y` coordinates for all 36 Locations to better align with the realm map image and established lore (river source at Fujin, Guyu Island's position relative to Muyu/Linzhao, and related fixes).
- Updated image for **Tiexue Camp**.

## Do you need to do this?
- **Haven't started playing, or starting a brand-new save?** No action needed — new saves already use the current world data.
- **Already playing?** This kind of change does not sync automatically to a save in progress. Follow the steps below to update it manually.

---

## How to apply this update

1. In-game, open **Settings → Creator Tools**
2. Scroll to the very bottom until you see **Advanced / State Editor**
3. Open the **Section** dropdown and select **`locations`**
4. Select all the text currently in the edit box and delete it
5. Paste in the full contents of [`locations_section.json`](locations_section.json) — copy the *entire* file, not just the changed parts
6. Tap **Save Section**
7. Tap **Submit All Changes**

That's it — your save's location data now matches the current world.

## Notes

- This replaces the *entire* `locations` section — paste the whole file. There's no need to find or edit individual coordinates yourself; the file already contains everything, changed and unchanged, exactly as it should look.
- Your own play history, visited areas, and discovered state for each Location are not affected by this — only the authored Location data itself (coordinates, image, and related fields) is refreshed to current.
- If something looks wrong after applying it (a Location missing, an error on Save), don't proceed to Submit All Changes — instead reach out via [Issues](../../../issues) with a screenshot of the error before making further changes.

**[← Back to update index](../)**
