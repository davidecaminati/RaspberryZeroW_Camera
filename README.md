# RaspberryZeroW_Camera
Use a RaspberryPi Zero as Wireless Camera

based on 
https://medium.com/home-wireless/headless-streaming-video-with-the-raspberry-pi-zero-w-and-raspberry-pi-camera-38bef1968e1



## Helpful Commands

Show the current chip temperature (vcgencmd is in /opt/vc/bin):

    vcgencmd measure_temp

Show CPU usage:

This requires systat for a simple rolling cpu usage view.

    sudo apt-get install sysstat

    sar -u 2 # every two seconds show usage
