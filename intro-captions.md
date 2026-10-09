# Intro and captions

The **intro** is the opening title card. **Captions** are optional text on individual slides. New projects start with **Show Intro Slide** on and title **Memories**.

![Intro card on the stage](../.gitbook/assets/preview-stage.png)

![Intro Slide, Background, Text, Card & Motion](../.gitbook/assets/inspector-intro-top.png)

The intro is full-screen. It is not a floating photo card. Intro stays **first** in order. Intro fonts are separate from slide caption fonts.

Intro length follows **Energy** on its own timing: about **7s** at Calm, **6s** at default, **4s** at Intense. Photo stills use shorter holds at high Energy. See [Looks → Energy](style/looks.md#energy).

## Show cover and project name

The **cover** is the poster image — intro background and **Library** thumbnail — not necessarily the first slide after the title.

After import, MemoryString may pick cover and name while intro text is still **Memories**.

### How the cover is chosen

1. **Photos albums** — Apple key photo if available, unless it is already first or second on the show. People, Trips, Recent, By Month, and Media Type have no key photo.
2. **Otherwise** — a still on the show (not **Outtakes**, not video). Prefers middle of story, sharp face when possible.

Same on all import paths.

**Choose from Library**, **Choose File…**, drop on **Background**, **Set Background Image**, or **Remove** stops automatic cover, including after **Keep Best Shots**.

### Project name and intro title

First import may set window title and suggested save name from:

- One Photos **album**, **person**, or **trip** name
- **Add Folder** or Finder folder name

Title Case applied to folder names. Generic names skipped. Existing titles are not overwritten.

Export **Save As** prefers intro title — see [Format and export](export.md#export-movie).

## Intro Slide (Essential and Studio)

- **Show Intro Slide** — off removes opening card
- Text field — type here or in Inspector clip bar. Up to three lines on card. Export filename suggestion uses this title
- Pause and **double-click** title on stage to edit. **Single** click sets [center of interest](preview.md#center-of-interest)

Right-click intro → **Disable Intro Slide**, **Set Intro Title**, **Set Background Image**. Studio adds **Lens Effect**. With background still, **Rotate & Flip** turns the photo, not the title.

**Reset Intro to Defaults** turns card off and restores intro settings. Does not clear slide captions.

## Background (Essential and Studio)

Add a still behind the title: click well, **Choose…** / **Change…**, drop on well, **Choose from Library** / **Choose File…**, **Remove**. Missing file shows **Missing**. See [Show cover](#show-cover-and-project-name).

**Studio** with background: **Dim**, **Start zoom** (100–140%), **Slow Zoom**, **Soften**, **Color** / **Grayscale**.

Background still fades up from stage color. **Slow Zoom** can run when Card Motion is **None**.

## Text (Studio)

Hidden in **Essential** — type in Intro field; styling in **Studio**.

Font, color, **Auto Size** / **Size**, **Align**, **Outline**, **Shadow**.

## Card & Motion (Studio)

**Frame**, **Motion**, **Lens**, **Decoration** for the title card.

**Look** chips also skin intro (font, colors, frame, motion, lens). They do not change intro on/off, title text, or a background you chose.

## Slide captions

Optional. Not added unless you type or run **Auto Caption**. Not the intro title — usually place · date under a photo.

## Set a caption in the Inspector

**Studio:** **Style** → **Captions** → **Type & Placement** for font, color, size, align, motion, placement, shade. Bulk **Auto Caption** / **Clear** here too.

**Size** sets one text size for every slide. Long captions wrap. Turn off **Auto Size** to set it by hand. Captions rise in by default (**Rise**). A group shows its caption once, with one entrance and one exit for the whole group.

Select a clip. Type in Inspector clip bar (**Add a caption…**), **⇧⌘C**, or right-click **Set Caption**. **Generate** for one slide. **Aa** opens caption style.

On stage, groups show the **lead** seat’s caption. Speech-bubble badge is on the **captioned seat** only in **Library** / **Timeline**.

![Timeline: typing a slide caption](../.gitbook/assets/caption-edit.png)

**Position** per slide: Inherit / Bottom / Top / Center, or drag on preview. **Essential** types in clip bar; open **Studio** for **Type & Placement**.

Bulk: **Auto Caption N Untitled Slides**, **Auto Caption All Slides…**, **Clear All Captions…**. **Studio**: **Reset Caption Style**, **Reset N Positions**.

### Auto Caption

Does **not** run on import. Fills empty captions on-device: place · date → capture date → readable filename. Never camera codes. Places lead with the landmark or neighborhood when Apple Maps knows one. See [Auto detection](auto-detection.md#auto-caption).

### Caption Details (Studio)

**Style** → **Captions** → **Caption Details** chooses what automatic captions say. The top line is a live example from the selected slide.

![Caption Details: Landmark, City, Country, Date, Day, Weekday, Language](../.gitbook/assets/caption-details.png)

- **Landmark** — for example **Golden Gate Park**
- **City**
- **Country** — with **Only When the Show Visits Several Countries** on, a one-country show leaves it out
- **Date** — **Off**, **Short**, **Long**, or **Numbers**. **Numbers** adds **Date Order** (Day/Month/Year, Month/Day/Year, Year-Month-Day) and **Two-Digit Year**
- **Day** — off shows month and year only. **Weekday** adds the day name
- **Language** — for place names and dates. **Same as Mac** by default

Changes apply to automatic captions. Captions you typed or edited stay as they are.

![Library captions: Auto Caption untitled, Auto Caption All, Clear All](../.gitbook/assets/library-menu-captions.png)

- **Library** captions bubble
- **Edit → Auto Caption N Untitled Slides**
- **Style** → Captions
- Inspector **Generate**

**Auto Caption All Slides…** overwrites after confirmation. **Clear All Captions…** removes all caption text.
