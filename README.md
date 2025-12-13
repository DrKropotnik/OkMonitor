# OkMonitor
Recycle e-ink screens as monitors.

Forked from https://github.com/bmsleight/OkMonitor.

Submission for Hack Club Blueprint.

# Preface
E-ink monitors are very useful for eye strain, but they are expensive. (https://shop.dasung.com/products/dasung-paperlike-color-world-first-color-e-ink-monitor is 1800 USD$!)
Yet, e-ink screens are relatively common and cheapish. They're used for price labels, for example.
How could we stream a video feed from a PC to a medium-sized display?
This project utilize a Raspberry Pi 4 and a Kindle Paperwhite to create a wireless e-ink monitor, useful for reading e.g. Wikipedia.

# Method
* Feeding an HDMI stream to a Raspberry Pi 4's USB input
* Encode it using ffmpeg
* Broadcast it using OpenWRT to a jailbroken Kindle Paperwhite.
Does not require CAD or PCBs or whatever else.

# Originality
I will attempt to implement the suggested security features outlined at https://github.com/bmsleight/OkMonitor/issues/1. Perhaps I will be able to submit a pull request.

# License 
MIT license as it builds up [geekmaster](https://www.mobileread.com/forums/showthread.php?t=177455) work

Full project details - https://barwap.com/projects/okmonitor/

# Bill of Materials

|Item|Description|Quantity|Unit Price ($USD)|URL|Running Total ($USD)|Running Total with Tax in Quebec ($USD)|
|---|---|---|---|---|---|---|
|Amazon Kindle Paperwhite 7th Generation 4GB Wi-Fi 6in Black - Grade B1|The device which will serve as the E-Ink screen. Buying Used.|1|42.20|https://www.ebay.ca/itm/267383364395|42.20|48.53|
|Raspberry Pi 4 Model B/1GB|Will receive an HDMI stream, encode it using FFMpeg then broadcast using OpenWRT. Lowest RAM possible. CPU speed is important so not using an Orange Pi.|1|40.49|pishop.ca/product/raspberry-pi-4-model-b-1gb|82.69|95.093|
