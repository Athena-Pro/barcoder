# Barcoder

Two browser synthesizers that play images. Drag a scan beam across a sheet and the colour under it becomes sound.

| File | Instrument | Sheet | Channels |
|---|---|---|---|
| [`RGB Barcoder.html`](RGB%20Barcoder.html) | 3-channel opto-synth | Light on a dark sheet | Red, green, blue |
| [`CMYK Barcoder.html`](CMYK%20Barcoder.html) | 4-ink press synth | Ink on white paper | Cyan, magenta, yellow, black |

In RGB, dark is silence. In CMYK, paper is silence and black ink is a fourth voice.

## Running

Open either file in a current desktop browser. There is nothing to install or build. Each file holds all of its own HTML, CSS and JavaScript, and the only network request is for Google Fonts.

## Features

- **10 modes:** Triad, Stereo, Matrix, FM, Spectral, Ring, Vox, Steps, Grain and Font
- **Layers:** two modes at once with Combi, and a layer A/B blend
- **Sheets:** built-in test sheets, a paint tool, or your own image
- **Modulation:** two LFOs and a patch bay that can route beam position, channel levels and edges to voice, effect and scanner settings
- **Samples:** load a `.sf2` SoundFont or an audio file for the Font and Grain modes, and export a `.zip` of WAVs
- **Patches and takes:** save and open patches as JSON, and record takes in the browser

## Keys

| Key | Action |
|---|---|
| `1`-`0` | Switch mode |
| `Shift`+`1`-`0` | Switch layer B mode |
| `C` | Combi |
| `Q` / `E` | Rotate beam |
| `R` | Reset angle |
| `B` | Beam shape |
| `H` | Hold |
| `A` | Auto-scan |
| `P` | Paint / scan |
| `Space` | Checkout beep |

Drop a picture on the sheet to load it. In CMYK it is separated into four inks. Drop a `.sf2` or audio file to play it in Font and Grain modes.
