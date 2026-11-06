# Neckmap

An interactive guitar fretboard for learning scales, modes, pentatonic boxes and CAGED chord shapes.

Pick a key and a mode, then stack up to three overlays on one neck:

- **Chord:** any chord in the key (triads or 7ths) or a custom chord, shown as all five CAGED shapes or one at a time.
- **Pentatonic:** major or minor, whole neck or boxes 1-5.
- **Scale / mode:** the selected mode, any other mode, harmonic or melodic minor, or blues, whole neck or positions 1-7.

Notes can be labelled with note names, intervals, scale degrees or Nashville numbers. Click a CAGED shape label to show only that shape.

## Use it

Open the live page: _add your link here after publishing_

Or download `index.html` and open it in any browser. There is nothing to install.

## Details

- Standard tuning, frets 0-17.
- Single file with no build step and no dependencies. Fonts load from Google Fonts.
- Settings are saved in your own browser (local storage). Nothing is sent anywhere.
- Colours come from the Okabe-Ito colour-blind-safe palette. Markers and labels are checked against WCAG 2 contrast ratios, and the page includes a contrast table.
- Layers also differ by shape (circle, square, diamond), so colour is never the only cue.

## Known limits

- CAGED shapes are fixed templates: no inversions or extended chords (9, 11, 13).
- A shape or box that would run past fret 17 is left out rather than drawn in part.

## License

Copyright (c) 2026. All rights reserved. The source is visible here, but no permission is given to copy, modify or redistribute it.
