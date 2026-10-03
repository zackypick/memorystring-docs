# Preview

The large area in the center is where you watch your movie while you edit. Photos and videos live in the **Library**. Order and trim also use the **Timeline**.

![Preview transport: time, slide counter, Warm Now, Stop, and Warming k/n — no Auto-warm checkbox](../.gitbook/assets/transport.png)

## Playback

Use **Space** or the toolbar **Play/Pause** button to play and pause.

The **speaker** button sits just to the right of **Play/Pause**. It mutes sound in the preview only. The exported movie still has sound.

Muting one clip is separate. Do that on the clip in the **Library**, the **Inspector**, or the **Audio** tab.

The mute choice lasts until you quit the app.

Other playback controls:

- Click or drag the playhead or time ruler to scrub
- Hover the **Timeline** photo lane to peek at that moment. When you move the pointer off the strip, the preview stays on that moment. Hover does not work while the movie is playing
- **←** / **→** nudge the playhead. **⇧** with arrow keys takes larger steps
- **⌘→** / **⌘←** go to the next or previous slide
- **⌥⌘←** goes to the start

The clock shows `current / total`. **1 of N** counts every photo card, including each seat in a group.

Both **Essential** and **Studio** warm up smooth playback when you press **Play**. **Studio** adds **Warm Now** and **Stop** on the transport row.

## Workbench ambilight

Soft color from the edges of the current slide can tint the window chrome around the preview. This is display only. It does not appear on the photo or in the export.

## Empty stage and opening loader

A new empty project shows **Nothing in library yet** in the **Library**, **Nothing on the timeline yet** on the **Timeline**, and **Add photos & videos** on the preview.

When you hover over the preview to drop media, the hint reads **Gather the thread**. When you hover a `.memorystring` file, the hint reads **Bring back memories**.

The first import shows a loader on the stage. It is a spinner with a smoke animation. The title is **Stringing it together...**. You may see a percent and **Cancel** if the import takes a while.

Opening an existing `.memorystring` uses the same loader with **It's coming back now...** and no percent.

You cannot drop files while the loader is visible. **Keep Best Shots** waits until the loader finishes.

After the show has clips, a media drop overlay reads **Add to story**.

## Live preview, smooth playback, and export

| | What it is |
| --- | --- |
| **Live preview** | What you see while you edit. Changes appear right away. A heavy show may stutter. |
| **Scrub** | Move the playhead or hover the photo lane. After smooth playback is ready, scrub uses that smoother pass. |
| **Smooth playback (baked)** | A prepared pass so **Space** and scrub stay fluid. **Play** switches to it when enough slides are ready. |
| **Export** | The H.264 MP4 you share. Same look and timing as smooth playback. Export format can differ from the preview swatch in **Format**. |

MemoryString does not prepare smooth playback in the background while you edit. Edits show on the live preview first.

## Smooth playback (warming)

Both modes start warming when you press **Play**.

**Essential** shows a **Preparing smooth playback** card on the preview until the next five photo slides from the playhead are ready. The card counts *Warming 1/5* through *Warming 5/5*. **Stop** or **Esc** cancels. Playback starts only after 5/5 or when you cancel.

**Studio** does not block the whole window. The movie can start live and switch to the smooth pass as slides finish. **Warm Now** prepares only segments that are not ready yet. **Stop** cancels warming.

Status under the preview can show:

1. Export — *Edits paused while creating memory*
2. Warming or updating — *Warming k/n* or *Updating k/n*
3. **Loading music…**

See [Essential and Studio](workspace/essential-studio.md#what-changes).

## Center of interest

When a photo is paused, you may see a small round ring. That is **center of interest**. Motion uses it so faces stay in frame.

**On import:** every photo and video gets a point. MemoryString picks the largest face, else the main subject, else the center. Videos use several frames in the trim window.

**Manual:** pause and click the photo. Drag to pan. Each change undoes with **⌘Z**.

**Reset Center of Interest** (right-click the paused photo) removes your override and runs detection again.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

Ken Burns and similar motion use center of interest. Some transitions show the whole photo and ignore it.

On the **intro**, a single click on the still sets the same aim. **Double-click** the title to edit text.

## Rotate while paused

Right-click the paused photo or video → **Rotate & Flip** → **Rotate Clockwise** / **Rotate Counter Clockwise** / **Flip Horizontal** / **Flip Vertical**. These options are hidden while playing.

On the intro: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, and (Studio) **Lens Effect**. With a background still, **Rotate & Flip** turns the cover photo.

**Double-click** intro text to edit. **Double-click** a caption to edit it. Captioned slides show a small speech-bubble badge on the **Timeline**.
