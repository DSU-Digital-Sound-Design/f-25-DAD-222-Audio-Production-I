---
title: "Delay in Reaper"
---

Delay is one of the most simple time based effects.

- Delay takes the incoming audio and stores it in a digital buffer for a set time before playing it back 
- The delayed signal is mixed with the original, undelayed signal 
- The length of the delay time determines the character of the effect:
- Long delays of 100ms+ create clear, audible echoes
- Short delays of 10-50ms thickens the sound without noticeable echoes 
- Very short delays of a few ms act like a comb filter, cutting frequencies
- Feeding the delay output back into the input creates fading repeats
- Adjusting the delay time with feedback creates different effects
## Examples

Here are some example songs that showcase different delay effects:

**Long Delay (100ms+) - Clear Echoes**
- [Guns N' Roses - Welcome To The Jungle](https://www.youtube.com/watch?v=o1tj2zJ2Wvg) - The guitar intro has long delays on it, creating prominent echoes.
- [ U2: Where The Streets Have No Name](https://www.youtube.com/watch?v=3FsrPEUt2Dg) - The guitar notes in the intro have long delay echoes.

**Medium Delay (10-50ms) - Thickening Effect**
- [Nirvana - Smells Like Teen Spirit](https://www.youtube.com/watch?v=hTWKbfoikeg) - The vocals have a medium delay that thickens the sound.

**Short Delay (Few ms) - Comb Filtering**
- [The White Stripes - Seven Nation Army](https://www.youtube.com/watch?v=0J2QdDbelmY) - The main riff has a very short delay that gives it a comb filtered sound.
- Chorus and Flanging are types of comb filtering. 

**Feedback Delay (Repeating Echoes)**
- [Harry Styles - As It Was](https://www.youtube.com/watch?v=H5v3kku4y6Q) - heard in the background 

## In class mix

We'll use three different types of sounds to experiment with our delays.

Download the practice tracks [here](../delay-files.zip). 

Add these to your project as separate tracks. Solo each of them individually to listen. They are not meant to be played together. 

Now, create three more tracks that will be your delay sends. Name these tracks "short delay", "medium delay", and "long delay". These will not have audio on them directly. We will send audio from our other tracks to these tracks. We do this so that multiple tracks can share the same delay.

Add a _ReaDelay_ plugin to each of these delay sends. Make sure the dry level is set to -inf dB. We don't want the dry signal to be in the delay send. Set the short delay between 10 and 50 ms, set the medium delay to 100 - 300 ms, and then set the long delay to something greater than 300 ms.

Listen to the effect each delay has on each track. Fade in your send amount until you achieve the desired sound. Remember that in a real production these delays won't be as noticeable because they'll be mixed with other sounds. Context is key.

## Flanger

A flanger is created from modulating the delay time periodically. The delay line should be short, around 20 ms, and the rate of modulation should be around 10 Hz. Reaper has two flanger effects, _Flanger_ and _Flanger Baby_. Try them both on their own send tracks.

Example: [Heart - Barracuda](https://www.youtube.com/watch?v=VdOkQ6THDVw)

## Chorus

A chorus effect consists of multiple varying delays added together. In an actual choral ensemble, it is impossible for multiple singers on one part to produce exactly the same pitch at exactly the same time; they will each be slightly detuned in relation to one another. The same is true of any group of instruments playing the same part, such as the violins in an orchestra. The multiple time-varying delays when combined with the original signal simulate such an effect. To keep the effect subtle, the depth is usually modest and the modulation rate not very high.

Find the chorus effect in Reaper and test it out.

> Extra credit: there are a lot of other delay effects available in reaper that you can find when searching for delays. Test these and and find otu what they can do.

Example: [Nirvana - Come As You Are](https://www.youtube.com/watch?v=vabnZ9-ex7o)