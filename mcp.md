# MCP Server

Let an agent drive the open project — import, restyle, scrub, export — without clicking every pane. Works only **while the app is open**. Nothing listens until you enable it, and only on your Mac (`127.0.0.1`).

**MemoryString → MCP Server** (**⌘,**).

![Enable MCP Server, Port, Copy Client Config, access token](../.gitbook/assets/mcp-settings.png)

## Turn it on

1. Launch MemoryString.
2. Open **MCP Server**.
3. Turn on **Enable MCP Server**.
4. Click **Copy Client Config**.
5. Paste the snippet into Claude, Cursor, or a similar client as a Streamable HTTP server.

Closing MemoryString disconnects the client.

Default **Port** is **18765**. If status shows the port is already in use, pick another number.

## Token

The door key for every request. MemoryString creates a Bearer token on first launch so **Show** / **Copy** work even before you enable the server.

**Regenerate Token…** replaces the secret — existing client configs stop working until you paste the new snippet. Stored on your Mac (Application Support), not in the project file.

**MemoryString → Reset All Settings…** turns the MCP server **off**. The token file is kept.

## What the client can do

Call **get_state** first. Then mutate the open project:

- **help** — list / search / read in-app Help (does not open the Help window)
- **document** — new, open, save, save as, close, delete, undo, redo
- **library** — import / remove / reorder / sort / shuffle / select
- **groups** — Photo Stack, Carousel, Ribbon, Perspective Pair, Filmstrip, Scatter & Settle
- **transitions** — slide kinds, mix, shuffle cuts
- **style** — Looks, Energy, Photo Size, stage, customize knobs (including Anamorphic Streaks and Refract Bubbles knobs and presets), **atmosphere** (`none` / `bubbles` / `leaves`) and **decals** (`none` / `travel` / `vacation` / `party` / `florals` / `wedding` / `pets` / `sports`) as single-choice menus, and **clip_lens** (Studio per-slide Lens Effect pins; consecutive Refract Bubbles pins share one field; `remove_all` clears that slide only). Look apply and Shuffle Transitions start a fresh deal across the show; captions, COI, duration, reorder, remove, and pool checkboxes leave neighbouring slides alone (pool toggles only move slides that prefer the changed effect; untick then re-tick restores them)
- **media_edit** — rotate, flip, [center of interest](preview.md#center-of-interest) (original files are never rewritten)
- **captions** / **intro** (including Studio **lens** on the opening card) / **timing** / **audio** / **output**
- **export_movie** — write an MP4 to a path you pass (no save panel). Optional `quality` (`low` / `medium` / `high` / `maximum` → Email / Share / Screen / Master; **Share** / `medium` default), `quality_level` (0…1), `resolution` (`1080p` / `4k`; 4K needs more than ~8 GB RAM and is not available for Cinema 21:9), `fps`, `format`, `social_safe`
- **playback** — play, pause, seek, next / previous slide, **warm_now** (dirty preview segments only, non-blocking), **stop_warming**

Help and About windows are not exposed as UI; use the **help** tool to read topics.

**get_state** also reports `introLens`, per-clip `lensPins` (`null` = inherit the pool, `[]` = none), and smooth-play warm readiness: `canWarmNow`, `isWarming`, `warmStatus` (transport pill text, e.g. `Warming 3/12`), and `autoWarmOnPlay` (Studio preference; Essential always warms on Play). Poll `get_state` after **warm_now** until `isWarming` is false and `canWarmNow` is false. **warm_now** is a no-op when every segment is already warm or a warm is already running (`reason`: `already_warm` / `already_warming`).

**Match Look Soundtrack** is on by default (same as the app). After the first photos land it soft-seeds mood music; a Look click retargets that bed while it is still untouched. `audio.import` replaces that auto bed, same as a Finder drop. Soundtrack edits (**import** / **remove** / **reorder** / **mute** / **volume** / music trim) error while `isLoadingMusic` is true — poll **get_state** and retry. Turn **match_look** off *before* importing photos or applying a Look if you want silence or only your files.

Destructive **delete** requires `confirm: true`. Untitled work is not thrown away unless you save first or pass `discard_unsaved` — the agent has to mean it.
