---
layout: post
title: Snap4Arduino 1.0.9 beta
---

This release fixes a couple of mostly internal issues you will probably not notice, _but_ what's most important is it features a new, more streamlined deployment system that paves the way for potential new versions for systems such as the Raspberry Pi or Chromebook machines.

This new system makes deploying new versions really easy, and we'll never need to compile the serial port plugin again, as we're now using the latest [nwjs](http://nwjs.io/blog/v0.13.0-beta5/), which supports native serial port communication out of the box.

Additionally, this side-fixed an annoying digital reading bug, and we've turned the digital read block into a predicate, which is what it should have always been.

As usual, you can get it [here](http://s4a.cat/snap).

Enjoy! :)
