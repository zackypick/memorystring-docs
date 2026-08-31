# Auto detection

Helpers on your Mac — less time muting fridge hum, chasing faces, typing `IMG_4821`, or keeping every near-duplicate burst. **Video mute** and **center of interest** run on **import**. **Keep Best Shots** can offer itself after import (and anytime from Library **⋯**). **Auto Trim** is on you — right-click or Library **⋯**, never automatic. **Captions** only when you choose **Auto Caption**.

Everything stays on your Mac. Original files are never rewritten.

![Paused photo with the center-of-interest ring](../.gitbook/assets/preview-coi.png)

## Keep Best Shots

Burst of nearly the same smile? MemoryString finds the similar groups and can keep the one that looks best — open eyes, smile, sharpness, exposure.

**When:** after **import** when new stills join a similar group, or anytime from Library **⋯** → **Keep Best Shots…**. Videos are left alone.

**The ask:** how many similar groups, how many extra shots, and **Keep the best shot only?** Default button is **Keep Best** (blue, right). **Keep All** leaves every photo.

{% hint style="info" %}
The other shots leave the Library and timeline. Undo with **⌘Z**.
{% endhint %}

One undo restores the whole pass. See [Library](library.md#import) and [Library ⋯](library.md#-options).

## Auto Trim

Long phone clip — wait, then the moment, then leftover? **Auto Trim** keeps the Energy-length window on the interesting climax and drops the wait and the leftover. If the climax is already at the start, it keeps that front window and still cuts the leftover.

**When:** **not** on import. Right-click a video → **Auto Trim** (runs immediately — no confirm). Or Library **⋯** → **Auto Trim Videos…** (asks when more than one video is in play).

**Undo:** **⌘Z**. **Reset Length** restores the full source anytime.

{% hint style="info" %}
Auto Trim reads the full source for the highlight, then trims to an Energy-length window on it. It does not mute, caption, or remove clips.
{% endhint %}

See [Library → Videos](library.md#videos) and [Timeline](timeline.md#reorder-and-trim).

## Video sound (auto-mute)

Speech on camera? Keep it. Wind and empty hallway? Quiet them.

**When:** as each **video** is imported (Essential and Studio). Stills have no clip audio. Soundtrack tracks are not auto-muted.

**First import:** MemoryString may ask **Allow On-Device Speech Detection?**

- **Continue** — then macOS’s Speech prompt. Detection is **on-device**; it does **not** transcribe or save what was said. The system prompt may mention Apple; MemoryString has no cloud speech path.
- **Use Loudness Only** — skip speech. Mute still runs from loudness / tonality.

If you skip or deny speech, later imports keep loudness only (until you reset that preference).

**How it decides** (whole file, not just the start):

1. **No audio track** → muted
2. **Very quiet** throughout → muted
3. If speech is allowed and **speech is found anywhere** in the clip → **stays audible**
4. Else if the energy looks like **music, singing, or cries** (tonal / periodic) → **stays audible**
5. Else **steady non-speech ambience / noise** → muted

There is no toast. A muted clip shows a speaker-off badge in the Library and Timeline.

**Override:** right-click **Mute Video Sound** / **Unmute Video Sound**, the speaker badge, or the Inspector clip footer. Manual mute is yours. See [Library](library.md#videos) and [Music](music.md#video-sound-not-the-music-lane).

## Center of interest

Eyes, not shoulder. **When:** on **import**, every photo and every video gets a focus point. Cached with the file so reopen keeps the same pick.

**How it picks** (on-device Vision):

1. **Largest usable face** in the frame — aim near the **eyes**, not the chest
2. Else the **main subject** (attention saliency)
3. Else the **middle** of the frame

**Videos:** several frames across the used trim window (not one opening frame). Strongest face / subject wins — a title card or wrong person at the start does not lock focus.

**Override:** pause and click (*Tap photo to set focus*). Ring moves; status shows **Focus · x%, y%**. Drag pans; leaves focus alone. **Reset Center of Interest** (right-click) drops the override and re-runs detection.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

Ken Burns and punch-in end here; backdrop follows; group cards use it too. Some whole-photo cuts ignore it. Details: [Preview](preview.md#center-of-interest).

## Auto Caption

Place and date — not camera codes. Run it: Library captions bubble, **Edit → Auto Caption N Untitled Slides**, Style → Captions, Timeline **Generate**, or a slide’s **Auto Caption**. Not on import.

Untitled-only entry points **never overwrite** what you typed. **Auto Caption All Slides…** overwrites after confirmation.

**How it fills an empty caption**, in order:

1. **Place · date** — GPS on the file (stills: EXIF; videos: QuickTime) reverse-geocoded with Apple’s geocoder, or IPTC city/country if GPS is missing. Format like `Tel Aviv-Yafo · 29 July 2026`. **Country** only when the show has photos from **more than one country**.
2. Else **capture date** — EXIF DateTimeOriginal / video creation date (not the import copy date). Same long-date style.
3. Else a **readable filename** with real words (`dan_and_mom-beach` → `Dan and Mom Beach`). Embedded calendar dates rewritten as dates; clock times dropped.

**Never copied:** UUID / hash names, camera codes (`IMG_1234`, `DSC…`, `Screenshot …`), WhatsApp export titles. Stay blank — better empty than `IMG_4821` as poetry.

Geocoding uses coordinates **already in the media** — not your Mac’s location. Offline still writes date / IPTC captions. One **⌘Z** undoes the whole Auto Caption pass.

See [Intro and captions](intro-captions.md#auto-caption).
