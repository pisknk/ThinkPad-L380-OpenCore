### ThinkPad L380 | OpenCore EFI Config

------------

![](https://github.com/pisknk/ThinkPad-L380-OpenCore/blob/main/screenshots/1.png)


------------

#### Friendly Reminders:
> ⚠️ Even though this EFI works on my L380, it does not automatically mean that it will work on yours. I am not be held liable for bricked devices. Use this EFI at your own risk.

------------



> 📝 **Create your own SMBIOS-es.** You can use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS "GenSMBIOS") to generate one.

------------


> 🤝 If we have similar specs, this EFI **may** work on your device (with a little bit of tinkering).


------------

### About this EFI

**OpenCore Version:** RELEASE-099-2024-03-11

**Tested macOS version(s):**

- Big Sur [11] (Works, but most apps and services like Homebrew does not work anymore)
- Monterey [12.7.4] (Honestly, this is the sweet spot!)
- Ventura [13.3] (Works great, specially with Continuity Camera!)
- Sonoma [14.5] (Has heating issues)
- Sequoia [15] (Really laggy, wouldn't recommend)

This will theoratically work on Catalina and below.

------------


### My Specifications:

> Again, if we had the same processor and graphics, this may work on your device with a little bit of tinkering. Also, this is the default configuration from the factory. No replaced chips or whatsoever.

|  **Hardware**  |  **Details**  |
| ------------ | ------------ |
|  **CPU** |  i5-8250u |
| **GPU** | Intel UHD 620 |
|  **Memory** |  16GB DDR4 |
| **Storage** | Samsung M.2|
| **Network Card** | BCM94360NG (Switched from Intel Dual Band Wireless-AC 3165) |
| **Audio** | ALC257 |


------------

### 🤔 What works?

**Status Indicators:**

✅ - Working

❎ - Does not Work

🤔 - Untested Yet

(*) - Read Comment below table

| Feature  | Is it working?  |
| ------------ | ------------ |
|  **WiFi & Bluetooth**  |  ✅ *1 |
| **Audio (Speaker)**   |  ✅ |
| **Audio (Jack)**   |  ✅ |
| **Graphics Acceleration**   |   ✅|
| **Brightness & Audio Controls**   |  ✅ |
| **TrackPad & Red Nibble**   | ✅  |
| **Battery Information**   | ✅  |
| **USB Port Mapping (Type-C & A)**   |  ✅ |
| **Camera & Microphone**   |  ✅ |
| **Sleep** | ✅|
| **Power Management**   |  ✅ |
| **Software Updates**   |  ✅*# |
| **iServices (iMessage & FaceTime)**   |  ✅ |
| **AirDrop & Continuity**   |  ✅ |
| **DRM (Apple Music & TV)**   |  ❎ *! |
| **HDMI**  |  ✅ |

> *1 - I had switched to an Broadcom Chip. Previous Releases like [Version 2](https://github.com/pisknk/ThinkPad-L380-OpenCore/releases/tag/v2) still has Intel Drivers.

------------

> *! DRM would not work on Integrated Intel GPUs. Descrete GPUs are required for DRM to work.
Apple Music can still play songs, but not with Dolby Atmos or the fancy Hi-Res Lossless Audio Quality. Apple TV can play videos just fine. There is a Pre-Release EFI that brings Apple Lossless and Dolby Atmos Audio at the expense of Energy Management.

------------

> *# Update macOS with caution. May cause your system to not boot up or break some features. Always check if the OpenCore version is compatible with the update.

------------

### How to use this?

**Pre-Requisites:**
- A USB stick or drive with 4GBs and up.
- Backup your data.
- A stable internet connection.
- Access to another computer or laptop.
- 1-3 hours of free time on your hands.

**Tutorials:**

🪟 [Create macOS Installer using Windows](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.htmlhttp:// "Create macOS Installer using Windows")

🐧 [Create macOS Installer using Linux](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.htmlhttp:// "Create macOS Installer using Linux")

🍎 [Create macOS Installer using a Mac](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html "Create macOS Installer using a Mac")


------------

### Questions and Clarifications?

I would love to hear them! Please leave it in the Issues tab. Found an Issue? Freely do that too! I really appreciate it :3
