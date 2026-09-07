# Preview

The big stage is where you watch what you’re making — the movie someone opens on a phone after dinner. Import lives in the Library; order and trim also use the Timeline.

![Preview transport: time, slide counter, Warm Now — no Auto-warm checkbox](../.gitbook/assets/transport.png)

## Playback

Hit **Space**. Scrub. Nudge. Does the toast land before the song swells?

- **Space** or the Play/Pause control
- Click or drag the playhead / time ruler to scrub
- Hover the ruler for a ghost preview before seeking
- **←** / **→** nudge; **⇧** for larger steps
- **⌘→** / **⌘←** next / previous slide; **⌥⌘←** go to start

The clock is `current / total`. Beside it, **1 of N** counts every photo card (including each seat in a group). Both modes auto-warm on **Play**. Studio adds **Warm Now** and **Stop** on that row — there is no Auto-warm checkbox.

## Empty stage and opening fog

A blank Untitled project is quiet: Library **Nothing in library yet**, Timeline **Nothing on the timeline yet**, preview **Add photos & videos** plus *Drop photos and videos to start a memory*. Hover a media drop and the plate pulse reads **Let the story begin** (ants on the preview plate only). Hover a `.memorystring` and it reads **The plot thickens**.

Opening an existing `.memorystring` fogs **The story continues…** (same brew as first-import **The story begins…**, no percent). Drops are ignored until that fog lifts. **Keep Best Shots** waits until after the fog. Once the show has clips, a media drop overlay reads **Add to story**.

## Live, baked, and export

Edit wants instant. Share wants smooth. Export wants the file.

| | What it is |
| --- | --- |
| **Live preview** | The stage while you edit. Motion, Looks, and captions update immediately. Can hitch on a heavy show. |
| **Scrub** | Drag the playhead or ruler. Hover the ruler for a ghost frame before you commit. After a bake, scrub uses that smooth pass; moving the playhead drops any paused cover so the head stays honest. |
| **Baked (smooth play)** | A pre-encoded pass so **Space** and scrub stay fluid. Finished segments stay on disk; reopen restores them if nothing changed. Play switches to this pass as soon as the first slides (or the whole show) are ready — it should not stay on the live, laggy preview. |
| **Export** | The H.264 MP4. Same choreography, framing, and audio as the baked show (preview seed matches export). Format in the Export dialog can differ from the live preview swatch. |

MemoryString does **not** bake in the background while you edit. Edits appear live; style and framing keep updating the live stage while a bake catches up.

## Smooth play (warming)

A heavy anniversary album should not stutter for the person who matters.

**Essential** and **Studio** both auto-warm when you press **Play** (there is no Auto-warm checkbox). **Essential** also shows **Stop** while a warm is running. On a cold Essential show, Play blocks with a **Preparing smooth playback** card **centered on the preview stage** until the next five *photo* slides from the playhead are ready (intro title and the closing MemoryString card do not hold the gate). The card counts the lead — *Warming 1/5* through *Warming 5/5* — then starts on the baked pass. The dialog never lifts early: playback begins only after it reads 5/5 (or you **Stop** / **Esc**).

**Studio** Play does not block the workbench — the movie can start live and switch to the baked pass as the first slides land. Studio adds controls on the transport row beside the slide counter:

- **Warm Now** — bake only segments that are not ready yet (already-warm slides are skipped). Blocks the workbench with the same centered **Preparing smooth playback** card until those dirty segments finish, or until **Stop** / **Esc**. Disabled when everything is already warm
- **Stop** — cancel an in-flight warm (Play warm or Warm Now)

A champagne **working-status pill** under the preview covers, in this order:

1. Export — *Edits paused while creating memory*
2. Bake — *Warming k/n* (Play / Warm Now) or *Updating k/n* (a look/edit refresh of a finished bake)
3. Asset / **Loading music…**

**k/n** matches the slide counter (every photo seat). Quiet stage means ready — no idle “Smooth play ready” message. Silence is the compliment.

See [Essential and Studio](workspace/essential-studio.md#what-changes).

## Center of interest

The small round ring on a **paused** photo is **center of interest** — where motion aims so faces stay framed, not cropped at the ear. Originals never modified.

**Auto (on import):** every photo and video gets one — **largest face** (near the eyes), else **main subject**, else **middle** of the frame. Videos sample several frames in the trim window. Full order: [Auto detection](auto-detection.md#center-of-interest).

**Manual override:** pause and click (*Tap photo to set focus*). Ring jumps; status shows **Focus · 62%, 38%** (example). Drag pans and leaves focus alone. Each change its own **⌘Z**.

**Reset Center of Interest** (right-click the paused photo) drops the override, re-runs detection, restores the import pick.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

**What it aims:** Ken Burns and punch-in end here; blurred backdrop follows; Photo Stack, Carousel, 3D Ribbon, Perspective Pair, Filmstrip cards use it too. Depth dissolve, card flip, slide rotate, spiral-in, and reveal from depth show the whole photo — they ignore it.

On the **intro**, a single click on the still (or title) sets the same aim; **double-click** the title to edit text. Framing aim, not caption position.

## Rotate while paused

Sideways phone photos happen. Fix here; originals stay untouched.

Right-click the paused photo or video (not the intro) → **Rotate Clockwise** / **Rotate Counter Clockwise** / **Flip Horizontal** / **Flip Vertical**. Hidden while playing.

Paused on the intro: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, and (Studio) **Lens Effect**.

While paused, **double-click** intro text to edit inline. Captions: single click selects; **double-click** hands off to the caption field. Captioned slides get a small blue speech-bubble badge on the Timeline.
