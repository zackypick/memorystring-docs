# MCP Server

Let an agent drive the open project — import, restyle, scrub, export — without clicking every pane. Works only **while the app is open**. Nothing listens until you enable it, and only on your Mac (`127.0.0.1`).

**MemoryString → Settings…** (**⌘,**).

![Enable MCP Server, Port, Copy Client Config, access token](../.gitbook/assets/mcp-settings.png)

## Turn it on

1. Launch MemoryString.
2. Open **Settings…**.
3. Turn on **Enable MCP Server**.
4. Click **Copy Client Config**.
5. Paste the snippet into Claude, Cursor, or a similar client as a Streamable HTTP server.

Closing MemoryString disconnects the client.

Default **Port** is **18765**. If status shows the port is already in use, pick another number.

## Token

The door key for every request. MemoryString creates a Bearer token on first launch so **Show** / **Copy** work even before you enable the server.

**Regenerate Token** replaces the secret (asks first) — existing client configs stop working until you paste the new snippet. Stored on your Mac (Application Support), not in the project file.

**MemoryString → Reset All Settings…** turns the MCP server **off**. The token file is kept.

## What the client can do

Call **get_state** first. Then mutate the open project:

- **help** — list / search / read in-app Help (does not open the Help window)
- **document** — new, open, save, save as, close, delete, undo, redo. Untitled dirty work needs `save_first` (with a `path`) or `discard_unsaved`
- **library** — import / remove / reorder / sort / shuffle / select / **keep_best** (`confirm: true` required — same as Library **⋯** → **Keep Best Shots…**; extras move to Outtakes; videos are never Keep Best targets; one undo via **document** `undo`) / **move_to_outtakes** / **move_to_takes** (same as the context menu; all given paths or the current selection). Same ingest as **Add / +**, Finder drop (files or a folder), Photos.app drag, and paste. After a UI import, MemoryString may also prompt Keep Best when similar photo groups appear (after fog).
- **photos** — `list_albums`, `import_album` (title match), or `import_recent` (`Last 7 Days` / `Last 30 Days` / `Last Year`) without opening the sheet (same ingest as **File → Import from Photos…**; needs Photos access)
- **groups** — Photo Stack, Carousel, Ribbon, Perspective Pair, Filmstrip, Scatter & Settle
- **transitions** — slide kinds, mix, shuffle cuts, pin / unpin group windows
- **style** — Looks, Energy (photo stills ~7.6s Calm / ~3.4s default / 2s Intense; intro uses its own 7s / 6s / 4s curve), Photo Size, stage, customize knobs (including Anamorphic Streaks and Refract Bubbles knobs and presets), **atmosphere** (`none` / `bubbles` / `leaves`) and **decals** (`none` / `travel` / `vacation` / `party` / `florals` / `wedding` / `pets` / `sports`) as single-choice menus, and **clip_lens** (Studio per-slide Lens Effect hand picks; consecutive Refract Bubbles pins share one field; empty `effects` = deliberate **None**; `remove_all` = **Use automatic** — the slide rejoins the shared deal and an effect may reappear). Look / Shuffle re-deal automatic slides only; hand picks including None stay until cleared; pool checkboxes and How often govern automatic slides only
- **media_edit** — rotate (`cw` / `right` = Clockwise, `ccw` / `left` = Counter Clockwise), flip, [center of interest](preview.md#center-of-interest) (original files are never rewritten)
- **captions** / **intro** (including Studio **lens** on the opening card) / **timing** (includes **auto_trim** — same as context-menu **Auto Trim**: middle four seconds plus up to 1s toward a face; best-effort, not guaranteed; no confirm; not on import; **`reset_video`** matches **Reset Video Duration**; undo with **document** `undo`) / **audio** (`import` / `remove` / `reorder` / `mute` / `volume` / `match_look` / `mute_video` / **`pick_new`** / **`extend_to_fill`** / **`surprise`** — Surprise remembers the pick immediately so a second tap is not the same bed; pick_new / surprise on music you added need `confirm: true`) / **output**
- **export_movie** — `export` writes an MP4 to a path you pass (no save panel, no Finder bounce); `cancel` stops an in-flight encode. Optional `quality` (`low` / `medium` / `high` / `maximum` → Compact / Share / High / Best; **Share** / `medium` default), `quality_level` (0…1), `resolution` (`1080p` / `4k`; not available for Cinema 21:9; rarely refuses `4k` if the Mac is short of free memory — close other apps or use `1080p`), `fps`, `format`, `social_safe`, **`screensaver`** (same as the Export Movie **Screensaver** checkbox — no audio, skip intro, Stage-color loop, no end credit)
- **playback** — play, pause, seek, next / previous slide, **start** (go to start), **`set_preview_mute`** (`muted: true` / `false` — same as clicking the transport speaker immediately right of Play/Pause to mute **or unmute**; silences soundtrack + unmuted video clips in preview only; export and per-clip mute unchanged), **warm_now** (dirty preview segments only, non-blocking), **stop_warming**

Help and About windows are not exposed as UI; use the **help** tool to read topics.

**get_state** also reports `introLens`, per-clip `lensPins` (`null` = inherit the pool, `[]` = none), `isLoadingMusic`, `matchLookSoundtrack`, `untitledNeedsSave`, `playlistIsPristineAutoManaged`, **`previewAudioMuted`**, `isExporting` / `exportProgress`, and smooth-play warm readiness: `canWarmNow`, `isWarming`, `warmStatus` (transport pill text, e.g. `Warming 3/12`), and `autoWarmOnPlay` (always `true` — both modes auto-warm on Play). Poll `get_state` after **warm_now** until `isWarming` is false and `canWarmNow` is false. **warm_now** is a no-op when every segment is already warm or a warm is already running (`reason`: `already_warm` / `already_warming`).

**Match Look Soundtrack** is on by default (same as the app). After the first photos land it soft-seeds mood music from that Look’s pool; a Look click retargets that bed while it is still untouched. `audio.import` replaces that auto bed, same as a Finder drop. `audio.surprise` draws from the whole catalog (not the Look pool) and remembers the pick at tap time. `pick_new` / `surprise` on music you added need `confirm: true` (no UI alert). Soundtrack edits (**import** / **remove** / **reorder** / **mute** / **volume** / music trim / pick_new / extend_to_fill / surprise) error while `isLoadingMusic` is true — poll **get_state** and retry. Turn **match_look** off *before* importing photos or applying a Look if you want silence or only your files.

Destructive **delete** requires `confirm: true`. Untitled dirty work is not thrown away unless you pass `save_first` (with a `path`) or `discard_unsaved` — the agent has to mean it.
