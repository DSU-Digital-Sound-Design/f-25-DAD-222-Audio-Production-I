---
title: "Delay in Reaper"
---

Delay is one of the most simple time based effects.

> Delay involves storing the audio in a digital delay line for some amount of time and then playing back the stored audio combined with the undelayed signal. The delayed signal will naturally be “behind” the original. The length of the delay line determines the results of the effect. A delay line of about 100ms (one-tenth of a second) or more will create clear echoes of the original signal. A shorter delay time of around 10 to 50ms will give the sound some “thickness.” Extremely short delay times of a few milliseconds or less produce effects similar to that of a “comb” filter, where evenly spaced frequencies in the spectrum are cut out. The output of a delay line can also be fed back to its input, resulting in a series of echoes that gradually die out or other effects if the delay time is very short.

We'll use three different types of sounds to experiment with our delays.

Find the following sounds from [Mike's free multitrack library](https://cambridge-mt.com/ms/mtk/). Get sounds from different projects.

- simple percussion loop with only one instrument
- guitar chord or melody loop
- An a capella vocal

Add these to your project as separate tracks.

Now, create three more tracks that will be your delay sends. Name these tracks "short delay", "medium delay", and "long delay". These will not have audio on them directly. We will send audio from our other tracks to these tracks. We do this so that multiple tracks can share the same delay.

Add a _ReaDelay_ plugin to each of these delay sends. Make sure the dry level is set to -inf dB. We don't want the dry signal to be in the delay send. Set the short delay between 10 and 50 ms, set the medium delay to 100 - 300 ms, and then set the long delay to something greater than 300 ms.

Listen to the effect each delay has on each track. Fade in your send amount until you achieve the desired sound. Remember that in a real production these delays won't be as noticeable because they'll be mixed with other sounds. Context is key.

## Flanger

A flanger is created from modulating the delay time periodically. The delay line should be short, around 20 ms, and the rate of modulation should be around 10 Hz. Reaper has two flanger effects, _Flanger_ and _Flanger Baby_. Try them both on their own send tracks.

## Chorus

A chorus effect consists of multiple varying delays added together. In an actual choral ensemble, it is impossible for multiple singers on one part to produce exactly the same pitch at exactly the same time; they will each be slightly detuned in relation to one another. The same is true of any group of instruments playing the same part, such as the violins in an orchestra. The multiple time-varying delays when combined with the original signal simulate such an effect. To keep the effect subtle, the depth is usually modest and the modulation rate not very high.

Find the chorus effect in Reaper and test it out.

> Extra credit: there are a lot of other delay effects available in reaper that you can find when searching for delays. Test these and and find otu what they can do.
