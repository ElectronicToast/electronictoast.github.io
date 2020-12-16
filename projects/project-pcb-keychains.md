---
layout: project
type: project
image: images/keychains.jpg
title: PCB Keychains
permalink: projects/keychains
# All dates must be YYYY-MM-DD format!
date: 2020-02-06
labels:
  - PCB Design
  - AVR
summary: Some simple keychains made out of PCBs.
---

<img class="ui medium right floated rounded image" src="{{ site.baseurl }}/images/keychains.jpg">

Back when I was at Caltech, I designed PCB leychains for several of the [student residences (Houses)](https://en.wikipedia.org/wiki/House_System_at_the_California_Institute_of_Technology), taking advantage of the extremely low cost of basic PCB fabrication in this day and age. These (top row) were simply boards with no components, with the logos of the Houses in exposed copper and silkscreen. 

Someone then gave me an idea: add programmable LEDs. So I designed [RuddBlink](https://github.com/ElectronicToast/ruddblink) (bottom row), which features an ATtiny85 MCU and eight LEDs on the same form factor. This was my first foray into bare metal programming outside of coursework; I wrote the [firmware](https://github.com/ElectronicToast/tinyblinkware) in C and established a cross-platform toolchain for updating the code. 

<img class="ui medium centered image" src="{{ site.baseurl }}/images/ruddblink-back.jpg">

The keychain is coin cell powered and shockingly waterproof - I have a friend who washed theirs in the laundry and found it still working afterward. I graduated Caltech before I found the time to make a more capable version (perhaps with an STM32F0 and RGB LEDs).

