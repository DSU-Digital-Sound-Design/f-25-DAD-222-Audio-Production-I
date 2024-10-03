---
title: "Compression and When to Use It"
---

Download [these audio tracks](../comp-audio.zip) to practice with in class.

> Compression is a technique that controls the dynamic range of an audio signal—this means balancing the loudest and quietest parts by reducing peaks and boosting lower parts when needed.

![](../Figure-7.11-Dynamics-compression-and-expansion.png)

This image shows how compression affects the dynamic range, balancing the loud and quiet moments of a signal.

For more detailed definitions of compressor parameters, check out the [Reaper Effects guide](https://dlz.reaper.fm/userguide/REAPEREffectsGuide2021.pdf), specifically Chapter 2 on compression.

### Why Use Compression?

Here are some common uses for compression in music:

- **Vocals**: Compression keeps vocals at a steady level, so softer parts don’t get lost and louder parts don’t overwhelm the mix.
- **Drums**: Compressing drums can make them punchier by controlling their dynamic range, giving them more presence.
- **Instruments**: Compression can also add sustain to instruments like guitars, making notes last longer and sound fuller.

### Applying Compression to Drums

Let's start by compressing the **kick drum** in our mix using ReaComp in Reaper:

1. Click on the FX button on the kick drum track.
2. Search for "ReaComp" in the FX browser and add it to the track.
3. Enable **Auto Make-up** gain to keep the output volume consistent after compression.

Two important parameters to focus on are **threshold** and **ratio**.

> **Threshold**: This determines the volume level at which the compressor starts to work. If the sound goes above this level, the compressor kicks in.
>
> **Ratio**: Once the threshold is crossed, the ratio determines how much the volume is reduced. For example, with a 4:1 ratio, for every 4 dB over the threshold, the output only increases by 1 dB.

![](../Audio-Compressor-Ratio-Chart-652x435-1418756899.jpg)

Try setting the ratio to 4:1 and adjust the threshold. As you lower the threshold, you’ll see the gain reduction meter show how much the volume is being reduced.

Listen carefully to the kick drum before and after applying compression to hear how the sound becomes more controlled.

### Fine-Tuning Attack and Release

Once you have set the threshold and ratio, you can adjust the **attack** and **release** settings. These determine how quickly the compressor reacts to changes in volume.

> **Attack**: Controls how fast the compressor kicks in after the threshold is crossed. A fast attack (e.g., 10 ms) clamps down on transients quickly, while a slower attack allows more of the initial hit to come through, adding punch.
>
> **Release**: Determines how fast the compressor stops compressing after the volume falls below the threshold. A fast release (e.g., 100 ms) ensures that the compression stops quickly, preserving the natural sound between hits.

For a punchy kick drum, set the attack to around 10 ms and release to 100 ms. Watch the gain reduction meter and adjust these values while listening for the best sound.

### Applying Compression to Other Instruments

Once you're comfortable with compressing the kick drum, apply similar techniques to other drum elements, such as the snare, adjusting the threshold, ratio, attack, and release according to the characteristics of each sound.

### Bus Compression

After compressing individual drum tracks, you can try **bus compression**, which applies compression to all the drum tracks together. This can help glue the drum sounds together for a more cohesive mix.

Here’s how to set up bus compression:

1. Create a new track and name it "Drum Bus."
2. Route all individual drum tracks (kick, snare, etc.) to this new bus.
3. Add ReaComp to the Drum Bus and set a gentle ratio (e.g., 2:1). This will bring all the drum elements together without sounding over-compressed.

### Conclusion: Keep Experimenting

Compression is a versatile tool for shaping the dynamics of your audio. Start by experimenting with your drums, then try applying compression to other elements like vocals and guitars. Over time, you’ll develop an ear for how compression can enhance your mix.

