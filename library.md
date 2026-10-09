# Library

Photos and videos for your movie appear in the **Library** on the left. Music is in Inspector → **Audio**, not here.

![Library with photos, transition names, mute badges](../.gitbook/assets/library-photos.png)

When the **Library** has items, the header has **calendar** (sort / shuffle), **captions** bubble, **⋯**, and **+**. When empty, only **⋯** and **+** show.

Drag the right **divider** to resize. It snaps to whole columns. **View → Toggle Sidebar** (**⌃⌘S**) hides the sidebar. **⌘+** / **⌘-** / **⌘0** change UI text size for **Library** cards (same as **Timeline** strip height).

## Import

Use menus, drag-and-drop, paste, or **Import from Photos…**.

Folder and Finder imports stay **linked** to originals. If you move or delete an original, the clip breaks until you relink.

**Photos.app** media is **copied** to Application Support **Imports** because Photos does not allow stable links. Pasted images with no file are copied the same way.

- Toolbar or **Library** **+** → **Photos & Videos…**, or **File → Import Media…**
- **File → Import from Photos…** — see [Import from Photos](#import-from-photos)
- Drop folders, photos, or videos on the window
- **Edit → Paste** (**⌘V**) — files, folders, images from other apps, or screenshots. A `.memorystring` file **opens** when pasted.
- Empty **Library**: **Nothing in library yet**. Preview accepts drops. Hover: **Gather the thread** for media; **Bring back memories** for a project file.

**Photos:** `.jpg` / `.jpeg` / `.jfif`, `.png`, `.heic` / `.heif`, `.tif` / `.tiff`, `.webp`, `.bmp`, `.gif`  
**Videos:** `.mp4`, `.mov`, `.m4v`, `.avi`, `.mkv`, `.mpg` / `.mpeg`, `.m2v`

Unsupported types are skipped. **⌘C** copies selected items as files. In a caption or title field, **⌘V** / **⌘C** are plain text.

Videos show a play badge and duration. Multi-select shows a count.

**Essential:** after import, if the **Library** was empty or already **Oldest First**, new stills auto-sort **Oldest First (Story Order)**. **Studio** does not. **⌘Z** undoes.

{% hint style="info" %}
**Keep Best Shots** may ask after import when similar groups appear. **Keep Best** (default) or **Keep All**. Extras go to **Outtakes**. Undo **⌘Z**. Videos are not Keep Best targets. Prompt waits until import loader clears. Videos are not auto-trimmed on import — use **Auto Trim** from menu or **Library** **⋯**. See [Auto detection](auto-detection.md#keep-best-shots).
{% endhint %}

![Keep Best import prompt: Keep All or Keep Best](../.gitbook/assets/keep-best-import-prompt.png)

{% hint style="info" %}
An import that would put more than **150** photos and videos on the show asks first: **Long story short**, **Import all**, or **Cancel**. See [Long story short](long-story-short.md#large-imports).
{% endhint %}

## Import from Photos

**File → Import from Photos…** (also toolbar **+**, empty-stage Add, **Library** **+**).

![Toolbar + menu includes Import from Photos…](../.gitbook/assets/toolbar-plus-menu.png)

![File menu: Import from Photos…](../.gitbook/assets/file-menu-import-photos.png)

![Import from Photos — Recent, Albums, People, By Month, Trips & Events, Media Type](../.gitbook/assets/photos-import-hub.png)

Categories:

- **Recent** — Last 7 Days / Last 30 Days / Last Year
- **Albums**
- **People** — A–Z. If empty, **Choose Photos Library…** once
- **By Month**
- **Trips & Events**
- **Media Type** — Videos, Panoramas, Screenshots, Live Photos, Bursts

![Recent — Last 30 Days, Select All / Deselect, ready to import](../.gitbook/assets/photos-import-recent.png)

![Albums — pick one or more, then Import](../.gitbook/assets/photos-import-albums.png)

![People — named faces, A–Z](../.gitbook/assets/photos-import-people.png)

![Date filter open — From / To, Apply, Clear](../.gitbook/assets/photos-import-dates.png)

![By Month — years and months](../.gitbook/assets/photos-import-by-month.png)

![Trips & Events — Photos events, or empty if none](../.gitbook/assets/photos-import-trips.png)

![Media Type — Videos, Panoramas, Screenshots, Live Photos, Bursts](../.gitbook/assets/photos-import-media-type.png)

**Select All** / **Deselect** on Recent. **From** / **To** date filter on most lists. Footer **Import** / **Cancel**.

First time, macOS asks for Photos access. Allow both prompts.

![Photo Library — Allow Access to All Photos](../.gitbook/assets/photos-permission-library.png)

![Photos automation — Allow so album counts and covers can load](../.gitbook/assets/photos-permission-automation.png)

If **Allow “MemoryString” to find devices on local networks?** appears, **Allow** is fine. The show does not browse your LAN.

![Local Network — Allow if it appears](../.gitbook/assets/photos-permission-local-network.png)

If denied: **Photos Access Required**, then System Settings → Privacy & Security → Photos.

Photos imports are **copied** to Application Support **Imports**. Finder folder drops stay linked.

Same rules on every path: **+**, Finder drop, Photos.app drag (often one file at a time), paste. **Keep Best** counts the **whole drop**.

While loader runs — **Stringing it together...** (percent, **Cancel**) or **It's coming back now...** (open project, no percent) — drops are ignored. Toolbar **+** and File menus still work. Loader is a spinner with smoke animation.

## Cover and show name

First import into a new show (intro title **Memories**) can set project name and cover poster. Rules: [Intro and captions → Show cover and project name](intro-captions.md#show-cover-and-project-name).

- **Photos albums:** Apple key photo may become cover unless it is already first or second on the show.
- **Name:** single album, person, or trip import; or folder name from **Add Folder** / Finder folder drop. Title Case applied. Generic names skipped.
- Manual **Choose from Library**, **Choose File…**, intro drop, or **Remove** stops automatic cover forever.

## Outtakes

**Takes** (the show) and **Outtakes** split the left column. Drag the seam to resize **Outtakes**.

![Outtakes bin with three photos](../.gitbook/assets/library-outtakes.png)

Header shows count when not empty. **Outtakes** holds shots in the project but not on the show — from **Keep Best**, [Long story short](long-story-short.md), or **Move to Outtakes**. On a group, **Move to Outtakes** moves one seat; **Entire group ▸** moves all. Empty: **Nothing discarded.**

Click selects; preview stays on current slide. Drag up to return to show. Drop on intro sets intro background. Right-click **Move to Takes** or **Remove from Project**. Calendar sort sorts **Outtakes** too. **Shuffle** is show-only.

![Outtake menu: Move to Takes, Remove from Project](../.gitbook/assets/library-outtakes-menu.png)

## Sort (calendar)

![Library calendar: Oldest First, Newest First, Import Order, Shuffle](../.gitbook/assets/library-menu-sort.png)

- **Oldest First (Story Order)**
- **Newest First**
- **Import Order**
- **Shuffle**

**Edit → Sort by Date Taken** and **Motion → Timeline → Sort by Date Taken** offer three date/import choices (no Shuffle). **Studio** **Motion → Timeline** has **Shuffle Slides**.

Capture date from EXIF; file date if missing. Undated at end. Intro stays first. **⌘Z** undoes.

## Captions (bubble)

![Library captions: Auto Caption untitled, Auto Caption All, Clear All](../.gitbook/assets/library-menu-captions.png)

- **Auto Caption N Untitled Slide(s)**
- **Auto Caption All Slides…**
- **Clear All Captions…**

See [Intro and captions](intro-captions.md#auto-caption).

## ⋯ options

![Library ⋯: Long story short, Show, Videos, Import](../.gitbook/assets/library-options-menu.png)

- **Long story short** — see [Long story short](long-story-short.md)
- **Show** — **Shuffle Transitions**, **Reset Slide Durations**, **Keep Best Shots…**
- **Videos** — **Auto Trim Videos…**, **Reset Video Durations**
- **Import** — **Import from Photos…**
- **Show Transition Names**

## Reorder and replace

Drag thumbs. Drop on a group’s **first seat** to **join**. On **Timeline**: gap = insert; slide or group seat = **Replace**; intro = background.

Whole groups move together until you select one seat. See [Organizing](organizing.md#drag-to-reorder).

## Right-click a slide

On a photo or video (not empty space):

![Grouped seat menu: Photo 1 of 5 · Ribbon, Entire group, Ungroup](../.gitbook/assets/library-context-ungroup.png)

- **Slide Transition** or **Random**
- **Group Transition** — two or more singles, or change group type
- **Ungroup**
- **Lens Effect** — Studio only
- **Rotate & Flip**
- **Set Duration…** (**⌘D**)

![Set Duration… for selected slides](../.gitbook/assets/set-duration.png)

- Videos: mute, **Auto Trim**, **Reset Video Duration**
- **Set Caption** (**⇧⌘C**), **Clear Caption**
- **Move to Outtakes** / **Move to Takes**
- **Remove from Project** (**⌘⌫**)

Grouped seat: menu for **that photo** first. **Entire group ▸** for all seats. **Ungroup** nearby.

On a group, **Set Duration…** sets the length of the **whole group**, the same as dragging its edge on the **Timeline**. It works from any seat, and from the Inspector length field.

![Entire group ▸: Rotate & Flip, Set Duration…, Move N to Outtakes, Remove N](../.gitbook/assets/library-entire-group-menu.png)

Intro: **Set Intro Title**, **Set Background Image**, **Disable Intro Slide**, (Studio) **Lens Effect**, [Reset Center of Interest](preview.md#center-of-interest).

Right-click **empty** **Library**: same sort / shuffle / captions / **Shuffle Transitions** as header menus.

## Select

Click selects and seeks. Right-click opens menu and stages clip on preview. **⌘**-click toggles; **⇧**-click range. **Esc** deselects. **Library** and **Timeline** selection stay in sync.

### Videos

On import: speech stays; silence or noise may mute. On-device. Skip speech prompt → loudness only. [Auto detection](auto-detection.md#video-sound-auto-mute).

**Mute Video Sound** / **Unmute Video Sound** — right-click, badge, or Inspector.

**Auto Trim** — right-click or **Library** **⋯**. Not on import. ~4s middle, ~70% success. **2 second** minimum trim. **Reset Video Duration** restores full clip.

## Multi-photo badges

Badges like **carousel 2/5**, **stack 1/5**. Group select shows one outline. Click member to seek that seat. **Timeline**: click cell for whole group; click again for one seat. See [Multi-photo groups](motion/groups.md#timeline-library).

**File → Delete Project…** trashes the `.memorystring` and app-owned copies. Linked originals on disk are not deleted.
