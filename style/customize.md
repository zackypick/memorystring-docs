# Customize

Studio only. Inspector → **Style** → **Customize** (open by default in Studio). Each inner block starts **collapsed**:

**Plate · Ambience · Lens Effects · Film · Atmosphere & Decals**

![Customize disclosures at the bottom of Style](../.gitbook/assets/inspector-style.png)

A Look that ticks several lens boxes still plays **at most one** pooled effect per photo. Clicking the **same Look chip again** deals a fresh three (except **Clean**). See [Looks](looks.md).

**Reset Style to Defaults** restores this tab (and caption *style*, not caption *text*). Per-photo film overrides clear too. Tab resets undo with **⌘Z** and never remove photos, music, order, or trims.

## Plate

- **Photo Border** — **White** or **Black** matte; thick white frames get a heavier bottom margin
- **Border Width** and **Border Opacity** — opacity fades the whole matte
- **Torn Edge** + strength — Soft deckle or Rough hand-torn (when not off)
- **Paper Curl**
- **Drop Shadow** — Soft or Strong (also from nearer seats onto ones behind in a stack, carousel, or ribbon)
- **Rim Glow** — Soft or Strong luminous edge (with Drop Shadow or instead of it)
- **Corners** — Rounded / Sharp — sharp for Polaroid / Cinematic / Noir / Crisp; Clean, Vintage, B&W, and Golden Hour stay rounded

## Ambience

- **Floor Reflection** — Soft or Strong mirrored floor (with Drop Shadow / Rim Glow or instead of them)
- **Glow on Entry** — soft warm settle; on a group window the whole open catches it once
- **Wind** — **None**, **Gentle Wind**, or **Light Wind** (paper sway on the hold)
- **Wind Direction** — when Wind is on: **Horizontal**, **Diagonal ↗**, **Diagonal ↘**
- **Light Leak** — amber edge burn (+ Soft Colored accent); burns through group windows too
- **Backdrop** — Grayscale / Colored / Random
- **Backdrop Seat** — Centered / Offset

The backdrop is a blurred, enlarged copy of the photo — including multi-photo flourishes, whose washes crossfade every couple of cards. It drifts with the plate, softens less on Light stage, and settles with the card.

| Backdrop | What it does |
| --- | --- |
| **Grayscale** | Every wash fully mono |
| **Colored** | Every wash keeps the photo’s colours |
| **Random** | About half mono / half colour, **stable per photo seed** — preview matches export |

Older projects migrate: Black & White → Grayscale, Color → Colored, Mixed → Random.

## Lens Effects

Optical light on the frame. Atmosphere is weather; Decals are stick-on motifs. Checkboxes A–Z (same column-major order as Motion):

**Anamorphic Streaks, Bokeh, Flare, Ghosting, Orbs, 50mm Prime, Pulse, Refract Bubbles, Sparkle, Starburst, Sweep, Veiling Glare, Vignette**

Plus **Randomize Selected** and **How often**. Each clip below is 1080p from a real export with that effect pinned; the still is the video cover.

<figure>
  <video src="../.gitbook/assets/catalog/lens-anamorphic-streaks.mp4" poster="../.gitbook/assets/catalog/lens-anamorphic-streaks.jpg" controls></video>
  <figcaption>Anamorphic Streaks</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-bokeh.mp4" poster="../.gitbook/assets/catalog/lens-bokeh.jpg" controls></video>
  <figcaption>Bokeh</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-flare.mp4" poster="../.gitbook/assets/catalog/lens-flare.jpg" controls></video>
  <figcaption>Flare</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-ghosting.mp4" poster="../.gitbook/assets/catalog/lens-ghosting.jpg" controls></video>
  <figcaption>Ghosting</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-orbs.mp4" poster="../.gitbook/assets/catalog/lens-orbs.jpg" controls></video>
  <figcaption>Orbs</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-50mm-prime.mp4" poster="../.gitbook/assets/catalog/lens-50mm-prime.jpg" controls></video>
  <figcaption>50mm Prime</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-pulse.mp4" poster="../.gitbook/assets/catalog/lens-pulse.jpg" controls></video>
  <figcaption>Pulse</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-refract-bubbles.mp4" poster="../.gitbook/assets/catalog/lens-refract-bubbles.jpg" controls></video>
  <figcaption>Refract Bubbles</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-sparkle.mp4" poster="../.gitbook/assets/catalog/lens-sparkle.jpg" controls></video>
  <figcaption>Sparkle</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-starburst.mp4" poster="../.gitbook/assets/catalog/lens-starburst.jpg" controls></video>
  <figcaption>Starburst</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-sweep.mp4" poster="../.gitbook/assets/catalog/lens-sweep.jpg" controls></video>
  <figcaption>Sweep</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-veiling-glare.mp4" poster="../.gitbook/assets/catalog/lens-veiling-glare.jpg" controls></video>
  <figcaption>Veiling Glare</figcaption>
</figure>

<figure>
  <video src="../.gitbook/assets/catalog/lens-vignette.mp4" poster="../.gitbook/assets/catalog/lens-vignette.jpg" controls></video>
  <figcaption>Vignette</figcaption>
</figure>

A photo plays **at most one** pooled lens effect. Choice is stable from the photo’s seed.

- **Randomize Selected on** (how every Look leaves it): every checked box has **equal odds**; **How often** (default **70%**) is how many photos get one at all. Groups a bit more often. **Refract Bubbles** plays as a 2–3 slide take when it wins, and wins fewer anchors so its screen time stays near a fair share.
- **Randomize Selected off**: Vignette and optical accents (Bokeh, 50mm Prime, Ghosting, Veiling Glare, Starburst, Anamorphic Streaks) can paint on **every** photo instead of taking the slot. Checking **Refract Bubbles** puts them all back into one draw (bubbles never stack). **How often** stays enabled when Refract Bubbles is on.

**Bokeh / Sweep / Pulse** are three styles of the same bokeh-circle effect (each takes a pool slot). Anything you check yourself joins the rotation on equal odds — there is no cap of three.

If Randomize is on and **no other lens boxes** are checked, MemoryString draws one stable optical effect per photo from the full pool. Atmosphere and film grain / fringe / scratches are never in that pool.

**Studio:** right-click a Timeline or Library slide → **Lens Effect** (under Slide Transition) to pin effects on that slide or the whole multi-photo group. Current effects are checked. **Refract Bubbles** is scenery: consecutive slides (or consecutive seats) with Bubbles checked share one field; other pins still stack. Unchecking Bubbles on one slide drops only that slide. Pins survive Look re-deals. Essential does not show this menu.

On a group window, vignette and light leak ride the whole open once. Atmosphere and Decals also paint on Photo Stack / Carousel / Ribbon / Filmstrip windows. Grain and scratches stop once the closing fade owns the frame.

### Anamorphic Streaks (when checked)

Horizontal blue/amber light bars across the stage (backdrop and card), steered off the subject (center of interest).

Presets: **Subtle Cinema** (default) · **Strong Anamorphic** · **Vintage Film** · **Blue Heavy**

Knobs: **Streak Length**, **Intensity**, **Color Split**, **Softness**

On **Noir** / **B&W**, streaks keep their shape as **plain light bars** (not blue/amber).

### Refract Bubbles (when checked)

Glassy spheres that magnify and bend the photo, kept to the backdrop and sides so they stay off the subject.

**Look** menu: **Subtle Bubbles** · **Dreamy** · **Strong Refraction** (default) · **Vintage Soap**

Knobs: **Count**, **Size**, **Speed**, **Refraction**, **Rainbow**. Count, size, speed, and rainbow stay editable after a preset.

On **Noir** / **B&W**, bubbles lose the rainbow rim and read as **clear glass**.

## Film

Outside the lens pool — never thinned by Randomize.

- **Film Grain** + **Grain Amount** — soft warm stock over the whole frame; sized to the frame so 4K matches preview
- **Color Fringe** + **Fringe Amount** — soft red/blue at photo edges
- **Film Scratches** + **Scratch Amount** — sparse hairlines on the **blurred backdrop only**; photo cards stay clean

With a photo selected, **This Photo** sets each of those to **Inherit**, **Off**, or **On** (plus amount when not Inherit). Per-photo film edits do **not** switch Style to Custom.

## Atmosphere & Decals

Each menu is a **single choice**. Default **None**. Looks never set these. Picking one does not re-deal the lens pool.

- **Atmosphere** — **None** · **Bubbles** (soap films) · **Leaves** (autumn drift + maple edge motifs)
- **Decals** — **None** · **Travel** (pins / routes / folded map / plane / suitcase **plus** a dotted route plane) · **Vacation** (holiday motifs + the same route plane) · **Party** (sparse cues + a sparkle tick) · **Florals** · **Wedding** · **Pets** · **Sports**

All edge-biased, never a sticker bomb on the hero print. There is no separate Map or Route checkbox.

Each clip below is 1080p from a real export with that one choice on; the still is the video cover.

### Atmosphere — Bubbles

<figure>
  <video src="../.gitbook/assets/catalog/atm-bubbles.mp4" poster="../.gitbook/assets/catalog/atm-bubbles.jpg" controls></video>
  <figcaption>Atmosphere · Bubbles</figcaption>
</figure>

### Atmosphere — Leaves

<figure>
  <video src="../.gitbook/assets/catalog/atm-leaves.mp4" poster="../.gitbook/assets/catalog/atm-leaves.jpg" controls></video>
  <figcaption>Atmosphere · Leaves</figcaption>
</figure>

### Decals — Travel

<figure>
  <video src="../.gitbook/assets/catalog/decal-travel.mp4" poster="../.gitbook/assets/catalog/decal-travel.jpg" controls></video>
  <figcaption>Decals · Travel</figcaption>
</figure>

### Decals — Vacation

<figure>
  <video src="../.gitbook/assets/catalog/decal-vacation.mp4" poster="../.gitbook/assets/catalog/decal-vacation.jpg" controls></video>
  <figcaption>Decals · Vacation</figcaption>
</figure>

### Decals — Party

<figure>
  <video src="../.gitbook/assets/catalog/decal-party.mp4" poster="../.gitbook/assets/catalog/decal-party.jpg" controls></video>
  <figcaption>Decals · Party</figcaption>
</figure>

### Decals — Florals

<figure>
  <video src="../.gitbook/assets/catalog/decal-florals.mp4" poster="../.gitbook/assets/catalog/decal-florals.jpg" controls></video>
  <figcaption>Decals · Florals</figcaption>
</figure>

### Decals — Wedding

<figure>
  <video src="../.gitbook/assets/catalog/decal-wedding.mp4" poster="../.gitbook/assets/catalog/decal-wedding.jpg" controls></video>
  <figcaption>Decals · Wedding</figcaption>
</figure>

### Decals — Pets

<figure>
  <video src="../.gitbook/assets/catalog/decal-pets.mp4" poster="../.gitbook/assets/catalog/decal-pets.jpg" controls></video>
  <figcaption>Decals · Pets</figcaption>
</figure>

### Decals — Sports

<figure>
  <video src="../.gitbook/assets/catalog/decal-sports.mp4" poster="../.gitbook/assets/catalog/decal-sports.jpg" controls></video>
  <figcaption>Decals · Sports</figcaption>
</figure>
