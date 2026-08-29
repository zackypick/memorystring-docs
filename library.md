# Library

The left sidebar is this project’s photos and videos. Music is in Inspector → **Audio**, not here.

![Library header: sort, captions, options, add](../.gitbook/assets/library-header.png)

Left to right when the Library has items: **calendar** (sort), **captions** bubble, **⋯**, and **+** on the trailing edge.

## Import

- Toolbar or Library **+** → **Photos & Videos…**, or **File → Import Media…**
- Drop folders, photos, or videos onto the window
- **Edit → Paste** (**⌘V**) — Finder files, or an image/video copied from Preview, Photos, Safari, Messages, or a screenshot. Clipboard images with no file are saved under Application Support **Imports**.
- Empty Library: dashed target — *Drop photos & videos here*

**⌘C** copies selected Library or Timeline items out as files. While you type in a caption or title field, **⌘V** / **⌘C** stay ordinary text paste and copy.

Videos show a play badge. Multi-select shows a count.

## Sort (calendar)

- **Oldest First (Story Order)**
- **Newest First**
- **Import Order**

Same items: **Edit → Sort by Date Taken**, Inspector → **Motion** → **Timeline**, or right-click empty Library space.

Date sorts use the camera capture date (EXIF / recording date). Files with no date land at the end. Filenames are never used for date sorting. The intro stays first. **⌘Z** undoes a sort.

## Captions (bubble)

- **Auto Caption N Untitled Slide(s)** — fills empty captions only
- **Auto Caption All Slides…** — overwrites after confirmation
- **Clear All Captions…** — confirmed

See [Intro and captions](intro-captions.md).

## ⋯ options

- **Shuffle Slides** — randomizes photo order (intro stays first)
- **Shuffle Transitions** — keeps photo order; re-rolls single-slide cuts, group kinds, and where group windows sit. Card counts stay with the Look / Inspector.
- **Reset Slide Durations** — restores default slide timing
- **Show Transition Names** — badges on Library thumbs

## Select, rotate, remove

- Click a thumb to select and seek. **⌘**-click toggles; **⇧**-click extends a range.
- Right-click → **Rotate Right** / **Rotate Left** (90°, project-only) or **Flip Horizontal** / **Flip Vertical**. Original files are never rewritten. **⌘]** / **⌘[** and **⇧⌘]** / **⇧⌘[** from the Edit menu.
- **Remove from Project** or **Edit → Delete** (**⌘⌫**). Originals outside MemoryString’s **Imports** folder are never deleted.
- **File → Delete Project…** trashes the `.memorystring` file (if saved) and that project’s Imports copies, then opens an empty Untitled project.

### Videos

On import, speech keeps clip audio; silence or noise is muted. Right-click **Mute Video Sound** / **Unmute Video Sound**. Videos have a **2 second** minimum trim. **Reset Length** restores the full clip.

## Multi-photo badges

Members of a group are one clip. Library badges look like **carousel 2/5**, **stack 1/5**, **ribbon 5/5**, **pair 1/2**, **filmstrip 3/5**. Selecting the group draws one champagne outline around the thumbs. Clicking a member seeks to that photo’s turn on stage. See [Multi-photo groups](motion/groups.md).
