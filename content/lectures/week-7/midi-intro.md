---
title: "MIDI Introduction in Reaper"
---

> Download the Sitala plugin (free): https://decomposer.de/sitala/#downloads

## Setting Up MIDI

1. **Create an instrument track**: Use `Track -> Insert virtual instrument on new track...` (recommended). This inserts a track, opens the FX browser, and sets the track to receive MIDI. Alternatively, create a track, set input to `MIDI > All MIDI inputs > All channels`, enable record monitoring (speaker icon), and arm the track.
2. **Connect your MIDI keyboard**: Go to `Options > Preferences > Audio > MIDI Devices`, enable your device for input (and optionally “Enable input for control messages”). Then choose it—or “All MIDI inputs”—as the track input.
3. **Use the Virtual MIDI Keyboard (optional)**: `View > Virtual MIDI Keyboard`. Set the track input to “Virtual MIDI keyboard” or “All MIDI inputs” to play from your computer keys.
4. **Verify activity**: The track shows a small MIDI activity indicator when MIDI is received. With an instrument inserted and record monitoring on, the audio meter should move as you play.

## Working with Sitala

> For this exercise, gather a few drum one‑shots (kick, snare, hi‑hat). Sitala is a 16‑pad drum sampler, ideal for one‑shots. For a playable bass instrument, use a synth (e.g., ReaSynth) or a sampler that maps samples chromatically (e.g., ReaSamplomatic5000)—not Sitala.

1. **Add Sitala to a track**: Insert Sitala on your instrument track.
2. **Load drum samples**: Drag one‑shot samples onto Sitala’s pads or load a kit. Pads map to consecutive MIDI notes by default (often starting near C1). Use Sitala’s six controls—Shape, Compression, Tuning, Tone, Volume, and Pan—to sculpt each sound. Adjust sample start/end in the waveform view as needed.
3. **Record a MIDI pattern**:
   - Arm the track and turn record monitoring on.
   - Right‑click the track’s Record Arm button > `Record: MIDI overdub/replace` > choose `Overdub`.
   - Set a time selection and enable Repeat if you want to loop while layering.
   - Record your drum pattern.
4. **Edit MIDI**: Double‑click the MIDI item to open the MIDI editor. Draw notes with the pencil, move/resize to adjust timing and length, and set velocities.

## Quantizing MIDI Notes

1. **Open Quantize**: Press `Q` in the MIDI editor (or `Edit > Quantize events...`).
2. **Choose grid and strength**: Set the grid (e.g., 1/16, 1/8T), adjust Strength/Amount, and choose whether to quantize note positions, note ends, or both. Add Swing for groove if desired.
3. **Apply and listen**: Apply, listen, and tweak. Undo if needed; aim for musical feel over perfect alignment.

## Adding More Tracks

1. **Another drum track**: Add a second Sitala for more kits or layers.
2. **Pad mapping and shaping**: Each pad triggers a specific MIDI note; adjust pad note mapping or use MIDI Learn if needed. Sculpt sounds with Shape, Compression, Tuning, Tone, Volume, and Pan; trim start/end in the waveform view.
3. **Layer parts**: Keep `Record: MIDI overdub` enabled to add elements across multiple passes.

## Common Gotchas

- No sound? Ensure an instrument is inserted, the track is armed, record monitoring is on, and the input is set to your MIDI device (or Virtual MIDI Keyboard).
- High latency? Lower your audio buffer size in Preferences (CoreAudio/ASIO settings) while avoiding crackles.
- Virtual MIDI Keyboard tip: The window needs focus for your computer keys to play notes.
