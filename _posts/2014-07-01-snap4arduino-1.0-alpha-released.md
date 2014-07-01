---
layout: post
title: Snap4Arduino 1.0 alpha released
---

It took a little bit longer than expected, but we've finally released the first alpha version of [Snap4Arduino](http://s4a.cat/snap)!

There have been many changes and improvements since the last pre-alpha version, such as:

- **Desktop based**
- Snap4Arduino is now a desktop application, so you don't need a browser anymore! This also means there is no intermediate server dealing with HTTP and WebSocket requests, which translates into a much (**much!**) faster development experience, and shorter response cycles between the PC and the board. Fewer layers and components also mean easier maintainance and development.

- **Modified connect block**
- You no longer need to specify which board you are using. This means the same program will work regardless of the board you plug.

- **Export file dialog**
- When you export a project, you don't need to manually copy-paste (or right-click, download as) an XML anymore. A file dialog will pop up asking for a file name. This is also thanks to Snap4Arduino being now a desktop application.

- **Win32 installer**
- Windows users can now enjoy an installer (and un-installer, although we hope you don't need to use it).

- **Bugfixes**
- A bunch of bugs have been tracked down and fixed too.

All programs written in previous versions will work in this new release, as long as you first take care to remove the *connect* block. Since this block has been modified, failing to remove it before importing the project will result in an error and the software will most probably crash.

This version has been tested and found to work perfectly in all the boards we own at [Citilab](http://citilab.eu), namely:

- UNO
- Mega 2560
- Duemilanova
- Diecimila
- Nano

As always, there will be bugs, so we need your help to hunt them and fix them until we feel the software is ready for a beta release.

You can find the new alpha version at [http://s4a.cat/snap](http://s4a.cat/snap)

Happy prototyping!
