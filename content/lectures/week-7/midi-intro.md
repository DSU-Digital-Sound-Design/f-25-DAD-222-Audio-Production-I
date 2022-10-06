---
title: "Midi Intro in Reaper"
---

## Setup

When working with MIDI in Reaper we can speed up the process of creating the correct inputs by right clicking and selecting "insert virtual instrument on new track." What this does is insert a new track, prompt you to add a virtual instrument to it, and set MIDI as the track input.

If you would like to use one of the MIDI keyboards we have in class, you can plug one in. You then have to enable the device from the MIDI Devices menu in the preferences. Once enabled your device will show up in the MIDI inputs on your track.

If you don't have access to a MIDI device you will use Reaper's _Virtual MIDI Keyboard_, which allows you to trigger MIDI with your computer keyboard. Select that and listen for all channels. To see the _Virtual MIDI Keyboard_: View -> Virtual MIDI Keyboard.

You can see that it is working if you can see yellow meters on your track. This is not audio, but MIDI input.

## ReaSamplOmatic5000

_ReaSamplOmatic5000_ is the default sampler in Reaper. It plays one sample at a time and is perfect for learning how MIDI and sampling work. Add an instance to your track.

> Download these [samples](https://dakotastateuniversity-my.sharepoint.com/:u:/g/personal/tate_carson_dsu_edu/EWOvi1UXOD9Bg3vmW-a6GY0BBZMIGLCl8kdHBATbTnt2Gg?e=pGiHQc) to use for this example.

Drag and drop the bass pluck sample into the empty file window of the sampler. Now we can play any note on our keyboard and it will play the sample.

If you change the mode to _Note (Semitone shifted)_ the sampler will pitch shift the sample depending on what note you play.

Name your track _bass pluck_. Now record a MIDI loop into the track. This works the same way as recording audio. Make sure your track is record armed. You may want to have the metronome on while recording to have something to time your loop to.

Double clicking the MIDI item will open up the MIDI editor. Here we can see what notes we played, their lengths, and velocities. Here we can edit our part by dragging the notes up or down to change the pitch, or left and right to change the timing. We can also lengthen or shorten our notes the same way we do with media items. Notice that lengthening the note here doesn't make any difference because the sample is short.

You can also create new notes with the midi pencil tool by clicking and dragging.

## Quantization

This performance left a lot to be desired so lets fix it. We can do this with quantization. Click the Q button in the editor. Tell it to quantize all notes and watch the notes shift. You can now listen to the quantized notes, but this change isn't permanent yet. If you like what you hear you can _commit_ the quantization permanently.

If you want to try a different grid size to quantize to you can change that in the bar at the bottom of the MIDI Editor. Also experiment with the grid types of triplet, dotted, or swing.

## Adding more tracks

Add another virtual instrument track with the sampler on it and call it _Drums_. We're going to add all of the drum samples this one track. First add the kick sample to the first sampler. We want to map this sample to a single key. Pick the note on your MIDI device that you want to trigger the drum and press it. Then double click on the note start and note end knobs to set their value to the note you just clicked on your device. Now we should only hear that kick sample when we play one note but not the others.

Do this same process for the other drums in the sample pack adding each to the next key on your keyboard. You can copy/paste the sampler then choose another sample from the dropdown menu.

It can be helpful to set your MIDI record mode to _MIDI overdub_. This allows your to record the part in multiple passes without deleting what you had done before.
