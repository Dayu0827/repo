# CoolBooterAudioFix iOS 7 beta

Experimental iOS 7.x package; not validated on physical iOS 7 hardware. It renames `/Library/Audio/Plug-Ins/HAL/AirTunesHAL.pdev` to `.bak` and attempts to restore it on removal. Disabling the plugin may remove AirPlay output support.

Before testing, back up the plugin externally, confirm the device is booted into iOS 7, inspect the exact paths, and do not install if the original path is absent or `.bak` already exists. Reboot after installation and after restoration. Do not claim iOS 7 support until a physical-device test verifies installation, playback behavior, and rollback.
