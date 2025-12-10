---
layout: post
title: Final Project Write Up
thumbnail-img: /assets/img/.jpg
tags: [Arduino, Arrays]
author: Peter Kane
---

Here's My Final Project, 

**Cat Nap Sleep Mask**

**Motivation:** 

My idea was motivated by the fact that, as a wrestler, on tournament days, the period between weigh-ins and the start of wrestling is really the only time I get to rest throughout the day, and I often like to take a nap. That being said, I really need complete darkness, hence the sleep mask, and given a short time, if I’m woken up abruptly, like when someone has to shake me awake, it can really hurt the quality of my warm-up and early matches.

**Description:** 

I made a sleep mask that acts like a mini sunrise alarm clock, so when the wearer presses the button, the mask begins a short timer. After that timer expires, the LEDs slowly fade in, similar to the functionality of the mid-semester project, and it plays the buzzer. There’s also an alternative function, where if it’s bright enough already, the LEDs won’t turn on, and only the buzzer plays.


**Material List** 
* LilyPad Arduino + LiPo Battery
* Light Sensor (analog input)
* Momentary Button (Starts sleep timer)
* Switch (For ON/OFF)
* Lilypad Buzzer (Digital Output)
* Conductive Thread
* 4 White LEDs, 2 Blue LEDs (Fade-in light)
* 3 pieces of 10" x 4" Felt
* ~12” fold-over elastic
* 2 metal snaps
* 2-inch square of conductive fabric
* Needle, Scissors, thread, embroidery floss 

**Paper Prototype**

![Prototype](/assets/img/Paper Prototype.jpg)

**Alligator Clip Prototype**

I only used one LED for each of the LED traces on the alligator clip prototype because I didn't have enough clips, but they were running in parallel, so it modeled the behavior anyway. 

![Alligator Clip](/assets/img/AlligatorClip.jpg)

**Working Video**

[![Working Video](http://img.youtube.com/vi/7uxRzHIFx3Q/0.jpg)](http://www.youtube.com/watch?v=7uxRzHIFx3Q)

^Click for video

**Tips for Myself**

* Test everything as you are going! Doing this was really valuable because I had so many different traces and components. Making sure it all worked throughout every stage was really helpful
* Simplify code as much as possible. I adapted some of the code from the mid-semester project to fade my lights in, and it was really helpful to simplify my work because I wasn't using the same state-based approach; I was using a sequential one instead.
* Be creative with how you connect and insulate things. I ended up using snaps as a way to pass my connections through 3 layers of fabric, and being creative like that was very important for getting my project to work. 


Pattern From: https://no.pinterest.com/pin/610448924530430568/


