---
title: "Midi Intro in Reaper"
---
# Midi Intro in Reaper

## Setup

1. Insert a new track and select "Insert virtual instrument on new track" when prompted. This will create a track with MIDI as the input.
2. If using a MIDI keyboard, plug it in and enable it in Reaper's preferences under MIDI Devices. The keyboard will now show up as a MIDI input for your tracks.
3. If no MIDI keyboard, use Reaper's Virtual MIDI Keyboard under View -> Virtual MIDI Keyboard. This allows you to trigger MIDI notes from your computer keyboard.
4. Look for yellow meters on the track input to verify MIDI input is working.

## ReaSamplOmatic5000

> Download these samples to use for this example.
>
> * [drums](../samples/drums.wav), [bass](../samples/bass.wav)

1. Add ReaSamplOmatic5000 to the new track. This is Reaper's default sampler plugin.
2. Download the provided samples and drag the bass sample onto the ReaSamplomatic plugin.
3. Play notes on the MIDI keyboard and the sample will trigger.
4. Switch the sampler to Note (Semitone shifted) mode to pitch shift the sample with different notes.
5. Record a MIDI loop using the Record Arm button. Double click the MIDI item to open the MIDI editor.
6. In the editor, notes can be edited by dragging. Create new notes with the Pencil tool.

## Quantization

1. Click the Q button to quantize the recording. Adjust settings to taste.
2. Commit the changes to make quantization permanent if it sounds good.
3. Try different grid sizes like triplet or swing for creative results.

## Adding more tracks

1. Add another track with ReaSamplomatic5000 for drums.
2. Add each drum sample to a different note by setting Note Start and End knobs.
3. Use MIDI Overdub recording mode to build up drum pattern over multiple passes.

## Setup

When working with MIDI in Reaper we can speed up the process of creating the correct inputs by right clicking and selecting "insert virtual instrument on new track." What this does is insert a new track, prompt you to add a virtual instrument to it, and set MIDI as the track input.

If you would like to use one of the MIDI keyboards we have in class, you can plug one in. You then have to enable the device from the MIDI Devices menu in the preferences. Once enabled your device will show up in the MIDI inputs on your track.

If you don't have access to a MIDI device you will use Reaper's _Virtual MIDI Keyboard_, which allows you to trigger MIDI with your computer keyboard. Select that and listen for all channels. To see the _Virtual MIDI Keyboard_: View -> Virtual MIDI Keyboard.

You can see that it is working if you can see yellow meters on your track. This is not audio, but MIDI input.

## ReaSamplOmatic5000

_ReaSamplOmatic5000_ is the default sampler in Reaper. It plays one sample at a time and is perfect for learning how MIDI and sampling work. Add an instance to your track.

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
