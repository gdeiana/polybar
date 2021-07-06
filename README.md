# Polybar Setup

This folder is my personal polybar setup for Pop OS with two screens (laptop + external monitor).  
The polybar is only active in the main screen.  
I could not find a way to automatically resize the bar when connecting/disconnecting from the external monitor, so I created a shortcut in the start menu to relaunch the bar quickly when connecting/disconnecting from the monitor.

## Requirements
- Polybar installed
- fonts:
    - fontawesome
    - fixed
    - unifont

## Instructions

- Place this in *user/.config/polybar*
- Add the launch.sh as a startup program
- Create a program called **polybar** in the super menu that runs launch.sh  
    This is necessary for when you connect or disconnect from external monitor and the polybar gets disconnected


