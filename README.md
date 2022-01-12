# MateBook 2018 OC EFI
__OpenCore EFI for Huawei Matebook D 2018 (MRC-W00A)__

- OpenCore ```REL 0.7.7 (Stable)```
- Optimized for MacOS ```12.1 Monterey```


__To-do list__

- [x] iGPU Graphics and HDMI (with acceleration)
- [x] Audio (alcid=21)
- [x] Trackpad and keyboard
- [x] iServices
- [x] USB Ports (Mapped with [USBToolBox](https://github.com/USBToolBox))
- [x] Wi-Fi and Bluetooth (Using BCM94360NG)
- [x] Apple Continuity (Thanks to BCM94360NG card and [Feature Unlock Kext](https://github.com/acidanthera/FeatureUnlock))
- [x] Cosmetic fixes (OpenCanopy and HD OC picker working)
- [x] Brightness and media keys working[^1]
- [ ] Lid wake (First try: screen is extremely dim. Second try: wakes as it should)[^2]

[^1]: List of NOT working keys: Mic mute, WiFI toggle, GMail key
[^2]: Already tried the backlight fixes in the [Dortania Guide](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html#what-this-ssdt-does)

__Laptop specs__

- CPU: i3 8130u (KabyLake-R)
- iGPU: UHD 620
- RAM: 8GB DDR4
- 256GB SSD NVMe
- Wi-Fi & Bluetooth: BCM94360NG 



