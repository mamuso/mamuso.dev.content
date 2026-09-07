---
title: Hi, fluxcapacitor!
date: '2020-04-23'
basename: '2020-04-23-hi-fluxcapacitor.png'
category: note
width: 3360
height: 2100
---

WELL, WELL! Fluxcapacitor (formerly Timesled, I’m terrible at naming projects) runs like a charm on GitHub Actions, and I rewrote a big chunk of the code to make it easier to maintain:

- It runs every three days
- The first stable run (capture, process, compare, store) had 104 endpoints and 3 devices
- It took 1h 32m to finish
- The next run will process over 140 endpoints

The infra is more sophisticated than a few months ago. The images and the tgzs of the captures are blobs in Azure, and Prisma 2 handles the data layer.

I'm really happy with the progress so far :)
