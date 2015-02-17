# MilkDrop138
to get multi-monitor desktop mode

Hey, so MilkDrop is a music-visualisation plugin-for Winamp and he has an awesome "desktop mode."

There are some bugs, like icons do not show (despite a lot of effort) on 64 bit systems.
What I'm primarily concerned with, however, is getting Desktop-mode to work accross multiple monitors.

It is possible to have fullscreen mode do this, for example.

A place to start looking:
Line 754 of vis_milk2/dxcontext.cpp
