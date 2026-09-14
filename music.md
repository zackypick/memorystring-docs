# Music

Pictures move people; music finishes the job. Soundtrack: Inspector → **Audio** and the **Audioline** (the music lane under the Timeline) — not the Library.

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
- **Extend to Fill** — keeps your tracks and appends free music after them so the bed covers the show.
- **Surprise me** — random pick from the **whole** royalty-free catalog, not the current Look’s pool. The app **remembers that pick immediately**, so a second tap does not land on the same bed while the first is still loading. After Surprise, Look clicks do not overwrite it.

## Audition the Audioline

The job: **hear the song at the playhead so you can trim start and end**. Shop a catalog track with the royalty-free play button or the Audio tab’s local play/pause (those do **not** move the movie). Use the Audioline when you need a *place in the song* for **Set Start Here** / **Set End Here**.

{% stepper %}
{% step %}
## Select the track

Click a soundtrack clip on the **Audioline** (the waveform lane under the photos). It highlights. You must have a clip selected — otherwise scrub is silent.

When the playhead crosses from one song to the next, the highlight and the sound switch to the clip **under the needle** at that join. You hear the new song, not leftover fade from the previous one.
{% endstep %}

{% step %}
## Scrub until you hear the moment

Drag the playhead (or hold **←** / **→**). You hear **that selected song** at the needle. Pictures stay paused; the mixed bed and video sound stay quiet while you scrub. Audition stops when the head sits still. A click without dragging does not play.

Hovering along the Audioline after a track is selected does the same — you hear the song under the pointer.

Dragging a clip’s **edge grip** also plays that cut in the source song, so you can hear the in or out while you trim by hand.
{% endstep %}

{% step %}
## Mark start or end

When the needle is on the bar or lyric you want:

- Right-click the clip → **Set Start Here** / **Set End Here**
- Inspector clip footer → **Set Start** / **Set End** (soundtrack selected)
- **⌘1** / **⌘2**

**Reset Length** returns to the auto-skipped quiet edges (or the full file if none were found). Undo with **⌘Z**.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Royalty-free sheet play, and play/pause on an Audio tab playlist row, preview the file **without** moving the show playhead (gold fill is already heard). Use those to pick a track. Use Audioline scrub to pick a **trim**.
{% endhint %}

## Arrange on the Timeline

Line up tracks on the **Audioline** (drag clips). Audio tab also has up / down arrows per row.

On import, MemoryString **auto-skips silent lead-in and run-out**. To cut by ear, [audition on the Audioline](#audition-the-audioline) then **Set Start Here** / **Set End Here**, or drag the edge grips. **Reset Length** returns to that auto window, or the full file if no quiet edges.

**Mute Track** / **Unmute Track** — Audioline context menu, Audio tab (click the time readout for mute and track volume 0…100%), or the Inspector clip footer when a soundtrack is selected.

**Remove from Project** — royalty-free catalog tracks remove immediately (file stays in the app). Your imports ask **Remove from project?** first. **⌘Z** either way.

Audio tab: local play/pause preview (does not move the show playhead), **Royalty-Free Library…** then **Add Music…**, plus **Pick New Music** / **Extend to Fill** / **Surprise me**. **Reset Length** clears a track’s trim. Tab **Reset Audio Settings** restores volume, mute, and Match Look — tracks and trims stay.

## Mix

Fades and ducks so speech wins the toast. Neighbouring tracks butt with short tapers (no designed silence between songs). Waveform **narrows at the fade edges**. Ease-in ~**1.5 seconds** at the start; **final 2.5 seconds** ease out with the closing fade. Music **ducks** under video sound. Loudness ~**−14 LUFS**. Per-track volume (0…100%) and mute apply in preview and export, on top of ducking.

The transport **speaker** immediately right of Play/Pause is separate: click it to **mute or unmute** all preview audio (soundtrack + unmuted video clips) without changing export mix or per-clip mute. White icon both ways; slash through the speaker when muted. See [Preview](preview.md#playback).

The Audio tab’s local play/pause does not move the show playhead (gold fill is already heard).

While a soundtrack decodes, the stage may show **Loading music…**. Photos stay usable; Export and soundtrack edits wait.

Only import tracks you have the rights to use. MemoryString does not claim ownership of imported audio. Rights notice on the import panel and royalty-free sheet. Bundled tracks suit personal movies without attribution.

## Video sound (not the Audioline)

Clip audio ≠ soundtrack. On import, MemoryString listens to each **video**: **speech keeps clip audio**; **silence or noise is muted**. Same in Essential and Studio. Decline speech detection and mute still runs from **loudness only**. How it decides: [Auto detection](auto-detection.md#video-sound-auto-mute).

Unmute or mute anytime: right-click **Mute Video Sound** / **Unmute Video Sound**, the Library / Timeline speaker badge, or the Inspector clip footer. No toast. See [Library](library.md#videos).
