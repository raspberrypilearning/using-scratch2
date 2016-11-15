# Using Scratch 2.0 on Raspberry Pi

In this resource you will find out how to use Scratch 2.0 on Raspberry Pi

https://www.raspberrypi.org/blog/introducing-pixel/
https://www.raspberrypi.org/learning/software-guide/update-sd-card/

Type about:plugins into the address bar at the top of a Chromium browser window.
Click Details at the upper-right corner of the page.
Find the Flash or Shockwave Flash listing on the Plug-ins page and click the corresponding Enable button.
Close all Chromium windows and restart the browser.
https://helpx.adobe.com/flash-player/kb/flash-player-chromium.html

## Updating your software

Scratch 2.0 requires software to allow Flash content to run. You will need the latest version of NOOBS to be able to use this software. Follow this guide to [get started with a blank SD card](https://www.raspberrypi.org/learning/software-guide/quickstart/) or learn how to [upgrade an existing SD card](https://www.raspberrypi.org/learning/software-guide/update-sd-card/). 

If you are updating an old SD card, after updating the distribution you should also install the Chromium mods which will enable the Flash player software, followed by a reboot.

```
sudo apt-get install -y rpi-chromium-mods
sudo reboot
```

