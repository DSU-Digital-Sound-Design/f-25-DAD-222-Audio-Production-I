+++
title = "MIDI"
outputs = ["Reveal"]
[reveal_hugo]
theme = "solarized"
# show_notes = "separate-page"
+++

![](MIDI_LOGO.svg)

{{% note %}}

- **MIDI stands for Musical Instrument Digital Interface**. It is a technical standard that was created in the early 1980s to allow electronic musical instruments, computers, and other equipment made by different manufacturers to connect with each other and exchange information.
  Here is an expanded version of the notes:
- **How does MIDI work?**
  - MIDI allows devices to communicate information about musical performances. This includes data like what notes are played, for how long, loudness, vibrato, panning, and many other parameters. This data can be recorded into and played back from a DAW.
- **What can MIDI Connect?**
  - MIDI can connect instruments such as keyboards, guitars, drums, and synthesizers. It can also connect mixer consoles, effects units, audio interfaces, computers, tablets, smartphones, and more. Any device with MIDI input and output ports can send and receive MIDI data.
- **What can you do with MIDI?**
  - MIDI connections enable many powerful creative applications:
    - Use a MIDI controller keyboard to play software instruments in a DAW
    - Use MIDI to sync timing between multiple devices
    - Trigger loops, samples, and effects using MIDI notes and controllers
    - Record complex performances into a DAW by playing devices via MIDI
    - Use MIDI to automate parameters like volume, panning, synth patches, etc.

{{% / note %}}

---

# MIDI Hardware

## A brief history of MIDI

{{% note %}}

- **MIDI Hardware Specifications**
  - **Cables and Ports**
    - MIDI devices connect with 5-pin DIN cables between MIDI In and MIDI Out ports. Many audio interfaces also have MIDI ports. USB and Firewire connections can also carry MIDI data.
  - **Messages**
    - The MIDI specification defines the structure of MIDI messages. Messages contain commands for things like note on/off, controllers, program change, pitch bend, etc. Commands include the channel number, note/controller numbers, velocities, and other parameters.

---

## MIDI 1.0 Specification

- synth manufacturers wanted to create a communications standard
- MIDI 1.0 Specification - published in 1983
- first connections at NAMM - Sequential Circuits Prophet 600 and a Roland JP-6.

{{% note %}}

- In the early 1980s, different synth manufacturers like Sequential Circuits and Roland had proprietary communications protocols between their own instruments. But there was no standard way for equipment from different companies to communicate.
- Dave Smith of Sequential Circuits and Ikutaru Kakehashi of Roland worked together to develop a standard that could work across manufacturers.
- In 1981, they invited other companies like Oberheim, Korg, and Yamaha to participate in creating the standard.
- The MIDI Manufacturers Association was formed to oversee the spec development.
- Key goals were universality, low cost implementation, backwards compatibility, and future extensibility.
- The MIDI 1.0 specification was published and introduced at the 1982 NAMM conference.
- At NAMM 1983, the first public MIDI connection was made between a Sequential Circuits Prophet 600 and a Roland JP-6 synthesizer.
- The successful connection and communication demonstrated the interoperability of the new MIDI specification.
- MIDI 1.0 had limitations but was still adopted rapidly starting in 1983. Significant for electronic music production.
- MIDI 1.0 defined the physical connector, basic message format, data protocol, and some messages.
- Later MIDI 2.0 expanded bandwidth, added new messages, bidirectional communication, and more.
{{%/ note %}}

---

- Types of MIDI Devices
  - Controllers
  - Modules
  - Workstations
  - Alternate Controllers

{{% note %}}

- **Types of MIDI Devices**
  - **Controllers** - MIDI controllers like keyboards, pads, and surfaces only send MIDI data, they don't generate sound themselves. They need to be connected to downstream devices that generate sound.
  - **Modules** - These receive MIDI data and generate sound, but have no built-in controllers. Modules are controlled by connecting MIDI controllers.
  - **Workstations** - All-in-one devices with controllers, sound engines, sequencers, effects, and more. Allow full music production capability in a standalone device.
  - **Alternate Controllers** - Non-traditional controllers like gestural sensors, modified instruments, multi-touch, etc. that send MIDI data to extend creative options. Also called New Interfaces for Musical Expression (NIMEs).

{{%/ note %}}

---

## Controllers

[Various controllers](https://duckduckgo.com/?q=midi+controllers&t=newext&atb=v265-1&iax=images&ia=images&iai=https%3A%2F%2Fwww.bhphotovideo.com%2Fimages%2Fimages2500x2500%2Flivid_instruments_lvbase02_multipurpose_performance_controler_for_1054583.jpg)

{{% note %}}

- only sends MIDI messages
- doesn't generate sound on its own
- before personal computers it would send messages to a hardware synth but now we connect them to computers

{{% / note %}}

---

Modules

<img src="roland-fantom-xr.jpg" width="50%">

{{% note %}}
A module is a device that can generate sound when it receives MIDI messages but has no keys to play, and hence can’t output MIDI messages.

Here are some key details about the Roland Fantom XR module in bullet points:

- Released in 2008 as part of Roland's Fantom series
- An expandable sound module designed to be controlled by external MIDI devices
- Contains over 1,600 onboard sounds derived from Roland's famous SRX expansion cards
- 128-voice polyphony with seamless sound switching
{{% / note %}}

---

## Workstations - Akai MPC

<iframe width="560" height="315" src="https://www.youtube.com/embed/SENzTt3ftiU?start=165" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{{% note %}}
Here are some key details about the Akai MPC series in bullet points:

- Created by Roger Linn and introduced in 1988, the MPC60 was the first MPC model
- Revolutionary combination of sampling, sequencing, and drum machine capabilities in one unit
- Pads allow live playing and sequencing of samples and loops
- Classic MPC workflow using Mode, Timing Correct, Note Repeat, 16 Levels, and more
{{%/ note %}}

---

## Alternate controllers - AKA NIMES

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZRHLtkeWwwA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
