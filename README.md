
![OpenCore_with_text_Small](https://user-images.githubusercontent.com/50609693/162792803-ba54a898-54d7-4b8f-9fc5-c46061deb27d.png)



# MateBook D 2018 OC EFI
__OpenCore EFI for Huawei Matebook D 2018 (MRC-W00A)__

- OpenCore ```REL 0.8.4 (Stable)```
- Optimized for MacOS ```12.6 Monterey```


## __To-do list__

- [x] iGPU Graphics and HDMI (with acceleration)
- [x] Audio (alcid=21)
- [x] Trackpad and keyboard
- [x] iServices
- [x] USB Ports (Mapped with [USBToolBox](https://github.com/USBToolBox))
- [x] Wi-Fi and Bluetooth (Using [BCM94360NG](https://www.ebay.es/itm/174224694910))
- [x] Apple Continuity (Thanks to [BCM94360NG card](https://www.ebay.es/itm/174224694910) and [Feature Unlock Kext](https://github.com/acidanthera/FeatureUnlock))
- [x] Cosmetic fixes (OpenCanopy and HD OC picker working)
- [x] Brightness and media keys working[^1]
- [ ] Lid wake (First try: screen is extremely dim. Second try: wakes as it should)[^2]

[^1]: List of NOT working keys: Mic mute, WiFI toggle, GMail key
[^2]: Already tried the backlight fixes in the [Dortania Guide](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html#what-this-ssdt-does)

## __Laptop specs__

- CPU: i3 8130u (KabyLake-R)
- iGPU: UHD 620
- RAM: 16GB DDR4 (2400mhz)
- 256GB SSD M.2 SATA
- Wi-Fi & Bluetooth: BCM94360NG 



