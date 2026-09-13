# Library

Birthday photos, trip videos, that clip of everyone singing — they land here before they become a movie. Music lives in Inspector → **Audio**.

![Library with photos, transition names, mute badges](../.gitbook/assets/library-photos.png)

When the Library has items, left to right: **calendar** (sort / shuffle), **captions** bubble, **⋯**, and **+** on the trailing edge. An empty Library hides calendar and captions — only **⋯** and **+**.

Drag the **vertical divider** on the right and it **snaps to whole columns** of cards (two and up). Thumbs stay a size that looks like photos — not postage stamps, not billboards. Remembered. **View → Toggle Sidebar** (**⌃⌘S**) hides it. **⌘+** / **⌘-** / **⌘0** (UI text size) also enlarge or shrink Library cards — same factor as Timeline strip height.

## Import

Dump a folder, paste a screenshot, pull from Photos.app, or use the menus.

MemoryString **does not copy** your photos and videos into the show. It keeps **links to the original files** on disk, so the camera roll stays where it is. If you later move or delete an original, that clip looks broken until you point MemoryString at the file again. The exception: a screenshot or other paste with no file behind it — then MemoryString stores its own copy.

- Toolbar or Library **+** → **Photos & Videos…**, or **File → Import Media…**
- **File → Import from Photos…** (also on toolbar **+**, the empty-stage Add pill, and Library **+**) — see [Import from Photos](#import-from-photos)
- Drop folders, photos, or videos onto the window
- **Edit → Paste** (**⌘V**) — Finder files or folders, an image/video from Preview, Photos, Safari, Messages, or a screenshot (**⇧⌘4**). Clipboard images with no file are saved as a copy (Application Support **Imports**). Music files join the soundtrack. A `.memorystring` file **opens**.
- Empty Library: quiet copy **Nothing in library yet** — the preview plate is the drop target (marching ants on that plate only). Hover pulse: **Let the story begin**; a `.memorystring` hover: **The plot thickens**

**Photos:** `.jpg` / `.jpeg` / `.jfif`, `.png`, `.heic` / `.heif`, `.tif` / `.tiff`, `.webp`, `.bmp`, `.gif`  
**Videos:** `.mp4`, `.mov`, `.m4v`, `.avi`, `.mkv`, `.mpg` / `.mpeg`, `.m2v`

Unsupported types are skipped. **⌘C** copies selected Library or Timeline items as files. In a caption or title field, **⌘V** / **⌘C** stay ordinary text paste and copy.

Videos show a play badge and a duration stamp (clock + clip seconds). Multi-select shows a count.

**Essential:** after import, if the Library was empty or already **Oldest First**, MemoryString auto-sorts new stills **Oldest First (Story Order)**. Studio does not. **⌘Z** undoes it.

{% hint style="info" %}
**Keep Best Shots** may ask after import when similar photo groups appear. The sheet asks **Keep the best shot only?** — **Keep Best** (default) or **Keep All**. *The other shots move to Outtakes. Undo with ⌘Z.* Videos are never Keep Best targets. The prompt waits until import fog has cleared. Videos are not auto-trimmed on import — use **Auto Trim** from the context menu or Library **⋯**. Full story: [Auto detection](auto-detection.md#keep-best-shots).
{% endhint %}

![Keep Best import prompt: Keep All or Keep Best](../.gitbook/assets/keep-best-import-prompt.png)

## Import from Photos

Stay in MemoryString. **File → Import from Photos…** (same item on toolbar **+**, the empty-stage Add pill, and Library **+**) opens the **Import from Photos** sheet.

![Toolbar + menu includes Import from Photos…](../.gitbook/assets/toolbar-plus-menu.png)

![File menu: Import from Photos…](../.gitbook/assets/file-menu-import-photos.png)

Categories:

- **Recent** — Last 7 Days / Last 30 Days / Last Year
- **Albums** — your Photos albums (the path for “import this album”)
- **People** — named faces, A–Z. If PhotoKit is empty, **Choose Photos Library…** points at your `.photoslibrary` once so named People & Pets can be listed
- **By Month** — years and months
- **Trips & Events** — Photos events
- **Media Type** — Videos, Panoramas, Screenshots, Live Photos, Bursts

Recent has **Select All** / **Deselect**. Most lists can take a **From** / **To** date filter (**Any dates**, **Apply**, **Clear**). Footer **Import** / **Cancel**. First time: **Access Your Photos**, then **Allow Access**. If access is denied: **Photos Access Required**, then System Settings → Privacy & Security → Photos.

Import uses the same ingest as a Finder drop — Keep Best may ask after the fog lifts; extras go to Outtakes.

Same ingest on every path: **Add / +**, Finder drop (files or a folder), **Photos.app** drag (stills often arrive one remux at a time), and paste. Keep Best, park, and skip count the **whole drop**, not one Photos hop.

While **The story begins…** (first import — percent, then **Cancel** if it is still going) or **The story continues…** (opening a `.memorystring` — no percent) is on the stage, Finder / Photos / project-file **drops are ignored**. Toolbar **+** and File menus still work.

## Cover and show name

The **first** import into a new show (intro still **Memories**) can name it and pick a cover. Full cover rules: [Intro and captions → Show cover and project name](intro-captions.md#show-cover-and-project-name).

- **Photos albums:** Apple’s key photo becomes the cover unless it is already the first or second still on the show. It can be the poster even if it never landed on the timeline. People, Trips & Events, Recent, By Month, and Media Type have no album key photo — those use a middle-of-show still instead (same as a Finder drop).
- **Name:** a Photos album, person, or trip — when you imported just one of them. A folder dropped from Finder, or several files from the same Finder folder — that folder’s name. Folder and Photos names are turned into **Title Case** (`july-trip_photos` → `July Trip Photos`). Generic names — **All Photos**, **Recents**, **Recently Deleted**, **Desktop**, **Downloads**, and the like — are skipped. A name you already set, or an earlier auto-name, is never overwritten.
- **Your pick sticks:** **Choose from Library**, **Choose File…**, drop onto the intro, or **Remove** — after that, automatic cover never runs again, even after **Keep Best Shots**.

## Outtakes

The left column splits into **Takes** (the show) and **Outtakes**, with a hairline seam between them. Drag the seam up to enlarge Outtakes (Takes shrinks), or down for the opposite.

When the bin has at least one item, the **Outtakes** header shows a count (for example **Outtakes, 3**). Outtakes holds shots that are in the project but not on the show — Keep Best extras, or anything you **Move to Outtakes** / drag down from Takes or the filmstrip (a move, not a copy). Empty body: **Nothing discarded.**

Click an outtake to select it (tile ring); the playhead and preview stay on the current movie slide. Drag an outtake up into Takes or the filmstrip to put it on the show; drop onto the intro tile to use it as the intro background (it stays in Outtakes). Right-click → **Move to Takes**, or **Remove from Project** to delete it for real. Calendar sort also sorts Outtakes; Shuffle is show-only.

## Sort (calendar)

Cake after the drive — or shuffle and see:

![Library calendar: Oldest First, Newest First, Import Order, Shuffle](../.gitbook/assets/library-menu-sort.png)

- **Oldest First (Story Order)**
- **Newest First**
- **Import Order**
- **Shuffle** — randomizes photo order (intro stays first)

**Edit → Sort by Date Taken** and Studio **Motion → Timeline → Sort by Date Taken** are the three date/import choices only (no Shuffle). **Shuffle** is on this calendar (and empty-Library right-click). Studio **Motion → Timeline** names the same command **Shuffle Slides** (a separate button, not inside Sort).

Date sorts use camera capture date (EXIF / recording date); file date only if neither exists. Undated files land at the end. Filenames never used. Captions, trims, and rotations stay; groups are planned fresh; intro stays first. **⌘Z** undoes.

## Captions (bubble)

Beats hearing “wait, which trip was that?”

![Library captions: Auto Caption untitled, Auto Caption All, Clear All](../.gitbook/assets/library-menu-captions.png)

- **Auto Caption N Untitled Slide(s)** — fills empty captions only
- **Auto Caption All Slides…** — overwrites after confirmation
- **Clear All Captions…** — confirmed

See [Intro and captions](intro-captions.md#auto-caption).

## ⋯ options

Same photos, different cuts — when motion feels stuck:

![Library ⋯: Keep Best Shots… and Auto Trim Videos…](../.gitbook/assets/library-keep-best-auto-trim-menu.png)

- **Shuffle Transitions** — keeps photo order; re-rolls single-slide cuts, group kinds, and where group windows sit. Card counts stay with the Look / Inspector. If you hand-picked **Slide Transition**s, it asks before clearing them.
- **Reset Slide Durations** — restores default slide timing
- **Keep Best Shots…** — find similar photo groups and keep the best shot in each (videos are never targets; [Auto detection](auto-detection.md#keep-best-shots))
- **Auto Trim Videos…** — best-effort highlight window (not guaranteed; trim by hand if it misses) ([Auto detection](auto-detection.md#auto-trim))
- **Reset Video Durations** — restores every video to its original full-source length
- **Show Transition Names** — badges on Library thumbs

## Reorder and replace

Drag thumbs in the grid. A grouped set keeps **one** champagne plate, even when it wraps onto the next row. Drop a photo onto the group’s **first seat** (the hole at the start of that plate) to **join** the window — not to squeeze in beside it like a stranger at the table. Onto the Timeline **photo lane**: a **gap** inserts or moves; drop on a **single** or a **group seat** until **Replace**; drop on the **intro** tile sets the intro background.

Whole groups move together until you drill into a seat. Full story: [Organizing](organizing.md#drag-to-reorder).

## Right-click a slide

On a **photo or video** in the Library (not empty space):

![Library: Group Transition and Ungroup on a grouped clip](../.gitbook/assets/library-context-ungroup.png)

![Library: Group Transition when several clips are selected](../.gitbook/assets/library-context-group.png)

- **Slide Transition** — pick a single-slide cut, or **Random**
- **Group Transition** — join **two or more** selected singles, or change the look of an existing group (A–Z: Carousel, Filmstrip Horizontal, Filmstrip Vertical, Perspective pair, Photo stack, Ribbon, Scatter & Settle). Illegal counts show *max N* / *min N*
- **Ungroup** — when the clip is in a group
- **Lens Effect** — Studio only; pin pooled effects on that slide or group
- **Rotate & Flip** — **Rotate Clockwise** / **Rotate Counter Clockwise** / **Flip Horizontal** / **Flip Vertical** — 90° / mirrors, project-only, original files untouched. **⌘]** / **⌘[** / **⇧⌘]** / **⇧⌘[**. Same items on the paused [preview](preview.md#rotate-while-paused) (right-click)
- **Set Duration…** (**⌘D**)

![Set Duration… for selected slides](../.gitbook/assets/set-duration.png)
- Videos: **Mute Video Sound** / **Unmute Video Sound**, **Auto Trim**, **Reset Video Duration**
- **Set Caption** — focuses the Inspector clip-bar field
- **Clear Caption** — when the slide already has text. **Auto Caption** is the Library captions bubble, **Edit**, Style → Captions, or **Generate** — not this menu
- **Move to Outtakes** (on a Take) or **Move to Takes** (on an Outtake)
- **Reveal in Finder**
- **Remove from Project** (**⌘⌫**)

The Timeline photo-lane menu is the same idea — see [Timeline](timeline.md#reorder-and-trim).

On the **intro**: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, (Studio) **Lens Effect**, [Reset Center of Interest](preview.md#center-of-interest).

Right-click **empty** Library space: the same sort / shuffle / captions / Shuffle Transitions items as the header menus.

## Select

Click a thumb to select and seek. Right-click a thumb to open its menu and stage that clip on the preview. **⌘**-click toggles; **⇧**-click extends a range. Select in the Timeline and the Library scrolls that tile into view (and the other way around). Playback does not scroll either pane.

### Videos

On import, MemoryString listens to each clip (Essential and Studio): **speech stays audible**; **silence or noise is muted**. Detection is on-device. Skip the speech prompt and mute still uses **loudness only**. How it decides: [Auto detection](auto-detection.md#video-sound-auto-mute).

**Mute Video Sound** / **Unmute Video Sound** — right-click, the speaker badge, or the Inspector footer. Manual mute is yours.

**Auto Trim** — right-click a video (no confirm) or Library **⋯** → **Auto Trim Videos…**. Best-effort highlight window — not guaranteed; trim by hand if it misses. Not on import. Undo with **⌘Z**. Details: [Auto detection](auto-detection.md#auto-trim).

Videos have a **2 second** minimum trim. **Reset Video Duration** restores the full clip (photos and music still say **Reset Length**).

## Multi-photo badges

Grouped cards share one clip. Badges: **carousel 2/5**, **stack 1/5**, **ribbon 5/5**, **pair 1/2**, **filmstrip 3/5**, **scatter 2/5**. Selecting the group draws one champagne outline and dims the rest. Click a member to seek to that photo’s turn on stage. Timeline: click the cell for the whole window; click again to drill into one seat. See [Multi-photo groups](motion/groups.md#timeline-library).

**File → Delete Project…** trashes the `.memorystring` file (if saved) and any snapshot copies the app owned, then opens an empty Untitled project. Originals MemoryString only **linked** to are never deleted.
