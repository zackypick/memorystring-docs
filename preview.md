---
description: "Watch and scrub your MemoryString slideshow, smooth playback warming, center of interest, and rotating photos while paused."
---

# Preview

The large area in the center is where you watch your movie while you edit. Photos and videos live in the **Library**. Order and trim also use the **Timeline**.

![Preview transport: time, slide counter, Warm Now, Stop, and Warming k/n: no Auto-warm checkbox](../.gitbook/assets/transport.png)

## Playback

Use **Space** or the **Play/Pause** button under the preview to play and pause.

The **speaker** button sits just to the right of **Play/Pause**. It mutes sound in the preview only. The exported movie still has sound.

Muting one clip is separate. Do that on the clip in the **Library**, the **Inspector**, or the **Audio** tab.

The mute choice lasts until you quit the app.

Other playback controls:

- Click or drag the playhead or time ruler to scrub. After you edit, dragging still follows. The slide you stop on comes up first. A slide with no backdrop fills in while you drag, and the stage stays light.
- Hover the **Timeline** photo lane to peek at that moment. When you move the pointer off the strip, the preview stays on that moment. Hover does not work while the movie is playing
- **←** / **→** nudge the playhead. **⇧** with arrow keys takes larger steps
- **⌘→** / **⌘←** go to the next or previous slide
- **⌥⌘←** goes to the start

The clock shows `current / total`. **1 of N** counts every photo card, including each seat in a group.

Both **Essential** and **Studio** warm up smooth playback when you press **Play**. **Studio** adds **Warm Now** and **Stop** on the transport row.

## Color glow

Soft color from the edges of the current slide can tint the window chrome around the preview. This is display only. It does not appear on the photo or in the export.

## Empty stage

A new empty project shows **Add photos & videos** on the preview. That button opens a menu (Photos & Videos, Import from Photos, Music, Royalty-Free Library). Escape closes it. You can also drop photos, videos, or a `.memorystring` project onto the preview.

While MemoryString imports or opens a show, a progress message sits on the stage and adding more media waits until it finishes. **Cancel** stops a long import.

## Live preview, smooth playback, and export

| | What it is |
| --- | --- |
| **Live preview** | What you see while you edit. Changes appear right away. A heavy show may stutter. |
| **Scrub** | Move the playhead or hover the photo lane. After smooth playback is ready, scrub uses that smoother pass. |
| **Smooth playback** | A prepared pass so **Space** and scrub stay fluid. **Play** switches to it when enough slides are ready. |
| **Export** | The H.264 MP4 you share. Same look and timing as smooth playback. Export format can differ from the preview swatch in **Format**. |

MemoryString does not prepare smooth playback in the background while you edit. Edits show on the live preview first.

## Smooth playback (warming)

Both modes start warming when you press **Play**.

**Essential** shows a **Preparing smooth playback** card on the preview until the next five photo slides from the playhead are ready. The card counts *Warming 1/5* through *Warming 5/5*. **Stop** or **Esc** cancels. Playback starts only after 5/5 or when you cancel.

**Studio** does not block the whole window. The movie can start live and switch to the smooth pass as slides finish. **Warm Now** prepares only segments that are not ready yet. **Stop** cancels warming.

Status under the preview can show:

1. Export: *Edits paused while creating memory*
2. Warming or updating. *Warming k/n* or *Updating k/n*
3. **Loading music…**

See [Essential and Studio](workspace/essential-studio.md#what-changes).

When the show ends on a group, Play fades that backdrop into the end card. On a Light stage the card is cream. On a Dark stage it is black.

## Center of interest

When a photo is paused, you may see a small round ring. That is **center of interest**. Motion uses it so faces stay in frame.

**On import:** every photo and video gets a point. MemoryString picks the largest face, else the main subject, else the center. Videos use several frames in the trim window.

**Manual:** pause and click the photo. Drag to pan. Each change undoes with **⌘Z**. While **Export** or **Warm Now** has edits paused, a click on the preview does **not** move the focus spot. The pointer is a grab hand while it is over the circle.

**Zoom the blur:** pinch, or hold **Command** and scroll, from half the automatic crop to 2.5×. A plain scroll still moves the playhead. Drag the circle to aim where the blur sits. The same zoom works on the opening card.

**Reset Center of Interest** (right-click the paused photo) removes your override and runs detection again.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

Ken Burns and similar motion use center of interest. Some transitions show the whole photo and ignore it.

On the **opening card**, a single click on the still sets the same aim. **Double-click** the title in the Preview to edit it in place, then press **Shift+Enter** to start a new line. On the **end card**, **double-click** the closing words and use **Shift+Enter** the same way. The fields in the inspector don't take line breaks. Long lines wrap on their own.

## Rotate while paused

Right-click the paused photo or video → **Rotate Clockwise** / **Rotate Counter Clockwise** / **Flip Horizontal** / **Flip Vertical**. These options are hidden while playing. Sideways shots are already upright from import. Turning one back to as-shot sticks. See [Orientation](auto-detection.md#orientation).

On the opening card: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, and (Studio) **Lens Effect**. With a background still, **Rotate & Flip** turns the cover photo.

**Double-click** opening title or closing words to edit. **Double-click** a caption to edit it. Captioned slides show a small speech-bubble badge on the **Timeline**.
