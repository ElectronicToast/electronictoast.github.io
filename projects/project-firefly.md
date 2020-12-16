---
layout: project
type: project
image: images/firefly_front_crop.png
title: Firefly
permalink: projects/firefly
# All dates must be YYYY-MM-DD format!
date: 2018-09-25
labels:
  - Embedded Systems
  - PCB Design
  - AVR
summary: A bare-metal development board for the ATmega328p in breadboard-friendly layout
---

It's rare to meet a hobbyist, electronics enthusiast, or EE/CS student these days who haven't worked with, or at least heard of, Arduino. 

But I suppose that not many of these folks have had the opportunity to work directly with AVR chips, with nothing separating you from the registers and I/O except for Assembly, or know what is truly happening under the hood. 

This is why I created [Firefly](https://github.com/ElectronicToast/FireFly), an open-source, Arduino-compatible ATmega8 target board. 

<img class="ui image" src="{{ site.baseurl }}/images/firefly_front_crop.png">

I have had the opportunity to take the digital electronics core class at Caltech, where microprocessor systems were taught from the ground up - from logic gates to counters to ALU design to [CPU emulators](https://github.com/ElectronicToast/Caltech10CPU). After that, we developed [AVR-based systems](https://github.com/ElectronicToast/BinarioBoard) while aware of the underlying logic, such as what makes Arduino `digitalWrite(ledPin)` turn on an LED and `Servo.write()` output a PWM signal. 

I created Firefly in order to have a tool for learning more about embedded systems development while sharpening my design skills.

<img class="ui image" src="{{ site.baseurl }}/images/firefly.png">
<br/>

Source: <a href="https://github.com/ElectronicToast/firefly"><i class="large github icon"></i>ElectronicToast/firefly</a>

