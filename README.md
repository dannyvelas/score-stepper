# Score Stepper

A single-file HTML tool for stepping through a sequence of musical notes one at a time, with audio playback.

## Usage

Open `score_stepper.html` in a browser. Enter your notes in the text area, click **Load**, then advance through the sequence with **Next note** or by pressing `Space`.

## Note formats

| Format | Examples |
|--------|---------|
| Scientific notation | `C4`, `D#4`, `Eb3`, `F#5` |
| Solfège | `Do`, `Re`, `Mi`, `Fa`, `Sol`, `La`, `Si` |
| Chords (slash-separated) | `C4/E4/G4`, `Do/Mi/Sol` |

Multiple notes can be separated by spaces, commas, semicolons, or pipes.

## Features

- Steps through notes one at a time — useful for ear training or practicing sight-reading
- Plays each note using a real piano sample (Salamander Grand via Tone.js)
- Scrollable pill strip shows the full sequence with past/current/upcoming states highlighted
- Progress bar and note counter
- Keyboard shortcut: `Space` to advance

## Dependencies

- [Tone.js](https://tonejs.github.io/) — loaded from CDN
- [Salamander Grand Piano](https://github.com/sfzinstruments/SalamanderGrandPiano) samples — streamed from `tonejs.github.io`

No build step or server required — just open the file.
