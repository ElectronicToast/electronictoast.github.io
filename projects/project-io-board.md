---
layout: project
type: project
image: images/io_board_v2.png
title: I/O Board
permalink: projects/io-board
# All dates must be YYYY-MM-DD format!
date: 2018-06-08
labels:
  - Embedded Systems
  - PCB Design
  - STM32F4
summary: A STM32F4-based board designed for the second generation Caltech Formula SAE electric vehicle.
---

I was involved in [Formula SAE at Caltech](http://fsae.caltech.edu/) while I was at Caltech, designing major subsystem components for the low voltage electrical system of our vehicle.

<img class="ui image" src="{{ site.baseurl }}/images/io_board_v2.png">

This is our I/O Board from 2018, a STM32F4-based microprocessor system that reads analog input from the pedals of the vehicle and a current sensor on the motor, asserts fault conditions, and communicates with the rest of the low voltage system through CANBus. 

I designed the non-programmable fault hardware that interrupts power to the motors in the event that one of the more strigent fault conditions in FSAE occurs - if the motor current is high and the brake is pressed hard. In addition, I wrote firmware for reading the analog inputs and determining if the inputs constitute a fault.

As an alumni of the Caltech FSAE team, I attend design reviews and provide feedback on new generations of hardware designs for the electric vehicle.

