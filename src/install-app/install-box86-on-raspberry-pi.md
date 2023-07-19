---
title: Install Box86 on Raspberry Pi | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Box86/icon-64.png" height=24> Box86 on <img src=/img/other-icons/raspberrypi-icon.svg height=24> Raspberry Pi

## <img src="/img/app-icons/Box86/icon-64.png"> Box86
> Easily emulate x86 linux apps on ARM32.
> Box86 lets you run x86 Linux programs (such as games) on non-x86 Linux, like ARM (host system needs to be 32bit little-endian).
> Because Box86 uses the native versions of some "system" libraries, like libc, libm, SDL and OpenGL, it's easy to integrate and use, and performance can be surprisingly high in some cases.
> Box86 now integrates a DynaRec (dynamic recompiler) for the ARM platform, providing a speed boost between 5 to 10 times faster than only using the interpreter.
> 
> To run in a terminal: box86

Fortunately, Box86 is very easy to install on your Raspberry Pi in just two steps.
1. Install Pi-Apps - the best app installer for Raspberry Pi.
2. Use Pi-Apps to install Box86.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Raspberry Pi OS](https://www.raspberrypi.com/software/), which is currently version **Bullseye**.
Raspberry Pi OS has 32-bit and 64-bit variants, both of which will run on most Raspberry Pi computers, including the Pi 3 and the Pi 4.
Box86 will run on either PiOS 32-bit or 64-bit.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Raspberry Pi with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install Box86

Now that you have Pi-Apps installed, it is time to install Box86.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the Tools category, which leads to the Emulation category.
<img src="/img/category-selections/Emulation.png">
Now scroll down to find Box86 in the list.
<img src="/img/app-icons/Box86/app-selection.png">
Just click Install and Pi-Apps will install Box86 for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>