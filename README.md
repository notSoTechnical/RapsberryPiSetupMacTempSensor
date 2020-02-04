# Setting up Rapsberry Pi with Macbook Pro late 2019 Mojave 10.14.5 (headless/monitor, keyboard, and mouse are not needed)
Video: https://www.youtube.com/watch?v=-v88m-HYeys

Hardware: 
1. Router + RJ45 or an ethernet cable
2. Raspberry Pi kit: Raspberry Pi 3 Model B+, 32GB SD card, sd card reader, 5V power supply

Software: 
1. Download Raspbian: https://www.raspberrypi.org/downloads/raspbian/
Note: This zip file would take a long time to download and it would get crrupted in the middle of downloading.  Make sure to resume the download.  If Google Chrome doesn’t work, try download it with Safari. 
2. Download Pi Filler (2.0.1): http://ivanx.com/raspberrypi/
3. Download The Unarchiver: https://www.raspberrypi.org/downloads/raspbian/

Details:
1. Insert the SD card
2. Open/unzip the Raspbian with The Unarchiver; Choose the .img; erase and format the SD card with the .img
3. Wait for approximately 5 minutes; eject the sd card when it's done
4. Insert the sd card again; "boot" should be on the desktop
5. Open TextEdit and save the textfile's name as ssh; plain text: UTF-8; put the ssh file into the boot folder; eject boot/sd card
6. Insert SD card into the Raspberry Pi; connect the ethernet cable to the pi; Power the Pi
7. Open terminal; ping raspberrypi.local; ssh pi@raspberrypi.local or ssh pi@ip.local; password: raspberry
8. Enter this in the terminal to configure the pi: sudo raspi-config; Config advanced option to expand the filesystem; finish+ reboot

# Rapsberry Pi Temperature Sensor
Instructions: https://www.thegeekpub.com/236867/using-the-dht11-temperature-sensor-with-the-raspberry-pi/
