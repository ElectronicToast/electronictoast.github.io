---
layout: project
type: project
image: images/bifrost.jpg
title: Bifrost
permalink: projects/bifrost
# All dates must be YYYY-MM-DD format!
date: 2020-02-06
labels:
  - PCB Design
  - Arduino
summary: A controller board for WS2811-based individually-addressable LED strips with an Arduino Nano.
---

<img class="ui medium right floated rounded image" src="{{ site.baseurl }}/images/bifrost.jpg">

I am a devotee of aesthetics. 

Mid junior year at Caltech, I learned that addressable LED strips existed, and I was hooked. I was attracted to the idea of visualizing music with LED strips, for example by analyzing audio with a Fourier transform and displaying the spectrum on LEDs. 

After a year of messing around with LED strips, I decided to make a PCB for a permanent LED fixture in my room, and [Bifrost](https://github.com/ElectronicToast/bifrost) was the result. This is a simple PCB that turns an Arduino Nano into a capable LED controller that can read audio from an audio jack or microphone module. I also implemented [OTA flashing](https://github.com/ElectronicToast/hc05-ota-adapter) of Arduinos using a common HC-05 Bluetooth module. 

This is a demonstration of a music reactive flame effect on a pair of LED strips. 

<div class="ui embed" data-source="youtube" data-id="sCmf3V_FEFw" >
</div>
<br/>

Source: <a href="https://github.com/ElectronicToast/bifrost"><i class="large github icon"></i>ElectronicToast/bifrost</a>

