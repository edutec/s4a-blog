---
layout: post
title: Snap4Arduino 1.0.3 beta
---

We have just released a new [Snap4Arduino](http://s4a.cat/snap) version that features a single improvement: now pin configurations happen automagically. You don't need to set up pins before using them anymore, [Snap4Arduino](http://s4a.cat/snap) will check whether the pin you asked for is set to the correct mode, and fix the problem otherwise.

Don't worry about older projects being loadable, the **[set pin () to mode ()]** block is still around and all of your saved projects will load properly, although this block has been deprecated and hidden from the UI to discourage its use.

We would like to thank [Bruno Schwander](https://github.com/bschwand), who suggested this change and convinced us it was the proper thing to do.

Happy prototyping!
