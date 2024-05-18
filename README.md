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

**OpenCore Version:** DBG-099-2024-03-11

**Tested macOS version:** macOS Ventura [14.5]

This will theoratically work on Ventura and below.

------------


### My Specifications:

> Again, if we had the same processor and graphics, this may work on your device with a little bit of tinkering. Also, this is the default configuration from the factory. No replaced chips or whatsoever.

|  **Hardware**  |  **Details**  |
| ------------ | ------------ |
|  **CPU** |  i5-8250u |
| **GPU** | Intel UHD 620|
|  **Memory** |  16GB DDR4 |
| **Storage** | Samsung M.2|
| **Network Card** | Intel |
| **Audio** | alcid=11 |


------------

### 🤔 What works?

**Status Indicators:**

✅ - Working

❎ - Does not Work

🤔 - Untested Yet

(*) - Read Comment below table

| Feature  | Is it working?  |
| ------------ | ------------ |
|  **WiFi & Bluetooth**  |  ✅ * |
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

> ** I had been using macOS Sonoma 14.5, and the latest Intel Pre-Release WiFi drivers only support up to 14.4. It is really buggy. If you want stable WiFi and Bluetooth, I suggest you should install macOS Ventura

------------

> *! DRM would not work on Integrated Intel GPUs. Descrete GPUs are required for DRM to work.
Apple Music can still play songs, but not with Dolby Atmos or the fancy Hi-Res Lossless Audio Quality. Apple TV can play videos just fine.

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
