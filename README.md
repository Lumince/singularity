![singularity icon](https://github.com/Lumince/singularity/blob/main/icon.png)

# Singularity

Singularity is an AIO fugu exploit root app for Meta VR headsets. \
Root in 3-10 seconds enjoy ;) \
The source for fugu can be found [here](https://github.com/Henry1887/fuguquest).

This supports Quest 2, pro, 3, and 3s currently. The process can take a bit to achieve root access. If you are having issues with it failing. Please power the device off and on and try again.

## Usage
1. Install the app with ADB with the command `adb install -g Singularity.apk`
2. Setup Wireless ADB (The app will tell you how too)
3. Press Root Now (If it stops and Root Now is no longer greyed out, press it again)
4. Once you gain root, it will soft reboot. Don't try to root again.
5. Check If an app called Singularity-Magisk is in Unknown Sources
6. If it is, open it and grant Singularity root in the Super User tab and close/reopen Singularity

## Features
- Root-on-boot for root
- Magisk installer built in
- Rooted/Unrooted Terminal
- Controller Pairing
- FreeXR [safe root things](https://github.com/FreeXR/safe-root-things) (LED color, UI tweaks, dogfood hub)
- Important Partition Protector
- Meta Telemetry disabler
- Update Engine disabler (Stops forced updates while rooted)
- Meta Backdoor disabler 
- Internet kill switch and Domain Blocker
- Wireless ADB Setup
- Manual Fan Controller
- Battery Charge Limter
- Frida-Server 
- Meta Based Zygisk "Fix"
- Build type spoofer (user, userdebug, eng)
- Fix Controllers option (Some have issues with controllers not working after root)
- Double Tap Passthrough disabler
- Proximity Sensor disabler (with dock charger Quest Pro detection)
- Soft Rebooting
- Boot animation switcher (Not permanent)
- USB notification auto accepting for MTP access
- Eye Calibration launcher for Quest Pro
- Loft Installation for devices missing the environment
- Simultaneous Hands & Controllers (Buggy)
- No-controller requirement
- System hang fix (prevents system from hanging in certain conditions)
- UI switching (DockUI/NavUI)
- CPU/GPU monitoring/configuration
- App manager (Installing/Uninstalling/Launching)
- Built in Magisk/Vector module manager

## Installation

Download the latest APK from [releases](https://github.com/Lumince/singularity/releases), and sideload it with "**adb install -g Singularity.apk**"

"-g" will grant the needed "WRITE_SECURE_SETTINGS" permission so Singularity can enable Wireless ADB on the device.

## Frida

This repo contains Frida-Server, source is [here](https://github.com/frida/frida)

## CONFIRMED LATEST BUILDS
Quest 3 (Eureka) [52433670036000520](https://files.cocaine.trade/firmware/meta/Quest%203/q3_52433670036000520.zip) /
Quest 3s (Panther) 3814840024700610 (Not current on cocaine) /
Quest 2 (Hollywood) [52242990024200150](https://files.cocaine.trade/firmware/meta/Quest%202/q2_52242990024200150.zip) /
Quest Pro (Seacliff) [51503870024400340](https://files.cocaine.trade/firmware/meta/Quest%20Pro/QPro_51503870024400340.zip) /

Find out your incremental with this command `adb shell getprop ro.build.version.incremental`

## Credits
- Henry for fugu exploit
- topjohnwu and the Magisk developers for Magisk
- Beom, & Darknight for their work on Pancake (ionstack quest port) (old pancake exploit)
- TrashyOne, ToastConcern, ARDiva, for testing Singularity
