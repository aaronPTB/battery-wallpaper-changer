# battery-wallpaper-changer
A simple bash script that changes the wallpaper based on the level of your battery. 
Can be very easily customized. Dependencies on upower and feh. 
If the script doesn't work, try changing where it says BAT1 to BAT0.

# Installation Instructions
Move the script in this file to somewhere in your PATH variable and then add the line

battery_indicator & 

to a startup dotfile such as ~/.xinitrc

You will also want to install the following packages:

image-magick
inotify-tools

and anything else that breaks dependencies
