---
layout: post
title: Snap4Arduino 1.1-beta
---

We've just published a new [Snap4Arduino](http://s4a.cat/snap) version, codenamed 1.1-beta.

These are the major changes included in this release:

* **New HTTP protocol**, analogous to the one that Scratch 1.4 used to have (and thus S4A), that allows us to control Snap4Arduino via the Internet or LAN. To learn more about it, please refer to [this old Scratch wiki entry](http://wiki.scratch.mit.edu/wiki/Remote_Sensors_Protocol). This also means you can now use our old S4A remote control Android app and webapp, which you can find [here](http://s4a.cat/#android).

* **Exporting to Processing** ("Arduino C") **has been heavily enhanced** for servomotors and also for code that only needs to run once (outside of the loop() function). You can now also choose your own file names.

* **Switched to nwjs beta**. This shouldn't bother you at all, but it paves the way for me to bring Snap4Arduino to other platforms such as the RaspberryPi or the Chromebook. MacOSX users may experience a funny error when closing Snap4Arduino, which you can ignore for now. As this nwjs version moves forward, this error should go away.

* **Ability to disconnect servo motors**, so that it doesn't matter whether they're properly calibrated, you can always make them stop.

* **Digital readings are now boolean reporters** (predicates). Block-wise, this means they're now diamond-shaped.

* **Added Snap!'s keyboard editing capabilities**. To try them out go to settings → Keyboard editing.

One final announcement. Ove Risberg contributed, a long while ago, an enhancement to Snap4Arduino to program the board via wifi (instead of a USB cable or bluetooth module) using an _ESP8266_ module. We couldn't get the time to include his changes in this release, but we'll hopefully manage to do so before the end of this month.

Enjoy!
