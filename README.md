# OkMonitor
Recycle e-ink screens as monitors
Forked from https://github.com/bmsleight/OkMonitor.

# Preface
E-ink monitors are very useful for eye strain, but they are expensive. (https://shop.dasung.com/products/dasung-paperlike-color-world-first-color-e-ink-monitor is 1800 USD$!)
Yet, e-ink screens are relatively common and cheapish. They're used for price labels, for example.
How could we stream a video feed from a PC to a medium-sized display?
This project utilize a Raspberry Pi 4 and a Kindle Paperwhite to create a wireless e-ink monitor, useful for reading e.g. Wikipedia.

# Method
* Feeding an HDMI stream to a Raspberry Pi 4's USB input
* Encode it using ffmpeg
* Broadcast it using OpenWRT to a jailbroken Kindle Paperwhite.

# Originality
I will attempt to implement the suggested security features outlined at https://github.com/bmsleight/OkMonitor/issues/1. Perhaps I will be able to submit a pull request.

# License 
MIT license as it builds up [geekmaster](https://www.mobileread.com/forums/showthread.php?t=177455) work

Full project details - https://barwap.com/projects/okmonitor/
