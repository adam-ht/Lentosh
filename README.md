# Lentosh
Lenovo Ideapad s340 Ryzentosh with opencore.
| Component | Model |
|-----------|-------|
| CPU | AMD Ryzen 5 3500U |
| GPU | AMD Radeon Vega 8 2GB allocated |
| RAM | 20GB(4GB soldered + 16GB sodimm) |
| Audio chipset | ALC257 |
| WiFi | Intel 3165NGW |
| Ethernet | ASIX AX88179 USB |
# Versions
- Working versions (tested): MacOS Monterey (12), MacOS Ventura (13)
- Current OS Version: 13.5.1
- OpenCore version: 0.9.4
#
<details>
<summary>What's working:</summary>
    <li>GPU Acceleration with NootedRed</li>
    <li>Keyboard with VoodooPS2</li>
    <li>Backlight with PNLF.aml</li>
    <li>Booting it up with GenericUSBXHCI</li>
    <li>Battery readouts with SMCBatteryManager</li>
    <li>Brightness keys with BrightnessKeys</li>
    <li>WiFi with AirportItlwm</li>
</details>
<details>
<summary>What's not working:</summary>
  <li>Touchpad</li>
  <li>Card reader (I don't need it now so I will fix it later)</li>
</details>
You need to use one of three SMBIOS listed in NootedRed guide, I use Macbook Pro 16,3 SMBIOS, but feel free to experiment

## Guys this EFI may not work for all of you so take it as a help for your setup

# Credits
- [Acidanthera](https://github.com/acidanthera) for OpenCore package and many of needed kexts
- [AMD OSX](https://github.com/AMD-OSX) for CPU patches
- [Apple](https://apple.com/) for MacOS
- [Trulyspinach](https://github.com/trulyspinach?tab=repositories) for AMD SMC plugin for VirtualSMC
- [ChefKissInc](https://github.com/ChefKissInc/NootedRed) for NootedRed
- [RehabMan](https://github.com/RehabMan/OS-X-Null-Ethernet) for NullEthernet kext
- [CorpNewt](https://github.com/corpnewt) for SSDTTime, GenSMBIOS, gibmacOS, MountEFI and ProperTree
- [RattletraPM](https://github.com/RattletraPM/GUX-RyzenXHCIFix) for GenericUSBXHCI.kext which fixed booting, without it the laptop would boot once a time
- [OpenIntelWireless](https://github.com/OpenIntelWireless)https://github.com/OpenIntelWireless) for intel wifi kexts
