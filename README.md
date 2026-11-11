# Score Converter

Open printed music and get a score you can play, change and save.

Open it here: https://deepspace000.github.io/score-converter/

## What it does

- **Open a score**: a PDF or a picture of printed music, or a MusicXML (also compressed .mxl), MIDI or saved score file. A **zip file** of any of these opens too: its pictures become the pages of one score, in name order, read as they are or tidied first; with several things inside, a list asks which to open. Press **Open score** or drop the file on the page. Read every page, one page, or chosen pages (for example 5-6). Time signatures from 1 to 16 over 2, 4, 8, 16 or 32 are read from the page, and any time from 1 to 32 over 1, 2, 4, 8, 16 or 32 can be set by hand under **Edit**.
- **Photos**: press **Photo** to take in photos of printed music (from the camera or your pictures). Each one opens on a tidy-up page first: turn it, drag the four corners onto the corners of the music so the staves run straight, and even out the light. A PDF still reads more accurately than a photo.
- **Play it**: every part together, with mute, solo, volume, pan and sound for each part. Start from any bar. The score follows the music.
- **Loop and count-in**: press **Loop** and the bars in the two boxes (or the chosen bookmark) are played round and round, with a bar or two of clicks before each time. The count-in also works without the loop.
- **Bookmarks**: press **+ Bookmark** (the pointer becomes a book), click the bar where a passage starts, then the bar where it ends. The bookmark appears above the score and its bars are shaded. Press it to play the passage; press **Loop** to go round it, with the count-in you choose. Bookmarks are saved with the score. Key M while the music plays marks the bar that is playing.
- **Change the tempo**: the Tempo box (a printed metronome mark sets it when the score is read).
- **Change the notes**: drag a note up or down on the staff, or click it and use the arrow keys or the buttons under **Edit** to change its pitch or rhythm, delete it, or add notes and rests. Key, time signature and title can be changed too.
- **Careful scan (slower)**: tick this on the scan page for a slower, more accurate reading. Every bar that does not add up is read again in nine different ways, and the reading most of them agree on is kept. It adds a few seconds for each doubtful bar. **Undo re-scan** puts the first reading back.
- **Phones and tablets**: on a small screen the toolbar is short, with the less used controls behind **More**. The screen stays on while music plays or a scan runs, and a **Stop careful scan** button takes the place of the Esc key.
- **Re-scan bars**: if some bars came out wrong, type their numbers under **Edit** (or click a note in the bar) and press **Re-scan from the page**. The bar is cut out of the printed page and read again. Each further press reads it a different way (on its own, larger, smaller, with the bars either side, each staff by itself, with the print made heavier or lighter) and shows the next reading you have not seen yet. **Undo re-scan** goes back one press at a time.
- **Transpose**: the score and the sound together, the score only, or the sound only.
- **Choose the sounds**: pianos, harpsichord, clavier (clavichord and fortepiano), harps, classical guitar, choir, flute, recorder, oboe, clarinet, bassoon, strings, and C64 and chiptune sounds, for each part.
- **Save it**: **Save score** keeps everything in one file to open again later. Export as MIDI (every part, the piano only, or the parts you tick), MusicXML or PDF.

The reader handles scores with several staves, piano parts with chords and two voices, lyrics, slurs, ties, dynamics, hairpins and tempo words. Everything runs in the browser; nothing is uploaded.

## Keys

| Key | Does |
| --- | --- |
| Space | Play / stop |
| Left / right arrow | Previous / next note |
| Up / down arrow | Selected note up / down a step in the key (with Shift: a semitone) |
| 1 to 6 | Rhythm: breve, semibreve, minim, crotchet, quaver, semiquaver |
| . | Dot |
| A to G | Add a note |
| R | Add a rest |
| M | Bookmark the bar that is playing |
| Delete | Delete the selected note |
| Ctrl+Z | Undo |
