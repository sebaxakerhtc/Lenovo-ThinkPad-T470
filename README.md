# Lenovo ThinkPad T470 OpenCore Configuration

<img width="1440" alt="screenshot" src="https://github.com/sebaxakerhtc/Lenovo-ThinkPad-T470/assets/32651506/042b036f-2fed-4d60-aac5-8c61e8f67819">

[![macOS](https://img.shields.io/badge/macOS-Ventura_13.5-green)](https://www.apple.com/macos/ventura/)
[![macOS](https://img.shields.io/badge/macOS-Sonoma_14.0-green)](https://www.apple.com/macos/ventura/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.3-blue)](https://github.com/acidanthera/OpenCorePkg)

#
<details>  
<summary><strong>Recent Changes ⌚️ </strong></summary>
</br>

**26.07.2023** : 
- Completely redesigned OpenCore bootloader
- OpenCore updated to ```0.9.3```
- Many kexts updated/deleted
- Deleted SSD-UIAC - so Windows can be loaded with opencore
- Some other changes

</details>

</details>




<details>  
<summary><strong>My ThinkPad T470 Hardware Specs 💻</strong></summary>
</br>

| Model              | Lenovo ThinkPad T470                                                                                      |
|:-------------------|:----------------------------------------------------------------------------------------------------------|
| Processor          | Intel Core i5-7300U (2C, 4T,  2.6GHz / 2.71GHz) vPro (The best compatibility with macOS)                  |
| Graphics           | Integrated Intel HD 620 Graphics with 4 GB of VRAM                                                        |
| Memory             | 8 GB DDR4                                                                                                 |
| Display            | 14" HD (1920x1080) IPS, (Touch disabled)                                                                  |
| Storage            | 256 GB Toshiba NVME SSD                                                                                   |
| Ethernet           | Intel Ethernet                                                                                            |
| WLAN + Bluetooth   | Intel Wifi 8265 + Bluetooth 4.0                                                                           |
| Camera             | 720p resolution, low light sensitive, fixed focus  (Infrared camera disabled by USB-MAP)                  |
| Audio support      | HD Audio, Realtek ALC3245 codec, stereo speakers 1Wx2, dual array microphone, combo audio/microphone jack |
| Keyboard           | 6-row, spill-resistant, multimedia Fn keys, LED backlight                                                 |
| Battery            | Internal Li-Polymer 3-cell (61) and External Li-Ion 3-cell (61)                                           |


</details>

</details>

<details>  
<summary><strong>Hardware Compatibility 🧰</strong></summary>
</br>
 
## What works:
- CPU Undervolting
- Dual Battery (X220 Battery patch) 
- All function keys working with yoga SMC
- Intel HD 620 Graphics
- Fan control (Fan stops at low temp below 60 and starts working above 55 automatically, not to worry)
- Touchscreen (VoodooI2C) - disabled it because it works like a f**king gaint touchpad!
- Power management (CPU friend data)
- Wi-Fi (Intel Wi-Fi 8265)
- Bluetooth 4.0 (Intel Wi-Fi 8265)
- USB C & Thunderbolt 3 (Hot plug not work, device should be connected before boot to work)
- Apple HD Audio (ALC id=29 but not 47, because 47 gives unwanted buzzing noise when 3.5mm jack connected)
- Sleep (works perfect!)
- wake works (no issues with resuming services like BT and wifi etc)
- SD Card slot
- Handoff and Continuity (idk, I don't use it)
- AirDrop (idk, I don't use it)

## What doesn't work:
- FingerPrint Reader (no implementation)
- HDMI (Will work through USB C / Thunderbolt Hub pass-through)



</details>

<details>  
<summary><strong> ⚠️ Anti-Piracy Warning / Disclaimer ⚠️ </strong></summary>
</br>

### ⚠️ PIRACY IS NO PARTY! ⚠️

I do not endorse or condone the use of pre-configured Hackintosh Distros because not only they cause unnecessary harm to your machine but it is considered to be a form of **Software Piracy**. Software Piracy is a serious crime according to copyright law and is punishable for up to 10 years in prison. 
</details>

<details>  
<summary><strong> ⚠️ Anti-Liability Disclaimer ⚠️ </strong></summary>
</br>

Hackintoshing may be dangerous and can damage your device and I am not responsible for bricked devices, dead devices, thermonuclear war, or you getting fired because your system failed. Please do some research if you have any concerns about hackintoshing before you proceed. 
</details>

</details>

## How to

Just download EFI for your choosen MacOS, change PlatformInfo and Enjoy!

## Donate

[![For EU and Other](https://github.com/sebaxakerhtc/sebaxakerhtc.github.io/raw/master/images/paypal.png)](https://paypal.me/sebaxakerhtc) &nbsp; [![Для дарений из России](https://github.com/sebaxakerhtc/sebaxakerhtc.github.io/raw/master/images/yoomoney.png)](https://donate.stream/sebaxakerhtc)

## Credits


<details>  
<summary><strong>Special Thanks to...</strong></summary>
</br>

- [Acidanthera](https://github.com/acidanthera)
- [Dortania OC guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Rehabman's battery patch guide](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/) and [Rehabman's ACPI hotpatching guide](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/)
- [CorpNewt's tools](https://github.com/corpnewt)
- [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI)
- [YogaSMC](https://github.com/zhen-zen/YogaSMC)
- [Daliansky's OC-little repo](https://github.com/daliansky/OC-little)
- [ommerus](https://github.com/ommerus), [momszx](https://github.com/momszx) and [MultimediaLukario](https://github.com/MultimediaLucario) for making this project possible.

