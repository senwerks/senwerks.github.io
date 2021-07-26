---
layout: post
author: Sen
title: "DIY LiPo Battery for the Original Gameboy"
tags: [diy, hardware]
categories: hardware
twitter: https://twitter.com/senwerks/status/1416976612470394882
github: https://github.com/senwerks/lipo-battery-for-original-gameboy/
image: 2021-07-20-DMG01-LiPo-07.jpg
---

I was pretty sick of worrying about the AA batteries for my original Gameboy, and just wanted a LiPo pack I could recharge via micro USB like so many of my modern devices. I found some existing projects that require cutting up the Gameboy, or modifying it in various ways... or some products from overseas that cost a fair bit and are basically just a LiPo + controller jammed into the battery cavity. I wanted something that didn't require any modification to the original Gameboy, and could be swapped back and forth with normal AAs if required.

I started off designing the basic idea in Fusion 360 and then repeatedly printing it while playing with sub-mm variations on my measurements until it fit into the existing battery compartment snugly, held in place by the original springs.


![Gameboy LiPo Battery initial CAD](/images/2021-07-20-DMG01-LiPo-00.png)

![Gameboy LiPo Battery case iterations](/images/2021-07-20-DMG01-LiPo-02.jpg)

For more details specific details on how the project was made, check [the Github repo](https://github.com/senwerks/lipo-battery-for-original-gameboy/) (pasted below), but with a few bits from [Core Electronics](https://core-electronics.com.au/) and some soldering, ended up with this:

![Gameboy LiPo Battery](/images/2021-07-20-DMG01-LiPo-06.jpg)

![Gameboy LiPo Battery](/images/2021-07-20-DMG01-LiPo-08.jpg)

*The below is a copy/paste from [the Github repo](https://github.com/senwerks/lipo-battery-for-original-gameboy/):*

# LiPo Battery Pack for the original Gameboy (DMG-01)

Inspired by the replaceable USB-rechargeable LiPo batteries inside the Ring doorbells/cameras, I wanted something similar for my original gameboy. There's plenty of LiPo mods that require cutting up the Gameboy and/or soldering to the boards inside, but I wanted to leave the console all-original.

It's a very simple build, and most of the effort was in iterating (and iterating, and iterating) the case/chassis design until it fit perfectly inside the battery compartment. I wanted it to utilise the existing battery springs to hold it stable enough to play on the go, and also use the original battery contact points so there was no modification required to the Gameboy itself.

## Ingredients

- [Polymer Lithium Ion Battery (LiPo) 3.7V 1100mAh](https://core-electronics.com.au/polymer-lithium-ion-battery-1000mah-38458.html)
- [Adafruit Micro Lipo w/MicroUSB Jack](https://core-electronics.com.au/adafruit-micro-lipo-w-microusb-jack-usb-liion-lipoly-charger-v1.html)
- 3D printed chassis/case
- 1mm brass wire
- 22AWG wire

## Instructions

Print the 2 STL files (I've also included gcode files for Prusa i3's, and a project file). 

![3D printed case for the Gameboy LiPo Battery](https://raw.githubusercontent.com/senwerks/lipo-battery-for-original-gameboy/main/Meta/2021-07-20-DMG01-LiPo-01.jpg)

Bend some small pieces of the 1mm brass wire and glue them into place as per the photos. Solder wires from the the positive brass wire piece (right side, check battery compartment markings to be sure) to the BAT point on the LiPo breakout, and the negative side (left side) to the GND point.

![Wiring for the Gameboy LiPo Battery](https://raw.githubusercontent.com/senwerks/lipo-battery-for-original-gameboy/main/Meta/2021-07-20-DMG01-LiPo-03.jpg)

![Wiring for the Gameboy LiPo Battery](https://raw.githubusercontent.com/senwerks/lipo-battery-for-original-gameboy/main/Meta/2021-07-20-DMG01-LiPo-04.jpg)

The photos should sum it up, it's not a very complex build.

When you're putting the new battery pack into the Gameboy, you want to lower the bottom edge in first and push it against the lower springs to compress them, then the top part with the brass contacts should lower down in without scraping anything. When you let go, the lower springs push the new battery up against the contacts at the top, holding it in place.

Voila, USB-rechargeable LiPo battery pack without modifying the console.

![Wiring for the Gameboy LiPo Battery](https://raw.githubusercontent.com/senwerks/lipo-battery-for-original-gameboy/main/Meta/2021-07-20-DMG01-LiPo-06.jpg)

![Wiring for the Gameboy LiPo Battery](https://raw.githubusercontent.com/senwerks/lipo-battery-for-original-gameboy/main/Meta/2021-07-20-DMG01-LiPo-07.jpg)