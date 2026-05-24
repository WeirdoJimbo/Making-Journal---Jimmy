---
layout: default
---

# Week 10

[← Back to Home](../index.md)

## Progress Reports:




## Independant Study
During the class in week 10 I talked to the lab techs about using a TFT screen and a ESP32 to create an interactive way for people to input their own data and to get it showing up on the screen. From this talk, over the weekend I began experimenting with it both the TFT screen and the ESP32, I first started with a breadboard the ESP32 and a led. Following some online tutorials I was able to connect the led and esp on the breadbood and create some code in AurdinoIDE to get the led to light up for a second every second. 

![LED Code](../assets/week-10/10-1.png)
*Code to get my LED to light up*

After that feeling confidence with my computer science skills from highschool I did a big jumo form the LED to working with the screen. This was a bad idea. I think I should've continue experimenting with the breadboard and the ESP as I instantly got lost once I started trying to connect the two. What I failed to realised was that each TFT screen is different with unique ports depending on the specs. I figured this out eventually however I stumbled upon another issue. The TFT screen that I was given from the Design Lab had no labels and no way to figure out the specs. After getting some help from my much smarter friends and flatmates I was eventually able to get the screen and ESP connected where I once again ran into another issue. The screen seemed to have a bug where it wouldn't reset before running the code, leading to and issue where half the screen was not working unless something updated the pixels in the bugged reigon. 

![Screen Bug](../assets/week-10/10-2.jpeg)
*Half on screen following a ArduinoIDE Example Sketch*

![Screen Bug](../assets/week-10/10-3.jpeg)
*The screen slightly more on after parts of it was updated mid sketch*


