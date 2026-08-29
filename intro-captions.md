# Intro and captions

The **Intro** tab is the opening **title card**, then (separately) captions on media slides. New projects start with **Show Intro Slide** on and the title **Memories**.

![Intro card on the stage](../.gitbook/assets/preview-stage.png)

![Intro Slide, Background, Text, Card & Motion](../.gitbook/assets/inspector-intro-top.png)

The intro is **full-bleed** — not a floating photo card, and not Photo Size / Photo Border. Film atmosphere (grain, scratches, vignette, light leak, Glow on Entry) still covers the frame. The intro stays **first**; sort and shuffle do not move it. Intro type and slide-caption type are independent.

## Intro Slide (Essential and Studio)

- **Show Intro Slide** — off removes the opening card
- Text field — up to three lines (export naming can use this text). Select the intro and type here or in the Inspector clip bar
- Pause and **double-click** the title on the stage to edit. A **single** click sets [center of interest](preview.md)

Right-click the intro (preview, Timeline, or Library) → **Disable Intro Slide**, **Set Intro Title**, **Set Background Image**. Studio adds **Lens Effect** (one accent or **None**, same list as Intro → Lens).

**Reset Intro to Defaults** turns the card off and restores text, type, frame, motion, lens, decoration, and background to new-project defaults. It does not clear slide captions.

## Background (Essential and Studio)

Click the well or **Choose…**, or drop a photo/video onto the well (**Choose from Library** / **Choose File…**). **Remove** clears it. The still is centre-cropped to fill; a missing file shows **Missing**.

**Studio** extras when a background is set (Essential keeps add / change / remove only):

- **Dim**
- **Start zoom** (100–140%)
- **Slow Zoom** (on by default)
- **Soften** — Off / Soft / Strong
- **Color** — Color / Grayscale

A background still always eases up from the Stage plate. Slow Zoom keeps pushing even when Card Motion is **None**.

## Text (Studio)

Hidden in Essential — type in the Intro Slide field or the clip bar; font and style knobs are in Studio.

- **Font** — System, Helvetica Neue, Avenir Next, Avenir Next Condensed, Futura, Optima, Georgia, Baskerville, Hoefler Text, Didot, Snell Roundhand (a legacy saved face still appears if the project used it)
- **Color** — color well
- **Auto Size** (on by default) — **Size** is a percentage of frame width (**30%–90%**) when Auto Size is off
- **Align** — Left / Center / Right
- **Outline** — None / Soft / Strong
- **Shadow** — None / Soft

## Card & Motion (Studio)

- **Frame** — None / Line / Corners / Matte (None by default). Line / Corners follow title color; Matte fills with Stage chrome
- **Motion** — None / Fade / Rise / Scale (Fade by default) — title + decoration only
- **Lens** — None, or one accent: Flare, 50mm Prime, Starburst, Veiling Glare, Ghosting, Anamorphic Streaks, Refract Bubbles. A Look deals a default and **re-rolls on every Look click**; the dropdown pins one until the next Look click. **Sparkle** stays off on the intro
- **Decoration** — when on, **Ornament**: Line / Diamond / Floral / Ribbon

A Look chip skins the intro (font, colour, outline, shadow, frame, ornament, enter motion, background treatment, one intro lens). It does **not** turn the intro on or off, change your title text, or replace a background you already chose.

Photo Size, border, torn edge, curl, shadow, wind, and backdrop wash stay on **photo** cards.

## Slide captions

Optional. MemoryString does not add them unless you type or use **Auto Caption**. These are **not** the intro title.

Select a media slide and type in the Inspector clip bar, or **Intro → This Slide → Add Caption**. **Generate** writes one. **Aa** opens position / color / size. A group’s caption belongs to its **lead** card.

**Position** per slide: Inherit / Bottom / Top / Center, or drag on the preview (**Reset** snaps back).

### Studio → Style → Captions → Type & Placement

Project-wide: **Font**, **Color**, **Auto Size** / **Size**, **Align**, **Motion** (None / Fade / Rise / Scale), **Default Placement**, **Shade Behind Text**.

Essential: type in the clip bar; font and style knobs are in Studio. Studio also offers **Reset Caption Style** (when style was changed) and **Reset N Positions** (when slides have dragged positions).

### Auto Caption

Fills empty captions on-device, in order: **Place · date** → **capture date** → a **readable filename**. UUID / hash-looking names, camera serials, and similar are never used — those slides stay blank.

- Library captions bubble → **Auto Caption N Untitled Slide(s)**
- **Edit → Auto Caption N Untitled Slides**
- Style → Captions
- Timeline / clip-bar **Generate**

**Auto Caption All Slides…** overwrites after confirmation (Library bubble in both modes; Style → Captions in Studio). **Clear All Captions…** wipes every caption.
