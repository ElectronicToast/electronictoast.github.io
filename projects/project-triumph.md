---
layout: project
type: project
image: images/triumph.jpg
title: Triumph
permalink: projects/triumph
# All dates must be YYYY-MM-DD format!
date: 2019-06-07
labels:
  - Electronics
  - Analog Circuits
  - PCB Design
summary: An accurate and robust analog function generator.
---

<img class="ui image" src="{{ site.baseurl }}/images/triumph.jpg">

Build an analog function generator.

That was the task for the Analog Electronics Project Laboratory (EE 90) course at Caltech for Spring 2019.

Aside from several minimum requirements - sine, square, and triangle waves over a minimum frequency range and with adjustible output amplitude - with the stipulation of no digital components in the signal path, I was pretty much given free reign. Other students produced designs that bristled with features or emphasized the accuracy of the signals. I created [Triumph](https://github.com/ElectronicToast/triumph) - an open source function generator that seeks to achieve the perfect balance between functionality, performance, and aesthetics.

<img class="ui image" src="{{ site.baseurl }}/images/triumph-in.jpg">

The base function generator circuitry consists of just four opamps, one comparator, two diodes, and one BJT. With several control knobs, the function generator can produce accurate waveforms over a wide range of frequencies and amplitudes. The square wave has an adjustible duty cycle.

I designed the enclosure in SolidWorks and produced it over the course of three days of fiddling around with laser cutter settings in the Caltech machine shop. White paint - regular old acrylic paint - does wonders when painted into engravings on black acrylic sheets.

Source: <a href="https://github.com/ElectronicToast/triumph"><i class="large github icon"></i>ElectronicToast/triumph</a>

