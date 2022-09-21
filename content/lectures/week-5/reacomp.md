---
title: "How and why to use Compression"
---

> Compression is the process of reducing the difference between a signal's loudest and quietest parts, or its dynamic range.

![](../Figure-7.11-Dynamics-compression-and-expansion.png)

[source](http://digitalsoundandmusic.com/chapters/ch7/)

See the [Reaper Effects guide](https://www.reaper.fm/guides/REAPEREffectsGuide2021.pdf) section on compression (Chapter 2) for basic definitions of parameters.

Some uses for compression:

- Our singer sings too softly causing the vocals to get lost in the mix
- Or conversely if the singer sings too loudly, it would overpower the mix
- Make drums and percussion more cutting and aggressive by reducing their dynamic range

### Drums

We'll start with the drums on our mix. Solo the **kick drum** and add a ReaComp to it. Check the auto make-up gain (the level of the output volume will be increased to compensate for any reduction caused by the compression).

The most important parameters are **threshold** and **ratio**

> **Threshold** - Determines the volume at which compression should be applied.
>
> **Ratio** - Determines the extent to which the compression will reduce the track's volume above the threshold.

![](../Audio-Compressor-Ratio-Chart-652x435-1418756899.jpg)

Set your ratio to 4:1 and the compressor will only compress your signal by 1 dB if it was 4 dB before it hit the threshold. As you pull down the threshold value, you will see how much gain reduction is happening in the gain reduction meter.

Listen to the kick before and after to hear the tonal changes that the compressor adds.

The next most important settings are the **attack** and **release** times. These parameters are towards the more advanced side of compressor usage.

> Attack - Determines how quickly the compressor responds when the threshold level is reached or exceeded. A zero
> setting means the full compression will be applied immediately and suddenly: the greater the number of
> milliseconds specified, the more gradual the response.

> Release - Determines how quickly the compressor responds when the volume drops below the threshold level. A zero
> setting means that the compression will be fully and instantly released. A higher setting ensures that the release
> will be more gradual

These are subtle to hear but easier to see in the gain reduction meter.

Now try the same process on our snare drum.

**Sidechain compression**

Sometimes you want to trigger your compression threshold from another instrument. An example would be to have any held instrument duck out of the way of the kick drum. Most of our sounds are already ducking so I have added a pink noise track to demonstrate this.

Take your threshold trigger and send it to inputs 3/4 of your target track. On your target track, change the "Detector Input" to auxilliary inputs. Now you can use the compressor to duck the track out of the way of your trigger.

**Buss Compression**

It is common to add another compressor to your drum bus to "glue" the sounds together. For this we can use the **1175 Compressor** with a gentle compression setting. When using this compression plugin you need to set the gain manually. Try to match your output gain to your input.

> Try a few of the other bus compressors and compare their sounds. Try _Digital Drum Compressor_ or _Express Buss Compressor_.

> What other elements in this mix do you think could use a compressor? Try it out on those. Try some other types of compressors as well. Some will have a pretty drastic effect on the tonal quality of the sound. See: _Dirt Squeeze Compressor_
