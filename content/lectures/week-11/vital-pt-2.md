---
title: "More Vital Synth"
---

We finished the last lesson by talking about he ADSR envelope in Vital. We'll now move onto adding more oscillators to get a more complex sound. Turn on oscillators 2 and 3 to hear them. The functionality of these oscillators is the same as oscillator 1, but they allow you to layer your sounds.

# Starting patches

## Patch 1 - ghostly choir

Set each oscillator to a sine tone, the first option in the basic shapes wave. Now set the detune for osc 1 and 2 to slightly above and below osc 1. What happens? Is it what you expect? Now turn on the filters, do you hear a change? If you look at your spectrogram you may only see a slight change. most of the timbre we're hearing is psychoacoustic (happening only in our brains), so will not show up on the meter. If you do turn on the filter, it won't filter out anything, because these are sine tones. But, it will add a harmonic because it is an "analogue modeling" filter.

## Patch 2 - Chorus bass

Now return your patch to its initial state. Set the first osc to a sawtooth wave and the second to the same. Change the pitch of the second osc to be -12. This sets its pitch down an octave or 12 semitones. Also set the second osc to go to filter 1.

## Patch 3 - Adding the sampler

This sampler allows you to add more texture to your synth patch. There are built in samples, or you can add your own. Pressing the keyboard button will cause the sample to repitch depending on what MIDI not is being played. There's also a loop button, play then reverse, and play from the previous place you stopped. You can either you use a textural sample to give some grit below your synths, or add a percussive sample to give a nice click at the beginning of the envelope.

## Some more basic details

The voices number is the number of sounds you can play at any one time. Bend will set the range of the pitch bend control on a MIDI keyboard. Vel Trk at will cause Vital to respond to velocity messages. Spread makes the sound more or less mono.

Glide causes one note to slide into the next at the glide time.

# Adding effects

## Chorus

A chorus is sort of like a delay that also modulates its pitch. You can choose the number of voices, how fast the voices move frequency.

- Delay Modulation Frequency. - Determines the amount of time before delay modulation repeats itself

Delay Timing Knobs
Delay 1: Relative control for delay time for half of the chorus voices.
Delay 2: Relative control for delay time for the other half of the chorus voices

## Compressor

This is a multi-band compressor.

## Flanger + Phaser

These are similar to the chorus but modulate filters. Play around with them and hear what sounds they make.

A flanger is a sound produced when the original sound is played with a duplicate of itself at a low but changing delay time.

A phaser duplicates the original sound runs it through an all-pass filter and then plays that back with the original sound.

# Matrix and Modulation, LFO and Envelopes

## LFO

As you play any note notice that the LFO is actively moving through a triangle oscillator. It isn't having an effect yet because we need to connect it to a parameter.

Drag the LFO icon down to the cutoff frequency control of Filter 1. Now notice that you can control this cutoff frequency parameter with the LFO. Notice the circle that now connects the two parts of the synth. This allows you to change the amount of modulation. You can also think of this as the _strength_ of the modulation. Now experiment with the frequency of the LFO.

As with our audible oscillators, we're not limited to basic oscillator shapes for our LFOs. Experiment with some of the other oscillator shapes that can give the sound a more rhythmic quality.

Currently, our modulation only acts in a positive direction, from the start of the parameter upward. We can change that and modulate +/- from our starting position by right clicking on the amount icon and choosing "make bipolar."

> All of these options can be more clearly seen in the matrix tab. Click on that now.
