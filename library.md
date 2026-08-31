# Library

Birthday photos, trip videos, that clip of everyone singing — they land here before they become a movie. Music lives in Inspector → **Audio**.

![Library with photos, transition names, mute badges](../.gitbook/assets/library-photos.png)

When the Library has items, left to right: **calendar** (sort / shuffle), **captions** bubble, **⋯**, and **+** on the trailing edge. An empty Library hides calendar and captions — only **⋯** and **+**.

Drag the **vertical divider** on the right to resize (remembered). **View → Toggle Sidebar** (**⌃⌘S**) hides it. **⌘+** / **⌘-** / **⌘0** (UI text size) also enlarge or shrink Library cards — same factor as Timeline strip height.

## Import

Dump a folder, paste a screenshot, or use the menus:

- Toolbar or Library **+** → **Photos & Videos…**, or **File → Import Media…**
- Drop folders, photos, or videos onto the window
- **Edit → Paste** (**⌘V**) — Finder files or folders, an image/video from Preview, Photos, Safari, Messages, or a screenshot (**⇧⌘4**). Clipboard images with no file are saved under Application Support **Imports**. Music files join the soundtrack. A `.memorystring` file **opens**.
- Empty Library: dashed target — *Drop photos & videos here*

**Photos:** `.jpg` / `.jpeg` / `.jfif`, `.png`, `.heic` / `.heif`, `.tif` / `.tiff`, `.webp`, `.bmp`, `.gif`  
**Videos:** `.mp4`, `.mov`, `.m4v`, `.avi`, `.mkv`, `.mpg` / `.mpeg`, `.m2v`

Unsupported types are skipped. **⌘C** copies selected Library or Timeline items as files. In a caption or title field, **⌘V** / **⌘C** stay ordinary text paste and copy.

Videos show a play badge. Multi-select shows a count.

**Essential:** after import, if the Library was empty or already **Oldest First**, MemoryString auto-sorts new stills **Oldest First (Story Order)**. Studio does not. **⌘Z** undoes it.

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

![Library ⋯: Shuffle Transitions, Reset Slide Durations, Show Transition Names](../.gitbook/assets/library-menu-options.png)

- **Shuffle Transitions** — keeps photo order; re-rolls single-slide cuts, group kinds, and where group windows sit. Card counts stay with the Look / Inspector. If you hand-picked **Slide Transition**s, it asks before clearing them.
- **Reset Slide Durations** — restores default slide timing
- **Show Transition Names** — badges on Library thumbs

## Reorder and replace

Drag thumbs in the grid. Onto the Timeline **photo lane**: a **gap** inserts or moves; drop on a **single** or a **group seat** until **Replace**; drop on the **intro** tile sets the intro background.

Whole groups move together until you drill into a seat. Full story: [Organizing](organizing.md#drag-to-reorder).

## Right-click a slide

On a **photo or video** in the Library (not empty space):

![Library: Change Transition and Ungroup on a grouped clip](../.gitbook/assets/library-context-ungroup.png)

![Library: Group Transition when several clips are selected](../.gitbook/assets/library-context-group.png)

- **Slide Transition** — pick a single-slide cut, or **Random**
- **Change Transition** — when the clip is already in a group
- **Group Transition** — when **two or more** media clips are selected (A–Z: Carousel, Filmstrip Horizontal, Filmstrip Vertical, Perspective pair, Photo stack, Ribbon, Scatter & Settle). Illegal counts show *max N* / *min N*
- **Ungroup** — when the clip is in a group
- **Lens Effect** — Studio only; pin pooled effects on that slide or group
- **Rotate Right** / **Rotate Left** / **Flip Horizontal** / **Flip Vertical** — 90° / mirrors, project-only, original files untouched. **⌘]** / **⌘[** / **⇧⌘]** / **⇧⌘[**. Same items on the paused [preview](preview.md#rotate-while-paused) (right-click)
- **Set Duration…** (**⌘D**)

![Set Duration… for selected slides](../.gitbook/assets/set-duration.png)
- Videos: **Mute Video Sound** / **Unmute Video Sound**, **Reset Length**
- **Auto Caption** or **Clear Caption**
- **Remove from Project** (**⌘⌫**)

The Timeline photo-lane menu is the same idea — see [Timeline](timeline.md#reorder-and-trim).

On the **intro**: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, (Studio) **Lens Effect**, [Reset Center of Interest](preview.md#center-of-interest).

Right-click **empty** Library space: the same sort / shuffle / captions / Shuffle Transitions items as the header menus.

## Select

Click a thumb to select and seek. **⌘**-click toggles; **⇧**-click extends a range. Select in the Timeline and the Library scrolls that tile into view (and the other way around). Playback does not scroll either pane.

### Videos

On import, MemoryString listens to each clip (Essential and Studio): **speech stays audible**; **silence or noise is muted**. Detection is on-device. Skip the speech prompt and mute still uses **loudness only**. How it decides: [Auto detection](auto-detection.md#video-sound-auto-mute).

**Mute Video Sound** / **Unmute Video Sound** — right-click, the speaker badge, or the Inspector footer. Manual mute is yours.

Videos have a **2 second** minimum trim. **Reset Length** restores the full clip.

## Multi-photo badges

Grouped cards share one clip. Badges: **carousel 2/5**, **stack 1/5**, **ribbon 5/5**, **pair 1/2**, **filmstrip 3/5**, **scatter 2/5**. Selecting the group draws one champagne outline and dims the rest. Click a member to seek to that photo’s turn on stage. Timeline: click the cell for the whole window; click again to drill into one seat. See [Multi-photo groups](motion/groups.md#timeline-library).

**File → Delete Project…** trashes the `.memorystring` file (if saved) and that project’s Imports copies, then opens an empty Untitled project. Originals outside **Imports** are never deleted.
