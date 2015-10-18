# Introduction

This code tries to do scattered data interpolation with ofxPolyfit addon for openframeworks.

The data passed in to this code via 2 arrays are X/Y positions from one fixed wide angle usb camera and pan/tilt angles from a PTZ camera.

See this thread for more information: http://forum.openframeworks.cc/t/bicubic-2d-interpolation-on-an-unregular-grid/20963/13

ofxPolyFit_Scattered_3rd_order uses x/y data and one angle as input and gives one angle as output
ofxPolyFit_Scattered_4th_order uses x/y data and two angle as input and gives two angles as output

# Dependencies

ofxPolyFit
https://github.com/elliotwoods/ofxPolyfit


# Operating systems

It has only been tested on osx 10.10 with OF 0.8.4

## Images

Screen shot:

![](https://raw.githubusercontent.com/antimodular/ofxPolyFit-Scarred/master/Screen%20Shot%202015-10-18%20at%208.18.55%20AM.png)