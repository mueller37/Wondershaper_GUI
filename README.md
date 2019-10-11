# Wondershaper_GUI
Simple GUI for wondershaper

![screenshot](screenshot.png)

## requriements:
Ubuntu: sudo , gtk2

## Important manual setup:
Wondershaper must be run-able, without asking for password:  Please run `sudo visudo` and add this line `YourUsername ALL=NOPASSWD:/sbin/wondershaper`

## Compile:
requirement: libgtk2.0-dev

cd Wondershaper_GUI

make

./speed
