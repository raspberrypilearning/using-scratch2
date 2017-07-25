## Updating your software

You will need an up-to-date version of NOOBS to be able to use Scratch 2.0. This is because Scratch 2.0 requires a browser software plug-in from the latest release of NOOBS to allow Flash content to run.

### Using a blank SD card

Follow this guide to [get started with a blank SD card](https://projects.raspberrypi.org/en/projects/software-guide/quickstart/).

### Updating an existing installation
You can follow this guide to [update an existing SD card](https://projects.raspberrypi.org/en/projects/software-guide/update-sd-card/) to the newest build.

After updating your SD card to the latest build, you should also install the Chromium mods which will enable the Flash player software. Then reboot your Raspberry Pi to allow the changes to take effect. Open a terminal window and type in the following commands:

```
sudo apt-get install -y rpi-chromium-mods
sudo reboot
```

