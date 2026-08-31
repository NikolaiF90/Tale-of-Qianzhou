# Patch: Locations Update

**What changed:** All Location coordinates (`x`/`y`) across every circuit have been adjusted to better match the realm map image and established lore (river source placement, Guyu Island positioning, and related fixes). Also included: an updated image for **Tiexue Camp**.

**Why you need to do this manually:** Changes like these do not automatically sync into saves that are already in progress. If you started your playthrough before this patch, your save is still running the old data until you apply this update yourself.

**Do you need to do this?** If you haven't started playing yet, or you're starting a brand-new save, **you don't need to do anything** — new saves already pull the current world data. This is only for saves already in progress.

---

## How to apply this update

1. In-game, open **Settings → Creator Tools**
2. Scroll to the very bottom until you see **Advanced / State Editor**
3. Open the **Section** dropdown and select **`locations`**
4. Select all the text currently in the edit box and delete it
5. Paste in the full contents of `locations_section.json` (attached with this patch) — copy the *entire* file, not just the changed parts
6. Tap **Save Section**
7. Tap **Submit All Changes**

That's it — your save's location data now matches the current world.

## Notes

- This replaces the *entire* `locations` section — paste the whole file. There's no need to find or edit individual coordinates yourself; the file already contains everything, changed and unchanged, exactly as it should look.
- Your own play history, visited areas, and discovered state for each Location are not affected by this — only the authored Location data itself (coordinates, image, and related fields) is refreshed to current.
- If something looks wrong after applying it (a Location missing, an error on Save), don't proceed to Submit All Changes — instead reach out via [Issues](../../issues) with a screenshot of the error before making further changes.

