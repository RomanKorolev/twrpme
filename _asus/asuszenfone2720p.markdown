---
layout: device
title:  "Asus ZenFone 2 720p"
codename: Z008
downloadfolder: Z008
supportstatus: Current
maintainer: jrior001
oem: Asus
devicetree: https://github.com/teamwin/android_device_asus_Z008
ddof: /dev/block/by-name/recovery
---

{% include disclaimer.html %}

{% include supportstatus.html %}
TWRP 3.1.1+ releases work only on Stock M bootloader, all previous versions should work on LP bootlaoder.
Starting with TWRP 3.0.0, Z008 and Z00A TWRP builds are unified. The same image will work on both models.

{% include appinstall.html %}

{% include download.html %}

{% include twrpinstall.html %}

{% include fastbootinstall.html %}

{% include ddinstall.html %}
