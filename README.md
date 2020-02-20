# chilipie-kiosk-linux

Easy-to-use **lubuntu** image for booting directly into **full-screen chromium**, with built-in convenience features for unattended operation. Perfect for **dashboards and build monitors**.

## Features

![Screenshots](https://github.com/futurice/chilipie-kiosk/blob/master/docs/screenshot.png)

```
▲ Customizable, full screen          ▲ Boots directly into a simple       ▲ WiFi & other system config
      startup graphics                    getting started -guide            is just one keypress away
```

- **Boots directly to full-screen Chrome** - with all the features of a modern browser
- **No automatic updates** - no surprises due to Chrome (or other packages) suddenly updating
- **Automatic crash-recovery** - accidental unpowering won't result in "Chrome did not shut down correctly :("
- **Custom startup graphics** - displays [customizable graphics](home/background.png) instead of console messages during startup
- **Lightweight window manager** - uses [Matchbox](https://www.yoctoproject.org/tools-resources/projects/matchbox) for minimal clutter and memory footprint
- **HDMI output control** - ready-made scripts for [turning off the display](home/crontab.example) outside of office hours, for example
- **Cursor hiding** - if you leave a mouse plugged in, the cursor is hidden after a brief period of inactivity
- **Automatic reboots** - reboots the Pi nightly, when nobody's watching, to keep it running smoothly
- **Based on a recent Debian** - if you want to add your own tweaks, all the expected packages are one `apt-get` away
- **Batteries included** - the most common how-to's and ProTips have been collected to the [first-boot document](docs/first-boot.md)

## Acknowledgements

This project is a grateful recipient of [Futurice Chilipie kiosk project](https://github.com/futurice/chilipie-kiosk). Thank you. 🙇

