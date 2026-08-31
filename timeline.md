# Timeline

The strip under the stage is the movie’s pulse — hold times, music, and where a too-long toast gets trimmed.

![Photo lane and music waveform for a full show](../.gitbook/assets/timeline-full.png)

![Timeline header: clip name, caption field, Generate, zoom](../.gitbook/assets/timeline-chrome.png)

![Timeline: typing a slide caption](../.gitbook/assets/caption-edit.png)

## Layout

Time, pictures, music:

1. **Time ruler** — click or drag to seek; hover for a ghost preview (ghost line + dimmer time chip) until you click
2. **Photo lane** — slides, intro, and group cells
3. **Music lane** — soundtrack clips

Chrome above shows selected clip **name + duration** and zoom. Readout is **fit-relative**: **1.0×** = whole project in the window; **3.0×** = three windows wide.

### Timeline height

Need taller thumbs? Drag the **thin seam above the Timeline** (between the preview row and the filmstrip) **up** to grow the photo lane, **down** to shrink it. Extra height runs from **0** to about **160** points and is remembered across launches. **⌘+** / **⌘-** still scale Timeline strip height (and Library cards) with UI text size; this drag adds on top of that base.

![Drag the seam to grow the filmstrip; zoom slider scales the strip live](.gitbook/assets/timeline-expand-zoom.gif)

### Zoom and gestures

Zoom out for the whole birthday; in when a half-second matters.

- **Zoom slider** (minus / plus magnifying glass) — scale updates **live** as you drag; all the way **left** for an end-to-end overview
- **Pinch** on a trackpad to zoom the strip
- **Scroll-wheel** zoom (pointer over the Timeline)
- **⌥⌘+** / **⌥⌘-** zoom in / out
- **Two-finger trackpad pan** or **horizontal scroll** to move along the strip
- **Middle-mouse drag** to pan

**⌘+** / **⌘-** / **⌘0** are UI text size — they scale **Library cards** and Timeline *strip height* together, not Timeline zoom.

Once slides exceed a readable fit, the timeline **scrolls** instead of squeezing. Cells keep a minimum width (thumbs, motion label, duration). Very long projects cap at about **8 windows** — zoom in from there. A very short hold still gets a clickable cell.

During playback the strip **follows the playhead**. Hand-pan while paused is never yanked back. Drag near either edge to auto-scroll. Hover-scrub on the ruler stands down while the strip travels under the pointer (trackpad momentum), then re-syncs when it settles.

Dragging the playhead, a blue time chip shows tenths, then hundredths / frames as you zoom in. **←** / **→** nudge (~0.1s, accelerates if held); **⇧** for larger steps.

## Reorder and trim

Move the awkward photo. Shorten what overstays. Leave the good ones alone.

Drag clips on the photo lane. Drag from the **Library** into a **gap** to insert or move; drop on a **single** or **group seat** to **Replace**. Music clips reorder on the music lane.

First click on a group selects the whole window; second click on a thumb drills into that seat. See [Organizing](organizing.md#in-group-photos-and-videos).

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
- Videos also: **Mute Video Sound** / **Unmute Video Sound**, **Auto Trim**, **Reset Length**

![Clip context menu with Auto Trim](../.gitbook/assets/auto-trim-context-menu.png)

**Auto Trim** (videos) finds the climax in the full source and keeps an Energy-length window on it — wait and leftover go. Context-menu choose runs immediately; undo with **⌘Z**. Not on import. See [Auto detection](auto-detection.md#auto-trim).

Right-click a video or music clip for trim:

- **Set Start Here** / **Set End Here** — trim in/out at the playhead
- **Reset Length**

The Inspector clip footer offers the same playhead trims for a selected **video** or **soundtrack**. **⌘1** / **⌘2** = Set Start / Set End; **⌘D** opens **Set Duration…** (value selected to type; applies to every selected *slide*). **Reset Slide Durations** (Motion → Timeline / Library ⋯) restores default still timing.

![Set Duration… for selected slides](../.gitbook/assets/set-duration.png)

A slide with no caption offers **Auto Caption** (or **Auto Caption N Untitled Slides** for a multi-selection of blanks). Once it has text, that item is **Clear Caption**.

Intro cell: **Disable Intro Slide**.

## Motion → Timeline (Studio)

Sort and shuffle from the Inspector when order still feels wrong.

Inspector → **Motion** → **Timeline**:

- **Sort by Date Taken** — Oldest First / Newest First / Import Order
- **Shuffle Slides** — pauses playback, randomizes photo order, seeks to the start
- **Shuffle Transitions** — keeps photo order; starts a fresh deal of single-slide cuts, group kinds, and window positions. Cadence, which group types are on, and card counts stay. Hand-picked Slide Transitions: asks before clearing. Also Library **⋯**:

![Library ⋯: Shuffle Transitions, Reset Slide Durations, Show Transition Names](../.gitbook/assets/library-menu-options.png)

- **Reset Slide Durations**

The intro stays first. **⌘Z** undoes sort / shuffle.

## End card

Every show closes on a short **MemoryString** credit. On the photo lane that hold is a trailing black **end** cell — click it to select the end card (same as scrubbing into the closing credit). It is not a media clip you can trim or reorder.

## Groups on the strip

Multi-photo windows collapse followers onto a **lead** cell (for example “stack of 4”, “carousel of 5”, “ribbon of N”, “pair of 2”, “filmstrip of N”, “Scatter & Settle”). The cell can show a multi-thumb strip and per-video mute badges. One cell, many faces. See [Multi-photo groups](motion/groups.md#timeline-library).
