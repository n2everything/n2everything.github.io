---
layout: page 
title: Meshtastic on a Raspberry Pi
date: 2024-12-15 12:00:00 -500
categories: [meshtastic]
tags: [pi, raspberry pi, meshtastic, pi hat, lora]
---

In this video, we install a LoRa pi hat onto a raspberry pi with the goal of installing meshtasticd for long range offgrid communications.

In the end, the LoRa hat that was selected and used in the build didn't work out. The waveshare LoRa hat is designed for LoraWan, which has much shorter messages.  During longer transmissions (like meshtastic) the chip heats up and drifts off frequency meaning the remote node never hears the end of the message (and actually discards it as invalid)

  I'll upload another (short) video later when I find one that works well.

{% include embed/youtube.html id='d1ZWiHuUwLc' %}

## Links
[Raspberry Pi 3b](https://amzn.to/3FtPYVr) (There are newer models available, the [Pi4](https://amzn.to/3Fv3c46), and [Pi5](https://www.amazon.com/dp/B0CK3L9WD3))<br>
[Waveshare PoE hat](https://amzn.to/41QJirE)<br>

