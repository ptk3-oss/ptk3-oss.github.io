---
layout: post
title: Simultaneous Sparklies
thumbnail-img: /assets/img/spark.jpeg
tags: [Arduino, LEDs]
author: Peter Kane
---

Here's my Simultaneous Sparklies,

For this project, I combined all three of my previous firefly LED behaviors into a single program that runs them simultaneously. One LED blinks like a flashbulb at regular intervals, another slowly fades up like the dipper, and the third performs a burst of fast flashes. Using a state-based approach allows each LED to keep track of what it should be doing without interrupting the others. 

A tip for my past self would be to use the serial monitor when unexpected things are happening. I was hesitant to use it at first, but it was very helpful when timings were going wrong. 

**Sparklies Photo**
![sparklies](assets/img/spark.jpeg)
