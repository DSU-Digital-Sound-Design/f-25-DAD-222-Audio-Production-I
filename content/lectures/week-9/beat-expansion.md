---
title: "From two measures to 16"
---

## Multi-velocity layers

In the previous lesson we used velocity values to change the strength of the MIDI note. Velocity can also be used to trigger different samples with the same note. This is the concept in sampled called _multi-velocity layers_. It's typically used to playback a sample that was recorded at different dynamic levels, ex: forte, mezzo forte, piano. These dynamics might match up with 127, 100, and 60 velocity values.

To add a velocity layer click on the _[list]_ button in ReaSamplomatic5000. Now add another sample to this list. The order here maters. Samples towards the top of the list will play with higher velocity values. Try to add multiple samples of similar types. Now in your MIDI item you can experiment with different velocity values to play different samples. This will make your drum part more interesting.

## Round robin

Similarly to multi-velocity layers round robin sampling allows you to play different samples with the same MIDI note. But instead of responding to a velocity value, it will play depending on a probability that you set in the sampler.

I used round robin sampling to play two different hi hat samples. Here are my settings:

![](../round-robin.png)

The first sample is set to 50% probability. Round-robin is turned on as well as "Remove played notes from FX chain MIDI Stream". The next hi hat sample has the same settings but 100% probability. With these settings the same MIDI note will trigger each sample every other time.

This is a great way of adding variation and interest to your drum loops.

## Building out the song

How do we make our short loop into a more fully fledged song? One musical technique we can use is to take the drum loop and bring in parts gradually. To do this we'll need to break up our MIDI item into separate tracks. We can do this with a function in Reaper called _explode MIDI item by note row (pitch)_. You can find this under _Item Processing_.

Your tracks will now look something like this:

![](../explode-midi.png)

To make the MIDI item "loopable" right click and select "glue items". You can now loop this MIDI item. Now you can stagger entrances of drum parts and create variations for different parts of the song.

## Send Drum Parts to Effects

And finally we might want to route some of our drum parts to effects. Because we have multiple parts on the same track we need to use effects routing.

Select the instance of _ReaSamplomatic5000_ that you want to send to an effect. Click the button that says "2 out". This opens up the effects routing.

Set the routing like this:

![](../effects-routing.png)

The track channels are set to 6 and we're sending this sampler to 1/2 and 3/4.

![](../routing.png)

Now in the routing section for the drums make sure audio 3/4 and getting send to 1/2 of the track that has the effect you want to use.
