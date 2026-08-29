# Format and export

Inspector → **Format** sets the aspect you edit in (and the default for Export). Frame rate and quality are in the **Export Movie** dialog, not this tab.

![Social and Classic destination swatches, Social Safe](../.gitbook/assets/inspector-format-swatches.png)

## Preview format

**Social**

| Swatch | Caption |
| --- | --- |
| **TikTok** | Reels · Shorts · 9:16 (1080×1920) |
| **Instagram** | Feed · 4:5 (1080×1350) |
| **Pinterest** | Pin · 2:3 |
| **YouTube** | TV · 16:9 (1920×1080, default) |

**Classic**

| Swatch | Caption |
| --- | --- |
| **Classic** | 4:3 (1440×1080) |
| **Photo** | 3:2 (1620×1080) |
| **Square** | Post · 1:1 (1080×1080) |
| **Cinema** | 21:9 (2560×1080) |

Every movie eases to the stage floor (black on Dark, cream on Light). There is no toggle for that fade.

## Social Safe

An **export mode**, not a Look. Same toggle on Format and in the Export dialog.

Turn it on to fill tall frames with soft stage wash (no letterbox bars), keep mats and effects, and clamp Photo Size to about **85–98%**.

It turns **on** automatically for **9:16**, **4:5**, and **2:3**. It stays **off** for Square, 16:9, and the other Classic frames. You can still toggle it by hand.

The **Created with MemoryString** end credit always shows.

## Export Movie

Toolbar **Export** or **File → Export Movie…** (**⌘E**).

![Save As, Format, Social Safe, Quality, Frame Rate](../.gitbook/assets/export-dialog.png)

- **Save As** — filename; **Browse…** for the folder. Default name prefers title text, then the project name, then **Untitled Memory**. The file is `.mp4`.
- **Format** — destination swatches for **this encode** (does not change the live preview)
- **Social Safe**
- **Quality** — Studio: Low / Medium / High / Maximum
- **Frame Rate** — **30** (smaller/faster) or **60** (smoother motion)

Click **Export** and wait. The toolbar shows **Creating memory…** and a percent. Editing is paused (*Edits paused while creating memory*). If music is still decoding, Export waits.

You get an H.264 MP4. The `.memorystring` project stays editable. Preview with **Space** (and Studio **Warm Now** if you want the baked pass) before you export — the file matches that show, not the workbench ambilight.
