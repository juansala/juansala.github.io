---
layout: default
# title: Example project
# description: Example project description
permalink: /projects/ring_watch
---

<style>
    .figure {
    display: block;
    width: 500px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 20px;
    }
</style>

# The Ring Watch

I designed a quirky watch that fits on your ring finger. It doesn’t use hands or any other conventional means to tell time; instead it lights an RGB LED to tell time. The PCB is based on the ATtiny85 8-bit microcontroller and the PCF8523 real-time clock (RTC), and is powered off of a CR2032 type coin cell.

<p><img class="figure" src="https://juansala.github.io/media/Images/ring_watch_topview.png"/></p>

<p><img class="figure" src="https://juansala.github.io/media/Images/ring_watch_bottom_view.png"/></p>

The PCB is mounted on a 3D printed ring that I designed using Onshape.

<p><img class="figure" src="https://juansala.github.io/media/Images/ring-mount-791x1024.png" style="width:45%"/></p>

To turn the device on and off I soldered a push button between the exposed copper pad and the coin cell holder. Upon turning on, the ring flashes a color each for the hour, minute digits, and time of day (AM/PM). This requires the user to memorize a color code, since each color (12 possible colors) represents an integer within 0-11 (12 am -> 11 pm or 12 pm -> 11 am).

Aside from the fact that this is not at all a user-friendly product, the challenge is selecting a color code that is intuitive and easy to memorize over multiple uses. I hope to someday adapt the PCB to display time using regular LEDs in a more intuitive way. Below is a demo video!

<p align="center">
<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/BsDXOiffLT4?si=QPBPyBZAzzAUXPp0" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>
</p>
