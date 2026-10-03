---
description: "Keep Best Shots and Auto Trim for a messy camera roll, on your Mac. MemoryString’s helpers stay on-device; Auto Trim is not on import, and original files are never rewritten."
---

# Auto detection

These tools help with a messy camera roll. Everything runs on your Mac. Original files are never changed.

## The helpers

- **Keep Best Shots** — From similar burst photos, keep one strong shot. Extras move to **Outtakes** (still in the project, not in the show). Import may ask; **Library** **⋯** anytime. Default: **Keep Best**. Undo **⌘Z**.
- **Auto Trim** — About four seconds from the middle of a video clip, with up to about one second nudge toward a face. Works about 70% of the time. Right-click or **Library** **⋯** — not on import. After it runs, use **Reset Video Duration** to restore full length. Undo **⌘Z**.
- **Video mute** — On import, quiet clips with only room noise so music can lead.
- **Center of interest** — Finds faces and subjects so motion frames the right area.
- **Auto Caption** — Fills captions only when you choose **Auto Caption** — never on import by itself.

![Paused photo with the center-of-interest ring](../.gitbook/assets/preview-coi.png)

## Keep Best Shots

When several photos look almost the same, MemoryString can keep the one with open eyes, a smile, sharpness, and good exposure.

**When:** after **import** when new stills join a similar group, or anytime from **Library** **⋯** → **Keep Best Shots…**. Videos are not included.

**The dialog** shows how many groups and extra shots. **Keep the best shot only?** Default button: **Keep Best**. **Keep All** leaves every photo.

![Keep Best import prompt: Keep All or Keep Best](../.gitbook/assets/keep-best-import-prompt.png)

{% hint style="info" %}
Other shots move to **Outtakes**. Undo with **⌘Z**.
{% endhint %}

One undo restores the whole pass. See [Library](library.md#import) and [Library ⋯](library.md#-options).

## Auto Trim

For a long phone clip, **Auto Trim** keeps about **four seconds** around the middle (two seconds before and after the midpoint, clamped to the clip). If a face is just outside that window, it may shift up to **~1 second** toward it. Clips shorter than four seconds keep the whole file.

The cut works about **70%** of the time. Trim by hand when you need to.

Clips trimmed by **Auto Trim** show a small scissors mark below the mute icon on **Timeline**, **Library**, and **Outtakes** cards. Solid scissors = **Auto Trim**. Outline = you trimmed by hand. The mark shows on hover or selection and goes away after **Reset Video Duration**.

**When:** **not** on import. Right-click a video → **Auto Trim** (runs immediately). Or **Library** **⋯** → **Auto Trim Videos…** (confirms when several videos are selected). Works on group videos too.

![Clip context menu with Auto Trim](../.gitbook/assets/auto-trim-context-menu.png)

It does not mute, caption, or delete clips.

**Undo:** **⌘Z**. **Reset Video Duration** restores the full source. **Library** **⋯** → **Reset Video Durations** resets all videos.

See [Library → Videos](library.md#videos) and [Timeline](timeline.md#reorder-and-trim).

## Video sound (auto-mute)

Speech on camera stays audible. Quiet room tone or hum may mute on import so the soundtrack can lead.

**When:** as each **video** is imported (**Essential** and **Studio**). Stills have no clip audio. Soundtrack tracks are not auto-muted.

**First import:** MemoryString may ask **Allow On-Device Speech Detection?**

- **Continue** — then macOS’s Speech prompt. Detection is **on-device**. It does not save a transcript.
- **Use Loudness Only** — skip speech. Mute still uses loudness.

If you deny speech, later imports use loudness only until you reset that choice.

**Rules** (whole file):

1. **No audio track** → muted
2. **Very quiet** throughout → muted
3. If speech is allowed and **speech is found** → **audible**
4. Else if energy looks like **music, singing, or cries** → **audible**
5. Else steady noise or ambience → muted

Muted clips show a speaker-off badge in **Library** and **Timeline**.

**Override:** right-click **Mute Video Sound** / **Unmute Video Sound**, the speaker badge, or the Inspector clip footer. See [Library](library.md#videos) and [Music](music.md#video-sound-not-the-music-lane).

## Center of interest

Motion aims at the person or subject that matters. **When:** on **import**, every photo and video gets a focus point.

**How it picks** (on-device):

1. **Largest usable face** — near the **eyes**
2. Else **main subject**
3. Else **center** of the frame

**Videos:** several frames in the trim window. The strongest face or subject wins.

**Override:** pause and click the photo. **Reset Center of Interest** (right-click) removes override and runs detection again.

![Paused preview: Rotate, Flip, Reset Center of Interest](../.gitbook/assets/preview-context-menu.png)

Ken Burns and punch-in use center of interest. Some whole-photo transitions ignore it. Details: [Preview](preview.md#center-of-interest).

## Auto Caption

**Auto Caption** can fill **place · date** — not camera codes like `IMG_4821`. You run it yourself from the **Library** captions bubble, **Edit → Auto Caption N Untitled Slides**, Style → Captions, or Inspector **Generate**. Not on import.

Untitled-only commands **never overwrite** text you typed. **Auto Caption All Slides…** overwrites after confirmation.

**Fill order** for an empty caption:

1. **Place · date** — GPS (EXIF / QuickTime) or IPTC city/country. **Country** only when the show has more than one country.
2. Else **capture date** from EXIF or video creation date.
3. Else a **readable filename** with real words.

**Never used:** UUID names, `IMG_1234`, `DSC…`, WhatsApp export titles. Those stay blank.

Geocoding uses coordinates **in the media**, not your Mac’s location. Offline still gets date / IPTC when available. One **⌘Z** undoes a full Auto Caption pass.

See [Intro and captions](intro-captions.md#auto-caption).
