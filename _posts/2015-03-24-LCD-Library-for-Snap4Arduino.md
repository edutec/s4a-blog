---
layout: post
title: LCD Library for Snap4Arduino
---

As promised, we are beginning to publish modified Firmata versions along with their block libraries for Snap4Arduino. This one allows you to control an LCD. Watch it in action:

<iframe width="560" height="315" src="//www.youtube.com/embed/rCrV-coweLg" frameborder="0" allowfullscreen></iframe>

We are using a 16x2 LCD display, but if your has a different number of rows or columns (as long as it is compatible with the Hitachi HD44780 driver) you will just need to modify the following piece of code in LCDFirmata.ino accordingly:

    lcd.begin(16, 2);

Please follow the [instructions in the Arduino official page](http://arduino.cc/en/pmwiki.php?n=Tutorial/LiquidCrystal) (look for the _Circuit_ section) in order to properly wire your LCD screen to the board.

In this package you will find the modified Firmata you need to push to your board (LCDFirmata.ino) and the blocks library for Snap4Arduino (LCD-library.xml). Just _File→Import_ it and you're done: [LCD-Snap4Arduino.zip](http://edutec.citilab.eu/files/LCD-Snap4Arduino.zip).

Enjoy it! :)
