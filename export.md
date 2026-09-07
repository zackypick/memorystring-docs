---
description: "Format and export a MemoryString slideshow as H.264 MP4 on your Mac — Social and Classic frames, Social Safe, 1080p or 4K."
---

# Format and export

This is where the movie leaves the desk and reaches family, friends, or a feed. Inspector → **Format** sets the aspect you edit in — and the default for Export. Frame rate, quality, and resolution live in the **Export Movie** dialog, not here.

![Social and Classic destination swatches, Social Safe](../.gitbook/assets/inspector-format-swatches.png)

Same show, same moment, one photo on stage — each destination frame side by side.

## Social

Tall frames for phones and feeds. Swatch order: **Instagram · TikTok · Pinterest · YouTube**. Destination name is 12pt; the caption under it is 9pt.

### Instagram

Feed · 4:5 (1080×1350)

![Same show exported as Instagram 4:5 (1080×1350)](../.gitbook/assets/format-instagram.jpg)

### TikTok

Reels · Shorts · 9:16 (1080×1920)

![Same show exported as TikTok 9:16 (1080×1920)](../.gitbook/assets/format-tiktok.jpg)

### Pinterest

Pin · 2:3 (1000×1500)

![Same show exported as Pinterest 2:3 (1000×1500)](../.gitbook/assets/format-pinterest.jpg)

### YouTube

TV · 16:9 (1920×1080, default)

![Same show exported as YouTube 16:9 (1920×1080)](../.gitbook/assets/format-youtube.jpg)

## Classic

Wider stages — TV, photo print, square post, cinema ribbon.

### Classic

4:3 (1440×1080)

<figure><img src="../.gitbook/assets/format-classic.jpg" alt="Same show exported as Classic 4:3 (1440×1080)"><figcaption>Classic · 1440×1080</figcaption></figure>

### Photo

3:2 (1620×1080)

<figure><img src="../.gitbook/assets/format-photo.jpg" alt="Same show exported as Photo 3:2 (1620×1080)"><figcaption>Photo · 1620×1080</figcaption></figure>

### Square

Post · 1:1 (1080×1080)

<figure><img src="../.gitbook/assets/format-square.jpg" alt="Same show exported as Square 1:1 (1080×1080)"><figcaption>Square · 1080×1080</figcaption></figure>

### Cinema

21:9 (2560×1080)

<figure><img src="../.gitbook/assets/format-cinema.jpg" alt="Same show exported as Cinema 21:9 (2560×1080)"><figcaption>Cinema · 2560×1080</figcaption></figure>

## Social Safe

An **export mode**, not a Look — same toggle in two places, on purpose. Built for tall frames that hate letterbox bars.

**Format tab** (Inspector → **Format**) is the live one. Turn Social Safe on here so the **preview** shows the safe frame while you edit: photos, captions, and mats sit inside the crop *before* you encode.

<figure><img src="../.gitbook/assets/inspector-format-social-safe.png" alt="Format tab: Social Safe checkbox so the preview matches the share crop"><figcaption>Social Safe — Format inspector (live preview)</figcaption></figure>

**Export Movie** is for **this file**. The dialog’s Format swatches and Social Safe apply to that encode only — they do **not** change the live preview. Compose in YouTube 16:9 on the Format tab, then export a TikTok 9:16 with Social Safe without switching the whole workbench. Frame rate, quality, and resolution live only in Export.

<figure><img src="../.gitbook/assets/export-social-safe.png" alt="Export Movie: Social Safe keeps photos and captions inside the frame"><figcaption>Social Safe — Export Movie dialog (this encode)</figcaption></figure>

Turn it on to fill tall frames with soft stage wash, keep mats and effects, and clamp Photo Size to about **85–98%**.

It turns **on** automatically for **9:16**, **4:5**, and **2:3**. It stays **off** for Square, 16:9, and the other Classic frames. You can still toggle it by hand.

## Export Movie

Toolbar **Export** or **File → Export Movie…** (**⌘E**).

![Save As, Format, Social Safe, Quality, Frame Rate](../.gitbook/assets/export-dialog.png)

- **Save As** — filename; folder chip (click to choose a folder). Default name prefers title text, then the project name, then **Untitled Memory**. The file is `.mp4`.
- **Format** — destination swatches for **this encode** (does not change the live preview)
- **Resolution** — **1080p** (default) or **4K**. 4K takes much longer — around three times the length of the show. **Cinema (21:9)** does not offer 4K — that format stays at 1080p because of the aspect, not the Mac. Rarely, when other apps leave too little free memory, 4K declines to start and asks you to close some apps or use 1080p. If memory tightens mid-export, the encode slows rather than failing.
- **Social Safe** — same mode as the Format tab
- **Quality** — slider stops **Compact**, **Share**, **High**, **Best** (**Share** is the default). Available in Essential and Studio; Studio also shows the target rate in Mbps.
- **Frame Rate** — **30** (smaller/faster) or **60** (smoother motion)
- **Screensaver** — see below

Check the footer **projected size** (and duration) for the current choices. Click **Export** and wait. Toolbar shows **Creating memory…** and a percent. Editing pauses (*Edits paused while creating memory*). If music is still decoding, Export waits.

You get an H.264 MP4; the `.memorystring` project stays editable. Preview with **Space** (and Studio **Warm Now** if you want the baked pass) before you export — the file matches that show.

## Screensaver

Check **Screensaver** at the bottom of Export Movie when the file is meant to loop on a Mac display — not a share movie.

- **No audio** — soundtrack and clip sound are omitted
- **Skips intro** — the opening title card is not painted
- **Fades to the stage** — first real slide fades in from Stage color; last slide fades out to Stage color (Dark or Light). No branded end hold
- Needs at least one photo or video (*Add at least one slide before exporting a screensaver*)
- Per-show — saved on this project. Turning it on seeds **1080p / 30 / Share**; you can still change those

After export: *Drop the file into System Settings → Wallpaper → add folder to use as a screensaver.*

## The MemoryString credit

Every movie (except a Screensaver export) eases to the stage floor before the end hold (black on Dark, cream on Light). A subtle bottom-right **Created with MemoryString** mark — name + logo — fades in once during the tail of the last photo and stays through the end floor (about three seconds). On **Light** stage the credit uses the logo’s **bronze** brown.

There is no toggle to turn it off. MemoryString is free — days, nights, weekends — and the credit is how the app reaches more families. If you want a loop with no end card, use **Screensaver**.

## Before you export

- Preview with **Space** and scrub for timing issues.
- Confirm music rights for imported audio.
- Check the Export dialog’s format matches where you will post.
- **⌘S** so the project is saved alongside the MP4.
