# Timeline

Under the preview: scrub, reorder, trim, and line up slides with music.

![Photo lane and music waveform for a full show](../.gitbook/assets/timeline-full.png)

![Timeline header: clip name, caption field, Generate, zoom](../.gitbook/assets/timeline-chrome.png)

![Timeline: typing a slide caption](../.gitbook/assets/caption-edit.png)

## Layout

Top to bottom:

1. **Time ruler** — click or drag to seek; hover for a ghost preview (ghost line + dimmer time chip) until you click
2. **Photo lane** — slides, intro, and group cells
3. **Music lane** — soundtrack clips

Chrome above the lanes shows the selected clip **name + duration** and a zoom control. The readout is **fit-relative**: **1.0×** means the whole project spans the window; **3.0×** means the strip is three windows wide.

### Zoom and gestures

- **Zoom slider** (minus / plus magnifying glass) — drag all the way **left** for an end-to-end overview
- **Pinch** on a trackpad to zoom the strip
- **Scroll-wheel** zoom (pointer over the Timeline)
- **⌥⌘+** / **⌥⌘-** zoom in / out
- **Two-finger trackpad pan** or **horizontal scroll** to move along the strip
- **Middle-mouse drag** to pan

**⌘+** / **⌘-** / **⌘0** are UI text size (Library thumbs and Timeline *row height*), not Timeline zoom.

Once there are more slides than fit at a readable size, the timeline **scrolls** instead of squeezing. Cells keep a minimum width (thumbs, motion label, duration). Very long projects stop widening at about **8 windows** — zoom in from there. A very short hold still gets a clickable cell.

During playback the strip **follows the playhead**. Panning by hand while paused is never yanked back. Drag a clip near the left or right edge and the strip auto-scrolls. Hover-scrub on the ruler stands down while the strip is travelling under the pointer (trackpad momentum), then re-syncs when it settles.

While dragging the playhead, a blue time chip shows tenths, then hundredths / frames as you zoom in. **←** / **→** nudge (~0.1s, accelerates if held); **⇧** for larger steps.

## Reorder and trim

Drag clips on the photo lane. Drag from the **Library** into a **gap** to insert or move; drop on a **single** or **group seat** to **Replace**. Music clips reorder on the music lane.

First click on a group cell selects the whole window; a second click on a thumb drills into that seat so you can drag it alone. See [Organizing](organizing.md).

Select a clip, then drag **edge grips** on either end:

- **Videos** — frame feedback in the trim; **2 second** minimum. **Reset Length** restores the full file
- **Music** — the edge **auditions** that moment in the source song (the mixed bed stays paused). **Reset Length** returns to the auto-skipped quiet-edge window, or the full file if none was found
- **Stills** — edge drag changes how long the slide holds

Right-click a photo or video on the **photo lane**:

![Timeline clip menu: Slide Transition, rotate, duration, Auto Caption, Remove](../.gitbook/assets/timeline-context-menu.png)

- **Slide Transition** — pick a cut, or **Random** (groups: **Change Transition** / **Ungroup** / **Group Transition** when several clips are selected)
- **Rotate Right** / **Rotate Left** / **Flip Horizontal** / **Flip Vertical**
- **Set Duration…** (**⌘D**)
- **Auto Caption** or **Clear Caption**
- **Remove from Project** (**⌘⌫**)
- Videos also: **Mute Video Sound** / **Unmute Video Sound**, **Reset Length**

Right-click a video or music clip for trim:

- **Set Start Here** / **Set End Here** — trim in/out at the playhead
- **Reset Length**

The Inspector clip footer offers the same playhead trims when a **video** or **soundtrack** is selected. **⌘1** / **⌘2** are Set Start / Set End; **⌘D** opens **Set Duration…** (value selected so you can type; applies to every selected *slide*). **Reset Slide Durations** (Motion → Timeline / Library ⋯) restores default still timing.

![Set Duration… for selected slides](../.gitbook/assets/set-duration.png)

A slide with no caption offers **Auto Caption** (or **Auto Caption N Untitled Slides** for a multi-selection of blanks). Once it has text, that item is **Clear Caption**.

Intro cell: **Disable Intro Slide**.

## Motion → Timeline (Studio)

Inspector → **Motion** → **Timeline**:

- **Sort by Date Taken** — Oldest First / Newest First / Import Order
- **Shuffle Slides** — pauses playback, randomizes photo order, seeks to the start
- **Shuffle Transitions** — keeps photo order; re-rolls single-slide cuts, group kinds, and window positions. Cadence, which group types are on, and card counts stay. Hand-picked Slide Transitions: asks before clearing. Also Library **⋯**:

![Library ⋯: Shuffle Transitions, Reset Slide Durations, Show Transition Names](../.gitbook/assets/library-menu-options.png)

- **Reset Slide Durations**

The intro stays first. **⌘Z** undoes sort / shuffle.

## Groups on the strip

When a multi-photo window is on, follower slides collapse onto a **lead** cell (for example “stack of 4”, “carousel of 5”, “ribbon of N”, “pair of 2”, “filmstrip of N”, “Scatter & Settle”). The cell can show a multi-thumb strip and per-video mute badges. See [Multi-photo groups](motion/groups.md).
