---
title: "Mixing with reverb"
---

> Download the audio files [here](https://dakotastateuniversity-my.sharepoint.com/:f:/g/personal/tate_carson_dsu_edu/Em4CtTSSKXRDhmr9Iaxn5TIBclFmF2zb6MVO49FjPDsR3A?e=2OBZ5y).

Reverb is an essential tool in mixing, used to enhance various elements in your sound. Here’s how it can affect your mix:

- **Blend**  
  Jimmy Page used spring reverb to help the guitar solo blend seamlessly with the rest of the track.  
  <iframe width="560" height="75" src="https://www.youtube.com/embed/QkF3oxziUI4?si=5HJuYhExAy0a5QEL&amp;start=353" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- **Size**  
  On *A Day in the Life* by The Beatles, George Martin used reverb on the strings to create the illusion of a large symphony orchestra playing in a concert hall.  
  <iframe width="560" height="75" src="https://www.youtube.com/embed/usNsCeOV4GM?si=c1ZvTXPjElePlG4u&amp;start=167" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- **Tone**  
  Reverb can change the tone of vocals, adding character and depth.  
  <iframe width="560" height="75" src="https://www.youtube.com/embed/CKTOvHw8qFM?si=HrEZlhPowoJjPhyc&amp;start=167" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- **Sustain**  
  Reverb helps sustain vocals, making them sound fuller and longer.  
  <iframe width="560" height="75" src="https://www.youtube.com/embed/4NRXx6U8ABQ?si=vIxpBWlNYGaTsBMd&amp;start=167" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- **Spread**  
  Reverb can spread out the snaps and vocals, especially noticeable in choruses.  
  <iframe width="560" height="75" src="https://www.youtube.com/embed/fWNaR-rxAic?si=M_aKnvjvDWzBnQGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Analog Reverb Techniques

Before digital plugins, engineers used physical spaces and devices to create reverb. Some of these methods included chambers, plates, and springs.

### Inside the Reverb Chambers at Capricorn Sound Studios

<iframe width="560" height="315" src="https://www.youtube.com/embed/Am0ELIQcCgQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Spring Reverb

<iframe width="560" height="315" src="https://www.youtube.com/embed/tU7U-U-n4EQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Plate Reverb

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y58nroQ0DMw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Reaper Stock Plugins for Reverb

In Reaper, there are two primary reverb plugins you can use:

- **ReaVerb**
- **ReaVerbate**

Check out the [ReaEffects Guide](https://www.reaper.fm/guides/REAPEREffectsGuide2021.pdf) for more details on these plugins.

## ReaVerbate

Let’s start by learning how to use ReaVerbate on single instruments, and then apply it to enhance the elements mentioned earlier. ReaVerbate is a stock reverb plugin in Reaper. Start by adding it to your guitar track.

Here are key parameter descriptions (from the ReaEffects guide):

- **Wet**: Determines how much of the processed signal is mixed with the original.
- **Dry**: Controls how much of the original signal remains unprocessed.
- **Room Size**: Adjusts the size of the simulated room.
- **Dampening**: Simulates how much the sound is absorbed by materials in the room (e.g., curtains, carpets).
- **Stereo Width**: Controls the width of the stereo field for the reverb.
- **Initial Delay**: Adds a delay before the reverb starts, creating more space.
- **Lowpass/Highpass**: Filter controls to apply reverb to only certain frequency ranges.

### Reverb on One Instrument

Set the room size to 100, then adjust the dampening. With low dampening, you'll hear a brighter reverb; with more dampening, the reverb becomes darker. You can further shape the sound using the high and low pass filters.

### Reverb on a Send

Often, you want to apply the same reverb to multiple instruments. To do this in Reaper, create a send.

1. Create a new track and name it "Reverb."
2. Route your drum tracks to this send by selecting all the drums, holding shift, and dragging them onto the Reverb track.
3. Add ReaVerbate to the Reverb track. Set the wet mix to 0 dB and the dry mix to -inf dB (since this is a send track).
4. Open the routing for the Reverb send and set all send levels to -inf dB. Then bring up the send levels for each drum one at a time. Start with the snare, then add reverb to the overheads.

> Try creating custom presets for the guitar and vocal tracks. Then apply this process to your drum editing project from earlier in the semester.

## ReaVerb

ReaVerb offers more advanced customization and supports convolution reverb. It has several modules, including:

- **Echo Generator**: Creates echo or delay effects.
- **Reverb Generator**: Adds traditional reverb.
- **Convolution Reverb**: Uses impulse responses to simulate different spaces.
- **High/Low Pass Filters**: Adjust the frequencies affected by the reverb.
- **Normalization**: Levels out the reverb volume.
- **Reverse**: Reverses the reverb tail.
- **Time/Gain/Stretch**: Alters the timing and pitch of the reverb.

Explore free impulse responses from sites like [Open Air](https://www.openair.hosted.york.ac.uk/) and [Voxengo](https://www.voxengo.com/impulses/), and try creating effects like a riser by combining modules such as reverse and time stretch.

Again, the [ReaEffects Guide](https://www.reaper.fm/guides/REAPEREffectsGuide2021.pdf) contains details on how to use each of these modules effectively.

