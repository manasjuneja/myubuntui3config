## Wallpaper 

A permanent wallpaper is there with a specific path. 
The path to the wallpaper should be : **/home/manas/Pictures/wallpaper.jpg**


## Locking your computer 

Pressing **Mod + Shift + x** will result in locking your computer


## Enabling the touch of the touchpad 

In the config file, change the line  **exec_always xinput set-prop "ELAN067B:00 04F3:31F8 Touchpad" "libinput Tapping Enabled" 1**  to  **exec_always xinput set-prop "<name of your touchpad>" "libinput Tapping Enabled" 1**.
You can find the name of your touchpad by typing **xinput** in terminal. The entry with 'Touchpad' in its name, is the name of your touchpad.
