---
layout: post
title: Coat Hangers and NOAA Satellites
date: 2020-06-23T:10:20:00Z
---

I've been meaning to gather weather images from satellites for a while now, ever since I've watched Thought Emporium's video on it. 

Last night, I built my first antenna using two coat hangers and some RG6 coax. The design is crude at best, but it worked for my purposes. I tested the antenna on FM radio stations using SDR#, and it was magnitudes better in gain than the tiny monopole antenna that came with the RTL.

I meant to capture NOAA 19 this morning because it supposedly had the best elevation (almost directly above me), but I slept through my alarm. The next best pass was the NOAA 18 in the afternoon. 

My first recording was incredibly noisy, and I didn't let WXtoImg record it fully, but the result is still legible.

![First Recording]({{ site.baseurl }}/images/042019/0420/04202017hvct.jpg)

The signal was rather hard to pick up on SDR#, so I stopped the recording and waited a while longer. I assume NOAA 18 eventually got closer to me, because I was able to pick up better signals on my second recording. 

![Second Recording]({{ site.baseurl }}/images/042019/0420/04202024c.jpg)

This is an image of Iceland and what looks like to be a bit of the United Kingdom. This recording is much more clear than the first pass, though still quite noisy. It is quite pretty though, also pretty badass.

I'm going to continue gathering images with my coat hanger antenna. My future plans are to make a double cross antenna like Thought Emporium because it seems to have incredible results. I would also like to pick up METEOR images. 

Some longer term plans would be to design some sort of system that would automatically record images of passing satellites. I would probably have to utilize a Raspberry Pi to run the software. 

Immediate goals though, is to probably to build a measuring tape antenna for my UCI team's CubeSat.
