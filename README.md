# Lenovo ThinkPad T14s Gen 1 - OpenCore Configuration - macOS SONOMA 14.7

[![macOS](https://img.shields.io/badge/macOS-Sonoma-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Monterey-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Mammoth-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.8.0-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)

&nbsp;

If you enjoyed this project — or just feeling generous, consider buying me a coffee. Cheers! :coffee:


**DISCLAIMER:**  
This OpenCore EFI works fine on my Thinkpad T14 Gen 1.
I am not responsible for any damages you may cause.  
Should you find an error or improve anything — whether in the config or in the documentation — please consider opening an issue or pull request.

&nbsp;

## 💻 My Hardware

| Category  | Component                                  |
| --------- | ------------------------------------------ |
| CPU       | Intel(R) Core(TM) i7-10610U CPU @ 1.60GHz  |
| GPU       | Intel UHD Graphics 630                     |
| SSD       | 500GB M.2 NVMe SSD                |
| Memory    | 32GB DDR4 2666Mhz due CPU                  |
| Camera    | 720p Camera + IR Camera                    |
| Audio     | Intel Smart Sound Technology: Realtek HDA ALC257 (aka ALC3287)    |
| WiFi & BT | Intel Wi-Fi 6 AX201 802.11ax 2x2 with BT5.2 (Soldered on)           |
| Display   | 14" Full HD (1920x1080) IPS, touch         |

&nbsp;


&nbsp;

## 🔄 Update Tracker

| Software  | Version                                                       |
| --------- | --------------------------------------------------------------|
| [MacOS](https://www.apple.com/macos/)                            | 14.7  |
| [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases)  | 1.0.1   |

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth 
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio Out (Audio Jack & Speaker)
- [X] Audio In (Microphone Only from Audio Jack)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] Automatic OS updates
- [X] Handoff / Universal Clipboard
- [X] SIP / FireVault 2
- [X] USB-C
- [X] Thunderbolt 3


</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>
- [ ] HDMI
- [ ] Internal Microphone, common issue laptop with Intel Smart Sound Technology ( Intel SST )
- [ ] Safari DRM ```Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others```
- [ ] AirDrop & Continuity

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock
- [ ] WWAN
- [ ] Sidecar (Cable) / AirPlay to Mac


</details>

&nbsp;

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

&nbsp;

## 📜 License

This repo is licensed under the [MIT License].

OpenCore is licensed under the [BSD 3-Clause License](https://github.com/acidanthera/OpenCorePkg/blob/master/LICENSE.txt).


&nbsp;

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Baio1977](https://github.com/Baio1977/) Ventura EFI for T14 Gen 1.
- [simprecicchiani](https://github.com/simprecicchiani/ThinkPad-T460s-macOS-OpenCore/) Helping me add Touchsreen to my T460s and works for T14 too.
- [askwakhid](https://github.com/askwakhid/ThinkPad-T14-macOS-OpenCore/tree/main/) Base EFI that I'm using
