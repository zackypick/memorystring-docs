# Format and export

This is where the movie leaves the desk and reaches family, friends, or a feed. Inspector → **Format** sets the aspect you edit in — and the default for Export. Frame rate, quality, resolution, and the save destination live in the **Export Movie** dialog, not here.

![Social and Classic destination swatches, Social Safe](../.gitbook/assets/inspector-format-swatches.png)

Same show, same moment, one photo on stage — each destination frame side by side.

## Social

Tall frames for phones and feeds.

### TikTok

Reels · Shorts · 9:16 (1080×1920)

<figure><img src="../.gitbook/assets/format-tiktok.jpg" alt="Same show exported as TikTok 9:16 (1080×1920)"><figcaption>TikTok · 1080×1920</figcaption></figure>

### Instagram

Feed · 4:5 (1080×1350)

<figure><img src="../.gitbook/assets/format-instagram.jpg" alt="Same show exported as Instagram 4:5 (1080×1350)"><figcaption>Instagram · 1080×1350</figcaption></figure>

### Pinterest

Pin · 2:3 (1000×1500)

<figure><img src="../.gitbook/assets/format-pinterest.jpg" alt="Same show exported as Pinterest 2:3 (1000×1500)"><figcaption>Pinterest · 1000×1500</figcaption></figure>

### YouTube

TV · 16:9 (1920×1080, default)

<figure><img src="../.gitbook/assets/format-youtube.jpg" alt="Same show exported as YouTube 16:9 (1920×1080)"><figcaption>YouTube · 1920×1080</figcaption></figure>

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

![Save As, Format, Resolution, Social Safe, Quality, Frame Rate, Projected size](../.gitbook/assets/export-dialog.png)

- **Save As** — filename; **Browse…** for the folder. Default name prefers title text, then the project name, then **Untitled Memory**. The file is `.mp4`.
- **Format** — destination swatches for **this encode** (does not change the live preview)
- **Resolution** — **1080p** (default) or **4K**. 4K takes much longer — around three times the length of the show. **Cinema (21:9)** does not offer 4K — that format stays at 1080p because of the aspect, not the Mac.
- **Social Safe**
- **Quality** — a slider with four stops: **Email**, **Share**, **Screen**, **Master**. **Share** is the default. The stop sets the encoder bit rate — smallest file at Email, master copy at Master. Same control in Essential and Studio; Studio also shows the target rate in Mbps.
- **Frame Rate** — **30** (smaller/faster) or **60** (smoother motion)

The footer shows a **projected size** and duration for the current choices. It tracks what the finished MP4 will weigh — same bit rate the encoder is handed, not a rough guess.

Click **Export** and wait. Toolbar shows **Creating memory…** and a percent. Editing pauses (*Edits paused while creating memory*). If music is still decoding, Export waits.

You get an H.264 MP4; the `.memorystring` project stays editable. Preview with **Space** (and Studio **Warm Now** if you want the baked pass) before you export — the file matches that show, not the workbench ambilight.

## Before you export

- Preview with **Space** and scrub for timing issues.
- Confirm music rights for imported audio.
- Check the Export dialog’s format matches where you will post.
- **⌘S** so the project is saved alongside the MP4.
