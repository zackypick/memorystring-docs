# Music

Soundtrack lives in Inspector → **Audio** and on the Timeline music lane — not in the Library.

![Match Look Soundtrack, playlist, Add Music, Royalty-Free Library](../.gitbook/assets/inspector-audio-music.png)

## Import your own

- Toolbar **+** → **Music…**, or **File → Import Music…**
- Drop audio onto the window
- **⌘V** with audio on the clipboard
- Audio tab → **Add Music…**

**Formats:** `.mp3`, `.m4a`, `.aac`, `.wav`, `.aiff` / `.aif`, `.flac`, `.caf`, `.ogg` / `.oga`, `.wma`, `.opus`

Only import tracks you have the rights to use.

## Royalty-free library

Toolbar **+**, **File**, or Audio → **Royalty-Free Library…**.

![Royalty Free - No Attribution Required sheet](../.gitbook/assets/royalty-free-library.png)

The sheet title is **Royalty Free - No Attribution Required**. Subtitle: *Tracks from the YouTube Audio Library.* Built-in tracks need no attribution; your own imports are not owned by MemoryString.

**Sort:** Catalog · Title (A–Z) · Genre (A–Z) · Duration (shortest / longest first).

Each row: checkbox, **title** / **artist**, **style** (e.g. Quiet ballad) or **In project** if it is already on the playlist, duration, and a play button to audition (does not move the show playhead). Check tracks, then **Add**. **Cancel** dismisses. **Add** stays disabled until at least one unused track is selected.

## Match Look Soundtrack

On by default. Empty projects start quiet. After the first photos or videos land, MemoryString **soft-seeds** bundled mood track(s) to cover the show — the current Look’s pool, or **Would It Matter** when no Look is selected. Mute or remove anytime. Saved projects that already have an empty playlist are left alone.

**While the playlist is still that untouched auto bed** (empty, or only auto-seeded and auto-ordered):

- Clicking a Style **Look** chip **retargets** the bed to a fitting track from that Look’s mood pool at random (Energy can lean the pool calmer or brighter)
- Longer shows stitch more tracks from the pool before repeating
- Dropping or importing your own audio **replaces** that bed

**Auto-adding / retargeting stops** as soon as you make a manual soundtrack change: royalty-free rows you picked, a reorder, a trim, a remove — or you already added your own files. After that, a Look click does **not** swap the bed, and a new import **appends** instead of replacing.

Turn **Match Look Soundtrack** off to keep the playlist when changing Looks. Library picks, reorders, and your own imports stay put either way.

## Audition

- **Royalty-free sheet** — play on a row (does **not** move the show playhead). The slideshow bed stays paused while you preview
- **Audio tab** — local play/pause + position on each playlist row (gold fill is already heard; does **not** move the show playhead)
- **Timeline** — select a soundtrack clip on the music lane, then **scrub** the playhead (or nudge **←** / **→**). You hear that track at the playhead; the mixed bed and video buses stay silent while you scrub. Audition stops shortly after the head sits still. Clicking without dragging does not start it
- **Trim grips** on a music clip audition the cut edge in the source song

## Arrange on the Timeline

Reorder on the **music lane** (drag clips). The Audio tab also has up / down arrows on each row.

On import, MemoryString **auto-skips silent lead-in and run-out**. Trim with edge grips or **Set Start Here** / **Set End Here** / **Reset Length** (Reset Length returns to that auto window, or the full file if no quiet edges were found).

**Mute Track** / **Unmute Track** — music-lane context menu, Audio tab (click the time readout for mute and track volume 0…100%), or the Inspector clip footer when a soundtrack is selected.

**Remove from Project** — royalty-free catalog tracks remove immediately (the file stays in the app). Audio you imported yourself asks **Remove from project?** first. **⌘Z** either way.

Audio tab: local play/pause preview (does not move the show playhead), **Reset music duration(s)** to clear trims, **Add Music…**, **Royalty-Free Library…**.

## Mix

Neighbouring tracks butt together with short tapers (no designed silence between songs). The music-lane waveform **narrows at the fade edges**. The show eases music in over about **1.5 seconds** at the start; the **final 2.5 seconds** of the soundtrack ease out with the closing fade. Music **ducks** under video sound. Loudness is aimed around **−14 LUFS**. Per-track volume (0…100%) and mute apply in preview and export, on top of ducking.

The Audio tab’s local play/pause does not move the show playhead (gold fill is already heard).

While a soundtrack decodes, the stage may show **Loading music…**. Photos stay usable; Export and soundtrack edits wait.

Only import tracks you have the rights to use. MemoryString does not claim ownership of imported audio. The rights notice appears on the import panel and in the royalty-free sheet. Bundled tracks are suitable for personal movies without attribution.

## Video sound (not the music lane)

On import, MemoryString listens to each **video**: **speech keeps clip audio**; **silence or noise is muted**. Same in Essential and Studio. If you decline on-device speech detection, mute still runs from **loudness only**. How it decides: [Auto detection](auto-detection.md).

Unmute or mute anytime: right-click **Mute Video Sound** / **Unmute Video Sound**, the Library / Timeline speaker badge, or the Inspector clip footer. No toast. See [Library](library.md).
