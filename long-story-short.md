---
description: "Long story short turns a big pile of photos and videos into a shareable movie. You pick the length. Nothing is deleted."
---

# Long story short

**Long story short** builds a movie you can actually share from a big pile of photos and videos. You pick the length. It picks the best shots and spreads them across the whole trip. Everything else goes to **Outtakes**. Nothing is deleted from your Mac.

## Start it

- **File → Long story short**
- **Library** **⋯** → **Long story short**

![Library ⋯: Long story short at the top](../.gitbook/assets/library-options-menu.png)

Choose a **Duration** from **1** to **20** minutes, then **Create**. The default is **3 min**, short enough to share. Next time the slider starts where you left it.

If the show already has slides, it asks first: **Rebuild the show?** **Continue** opens the Duration sheet. The show stays as it is behind the sheet. **Cancel** changes nothing. Only **Create** rebuilds.

![Rebuild the show? Continue or Cancel](../.gitbook/assets/long-story-short-rebuild.png)

While the sheet looks through the photos it says **Checking M of N photos…**. When that count is ready, the note under the slider says how many distinct shots can fill the movie. The offer is the nearest minute that show can actually reach. The finished movie lands close to the minute you pick.

## Large imports

When an import would put more than **150** photos and videos on the show, MemoryString asks first: **That would make a N-photo show**.

![That would make a 2359-photo show: Long story short, Import all, Cancel](../.gitbook/assets/long-story-short-large-import.png)

- **Long story short** — pick the best ones for a shareable movie
- **Import all** — put everything on the show
- **Cancel** — import nothing

Same on every import path: **+**, Finder drop, **Import from Photos…**, Photos.app drag, folders, and paste.

## What it picks

- **Sharp, well-exposed** photos. Blurry, very dark, and tiny files are skipped
- **Near-duplicates** stay out. A different pose stays in. At most two shots from one pose, and those are not placed side by side
- **One group per shoot.** Photos from the same moment stay together. A two-shot series does not have to be a **Perspective Pair**. **Auto** may still pick Pair as one of the kinds. Uncheck Pair and those shots become single slides, with another slide between them when there is room. Pair stays off after **Shuffle**, a length change, reopening the project, and clicking the **Look** again
- **The whole trip**, not just the best day. Shots are spread across your dates
- **Videos** too. Each one is cut with [Auto Trim](auto-detection.md#auto-trim)

The show plays in date order. The length lands close to the minute you picked.

While it works you may see **Making a long story short...**, **Checking M of N photos…**, **Picking the best shots...**, **Reviewing M of N...**, **Straightening M of N...**, and **Arranging N shots…**. While it fits the length, the line shows the clock so far, such as **2:23 of 10:00**. Kept shots are upright before the movie is laid out. **Cancel** on the Duration sheet changes nothing. **Cancel** while it is building puts the previous show back. See [Orientation](auto-detection.md#orientation).

## After it runs

![After Long story short: a one-minute show, extras in Outtakes](../.gitbook/assets/long-story-short-result.png)

- Groups are spread along the timeline with the usual gap between them, not back to back
- The title bar shows the new length
- Shots that did not make it are in [Outtakes](library.md#outtakes). Drag any of them up to put them back
- A show you already styled keeps its **Look** and soundtrack. If the new cut runs longer than your music, bundled songs fill the rest. Your own tracks are never replaced
- A brand-new project starts on **Cinematic** with bundled music
- Undo with **⌘Z**

Run it again anytime with a different length. It chooses from everything in the project, **Outtakes** included.
