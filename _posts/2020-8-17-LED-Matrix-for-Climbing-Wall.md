---
layout: post
title: LED Matrix for Climbing Wall
---

Aside from radio, one of my other passions is rock climbing. Climbing gyms started to close around March due to coronavirus, so up until August I've basically stopped climbing. In fact, I stopped going to the gym around Feburary because I was scared of the virus, so it's been a good 6 months since my last session.

I have almost zero clue about what makes a structure secure, so I let my architect friend design the wall. I helped with woodcutting and measuring, but the physics and structural integrity I left in his hands.

What my friend wanted for the wall (as well as myself, because it's a cool idea) is to have LED lights below the holds like moonboards. Moonboards are crazy expensive for just the electronics (in the range of $600; though this does make sense because presumably it comes with the phone app to control the LEDs. Factor in costs of design and engineering, it is probably a fair price), and we've already spent $900 on the wall itself. 

I estimate I could design a similar setup for about $50 worth of materials. The challenge would be developing a similar phone app, as I have no experience whatsoever with app development. 

The design will be pretty much identical to many of the LED matrix Arduino designs found on the internet. There is a lot of literature to reference, so this project should be a cinch. 

The wall will have 16 LEDs per column and there are 12 columns. So a 16x12 matrix for 192 LEDs. 

A very common IC used in these type of projects is the 74HC574. A demux IC could also be used such as the 74HC138 or 74HC238. A primary difference in LED matrix designs is charlieplexing and multiplexing. Where charlieplexing can only turn on 1 LED at a time, with multiplexing you can turn on multiple LEDs at a time. Of course, the end result for both are the same, due to a phenomenon called persistance of vision. There's lots of information about this online.

