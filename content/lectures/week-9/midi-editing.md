---
title: "MIDI Editing"
---

Now that we've recorded our parts they need to be edited. If you double click on any MIDI item it will bring up the MIDI editor.

Notice the bar below:

![](../bar.png)

Here you'll see a transport, grid line settings, quantization strength, note lengths, and key snapping. Grid line settings are important for setting the quantization, but also for editing your MIDI by hand. With snapping on, if you move a MIDI note, it will snap to the grid division you set here. When adding new notes with the pencil tool their length is determined by the _Notes_ setting. Current this is set to be the same as the grid. Double click to add a note at this length. To make notes that are longer, hold and drag the the pencil.

To draw in many notes at the grid size hold down _option+command_ then drag. This is using the paint tool.

To move a note around you can select it and drag it with the mouse. You can also use the keyboard shortcut _command+arrowkeys_. Moving left or right will snap the notes to the grid setting. Moving up or down will change their MIDI notes.

## Adding Variation to the loops

Your loops should sound interesting but not very lifelike yet. This is because we haven't added any velocity variation yet. Real drummers always play patterns with slightly different emphasis's on different parts of the beat and different drum parts.

![](../velocity.png)

See the velocity section above. Each of these red lines sets the _strength_ of the MIDI note. Velocity goes from 0-127. If you MIDI parts play back at 127 velocity for the whole part your song will song dry and robotic. So, we need to edit this.

The easiest way to edit a notes velocity is to select it then hold down _option_ and drag up or down with the mouse. Notice the red line below going down. If you select the note you can also go down to the red line and drag it down.

First we need to select all of the MIDI notes for one note right click on the note on the keyboard. With all of the notes selected you can go down to the velocity section and drag your mouse across the red lines to _draw in_ their velocities.

The other way of selecting events in the MIDI editor is the _Filter Events_ function.

It is usually a good idea to set notes that are on weaker beats to a lower velocity. If you have a hi hat pattern that is in eighth notes, you can set every other one to have a lower velocity value.
