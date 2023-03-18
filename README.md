# Lenovo ThinkPad T470 OpenCore Configuration

![repository-VENTURA-graph-template](https://user-images.githubusercontent.com/72415505/226120563-c3dc52be-ebb8-4e89-b143-b3c6c960af2f.png)



[![macOS](https://img.shields.io/badge/macOS-Big_Sur_11.7.4-red)](https://www.apple.com/macos/big-sur/)
[![macOS](https://img.shields.io/badge/macOS-Monterey_12.6.3-green)](https://www.apple.com/macos/monterey/)
[![macOS](https://img.shields.io/badge/macOS-Ventura_13.2.1-orange)](https://www.apple.com/macos/Ventura/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.8.8-blue)](https://github.com/acidanthera/OpenCorePkg)


<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>OpenCore Version: </strong>0.8.8
   <br />
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T440s/releases"><strong>Download now »</strong></a>
   <br />
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T440s/discussions">Report Bug</a>
   ·
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T440s/blob/main/CHANGELOG.md">Recent Changes</a>
   ·
   <a href=https://www.youtube.com/watch?v=6cAxwXj5Zy4">YouTube Review</a>
   ·
   <a href="https://github.com/momszx/Lenovo_T470_Opencore">Original Repo</a>
  </p>
</p>
</br>

#
<details>  
<summary><strong>Recent Changes ⌚️ </strong></summary>
</br>
                                                                                                        
**02/01/2023** : Updated to ```OpenCore 0.8.8``` .
                                                           
**12/14/2022** : Updated to ```OpenCore 0.8.7``` .

**11/14/2022** : Updated to ```OpenCore 0.8.6``` . 

**11/09/2022** : Changed the SMBIOS from ```MacBookPro12,1``` to ```MacBookPro14,1``` for better power management.

**10/25/2022** : Downgraded back to ```OpenCore 0.8.3``` to avoid kernel panics and improve stability.
                                                           
**10/14/2022** : Changed the SMBIOS from ```MacBookPro11,5``` to  ```MacBookPro12,1```  and finally added support for video out in macOS Monterey.

**10/12/2022** : Updated from OpenCore 0.8.3 to OpenCore 0.8.5                                                          
                                                           
**09/29/2022** : Added TrackPoint support and fixed the Instant Wake Issue when in sleep mode.

**09/26/2022** : Added Bluetooth support for macOS Monterey & fixed the slow startup issue.

**09/18/2022** : Changed the SMBIOS from ```MacBookPro11,1``` to  ```MacBookPro11,5``` for macOS Monterey.

</details>

</details>




<details>  
<summary><strong>My ThinkPad T470 Hardware Specs 💻</strong></summary>
</br>

| Model              | Lenovo ThinkPad T470                                                                              |
|:-------------------|:----------------------------------------------------------------------------------------------------------|
| Processor          | Intel Core i5-7300U (2C, 4T,  2.6GHz / 2.71GHz) vPro (The best compatibility with macOS)                                                              
| Graphics           | Integrated Intel HD 620 Graphics                                                                          |
| Memory             | 8 GB DDR4 (2x 4GB DDR4 SODIMM)                                                       |
| Display            | 14" HD (1920x1080) IPS, Non-Touch                                                                      |
| Storage            | 1 TB Pioneer SATA SSD + 16 GB mSATA SSD                                                                             |
| Ethernet           | Intel Ethernet                                                         |
| WLAN + Bluetooth   | Intel Wifi 18265 + Bluetooth 4.2                                        |
| Camera             | 720p resolution, low light sensitive, fixed focus                                                       |
| Audio support      | HD Audio, Realtek ALC3245 codec, stereo speakers 1Wx2, dual array microphone, combo audio/microphone jack |
| Keyboard           | 6-row, spill-resistant, multimedia Fn keys, LED backlight                                                 |
| Battery            | Internal Li-Polymer 3-cell (61) and External Li-Ion 3-cell (61)                       |


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
- Wi-Fi (Intel Wi-Fi 18265 & Broadcom BCM94360NG)
- Bluetooth 4.0 (Intel Wi-Fi 18265 & Broadcom BCM94360NG)
- USB C & Thunderbolt 3 
- Apple HD Audio (ALC id=29 but not 47, because 47 gives unwanted buzzing noise when 3.5mm jack connected)
- Sleep (works perfect!)
- wake works (no issues with resuming services like BT and wifi etc)
- SD Card slot
- Handoff and Continuity (Intel Wi-Fi 18265 & Broadcom BCM94360NG)
- AirDrop (Broadcom BCM94360NG Only)

## What doesn't work:
- FingerPrint Reader
- HDMI (Will work through USB C / Thunderbolt Hub pass-through)



</details>

</details>

<details>  
<summary><strong>Photos 📷 </strong></summary>
</br>

![Screenshot 2022-09-13 at 6 00 02 AM](https://user-images.githubusercontent.com/69560584/189782384-6f9df794-3fac-48b6-9e40-c135c030c8f5.png)

![Screenshot 2022-09-13 at 5 55 21 AM](https://user-images.githubusercontent.com/69560584/189782400-99d6fef9-711e-41a6-a687-c9dc68210f5d.png)

![Screenshot 2022-09-13 at 5 54 45 AM](https://user-images.githubusercontent.com/69560584/189782402-60d9235a-bb02-4887-8e1d-4b8764056cce.png)

![Screenshot 2022-09-13 at 5 54 37 AM](https://user-images.githubusercontent.com/69560584/189782404-569861de-ad6c-4695-8f87-2b967549b6db.png)


</details>

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

### ⚠️ Warning ⚠️

- Hackintoshing may be dangerous and can damage your device and I am not responsible for bricked devices, dead devices, thermonuclear war, or you getting fired because your system failed. Please do some research if you have any concerns about hackintoshing before you proceed. 
</details>



**Battery and power management performance and more perks!**
- Disable hibernation, since it doesn't work properly on hackintoshes
```
sudo pmset autopoweroff 0
sudo pmset powernap 0
sudo pmset standby 0
sudo pmset proximitywake 0
sudo pmset tcpkeepalive 0
```
- Use itlwm/Airportitlwm for wifi and bluetooth firmware & injector kexts if you are on an intel wifi card, no kexts needed for bcm94360ng. //Note: for Monterey and above use bluetool fixup instead of bluetooth injector kext.//
- Temperature management is decent and backup depends on how you use and on what task the system is running
- Battery performance is same as windows
- Sleep works fine with approx 8% for 6 Hrs loss (Which is neglegible)
- Enable HiDpi by using this beautiful tool at "https://github.com/xzhih/one-key-hidpi", Set 2048x1152x32 [16:9] as best screen resolution using RDM(Retina Display Menu) from here -> "https://github.com/avibrazil/RDM".
- If you are using FakeSMC fan rpm shows up natively, if you are using VirtualSMC then use YogaSMC.kext for fan rpm.
- unifiedmem values for vram 
```
00000040 = 1024MB
00000060 = 1536MB
00000080 = 2048MB
000000A0 = 2560MB
000000C0 = 3072MB
000000E0 = 3584MB
FFFFFFFF = 4096MB
```
**Undervolting the hackintoshed T470:**

![Screenshot 2022-11-20 at 4 55 01 PM](https://user-images.githubusercontent.com/69560584/202903425-7d8368f6-41a6-46c2-9930-2c26ad044bcb.png)

- T470 is powerful and efficent but very hungry machine and makes noise too.. so its important to calm down him so he can be cool enough.. which is where we need to undervolt the machine. Undervolting is safe than overclocking just that if you undervolt too much and your machine hangs up so know the limits and know where to hold him live!
- Go to recovery and open terminal, now follow the below instructions..
- type now : 
```
sudo csrutil enable --without kext
```
Now, reboot to your desktop and download voltage shift from "https://github.com/sicreative/VoltageShift/blob/master/voltageshift_1.25.zip" and extract the contents to your Documents folder, also move the VoltageShift.kext to your EFI/OC/Kexts and update your info.plist and use proper tree to take a snapshot too.
- Now open a terminal at this folder and run
```
sudo ./voltageshift info
```
- This should look like this if your overclocking unlock was successful:
```
CPU voltage offset: 0mv
GPU voltage offset: 0mv
CPU Cache voltage offset: 0mv
OC mailbox cmd failed
System Agency offset: 0mv
Analogy I/O: 0mv
OC mailbox cmd failed
Digital I/O: 0mv
CPU BaseFreq: 1200, CPU MaxFreq(1/2/4): 3400/3400/3400 (mhz) 
CPU Freq: 1.4ghz, Voltage: 0.6499v, Power:pkg 2.29w /core 0.22w,Temp: 53 c
```
- Now you can run (Values that match to your machine)
```
./voltageshift offset -60 -50 -60
```
- -60 offsets cpu voltage by -60mv, then -50 the gpu voltage and -60 again offsets the cpu cache voltage
- Test a range of values for all. For me, -155 -80 -155 caused a crash so I stayed at -130 -75 -130 which was stable.
- Once you have found a stable set of values run the following which will save the changes and rerun then on reboots when they would otherwise be disabled:
```
sudo ./voltageshift buildlaunchd  -130 -75 -130 0 0 0 0 0 1 10 12 1 160
```
- Here the values 10 and 12 are your PL1 and PL2s, since my CPU's TDP is 12w, I set the PL1 to 10W and PL2 to 12W. The 160 simply reruns the command every 160min since Hibernation resets your undervolts.
- The remaining values do this:
```
sudo ./voltageshift buildlaunchd <CPU> <GPU> <CPUCache> <SA> <AI/O> <DI/O> <turbo> <pl1> <pl2> <remain> <UpdateMins (0 only apply at bootup)>
```
- Now the T470 never heats up and the fan is on 0rpm most of the time even when 3-4 applications are running simultaneously and the temprature wouldnt exceed 46°C on normal browsing + Music + Mail + Messages tasks. The Fan would automatically start when the temperature rises above 55°C and drops down to normal again after closing the high CPU usage task which is completely normal

## Donate
<a href="https://paypal.me/momsz"><img src="blue.svg" height="40"></a>  
If you enjoyed this project — or just feeling generous, consider buying me a beer. Cheers! :beers:


## My sincere thanks to**

- [Acidanthera](https://github.com/acidanthera)
- [Dortania OC guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Rehabman's battery patch guide](https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/) and [Rehabman's ACPI hotpatching guide](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/)
- [CorpNewt's tools](https://github.com/corpnewt)
- [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI)
- [YogaSMC](https://github.com/zhen-zen/YogaSMC)
- [Daliansky's OC-little repo](https://github.com/daliansky/OC-little)
- and the entire community for inspiring me!

