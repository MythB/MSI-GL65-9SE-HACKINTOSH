### MSI GL65 9SE Hackintosh
[![macOS](https://img.shields.io/badge/macOS_Sonoma-14.0-Sbrightgreen.svg)](https://www.apple.com/macos/sonoma)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.5-blue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![DualBoot](https://img.shields.io/badge/DualBoot-8A2BE2.svg)]()

### Hardware
| Component      |Info                                      |
|----------------|------------------------------------------|
| **CPU**        |  Intel Core i7-9750H                     |
| **RAM**        |  Samsung 2x8GB 2666mhz M471AK43CB1-CTD   |
| **Storage**    |  Samsung SSD 970 EVO Plus 1TB            |
| **Screen**     |  15.6" 1920x1080 120hz                   |
| **iGPU**       |  Intel UHD Graphics 630                  |
| **dGPU**       |  Nvidia RTX 2060(disabled)               |
| **Audio**      |  Realtek ALC269                          |
| **Ethernet**   |  Realtek Gigabit Ethernet                |
| **Trackpad**   |  Synaptics                               |
| **WiFi card**  |  Intel(R) Wireless-AC 9560 160MHz        |
| **SD card**    |  Realtek USB 2.0 Card Reader             |
| **Battery**    |  53Wh                                    |

### Status
**Everything works!**

**Except:** `RTX 2060 (No macOS driver support)` and `HDMI (port wired to dGPU)`.

### BIOS Settings
* Fast Boot and Secure Boot = **Disabled**
* Intel(R) Speed Shift Technology: = **Enabled**
* USB Configuration > XHCI Hand-off = **Enabled**
* Intel Virtualization Technology and VT-d = **Enabled**
* System Agent (SA) Configuration > Graphics Configuration > DVMT Pre-Allocated = **64M**
* Power & Performance > CPU-Power Management Control > Configure CPU Lock Options > CFG lock = **Disabled**

<img align="center" src="./Media/macOS_About.png" width="420">
