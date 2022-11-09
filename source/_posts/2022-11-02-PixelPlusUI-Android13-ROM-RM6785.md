---
title: PixelPlusUI v5.0 ROM [Android13] Realme 6, 6i, 6s and Realme 7, Narzo 20 Pro, Narzo 30 4G (G90T Series) (RM6785) [OFFICIAL]
date: 2022-11-02 22:53:00 +0530
categories: [ROMs]
feature: false
tags: [PixelPlusUI, PPUI, RM6785]
---

![PixelPlusUI](/img/ppui_5.0/PPUI_A13.webp)

**PixelPlusUI** YET ANOTHER PIXEL ROM!
Android is one of the most featuristic OS. We all know that it is Google that provides the Android Platform and its maintenance. Based on which OEMs build their own custom Firmware/Skin/ROM such as Xiaomi's MIUI, Samsung's OneUI, OnePlus' OxygenOS, etc. Due to the fact that Android is an open-source platform, developers can build their own ROM/Firmware/Skin and that is what we commonly refer to as Custom ROM. Unlike OEMs, Custom ROM developers provide frequent updates, a bloatware-free, and ad-free experience with great flexibility when it comes to the usability of the OS.

# Working features
* VoLTE, Wifi calling
* Fingerprint sensor
* WiFi 
* Bluetooth
* SELinux
* RIL (Data,SMS,Calls)
* Camera
* Camcorder
* Audio
* GPS
* NFC
* Sensors
* Video Playback
* ZRAM
* Internal audio recording
* Faceunlock
* Safetynet without magisk
* DT2W
* EngineerMode

# Known issues

- Native video calling (ViLTE) and Voice over WiFi (VoWiFi)
- USB Audio

# Changelog

Initial Android 13 built.


# Screenshots 
<style> .screenshot {
  border-radius: 10px;
  margin: 10px;
  display: inline-block;
  width: 282px;
}
</style>
<div class="screenshot">

  ![UI](/img/ppui_5.0/01.jpg)   
  ![UI](/img/ppui_5.0/02.jpg)  
  ![UI](/img/ppui_5.0/03.jpg)  
  ![UI](/img/ppui_5.0/04.jpg)  
  ![UI](/img/ppui_5.0/05.jpg)  
  ![UI](/img/ppui_5.0/06.jpg)  
  ![UI](/img/ppui_5.0/07.jpg)  
  ![UI](/img/ppui_5.0/09.jpg)  
  ![UI](/img/ppui_5.0/10.jpg)  
  ![UI](/img/ppui_5.0/11.jpg)  
  ![UI](/img/ppui_5.0/12.jpg)  
  ![UI](/img/ppui_5.0/13.jpg)  
  ![UI](/img/ppui_5.0/14.jpg)  
  ![UI](/img/ppui_5.0/15.jpg)  
  ![UI](/img/ppui_5.0/16.jpg)  
  ![UI](/img/ppui_5.0/17.jpg)  
  ![UI](/img/ppui_5.0/18.jpg)  
  ![UI](/img/ppui_5.0/19.jpg)  
  ![UI](/img/ppui_5.0/20.jpg)  
  ![UI](/img/ppui_5.0/21.jpg)  
  ![UI](/img/ppui_5.0/22.jpg)  
  ![UI](/img/ppui_5.0/23.jpg)  
  ![UI](/img/ppui_5.0/24.jpg)  
</div>

# Reporting Bugs
- Don’t report bugs if you have any custom kernel or module installed
- Create new [issue here](https://github.com/iamthecloverly/android_device_realme_RM6785) or Report it [here](https://t.me/SriBalajiHub).
- Grab a logcat right after the problem has occurred. (Please include at least a few pages of the log, not just the last few lines, unless you know what you’re doing.)
- If it is a random reboot, grab /proc/last_kmsg. (Do not bother getting a logcat unless you can get it just before the reboot. A logcat after a reboot is useless)

# Instructions
If you are coming from RealmeUI-1.0 or RealmeUI-2.0 or any custom ROM
- Boot into custom recovery
- Format data
- Flash latest build
- Flash Lineage Recovery
- Reboot your device once the installation is done

# FAQs

## Can I flash this rom from RealmeUI-1.0 or custom ROM based on it?
- Yes! this build contains RealmeUI-2.0 firmware so doesn’t matter what ROM you are on.

## How to root?
- Download latest Magisk apk and flash it from RECOVERY.

## I can’t boot into RECOVERY mode after flashing this ROM

- You can, just not with the key combo. Realme have mapped that combo to bootloader instead of recovery unlike in RealmeUI-1.0.
Enable Advanced restart from `Settings->System->Buttons->Power Menu` and use that

## How to flash stuffs in recovery
- Use External SDCard or adb sideload

## Safetynet is failing after rooting the device
- If you are on Magisk 23.0:
- Enable MagiskHide from Magisk Manager app
- If you are on Magisk 24.0+ (Zygisk):
    - Enable `“Zygisk”` option from the Magisk Manager app
    - Reboot your device
    - Enable `“Enforce DenyList”` option
    - Go in `“Configure DenyList”`
    - Enable `“Show system apps” option then search ‘Google Play Services’ and tap on it (but NOT on the tick box!)` to expand activities
    - Enable `“com.google.android.gms” and “com.google.android.gms.unstable”`

# Downloads
*GApps Variant*<li> - [Download](https://ppui.site/download) 
