# Touchpad-Controls

![alt text](http://miyolinux.weebly.com/uploads/1/3/7/0/13707080/screenshot-from-2018-03-06-19-50-56_orig.png)

Requires: yad, xserver-xorg-input-synaptics

The Touchpad Controls application allows a user to turn their laptop's touchpad On, Off, or Off While Typing during a live session. 
The current delay for "Off While Typing" is 2 seconds. That can be adjusted in the code. If you're unsure what to change, look at the last line in the code...

--button="Off While Typing":"syndaemon -i 2.0 -d" \

Simply change the 2.0 in that line to your desired delay.
