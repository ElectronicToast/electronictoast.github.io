---
layout: project
type: project
image: images/ee91a.jpg
title: Analog Autonomous Car
permalink: projects/analog-car
# All dates must be YYYY-MM-DD format!
date: 2019-12-07
labels:
  - PCB Design
  - Analog Electronics
summary: An obstacle-avoiding robot with only analog circuitry.
---

<img class="ui medium right floated rounded image" src="{{ site.baseurl }}/images/ee91a.jpg">

Everyone has seen the Arduino robot that avoids obstacles with an ultrasonic sensor (I’ve built one too). How about one without any microprocessors? 

For the Experimental Projects in Electronic Circuits (EE 91) course at Caltech, I built this robot, which autonomously moves and avoids obstacles with no digital circuitry. 

Two pairs of ultrasonic transducers became a pair of ultrasonic sensors through an oscillator and a pair of sense amplifier circuits. A hardware PID controller implementation would compare the received sensor levels and adjust motor power to steer the robot away from obstacles.

Source: <a href="https://github.com/ElectronicToast/ee91"><i class="large github icon"></i>ElectronicToast/ee91</a>

