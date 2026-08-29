# Timeline

Under the preview: scrub, reorder, trim, and line up slides with music.

![Photo lane and music waveform for a full show](../.gitbook/assets/timeline-full.png)

![Timeline header: clip name, caption field, Generate, zoom](../.gitbook/assets/timeline-chrome.png)

## Layout

Top to bottom:

1. **Time ruler** — click or drag to seek; hover for a ghost preview (ghost line + dimmer time chip) until you click
2. **Photo lane** — slides, intro, and group cells
3. **Music lane** — soundtrack clips

Chrome above the lanes shows the selected clip **name + duration** and a zoom control. The readout is **fit-relative**: **1.0×** means the whole project spans the window; **3.0×** means the strip is three windows wide. Pinch, scroll-wheel zoom, **⌥⌘+** / **⌥⌘-**, or a middle-mouse drag to pan.

Once there are more slides than fit at a readable size, the timeline **scrolls** instead of squeezing. Cells keep a minimum width (thumbs, motion label, duration). Very long projects stop widening at about **8 windows** — zoom in from there. Drag the zoom slider all the way **left** for an end-to-end overview. A very short hold still gets a clickable cell.

During playback the strip **follows the playhead**. Panning by hand while paused is never yanked back. Drag a clip near the left or right edge and the strip auto-scrolls.

While dragging the playhead, a blue time chip shows tenths, then hundredths / frames as you zoom in. **←** / **→** nudge (~0.1s, accelerates if held); **⇧** for larger steps.

## Reorder and trim

Drag clips on the photo lane. Drag from the **Library** into a **gap** to insert or move; drop on a **single** or **group seat** to **Replace**. Music clips reorder on the music lane.

Select a clip, then drag **edge grips**. Videos show frame feedback; music can audition the edge. Videos have a **2 second** minimum. Right-click a video or music clip:

- **Set Start Here** / **Set End Here**
- **Reset Length**

The Inspector clip footer offers the same playhead trims. **⌘1** / **⌘2** are Set Start / Set End; **⌘D** opens **Set Duration…** (value selected so you can type; applies to every selected slide).

A slide with no caption offers **Auto Caption** (or **Auto Caption N Untitled Slides** for a multi-selection of blanks). Once it has text, that item is **Clear Caption**.

Intro cell: **Disable Intro Slide**.

## Motion → Timeline (Studio)

Inspector → **Motion** → **Timeline**:

- **Sort by Date Taken** — Oldest First / Newest First / Import Order
- **Shuffle Slides** — pauses playback, randomizes photo order, seeks to the start
- **Shuffle Transitions** — keeps photo order; re-rolls single-slide cuts, group kinds, and window positions. Cadence, which group types are on, and card counts stay. Hand-picked Slide Transitions: asks before clearing
- **Reset Slide Durations**

The intro stays first. **⌘Z** undoes sort / shuffle.

## Groups on the strip

When a multi-photo window is on, follower slides collapse onto a **lead** cell (for example “stack of 4”, “carousel of 5”, “ribbon of N”, “pair of 2”, “filmstrip of N”, “Scatter & Settle”). The cell can show a multi-thumb strip and per-video mute badges. See [Multi-photo groups](motion/groups.md).
