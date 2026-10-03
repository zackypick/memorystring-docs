# Music

Soundtrack lives in Inspector → **Audio** and on the **Audioline** under the **Timeline**. It is not in the **Library**.

![Audio tab: Match Look Soundtrack, Royalty-Free Library, Add Music, Pick New / Extend / Surprise](../.gitbook/assets/inspector-audio-music.png)

## Import your own

- Toolbar **+** → **Music…**, or **File → Add Music → Import Music…**
- Drop audio on the window
- **⌘V** with audio on the clipboard
- **Audio** tab → **Add Music…**

**Formats:** `.mp3`, `.m4a`, `.aac`, `.wav`, `.aiff` / `.aif`, `.flac`, `.caf`, `.ogg` / `.oga`, `.wma`, `.opus`

Only import tracks you have rights to use.

## Royalty-free library

Toolbar **+**, **File → Add Music → Royalty-Free Library…**, or **Audio** → **Royalty-Free Library…**.

![Toolbar + includes Royalty-Free Library…](../.gitbook/assets/toolbar-plus-menu.png)

![Royalty Free - No Attribution Required sheet](../.gitbook/assets/royalty-free-library.png)

Sheet title: **Royalty Free - No Attribution Required**. Subtitle: **YouTube Audio Library, cleared for MemoryString**. Built-in tracks need no attribution.

**Sort:** Catalog · Title (A–Z) · Genre (A–Z) · Duration (shortest / longest first).

![Sort the royalty-free catalog by Catalog order, Title, Genre, or Duration](../.gitbook/assets/royalty-free-library-sort.png)

Each row: checkbox, title / artist, style or **In project**, duration, play button to audition (does not move the show playhead). Check tracks, then **Add**. **Cancel** closes. **Add** needs at least one new track selected.

## Match Look Soundtrack

**Match Look Soundtrack** is on by default. Empty projects start quiet. After the first photos or videos land, MemoryString adds bundled track(s) from the current **Look** mood pool, or **Would It Matter** when no Look is selected. You can mute or remove anytime.

Each **Look** has a mood pool. **Energy** can lean calmer or brighter within that pool. The royalty-free sheet lists the **full catalog**, not only Look pools.

**While the playlist is still the auto bed** (empty, or only auto-seeded tracks):

- Clicking a **Look** chip picks a fitting track from that Look’s pool
- Longer shows may stitch more tracks before repeat
- Your own imported audio **replaces** the auto bed

**After you change the playlist by hand** (pick, reorder, trim, remove, or import), Look clicks do **not** swap the bed. New imports **append**.

Turn **Match Look Soundtrack** off to keep the playlist when changing Looks.

Audio files are never imported as photos.

## Audio tab bed actions

Under the playlist:

- **Pick New Music** — new Match Look bed for this Look. Asks before replacing music you added.
- **Extend to Fill** — keeps your tracks and adds music after them to cover the show.
- **Surprise me** — random track from the **full** catalog. Look clicks do not overwrite after Surprise.

## Audition the Audioline

Use the **Audioline** to hear a song at the playhead so you can set **Set Start Here** / **Set End Here**.

{% stepper %}
{% step %}
## Select the track

Click a soundtrack clip on the **Audioline**. It highlights. Scrub is silent until a clip is selected.

When the playhead crosses to another song, highlight and sound follow the clip under the needle.
{% endstep %}

{% step %}
## Scrub until you hear the moment

Drag the playhead or use **←** / **→**. You hear the selected song at the needle. Pictures stay paused. Video sound stays quiet while you scrub.

Hovering along the **Audioline** after selection auditions under the pointer.

Dragging a clip’s **edge grip** plays that point in the source while you trim.
{% endstep %}

{% step %}
## Mark start or end

When the playhead is on the bar or lyric you want:

![Audioline clip menu: Set Start Here, Set End Here, Reset Length](../.gitbook/assets/audioline-set-start-end-menu.png)

- Right-click the clip → **Set Start Here** / **Set End Here**
- Inspector clip footer → **Set Start** / **Set End**
- **⌘1** / **⌘2**

**Reset Length** restores auto-skipped quiet edges or the full file. Undo **⌘Z**.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Royalty-free sheet play and **Audio** tab row play preview the file without moving the show playhead. Use those to pick a track. Use **Audioline** scrub to pick trim points.
{% endhint %}

## Arrange on the Timeline

Drag clips on the **Audioline**. The **Audio** tab has up / down arrows per row.

On import, MemoryString **auto-skips silent lead-in and run-out** on tracks. Trim by ear with **Set Start Here** / **Set End Here** or edge grips. **Reset Length** restores the auto window or full file.

**Mute Track** / **Unmute Track** — **Audioline** menu, **Audio** tab (click time readout), or Inspector when a soundtrack is selected.

**Remove from Project** — royalty-free tracks remove immediately. Your imports ask first. **⌘Z** either way.

**Reset Audio Settings** on the tab restores volume, mute, and Match Look. Tracks and trims stay.

## Mix

Tracks crossfade with short tapers. Music **ducks** under video sound. Per-track volume and mute apply in preview and export.

The transport **speaker** (right of **Play/Pause**) mutes **all preview audio** without changing export or per-clip mute. See [Preview](preview.md#playback).

While a soundtrack decodes, the stage may show **Loading music…**. Photos stay editable. Export waits.

Only import tracks you have rights to use.

## Video sound (not the Audioline)

Clip audio is separate from the soundtrack. On import, **speech stays**; **silence or noise may mute**. Same in **Essential** and **Studio**. Details: [Auto detection](auto-detection.md#video-sound-auto-mute).

Unmute or mute anytime: right-click **Mute Video Sound** / **Unmute Video Sound**, speaker badge, or Inspector footer. See [Library](library.md#videos).
