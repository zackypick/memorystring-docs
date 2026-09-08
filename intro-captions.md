# Intro and captions

Every movie needs a first frame — whose anniversary — and captions that whisper place and date without stealing the photo. New projects start with **Show Intro Slide** on and the title **Memories**.

![Intro card on the stage](../.gitbook/assets/preview-stage.png)

![Intro Slide, Background, Text, Card & Motion](../.gitbook/assets/inspector-intro-top.png)

The intro is **full-bleed** — not a floating photo card, not Photo Size / Photo Border. Film atmosphere (grain, scratches, vignette, light leak, Glow on Entry) still covers the frame. Intro stays **first**; sort and shuffle leave it. Intro type and slide-caption type are independent.

Intro length follows Energy on its **own** curve — not photo still timing — so the title fade-in always has room: about **7s** at Calm, **6s** at the default, **4s** at Intense. Photo stills are shorter at the top of the slider (see [Looks → Energy](style/looks.md#energy)).

## Show cover and project name

The **cover** is the **poster** for your project — the intro background still and the thumbnail at the front of the Library — **not** the first photo that plays after the title card. Playback always starts on your real first photo or video.

After import, MemoryString can pick a cover and name the show while the intro still says **Memories**.

### How the cover is chosen

1. **Photos albums** — if Apple assigned a key photo, that becomes the cover, even if it never landed on the timeline. People, Trips & Events, Recent, By Month, and Media Type imports have no album key photo, so they skip this step. If that key photo *is* the first or second still on the show, MemoryString skips it (using it as the poster too would just repeat the open) and uses the next step instead.
2. **Otherwise** — a still already **on the show**, never an Outtake, never a video. Prefers the **middle third** of the story, not the first, second, or last slide, and a sharp shot with a face when it can tell. A show with one or two photos reuses what you have.

Same on every import path: **Import from Photos**, Finder drop (files or a folder), **Import Media**, or paste.

**Choose from Library**, **Choose File…**, dragging onto the Inspector **Background** well, right-click **Set Background Image**, or **Remove** always wins from then on. Once you pick or clear the cover yourself, automatic picking never touches it again — including after **Keep Best Shots**. If Keep Best parks an *auto* cover into Outtakes, MemoryString picks another in-show still.

### Project name and intro title

The first import into a new show can name it. MemoryString sets the intro title (also the window title and the suggested **Save As** filename) from:

- A Photos **album**, **person**, or **trip** — its name, when you imported just one of them
- A folder dropped from Finder, or several files from the same Finder folder — that folder’s name

Folder and Photos names are turned into **Title Case** (`july-trip_photos` → `July Trip Photos`). Typed intro text is never rewritten that way.

Generic Photos and Finder names — **All Photos**, **Recents**, **Recently Deleted**, **Desktop**, **Downloads**, and the like — are skipped. Once the show has a real title (yours, or an earlier auto-named import), later imports never rename it.

Export **Save As** also prefers intro title text — see [Format and export](export.md#export-movie).

## Intro Slide (Essential and Studio)

Name the night, or leave the card off.

- **Show Intro Slide** — off removes the opening card
- Text field — select the intro and type here or in the Inspector clip bar. The title wraps onto up to three lines on the card. When you export, MemoryString suggests this title as the movie filename
- Pause and **double-click** the title on the stage to edit. A **single** click sets [center of interest](preview.md#center-of-interest)

Right-click the intro (preview, Timeline, or Library) → **Disable Intro Slide**, **Set Intro Title**, **Set Background Image**. Studio adds **Lens Effect** (one accent or **None**, same list as Intro → Lens).

**Reset Intro to Defaults** turns the card off and restores text, type, frame, motion, lens, decoration, and background to new-project defaults. Does not clear slide captions.

## Background (Essential and Studio)

Soft still behind the title — couple, cake, skyline — without competing.

Click the well, or **Choose…** when empty / **Change…** when a still is already there. Drop a photo/video onto the well, or pick **Choose from Library** / **Choose File…**. **Remove** clears it. The still is centre-cropped to fill; a missing file shows **Missing**. After import, MemoryString may already have chosen a still — see [Show cover and project name](#show-cover-and-project-name). A pick or clear you make here is sticky.

**Studio** extras when a background is set (Essential keeps add / change / remove only):

- **Dim**
- **Start zoom** (100–140%)
- **Slow Zoom** (on by default)
- **Soften** — Off / Soft / Strong
- **Color** — Color / Grayscale

A background still always eases up from the Stage plate. Slow Zoom keeps pushing even when Card Motion is **None**.

## Text (Studio)

Hidden in Essential — type in the Intro Slide field or clip bar; fonts and style live in Studio.

- **Font** — System, Helvetica Neue, Avenir Next, Avenir Next Condensed, Futura, Optima, Georgia, Baskerville, Hoefler Text, Didot, Snell Roundhand (a legacy saved face still appears if the project used it)
- **Color** — color well
- **Auto Size** (on by default) — **Size** is a percentage of frame width (**30%–90%**) when Auto Size is off
- **Align** — Left / Center / Right
- **Outline** — None / Soft / Strong
- **Shadow** — None / Soft

## Card & Motion (Studio)

Frame, enter motion, lens, ornament — for the title, not photo cards.

- **Frame** — None / Line / Corners / Matte (None by default). Line / Corners follow title color; Matte fills with Stage chrome
- **Motion** — None / Fade / Rise / Scale (Fade by default) — title + decoration only
- **Lens** — None, or one accent: Flare, 50mm Prime, Starburst, Veiling Glare, Ghosting, Anamorphic Streaks, Refract Bubbles. A Look deals a default and **re-rolls on every Look click**; the dropdown pins one until the next Look click. **Sparkle** stays off on the intro
- **Decoration** — when on, **Ornament**: Line / Diamond / Floral / Ribbon

A Look chip skins the intro (font, colour, outline, shadow, frame, ornament, enter motion, background treatment, one intro lens). It does **not** turn intro on/off, change title text, or replace a background you chose. Photo Size, border, torn edge, curl, shadow, wind, and backdrop wash stay on **photo** cards.

## Slide captions

Optional. Not added unless you type or use **Auto Caption**. Not the intro title — place · date under a photo.

## Set a caption in the Inspector

Style for the look; Timeline or clip bar for the words.

![Style → Captions: Type & Placement (Font, Align, Motion, Default Placement, Shade Behind Text)](../.gitbook/assets/inspector-captions.png)

In the right-hand **Inspector**, open **Style** → **Captions** → **Type & Placement**. Set project-wide **Font**, color, **Auto Size** / **Size**, **Align**, **Motion**, **Default Placement**, and **Shade Behind Text**. Bulk fill / clear under the same **Captions** heading (**Auto Caption …**, **Clear All Captions…**).

Select a media clip; type in the Inspector clip bar (**Add a caption…**). **Generate** writes one. **Aa** opens position / color / size (**Caption Style…** → Style → Captions). On **stage**, a group still shows the **lead** card’s caption. In Library and Timeline chrome, the speech-bubble badge sits on the **captioned seat** only — siblings and the collapsed group plate do not inherit it. Auto Caption / Set Caption on a seat writes that photo only.

![Timeline: typing a slide caption](../.gitbook/assets/caption-edit.png)

**Position** per slide: Inherit / Bottom / Top / Center, or drag on the preview (**Reset** snaps back). Style knobs above are Studio; Essential types in the clip bar and opens Studio for **Type & Placement**.

Bulk: **Auto Caption N Untitled Slides** (empty only), **Auto Caption All Slides…**, **Clear All Captions…**. Studio also: **Reset Caption Style** (when style changed) and **Reset N Positions** (when slides have dragged positions).

### Auto Caption

Does **not** run on import — you choose when. Fills empty captions on-device: **Place · date** (GPS or IPTC city + capture date; country only when the show spans more than one country) → **capture date** → **readable filename** with real words. Place/date autofill when present. UUID / hash names, camera serials, WhatsApp titles never used — those slides stay blank. Pipeline: [Auto detection](auto-detection.md#auto-caption).

![Library captions: Auto Caption untitled, Auto Caption All, Clear All](../.gitbook/assets/library-menu-captions.png)

- Library captions bubble → **Auto Caption N Untitled Slide(s)**
- **Edit → Auto Caption N Untitled Slides**
- Style → Captions
- Inspector clip-bar **Generate**

**Auto Caption All Slides…** overwrites after confirmation (Library bubble in both modes; Style → Captions in Studio). **Clear All Captions…** wipes every caption.
