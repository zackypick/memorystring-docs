# Music

Pictures move people; music finishes the job. Soundtrack: Inspector → **Audio** and the Timeline music lane — not the Library.

![Match Look Soundtrack, playlist, Add Music, Royalty-Free Library](../.gitbook/assets/inspector-audio-music.png)

## Import your own

Wedding song, paid playlist — bring it in:

- Toolbar **+** → **Music…**, or **File → Import Music…**
- Drop audio onto the window
- **⌘V** with audio on the clipboard
- Audio tab → **Add Music…**

**Formats:** `.mp3`, `.m4a`, `.aac`, `.wav`, `.aiff` / `.aif`, `.flac`, `.caf`, `.ogg` / `.oga`, `.wma`, `.opus`

Only import tracks you have the rights to use.

## Royalty-free library

No clearance hunt — pick a mood. Toolbar **+**, **File**, or Audio → **Royalty-Free Library…**.

![Royalty Free - No Attribution Required sheet](../.gitbook/assets/royalty-free-library.png)

The sheet title is **Royalty Free - No Attribution Required**. Subtitle: *Tracks from the YouTube Audio Library.* Built-in tracks need no attribution; your own imports are not owned by MemoryString.

**Sort:** Catalog · Title (A–Z) · Genre (A–Z) · Duration (shortest / longest first).

![Sort the royalty-free catalog by Catalog order, Title, Genre, or Duration](../.gitbook/assets/royalty-free-library-sort.png)

Each row: checkbox, **title** / **artist**, **style** (e.g. Quiet ballad) or **In project** if it is already on the playlist, duration, and a play button to audition (does not move the show playhead). Check tracks, then **Add**. **Cancel** dismisses. **Add** stays disabled until at least one unused track is selected.

## Match Look Soundtrack

**Match Look Soundtrack** on by default. Empty projects start quiet. After the first photos or videos land, MemoryString **soft-seeds** bundled mood track(s) — the current Look’s pool, or **Would It Matter** when no Look is selected. Mute or remove anytime. Saved projects with an empty playlist are left alone.

**While the playlist is still that untouched auto bed** (empty, or only auto-seeded and auto-ordered):

- Clicking a Style **Look** chip **retargets** the bed to a fitting track from that Look’s mood pool at random (Energy can lean the pool calmer or brighter)
- Longer shows stitch more tracks from the pool before repeating
- Dropping or importing your own audio **replaces** that bed

**Auto-adding / retargeting stops** on any manual soundtrack change: royalty-free picks, reorder, trim, remove, or your own files. After that, Look clicks do **not** swap the bed; new imports **append**. The app notices when you take the wheel.

Turn **Match Look Soundtrack** off to keep the playlist when changing Looks. Library picks, reorders, and your own imports stay either way.

## Audition

Listen without moving the show — shop while the slideshow stays paused.

- **Royalty-free sheet** — play on a row (does **not** move the show playhead). The slideshow bed stays paused while you preview
- **Audio tab** — local play/pause + position on each playlist row (gold fill is already heard; does **not** move the show playhead)
- **Timeline** — select a soundtrack clip on the music lane, then **scrub** the playhead (or nudge **←** / **→**). You hear that track at the playhead; the mixed bed and video buses stay silent while you scrub. Audition stops shortly after the head sits still. Clicking without dragging does not start it
- **Trim grips** on a music clip audition the cut edge in the source song

## Arrange on the Timeline

Line up tracks on the **music lane** (drag clips). Audio tab also has up / down arrows per row.

On import, MemoryString **auto-skips silent lead-in and run-out**. Trim with edge grips or **Set Start Here** / **Set End Here** / **Reset Length** (returns to that auto window, or the full file if no quiet edges).

**Mute Track** / **Unmute Track** — music-lane context menu, Audio tab (click the time readout for mute and track volume 0…100%), or the Inspector clip footer when a soundtrack is selected.

**Remove from Project** — royalty-free catalog tracks remove immediately (file stays in the app). Your imports ask **Remove from project?** first. **⌘Z** either way.

Audio tab: local play/pause preview (does not move the show playhead), **Reset music duration(s)** to clear trims, **Add Music…**, **Royalty-Free Library…**.

## Mix

Fades and ducks so speech wins the toast. Neighbouring tracks butt with short tapers (no designed silence between songs). Waveform **narrows at the fade edges**. Ease-in ~**1.5 seconds** at the start; **final 2.5 seconds** ease out with the closing fade. Music **ducks** under video sound. Loudness ~**−14 LUFS**. Per-track volume (0…100%) and mute apply in preview and export, on top of ducking.

The Audio tab’s local play/pause does not move the show playhead (gold fill is already heard).

While a soundtrack decodes, the stage may show **Loading music…**. Photos stay usable; Export and soundtrack edits wait.

Only import tracks you have the rights to use. MemoryString does not claim ownership of imported audio. Rights notice on the import panel and royalty-free sheet. Bundled tracks suit personal movies without attribution.

## Video sound (not the music lane)

Clip audio ≠ soundtrack. On import, MemoryString listens to each **video**: **speech keeps clip audio**; **silence or noise is muted**. Same in Essential and Studio. Decline speech detection and mute still runs from **loudness only**. How it decides: [Auto detection](auto-detection.md).

Unmute or mute anytime: right-click **Mute Video Sound** / **Unmute Video Sound**, the Library / Timeline speaker badge, or the Inspector clip footer. No toast. See [Library](library.md).
