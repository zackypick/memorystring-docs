# Titles and captions

Inspector → **Titles** holds the **opening card** and optional **closing words**. **Captions** are optional text on individual slides. New projects start with **Show opening card** on and title **Memories**. Closing words are off until you turn them on.

![Opening card on the stage](../.gitbook/assets/preview-stage.png)

![Titles: Opening and Closing](../.gitbook/assets/inspector-intro-top.png)

The opening card is full bleed. It fills the stage. It is not a floating photo card. It stays **first** in order. Opening fonts are separate from slide caption fonts, and from closing words.

**Stage** is **Match**, **Dark**, or **Light**. **Match** follows Style → Stage. Title ink follows that stage (light ink on Dark, dark ink on Light) until you pick a color.

**Studio → Intensity** is how loud the photo behind the title is. It follows Style → Stage Intensity until you move it. **Match Show** puts it back. The wash eases into the first slide.

Opening length follows **Energy** on its own timing: about **7s** at Calm, **6s** at default, **4s** at Intense. Photo stills use shorter holds at high Energy. See [Looks → Energy](style/looks.md#energy).

## Multiline titles

Long opening or closing text **wraps on its own** when it does not fit one line.

To start a new line on purpose, press **Shift+Enter** (on stage after a double-click, or in the Titles field). Plain **Enter** keeps you in the field.

Up to three lines on the opening card. Closing words allow a few more.

## Fonts (Studio)

**Studio** font menus — captions, opening title, and closing words — list **every font installed on this Mac**. **System** stays first, then A–Z. Each name is drawn **in that type**, so you can pick without guessing.

A show stores the family name, not the font file. If that face is missing on another Mac, the menu still shows the saved name and the show falls back to System.

## Show cover and project name

The **cover** is the poster image — opening background and **Library** thumbnail — not necessarily the first slide after the title.

After import, MemoryString may pick cover and name while opening text is still **Memories**.

### How the cover is chosen

1. **Photos albums** — Apple key photo if available, unless it is already first or second on the show. People, Trips, Recent, By Month, and Media Type have no key photo.
2. **Otherwise** — a still on the show (not **Outtakes**, not video). Prefers middle of story, sharp face when possible.

Same on all import paths.

**Choose from Library**, **Choose File…**, drop on **Background**, **Set Background Image**, or **Remove** stops automatic cover, including after **Keep Best Shots**.

### Project name and opening title

First import may set window title and suggested save name from:

- One Photos **album**, **person**, or **trip** name
- **Add Folder** or Finder folder name

Title Case applied to folder names. Generic names skipped. Existing titles are not overwritten.

Export **Save As** prefers the opening title — see [Format and export](export.md#export-movie).

## Opening (Essential and Studio)

**Titles → Opening**

- **Show opening card** — off removes the opening card
- Text field — type here or in Inspector clip bar. Export filename suggestion uses this title
- Pause and **double-click** the title on stage to edit. **Single** click sets [center of interest](preview.md#center-of-interest)

Right-click the opening card → **Disable Intro Slide**, **Set Intro Title**, **Set Background Image**. Studio adds **Lens Effect**. With a background still, **Rotate & Flip** turns the photo, not the title.

**Reset Titles to Defaults** turns the opening card off, restores opening settings, and clears closing words. It does not clear slide captions. To drop only the opening photo, use **Remove** on the background well.

## Background (Essential and Studio)

Add a still behind the title: click well, **Choose…** / **Change…**, drop on well, **Choose from Library** / **Choose File…**, **Remove**. Missing file shows **Missing**. See [Show cover](#show-cover-and-project-name).

**Studio** with a background: **Start zoom** (100–140%), **Slow Zoom**, **Soften**, **Color** / **Grayscale**. How loud that photo is lives under **Stage → Intensity**, not a separate Dim slider.

The background fades up from the stage color and eases into the first slide. **Slow Zoom** eases in. It can run when Card Motion is **None**.

## Opening Text (Studio)

Hidden in **Essential** — type in the Opening field; styling in **Studio**.

Font (see [Fonts](#fonts-studio)), color, **Auto Size** / **Size**, **Align**, **Outline**, **Shadow**.

## Card & Motion (Studio)

**Frame**, **Motion**, **Lens**, **Decoration** for the opening card.

**Look** chips also skin the opening card (font, colors, frame, motion, lens). They do not change on/off, title text, or a background you chose.

## Closing words

Optional last line on the **existing** cream end card, above **Created with MemoryString**. No extra card, no credits roll, no subtitle.

**Show closing words** is off until you turn it on. The text box already holds **The End**, so checking the box puts that line on the card. Change it, or clear the field for the mark only. Older saved shows keep whatever they had.

**Titles → Closing → Show closing words**.

- Pause on the end card and **double-click** to edit on stage
- Same wrap and **Shift+Enter** as the opening title
- The end card stays about three seconds. There is no duration slider

**Studio:** **Ornament** (none, or a small mark under the words), then **Text** — font, color (**Match Stage** follows the MemoryString mark), **Auto Size** / **Size**, **Align**, **Legibility** (shadow, hairline outline, or both).

## Slide captions

Optional. Not added unless you type or run **Auto Caption**. Not the opening title — usually place · date under a photo.

![Auto caption on a slide: Golden Gate Park, San Francisco · 6 July 2024](../.gitbook/assets/caption-stage.jpg)

## Set a caption in the Inspector

**Studio:** **Style** → **Captions** → **Type & Placement** for font, color, size, align, motion, placement, shade. Bulk **Auto Caption** / **Clear** here too. The font menu is the same live Mac list as Titles.

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
