---
title: Capture and minify
date: '2019-12-05'
category: note
basename: '2019-12-05-capture-minify.png'
width: 3360
height: 2056
---

The action now iterates over a few devices and a list of URLs. It is slow, but that was expected.

I'm worried about the amount of image data each run produces, to the point where I'm considering implementing the storage layer straight away. I also added image optimization, but I wonder if it is going to mess with pixelmatch.
