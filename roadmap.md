---
description: "What's new in MemoryString 1.2.7, plus what comes next."
---

# What's new

MemoryString **1.2.7** refreshes the built-in music catalog (CC0), points Help links and support mail at memorystring.app, lets you zoom and aim the blurred backdrop, and keeps Golden Hour warm through the exit card. **1.2.6** closed the app when you closed the window and quieted crash reporting. **1.2.5** kept **Long story short** length steady after **Fit Show to Music**.

Bug fixes are listed by version on [Fixed](fixed.md).

## What's new

**1.2.7**

- Built-in soundtrack is a larger **CC0 / public domain** catalog. Look pools and loudness are leveled so quieter and louder songs sit nearer the same level in the show.
- **Surprise me** and **Pick New Music** rotate through fitting songs instead of always landing on the shortest catalog stem.
- Product site, docs, and support mail use **memorystring.app**, **docs.memorystring.app**, **feedback@memorystring.app**, and **reports@memorystring.app**.
- **Help → Send Feedback…** and **Help → Report a Problem…** open Apple Mail drafts, with a crash zip attached for Report a Problem.
- Crash upload stays silent in the background  -  no false “app hung” sheets while a report sends.
- Soft heroes after a fast scrub sharpen when you stop, instead of staying blurry until you click.
- Soft-stack and other wash seams keep coverage through the crossfade so cream holes do not flash between slides.
- Large imports stay responsive: identity hashing stays off the main thread so drops do not beach-ball.
- The blurred backdrop zooms wide photos so a face sits beside the card, and seats a tall frame in the open blur above or below the card. The crop does not cut a head off the top.
- Pinch, or hold **Command** and scroll, to zoom that blur from half the automatic crop to 2.5×. The same gesture works on the opening card. The pointer is a grab hand over the focus circle. Drag the circle to aim the blur.
- **Golden Hour** keeps the sun off faces, titles, and the end card. The exit card stays the same warm color as the slides. The exported movie matches the preview.
- When the show ends before the song does, the music fades out over about 5 seconds. A playlist song that would only start on the end card is left off.
- **Studio** titles: **Match Closing Style** and **Go to Opening** sit under the opening words. **Match Opening Style** and **Go to Closing** sit under the closing words. Match copies the look once. It does not keep the two in sync.
- **Help → YouTube Channel** opens the MemoryString channel. **Help → MemoryString Website** and **Help → Documentation** sit with it.

**1.2.6**

- Closing the main window (red button or **⌘W**) quits the app. Untitled work with content asks **Save** / **Don't Save** / **Cancel** first.
- **MemoryString → Settings…** (**⌘,**) opens MCP Server as a sheet on the main window. **Close** or Escape dismisses it. There is no separate Settings window.
- Turning **Music Follows Show** back on refills a short music bed so the song covers the show again.
- **Fit Show to Music** keeps group timing when it stretches the show to a longer song.
- Opening or closing a **Studio** title font menu previews that face on the stage. The choice sticks only when you click a name.

**1.2.5**

- A **Long story short** rebuild starts clean: hand-set slide lengths, transitions, and lens choices clear. Look, energy, rotation, captions, music, titles, cover, and muted videos stay.
- On a full-body photo, the person sits beside the card so the place stays in the blur.
- **Reset Titles to Defaults** says what it restores, and clears the opening background and closing words.

**1.2.4** (since the **1.2.2** App Store build)

- **Fit Show to Music** moves **Energy** so the song covers the whole film, including the end card, and fades across the credit. It turns **Music Follows Show** off. Your own tracks stay. See [Music](music.md#length).
- **Titles** holds the **opening card** and optional **closing words**. Closing words sit on the existing end card, above **Created with MemoryString**, and stay off until you turn them on. See [Titles and captions](intro-captions.md).
- **Music Follows Show** keeps the soundtrack with the Look. It is on by default. Turn it off to keep your playlist when you change Looks. See [Music](music.md#music-follows-show).
- **Peek**: double-click an Outtake, or right-click → **Peek**, to look at a parked shot over the preview without putting it on the show. See [Library](library.md#outtakes).
- **Studio fonts**: captions, the opening title, and closing words can use any font installed on this Mac, each name drawn in its own type. See [Titles and captions](intro-captions.md#fonts-studio).
- Scenic and person-and-pet backdrops keep the place and both subjects in the blur.

**1.2.2**

- **Library** Show menu → **Videos** can **Mute Noisy Videos**, **Mute All Videos**, and **Unmute All Videos**. Wind and hiss go quiet; talking, music, and sharp hits stay. Opening a show re-checks.
- On a group photo, the blurred backdrop shows the people in the photo, not the empty room.
- The 50 bundled songs take about 36 MB less space.

**1.2.1**

- **Long story short** goes up to **30** minutes, still capped at what the photos can fill. The finished movie lands within about 10 seconds of the minute you pick. Closing and opening the project keeps that order and that length.

**1.2.0**

- The intro is full bleed and follows the show’s stage. **Intensity** follows Stage Intensity until you change it. The intro eases into the first slide.
- A new show is **Clean** on the **Light** stage. **Cinematic** stays on **Dark**. **Clean** and **Crisp** use a grayscale backdrop. **Polaroid** and **Golden Hour** stay in color.
- The backdrop covers the stage and is never mirrored. A face that would hide behind the card moves into the open side.
- **Long story short** finds each face and deals groups across the finished show, the same way **Shuffle** does.
- You can check every group kind. **Auto** still picks a short list from the length of the show, and never more than three.

**1.1.3** (since the **1.1.2** App Store build)

- **Motion → Transitions.** Checked boxes are the kinds this show uses. **How many** and **Auto** set how many single-slide transitions and group kinds, and the list grows with the show. **Shuffle** keeps kinds you checked. Each change re-cuts the show.
- **Photo series.** Photos from the same shoot stay in one group. A group does not mix two shoots.
- **Long story short.** The Duration sheet leaves the show alone until **Create**. The offer is the nearest minute that show can fill. A series stays one group. Near-duplicates are not side by side.
- **Keep Best** flags the same moment in the same framing. A different pose stays.
- Imports from Photos are faster.
- **Pinned groups** stay when you delete, move, or change a transition. **Ungroup** keeps the mix on the other slides.
- New shows start **Stage Intensity** at **50%** on Dark and **80%** on Light.
- **Go to Start** (|◀) sits beside **Timeline**. It jumps the playhead to **0:00** and scrolls a zoomed filmstrip back to the start. Same as **⌥⌘←**.
- After **Long story short**, groups sit with the usual gap between them, not back to back. **Perspective Pair** can be turned off like any other group kind.

## Earlier releases

### **1.1**

**Long story short** and richer **captions**. Group lengths are easier to set, and Help moved to this site.

**Long story short.** Build a shareable movie from a big pile of photos and videos. Pick a length from 1 to 30 minutes (default 3), capped at what the photos can fill. The best shots go on the show, spread across the whole trip. Videos are trimmed. The rest stay in **Outtakes**. Nothing is deleted. An import of more than 150 photos and videos offers it first. See [Long story short](long-story-short.md).

**Caption Details.** Choose what automatic captions say: landmark, city, country, and date. Dates come short, long, or as numbers, with or without the weekday. Captions can be written in another language. One **Size** for every slide, and captions rise in by default. See [Titles and captions](intro-captions.md#caption-details-studio).

**Also in 1.1:** **Set Duration** on a group sets the whole group, the same as dragging its edge. **Esc** deselects. A live show clock in the title bar. **Help** opens this site. Lens effects show on fewer photos by default (**How often** 50%). A calmer default pace.

### **1.0**

**Photos import**, **Outtakes**, and **Auto Trim**. Also a compact export dialog, screensaver export, timeline multi-select, rebuilt Timing and Rotate & Flip menus, video duration on library thumbs, and an update notice in the footer and app menu.
