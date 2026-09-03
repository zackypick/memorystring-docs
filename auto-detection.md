---
description: "Keep Best Shots and Auto Trim for a messy camera roll, on your Mac. MemoryString’s helpers stay on-device; Auto Trim is not on import, and original files are never rewritten."
---

# Auto detection

Messy camera roll helpers, on your Mac: Keep Best Shots keeps the open-eyed one from a near-duplicate burst. Auto Trim jumps to the moment in a phone clip. Video mute hushes fridge hum so the soundtrack can lead. Motion aims at faces.

Everything stays on your Mac. Original files are never rewritten.

## The helpers

- **Keep Best Shots** — Similar burst photos? Keep the sharp, open-eyed, well-exposed one; extras leave the Library and timeline. Import may ask; Library **⋯** anytime. Default: **Keep Best**. Undo **⌘Z**.
- **Auto Trim** — Videos: keep the interesting moment (the blow, the kick, the laugh); drop the wait and the leftover. Right-click or Library **⋯** — not on import. No extra confirm after you pick it. Undo **⌘Z**.
- **Video mute** — Hush fridge hum and boring room tone on import so the soundtrack can lead.
- **Center of interest** — Finds faces and subjects so motion frames the right thing — you don’t chase focus yourself.
- **Auto Caption** — Titles from the photo, only when you choose **Auto Caption** — never written by itself.

![Paused photo with the center-of-interest ring](../.gitbook/assets/preview-coi.png)

## Keep Best Shots

Burst of nearly the same smile? MemoryString finds the similar groups and can keep the one that looks best — open eyes, smile, sharpness, exposure. The movie stays lean: one great shot instead of five near-duplicates.

**When:** after **import** when new stills join a similar group, or anytime from Library **⋯** → **Keep Best Shots…**. Videos are left alone.

**The ask:** how many similar groups, how many extra shots, and **Keep the best shot only?** Default button is **Keep Best** (blue, right). **Keep All** leaves every photo.

![Keep Best import prompt: Keep All or Keep Best](../.gitbook/assets/keep-best-import-prompt.png)

{% hint style="info" %}
The other shots leave the Library and timeline. Undo with **⌘Z**.
{% endhint %}

One undo restores the whole pass. See [Library](library.md#import) and [Library ⋯](library.md#-options).

## Auto Trim

Long phone clip — wait, then the moment, then leftover? **Auto Trim** keeps the interesting climax and drops the wait and the leftover, so the film hits the blow, the kick, the laugh instead of the setup.

**When:** **not** on import. Right-click a video → **Auto Trim** (runs immediately — no confirm). Or Library **⋯** → **Auto Trim Videos…** (asks when more than one video is in play).

![Clip context menu with Auto Trim](../.gitbook/assets/auto-trim-context-menu.png)

**Undo:** **⌘Z**. **Reset Length** restores the full source anytime.

{% hint style="info" %}
Auto Trim finds the highlight in the full source, then trims to that window. It does not mute, caption, or remove clips.
{% endhint %}

See [Library → Videos](library.md#videos) and [Timeline](timeline.md#reorder-and-trim).

## Video sound (auto-mute)

Speech on camera? Keep it. Fridge hum and empty hallway? Quiet them so the soundtrack can lead.

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

Eyes, not shoulder — so motion frames the person (or subject) that matters without you chasing focus. **When:** on **import**, every photo and every video gets a focus point. Cached with the file so reopen keeps the same pick.

**How it picks** (on-device Vision):

1. **Largest usable face** in the frame — aim near the **eyes**, not the chest
2. Else the **main subject** (attention saliency)
3. Else the **middle** of the frame

**Videos:** several frames across the used trim window (not one opening frame). Strongest face / subject wins — a title card or wrong person at the start does not lock focus.

**Override:** pause and click (*Tap photo to set focus*). Ring moves; status shows **Focus · x%, y%**. Drag pans; leaves focus alone. **Reset Center of Interest** (right-click) drops the override and re-runs detection.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

Ken Burns and punch-in end here; backdrop follows; group cards use it too. Some whole-photo cuts ignore it. Details: [Preview](preview.md#center-of-interest).

## Auto Caption

Place and date — not camera codes — so the film reads like a story instead of `IMG_4821`. Run it yourself: Library captions bubble, **Edit → Auto Caption N Untitled Slides**, Style → Captions, Timeline **Generate**, or a slide’s **Auto Caption**. Not on import — never written by itself.

Untitled-only entry points **never overwrite** what you typed. **Auto Caption All Slides…** overwrites after confirmation.

**How it fills an empty caption**, in order:

1. **Place · date** — GPS on the file (stills: EXIF; videos: QuickTime) reverse-geocoded with Apple’s geocoder, or IPTC city/country if GPS is missing. Format like `Lisbon · 29 July 2026`. **Country** only when the show has photos from **more than one country**.
2. Else **capture date** — EXIF DateTimeOriginal / video creation date (not the import copy date). Same long-date style.
3. Else a **readable filename** with real words (`dan_and_mom-beach` → `Dan and Mom Beach`). Embedded calendar dates rewritten as dates; clock times dropped.

**Never copied:** UUID / hash names, camera codes (`IMG_1234`, `DSC…`, `Screenshot …`), WhatsApp export titles. Stay blank — better empty than `IMG_4821` as poetry.

Geocoding uses coordinates **already in the media** — not your Mac’s location. Offline still writes date / IPTC captions. One **⌘Z** undoes the whole Auto Caption pass.

See [Intro and captions](intro-captions.md#auto-caption).
