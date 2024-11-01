---
title: "Getting Started with Vital Synth in Reaper"
---


### Installation
   - First, [download and install Vital Synth](https://vital.audio/#getvital). The **Basic** version is free and includes all essential features, so start there.
   - Once installed, open Reaper, create a new track, and add Vital as an instrument. You’ll see a default interface with multiple panels, including oscillators, filters, and envelopes.

### Load and Explore Presets
   - Before diving into patch creation, start by loading some **presets**. Presets are pre-made sounds, showcasing Vital’s capabilities and giving you a sense of the types of sounds you can create.
   - Click on the **Preset Browser** to open the preset list. Scroll through, select a few presets, and play them to hear what Vital can do.
   - Spend a few minutes experimenting with various presets to understand the variety of sounds Vital can produce, from deep basses to complex pads.

### Reinitialize the Patch
   - To start with a blank slate, **reinitialize** the preset:
       - Open the preset menu (click on the preset name) and select “**Initialize Patch**.”
   - This action resets the synth to a basic sawtooth waveform with no effects or complex settings, so you’re working from scratch.

---

## Creating Your First Patch in Vital

### Understanding the Oscillator
   - In the **Oscillator 1** panel, you’ll see a default **Sawtooth Wave**.
       - Click the waveform display to open a list of other **wave shapes**. Try selecting different shapes, like **Sine**, **Square**, and **Triangle**, and listen to how each one changes the tone.
   - Notice the **Position Slider** to the right of the waveform display. This slider lets you explore Vital’s **wavetable** capabilities:
       - Move the slider up to hear how the sound morphs. Vital’s wavetables contain multiple frames, and sliding through them changes the wave shape in real time.

### Adjusting Pitch and Tuning
   - Next, look for the **Pitch** and **Fine Tuning** controls, usually labeled as **Semitone** (for larger pitch adjustments) and **Cents** (for smaller adjustments).
       - Experiment with shifting the pitch up or down by semitones to get a feel for how these controls impact the sound.
       - Fine-tuning by a few cents can add slight detuning effects, which are especially useful when you add more oscillators.

### Activating the Filter
   - Move down to the **Filter 1** panel. Initially, it’s turned off (greyed out).
       - Click the **Dot** next to “Filter 1” to turn it on.
   - Vital offers various filter types, from **Low-Pass** and **High-Pass** to **Band-Pass**. Try selecting a **Low-Pass Filter** first:
       - Adjust the **Cutoff** knob to control the amount of high frequencies being filtered out.
       - Experiment with the **Resonance** knob to add emphasis around the cutoff frequency, which can make the sound more pronounced and resonant.

### Adding Depth with Unison
   - Locate the **Unison** section in the Oscillator 1 panel.
       - Set **Voices** to 4 or 5 to add extra copies of the oscillator.
   - Use the **Detune** and **Power** parameters to control how much each voice is detuned and how intensely the voices interact with each other.

### Exploring Spectral Morph and Wave Morph
   - Scroll down to the **Spectral Morph** and **Wave Morph** options, located under the oscillator controls.
       - **Spectral Morph** modifies the frequency spectrum of the wave, giving you access to effects like **Form Scale** and **Smear**. Experiment with these settings to hear how they shape the harmonic content of your sound.
   - **Wave Morph** alters the waveform’s shape itself, with options like **Sync**, **Formant**, **Bend**, and **Squeeze**, letting you blend between multiple waveforms. This allows for unique sound transformations, so try adjusting the morphing amount and hear the changes in real time.

### Shaping the Sound with the Amplitude Envelope
   - On the right side of the interface, locate the **Amplitude Envelope**. It has familiar **Attack, Decay, Sustain, and Release (ADSR)** parameters.
       - **Attack**: Controls how quickly the sound reaches its peak volume.
       - **Decay**: Determines how quickly the sound drops from the peak to the sustain level.
       - **Sustain**: Sets the volume level maintained as long as you hold down the note.
       - **Release**: Controls how quickly the sound fades away after you release the note.
   - Vital adds two additional parameters—**Hold** and **Delay**:
       - **Hold** keeps the sound at its peak level for a specified time before Decay begins.
       - **Delay** pauses the start of the envelope, creating a delayed onset for the sound.
   - Adjust these envelope settings to create different effects. A fast attack and short decay make a percussive sound, while a long attack and release create a more ambient effect.

> Spend the rest of the class creating different presets based on these parameters. Be sure to save them for future use with a descriptive name and category.