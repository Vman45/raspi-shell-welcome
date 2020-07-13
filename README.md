![enter image description here](https://i.ibb.co/PcbwRcQ/screenshot.jpg)
# Raspberry Pi - welcome shell script
Better welcome script for shell login on you Raspberry Pi

## Testet with Ubuntu/Rasbian

Place the script in any directory you want (here for example in **/home/pi/**) and make it executable.

    $ sudo chmod 777 /home/pi/welcome.sh

Than edit the file /etc/profile

    $ sudo nano /etc/profile

and at the very end of the file place this text
/home/pi/welcome.sh (here for example in /home/pi/)

![enter image description here](https://i.ibb.co/y4MJ81X/Anmerkung-2020-07-08-153005.jpg)

