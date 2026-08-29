# Intro and captions

Every movie needs a first frame — whose anniversary — and captions that whisper place and date without stealing the photo. New projects start with **Show Intro Slide** on and the title **Memories**.

![Intro card on the stage](../.gitbook/assets/preview-stage.png)

![Intro Slide, Background, Text, Card & Motion](../.gitbook/assets/inspector-intro-top.png)

The intro is **full-bleed** — not a floating photo card, not Photo Size / Photo Border. Film atmosphere (grain, scratches, vignette, light leak, Glow on Entry) still covers the frame. Intro stays **first**; sort and shuffle leave it. Intro type and slide-caption type are independent.

## Intro Slide (Essential and Studio)

Name the night, or leave the card off.

- **Show Intro Slide** — off removes the opening card
- Text field — select the intro and type here or in the Inspector clip bar. The title wraps onto up to three lines on the card. When you export, MemoryString suggests this title as the movie filename
- Pause and **double-click** the title on the stage to edit. A **single** click sets [center of interest](preview.md#center-of-interest)

Right-click the intro (preview, Timeline, or Library) → **Disable Intro Slide**, **Set Intro Title**, **Set Background Image**. Studio adds **Lens Effect** (one accent or **None**, same list as Intro → Lens).

**Reset Intro to Defaults** turns the card off and restores text, type, frame, motion, lens, decoration, and background to new-project defaults. Does not clear slide captions.

## Background (Essential and Studio)

Soft still behind the title — couple, cake, skyline — without competing.

Click the well or **Choose…**, or drop a photo/video onto the well (**Choose from Library** / **Choose File…**). **Remove** clears it. The still is centre-cropped to fill; a missing file shows **Missing**.

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

Optional. Not added unless you type or use **Auto Caption**. Not the intro title — “Tel Aviv · July” under a photo.

## Set a caption in the Inspector

Style for the look; Timeline or clip bar for the words.

![Style → Captions: Type & Placement (Font, Align, Motion, Default Placement, Shade Behind Text)](../.gitbook/assets/inspector-captions.png)

In the right-hand **Inspector**, open **Style** → **Captions** → **Type & Placement**. Set project-wide **Font**, color, **Auto Size** / **Size**, **Align**, **Motion**, **Default Placement**, and **Shade Behind Text**. Bulk fill / clear under the same **Captions** heading (**Auto Caption …**, **Clear All Captions…**).

Select a media clip; type in the Timeline caption field or Inspector clip bar (**Add a caption…**). **Generate** writes one. **Aa** opens position / color / size (**Caption Style…** → Style → Captions). A group’s caption belongs to its **lead** card.

![Timeline: typing a slide caption](../.gitbook/assets/caption-edit.png)

**Position** per slide: Inherit / Bottom / Top / Center, or drag on the preview (**Reset** snaps back). Style knobs above are Studio; Essential types in the clip bar and opens Studio for **Type & Placement**.

Bulk: **Auto Caption N Untitled Slides** (empty only), **Auto Caption All Slides…**, **Clear All Captions…**. Studio also: **Reset Caption Style** (when style changed) and **Reset N Positions** (when slides have dragged positions).

### Auto Caption

Does **not** run on import — you choose when. Fills empty captions on-device: **Place · date** (GPS or IPTC city + capture date; country only when the show spans more than one country) → **capture date** → **readable filename** with real words. Place/date autofill when present. UUID / hash names, camera serials, WhatsApp titles never used — those slides stay blank. Pipeline: [Auto detection](auto-detection.md#auto-caption).

![Library captions: Auto Caption untitled, Auto Caption All, Clear All](../.gitbook/assets/library-menu-captions.png)

- Library captions bubble → **Auto Caption N Untitled Slide(s)**
- **Edit → Auto Caption N Untitled Slides**
- Style → Captions
- Timeline / clip-bar **Generate**

**Auto Caption All Slides…** overwrites after confirmation (Library bubble in both modes; Style → Captions in Studio). **Clear All Captions…** wipes every caption.
