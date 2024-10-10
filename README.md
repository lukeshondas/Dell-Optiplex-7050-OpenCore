# Dell-Optiplex-7050 SFF OpenCore
## Overview

This EFI has been tested on Mac OS 14 `Sonoma` and Mac OS 15 `Sequoia`.
Also only been tested on the SFF Varient of the 7050 but I imagine it should work on the full tower too. 

## Specs

| Part             | Description                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| CPU              | Intel® Core™ i7-7700 Processor                                                                                 |
| iGPU             | Intel® HD 630                                                                                                  |
| Memory           | 32Gb (2 x 16Gb) (should work fine with 8gb+)                                                                   |
| Storage          | SSD 256gb NVMe (should work fine with SATA SSD's too)                                                          |
| Wifi & Bluetooth | None for now, May install a wifi card later.                                                                   |
| LAN              | Intel® Gigabit Ethernet, 10/100/1000                                                                           |
| Audio            | ALC ID 11                                                                                                      |
| External ports   | 1 x USB Type C, 4 x USB 3.0, 4 x USB 2.0, 1 x Ethernet, 1 x HDMI 1.4, 1 x 3.5 headphone/microphone combo, 2 x Displayport |

### Working and Not Working

|                                                   | Status | Note                              |
| ------------------------------------------------- | ------ | ----------------------------------|
| Ethernet                                          | ✅     |                                   |
| Speaker & 3.5mm audio port                        | ✅     |                                   |
| iGPU & VGA & HDMI                                 | ✅     |                                   |
| USB                                               | ✅     |                                   |
| Wifi                                              | ❌     |No Wifi card on my machine.        |
| Bluetooth                                         | ❌     |No Bluetooth card on my machine.   |
| Sleep                                             | ❌     |Unsure why not working, May explore issue more in future, but currently not an issue.   |
| Handoff                                           | ❌     |                                   |
| Airdrop                                           | ❌     |                                   |


## Usage

You will need to follow my guide [HERE](https://github.com/lukeshondas/Dell-Optiplex-7050-OpenCore/blob/main/Bios%20Guide.md) This EFI will NOT work at all unless you do so.

Download my EFI, Change your Serial with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and install.
