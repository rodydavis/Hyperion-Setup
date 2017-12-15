# Hyperion-Setup
This is a 100% compatible and affordable Hyperion Set up with 2017 Hardware for a 55" TV.

Here you can get all the hardware and supplies needed on Amazon Prime: http://a.co/6YOCJRK

Download Rasbian Stretch Lite: 
https://www.raspberrypi.org/downloads/raspbian/

Arduino Software: 
https://www.arduino.cc/en/Main/Software

Hyperion Offical Site: 
https://hyperion-project.org

HyperCon GUI Config Tool: 
https://hyperion-project.org/wiki/HyperCon-Information

Hyperion Remote (iOS):
https://itunes.apple.com/us/app/hyperion-remote/id943635503?mt=8

Hyperion Remote (Android):
https://play.google.com/store/apps/details?id=nl.hyperion.hyperionfree

Hyperion Remote (Web):
http://gamadril.github.io/hyperion-remote

Important Notes:
- On this configuration with the WS2812b lights I had to set the order from RGB to GRB.
- In order to get Hyperion talking with FastLED I needed to needed to set my Light Type to ADALight.
  How to find device path (Output) in Hypercon...
  1. SSH into Rasberry PI
  2. lsusb
  3. ls /dev
  You should see the arduino listed. If not run the command without the arduino plugged in, then again with it plugged in.
- You need to use the V2 Grabber and adjust the crop borders
- MAKE SURE YOU CORRECTLY SPECIFIY THE LED DIRECTION


![Finished Hub](https://i.imgur.com/hko62Wp.jpg)

All of the componets run off 1 5V 10A Powersource. The HDMI Splitter is actually powered from the input and even with this setup my Xbox One S will still turn on and off my TV no problem. All of the components fit in a IKEA tool box that comes with Zip Ties.

![Back of TV](https://i.imgur.com/M15SLg8.jpg)

In the Amazon list I included a LED strip extender, had I known this at the time of the build i would not have wasted 4 hours soldering the LED Strips on my TV on my bed. 

Useful Guides:

- General Guide

https://hyperion-project.org/threads/diy-amblight-project-guide-hyperion-ws2801-ws2812b-apa102.8/

- Video on a Similar Setup

[![Ambilight Setup](https://img.youtube.com/vi/JvcR2td1Cso/0.jpg)](https://www.youtube.com/watch?v=JvcR2td1Cso)

- How to Solder

[![How to Solder](https://img.youtube.com/vi/VxMV6wGS3NY/0.jpg)](https://www.youtube.com/watch?v=VxMV6wGS3NY)
