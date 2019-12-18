---
title: "Demo Abstract: A Microphone Sensor based System for Green Building Applications"
collection: publications
permalink: /publications/demoabstract
excerpt: ''
venue: 'PerCom'
citation: '<b>Md Abdullah Al Hafiz Khan</b>, Sheung Lu, Nirmalya Roy, Nilavra Pathak. <i>Pervasive Computing and Communication Workshops (PerCom Workshops), 2015 IEEE International Conference. Louis, Missouri.</i> '
---

[Download PDF](https://ahafizk.github.io/files/demoabstract.pdf)

<b>Abstract:</b>

Acoustic sensing has influenced many applications
in green building energy management, such as
designing multi-modal energy disaggregation algorithms
through fine-grained appliance state identifications or
efficiently controlling the HVAC system based on the occupancy
of the environment. In this demo paper we build a
low-cost system prototype using off-the-shelf commercially
available hardware (Raspberry Pi and super high gain
microphone) to handle both acoustic sensing and its processing
that is portable and easily deployable in any indoor
environment. Our system is useful in detecting appliance
noise for fine-grained energy metering and human voice
for managing building energy footprint. We use the decibel
strength of the sound to determine if it should be filtered
out as a silence or stored in as an audio of interest. A
fast fourier transform that quickly converts the sinusoidal
input of the audio signals into its associated frequencies
is implemented along with the Mel-Frequency Cepstral
Coefficients (MFCCs) feature to distinguish between a
human voice and an appliance noise. We also implement
all the computations on-chip to quantify the energy-delay
benefits.