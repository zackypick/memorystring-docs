# Preview

The large stage is where you watch the movie. Import lives in the Library; order and trim also use the Timeline.

![Preview transport: time, slide counter, Warm Now](../.gitbook/assets/transport.png)

## Playback

- **Space** or the Play/Pause control
- Click or drag the playhead / time ruler to scrub
- Hover the ruler for a ghost preview before seeking
- **←** / **→** nudge; **⇧** for larger steps
- **⌘→** / **⌘←** next / previous slide; **⌥⌘←** go to start

The clock is `current / total`. Beside it, **1 of N** counts every photo card (including each seat in a group).

Workbench **ambilight** (color spilling onto the chrome) is display-only. Soft color sampled from the slide at the playhead lights the title bar, Timeline bed, and Inspector seam. It never touches the photo and is never in the export. The title bar settles a beat later than the rest (it can only hold one flat color).

## Live, baked, and export

Three ways to see the same show:

| | What it is |
| --- | --- |
| **Live preview** | The stage while you edit. Motion, Looks, and captions update immediately. Can hitch on a heavy show. |
| **Scrub** | Drag the playhead or ruler. Hover the ruler for a ghost frame before you commit. After a bake, scrub uses that smooth pass; moving the playhead drops any paused cover so the head stays honest. |
| **Baked (smooth play)** | A pre-encoded pass so **Space** and scrub stay fluid. Finished segments stay on disk; reopen restores them if nothing changed. Play switches to this pass as soon as the first slides (or the whole show) are ready — it should not stay on the live, laggy preview. |
| **Export** | The H.264 MP4. Same choreography, framing, and audio as the baked show (preview seed matches export). Ambilight is not in the file. Format in the Export dialog can differ from the live preview swatch. |

MemoryString does **not** bake in the background while you edit. Edits still appear live. Style and framing keep updating the live stage while a bake catches up.

## Smooth play (warming)

**Essential** warms automatically when you press **Play**, and shows **Stop** while a warm is running.

**Studio** adds controls on the transport row beside the slide counter:

- **Auto-warm on Play** (off by default) — start warming from the playhead when you press **Space**, without blocking the workbench
- **Warm Now** — bake only segments that are not ready yet (already-warm slides are skipped). Blocks the workbench with a progress dialog until those dirty segments finish, or until **Cancel** / **Esc**. Disabled when everything is already warm
- **Stop** — cancel an in-flight warm (Play warm or Warm Now)

A champagne **working-status pill** under the preview covers, in this order:

1. Export — *Edits paused while creating memory*
2. Bake — *Warming k/n* (Play / Auto-warm / Warm Now) or *Updating k/n* (a look/edit refresh of a finished bake)
3. Asset / **Loading music…**

**k/n** matches the slide counter (every photo seat; the closing credit is not counted). A quiet stage means ready — there is no idle “Smooth play ready” message.

See [Essential and Studio](workspace/essential-studio.md).

## Center of interest

The small round ring on a **paused** photo is that slide’s **center of interest** (focus) — where MemoryString aims the motion. Original files are never modified.

**Auto (on import):** every photo and video gets one: the **largest face** (aim near the eyes), else the **main subject**, else the **middle** of the frame. Videos sample several frames in the trim window. Full order: [Auto detection](auto-detection.md).

**Manual override:** pause and click the spot you want (*Tap photo to set focus*). The ring jumps there; the status line shows **Focus · 62%, 38%** (example). Dragging instead of clicking pans the paused view and leaves focus alone. Each change is its own **⌘Z**.

**Reset Center of Interest** (right-click the paused photo) drops the override, re-runs detection, and restores the import pick.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

**What it aims:** Ken Burns and punch-in end framed around this point; the blurred backdrop follows it; cards in a Photo Stack, Carousel, 3D Ribbon, Perspective Pair, or Filmstrip use it too. Depth dissolve, card flip, slide rotate, spiral-in, and reveal from depth show the whole photo, so they ignore it.

On the **intro**, a single click on the still (or title) sets the same aim; **double-click** the title to edit text. This is a framing aim, not caption position.

## Rotate while paused

Right-click the paused photo or video (not the intro) → **Rotate Right** / **Rotate Left** / **Flip Horizontal** / **Flip Vertical**. Hidden while playing.

Paused on the intro: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, and (Studio) **Lens Effect**.

While paused, **double-click** intro text to edit it inline. Captions: a single click selects the slide; a **double-click** hands off to the caption field. Captioned slides get a small blue speech-bubble badge on the Timeline.
