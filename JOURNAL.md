---
title: "Slate"
github: "https://github.com/nsreeni07/Slate"
description: "A custom mechanical keyboard designed from scratch in CAD, it has a 65%-style layout with hot-swappable key switches, a Raspberry Pi Pico as the controller, screw-in stabilizers. I built this keyboard because for a long time I have always wanted my own keyboard and the keyboard on my laptop isnt the best. I also made a custom wrist rest to make typing easier for long durations."
created_at: "2026-08-06"
total_time: "9h 30m"
---

# October 25, 2026: Schematic
<!-- fabricate:entry 1255 -->

so today I followed the schematic and made my 60% keyboard I first used a website to get the overall layout I wanted and then made the actual schematic this only took a while because my kicad was tweaking and kept numbering the switches incorrectly so I had to go back and rename them. Thats pretty much it, tommorow I'm going to start with the pcb and then make the cad
![](https://fabricate.hackclub-assets.com/bfbb7b2f976de7ff3eaebeb2a545c3f12b1d55390a74d6c2c3ddd93fcbba7b31/image-png/image.png)

**Total time spent: 1h 30m**

# October 25, 2026 (entry 2): Routed the PCB
<!-- fabricate:entry 1256 -->

So today I worked on the pcb, This took forever for one reason and one reason only I kept messing up the order of the keys, for some reason when i exported the schematics (first the footprints were messed up) it ordered them in a random order, so I had to keep going back and forth checking the schematic to make sure I was ordering them right, and after spending what felt like and eternity and suffering through kicad crashing halfway through I finnaly finished the pcb placing, Then began the routing. Luckily this went much faster and a lot smoother, like I mean a lot smoother. After routing I added some small silkscreen and I exported the 3d files to start with my cad.

![](https://fabricate.hackclub-assets.com/31c2df34da40fc17e4cf0025b2fbbea15ab72551b2956341ad60df011f3fe02f/image-png/image.png)

**Total time spent: 3h**

# October 25, 2026 (entry 3): CAD
<!-- fabricate:entry 1258 -->

Today I started with my case for my keyboard, I hoped this would go better than the pcb and it did the only thing that I messed up was that when I was making the hole for the usb port I kept forgetting to save the sketch and when I went into assembly I though it should fit but it didnt and I only realized after I wasnt even changing the part which was one my other than that it went pretty well, I also designed a custom armrest to make typing easier. After I started lookig on aliexpress for switches and found some cool white and light orange colored ones I liked, I also found cheap diodes and cherrymx switches. I then made the BOM and after I fixed up my github and thats pretty much it. I also wrote the firmware for the 
![](https://fabricate.hackclub-assets.com/b3c07f8751bf78ecabc68005778a3a708431a91a454b4687d96c46de01abe149/image-png/image.png)

**Total time spent: 5h**
