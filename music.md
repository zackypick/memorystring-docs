# Music

Pictures move people; music finishes the job. Soundtrack: Inspector → **Audio** and the Timeline music lane — not the Library.

![Audio tab: Match Look Soundtrack, Royalty-Free Library, Add Music, Pick New / Extend / Surprise](../.gitbook/assets/inspector-audio-music.png)

## Import your own

Wedding song, paid playlist — bring it in:

- Toolbar **+** → **Music…**, or **File → Add Music → Import Music…**
- Drop audio onto the window
- **⌘V** with audio on the clipboard
- Audio tab → **Add Music…**

**Formats:** `.mp3`, `.m4a`, `.aac`, `.wav`, `.aiff` / `.aif`, `.flac`, `.caf`, `.ogg` / `.oga`, `.wma`, `.opus`

Only import tracks you have the rights to use.

## Royalty-free library

No clearance hunt — pick a mood. Toolbar **+**, **File → Add Music → Royalty-Free Library…**, or Audio → **Royalty-Free Library…**.

![Toolbar + includes Royalty-Free Library…](../.gitbook/assets/toolbar-plus-menu.png)

![Royalty Free - No Attribution Required sheet](../.gitbook/assets/royalty-free-library.png)

The sheet title is **Royalty Free - No Attribution Required**. One-liner under it: **YouTube Audio Library, cleared for MemoryString**. Built-in tracks need no attribution; your own imports are not owned by MemoryString. The sheet chrome matches Export / Import from Photos (oak surface, champagne title, centered Sort bar).

**Sort:** Catalog · Title (A–Z) · Genre (A–Z) · Duration (shortest / longest first).

![Sort the royalty-free catalog by Catalog order, Title, Genre, or Duration](../.gitbook/assets/royalty-free-library-sort.png)

Each row: checkbox, **title** / **artist**, **style** (e.g. Quiet ballad) or **In project** if it is already on the playlist, duration, and a play button to audition (does not move the show playhead). Check tracks, then **Add**. **Cancel** dismisses. **Add** stays disabled until at least one unused track is selected.

## Match Look Soundtrack

**Match Look Soundtrack** on by default. Empty projects start quiet. After the first photos or videos land, MemoryString **soft-seeds** bundled mood track(s) — the current Look’s pool, or **Would It Matter** when no Look is selected. Mute or remove anytime. Saved projects with an empty playlist are left alone.

Each Look has its own **mood pool** (A-list). Energy leans that list calmer or brighter. The royalty-free sheet lists the **full catalog** — including tracks that are not in any Look pool. Match Look never dumps the whole catalog into a show.

**While the playlist is still that untouched auto bed** (empty, or only auto-seeded and auto-ordered):

- Clicking a Style **Look** chip **retargets** the bed to a fitting track from that Look’s mood pool at random (Energy can lean the pool calmer or brighter)
- Longer shows stitch more tracks from the pool before repeating
- Dropping or importing your own audio **replaces** that bed

**Auto-adding / retargeting stops** on any manual soundtrack change: royalty-free picks, reorder, trim, remove, or your own files. After that, Look clicks do **not** swap the bed; new imports **append**. The app notices when you take the wheel.

Turn **Match Look Soundtrack** off to keep the playlist when changing Looks. Library picks, reorders, and your own imports stay either way.

Audio files are never treated as photos — dropping or seeding `.m4a` / `.mp3` does not run them through the still-image importer.

## Audio tab bed actions

Under the playlist, after **Royalty-Free Library…** / **Add Music…**:

- **Pick New Music** — fresh Match Look bed for this Look (skips recently used tracks). Asks before replacing music you added yourself.
- **Extend to Fill** — keeps your tracks and appends free music after them so the bed covers the show. The other direction is [Fit Show to Music](#fit-show-to-music) — pictures match the song.
- **Surprise me** — random pick from the **whole** royalty-free catalog, not the current Look’s pool. The app **remembers that pick immediately**, so a second tap does not land on the same bed while the first is still loading. After Surprise, Look clicks do not overwrite it.

## Fit Show to Music

The song is the length you want. **Fit Show to Music** changes still holds so the movie ends with the soundtrack.

Same label in three places:

- Inspector → **Motion** → **Timeline** (Studio), next to **Reset Slide Durations**
- Right-click a track on the music lane
- **Edit → Fit Show to Music**

{% hint style="info" %}
Videos keep their own length — they are not sped up or stretched. If the music is still longer than the pictures can cover, it fades out on the closing beat the same way it does today.
{% endhint %}

**Extend to Fill** (Audio tab) appends music so the *bed* covers the *show*. Fit Show to Music changes the show, not the playlist. **⌘Z** undoes it. **Reset Slide Durations** puts still timing back on Energy defaults.

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

**Fit Show to Music** — same music-lane menu, **Edit**, or Motion → Timeline. Changes still holds so the show matches the soundtrack; see [Fit Show to Music](#fit-show-to-music).

**Remove from Project** — royalty-free catalog tracks remove immediately (file stays in the app). Your imports ask **Remove from project?** first. **⌘Z** either way.

Audio tab: local play/pause preview (does not move the show playhead), **Royalty-Free Library…** then **Add Music…**, plus **Pick New Music** / **Extend to Fill** / **Surprise me**. **Reset Length** clears a track’s trim. Tab **Reset Audio Settings** restores volume, mute, and Match Look — tracks and trims stay.

## Mix

Fades and ducks so speech wins the toast. Neighbouring tracks butt with short tapers (no designed silence between songs). Waveform **narrows at the fade edges**. Ease-in ~**1.5 seconds** at the start; **final 2.5 seconds** ease out with the closing fade. Music **ducks** under video sound. Loudness ~**−14 LUFS**. Per-track volume (0…100%) and mute apply in preview and export, on top of ducking.

The transport **speaker** immediately right of Play/Pause is separate: click it to **mute or unmute** all preview audio (soundtrack + unmuted video clips) without changing export mix or per-clip mute. White icon both ways; slash through the speaker when muted. See [Preview](preview.md#playback).

The Audio tab’s local play/pause does not move the show playhead (gold fill is already heard).

While a soundtrack decodes, the stage may show **Loading music…**. Photos stay usable; Export and soundtrack edits wait.

Only import tracks you have the rights to use. MemoryString does not claim ownership of imported audio. Rights notice on the import panel and royalty-free sheet. Bundled tracks suit personal movies without attribution.

## Video sound (not the music lane)

Clip audio ≠ soundtrack. On import, MemoryString listens to each **video**: **speech keeps clip audio**; **silence or noise is muted**. Same in Essential and Studio. Decline speech detection and mute still runs from **loudness only**. How it decides: [Auto detection](auto-detection.md#video-sound-auto-mute).

Unmute or mute anytime: right-click **Mute Video Sound** / **Unmute Video Sound**, the Library / Timeline speaker badge, or the Inspector clip footer. No toast. See [Library](library.md#videos).
