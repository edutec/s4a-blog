---
layout: post
title: Snap4Arduino Arduino Sketch Generation
---

We've always been reluctant to add such a feature because we believe the main reason tools like S4A and Snap4Arduino are successful is because they inherit their parent project's dynamic properties. That is, you still have a live environment while your board is plugged in, you enjoy immediate response, you don't lose parallelism and you don't need to compile or translate code into text and push it to the board to see what it does. Code is code regardless of whether you draw it, punch it into cards, stack blocks together or write it.

However, several people have been asking for this for a long time, and although we praise dynamism we do understand the reasons behind this. So, lo and behold, __you can now translate simple scripts into Arduino sketches__!

To get this working, go to the File menu and select "_New Arduino translatable project_". This will open a new project in the Arduino translation mode.

Translatable scripts need to start with a green flag hat block, and the main program loop is represented by a forever block. Once you're done with your script, just right click on the green flag hat block and select "_export as Arduino sketch_". Now you've got a _.ino_ file ready to compile and push to your board.

Happy... compiling!

_<small>We never thought we'd ever end up saying that!</small>_
