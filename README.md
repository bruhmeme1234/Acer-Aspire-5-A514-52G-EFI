# Acer-Aspire-5-A514-52G-EFI
Hi. This is u/IanParas from Reddit. And I want to share to my fellow Hackintosher my EFI. Note that this will only work on the Aspire 5 A514-52G model. If you don't have the same model but have same specs you can try it. If you want to build your own EFI, just visit Dortania's OpenCore Guide for the instructions

Thanks for u/Nobbylobo for helping me create this EFI

macOS Monterey and macOS Ventura Ready EFI

`OpenCore Version: 0.8.6`

*Acer Aspire 5 A514-52G 31YS Specification*

- CPU: Intel Core i3-10110U @ 2.10GHz
- CPU Codename: Comet Lake
- GPU: Intel UHD Graphics | nVIDIA GeForce MX250 (Disabled)
- Trackpad: Synaptics I2C Trackpad with Windows Precision 
- Wireless: Fenvi BCM94360NG
- Ethernet Card: Realtek PCIe GbE Family Controller
- Audio: Realtek (R) Audio
- Apple Codec: ALC256 (alcid=21)
- RAM: 20GB DDR4 2400MHz
- Storage:  SSD: KINGSTON SNV2S1000G | HDD: WDC WD10SPZX-21Z10T0


Things that doesn't work inside the OS: 

Lossless, Hi-Res Lossless, Dolby Atmos Audio Quality on Apple Music, Apple TV, AirDrop, AirPlay, Sidecar etx


Things that doesn't work outside the OS (EFI):

N/A

Note:
- If the Trackpad is not working maybe try changing the Kext.
- If the Hackintosh failed and you wiped the WIndows partition, it's not my fault. So don't blame me if something terrible happened.
- Some of the kext might be outdated so if you encounter some driver problem, try updating the kext.
- If you expirence some problem on your headphone jack, please download ComboJack: https://github.com/hackintosh-stuff/ComboJack
- On the past EFI, there's a kext for Intel Wireless and Bluetooth. On the last update I removed every Intel Wireless and Bluetooth kext because I don't need anymore. You can always add it again. If you have Intel Network Card

Note from the creator:
This is my last upload of the EFI. It's up to you now if you want to update the EFI. I'll now archive this repo since there'll be no updates anymore.
