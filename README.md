## XPS13 9300

English/[中文](README-CN.md)

### Tested software configuration

**OpenCore Version**: [0.6.2](https://github.com/acidanthera/OpenCorePkg/releases)

**BIOS Version** : 1.2.0

**macOS Version**: macOS Catalina 10.15.7 (Big Sur version will update soon) 

### Tested hardware configuration

| Key                    | Value                                                        |
| ---------------------- | ------------------------------------------------------------ |
| SKU                    | [XPS13-9300](https://www.dell.com/en-us/shop/cty/pdp/spd/xps-13-9300-laptop) |
| CPU                    | Intel Core i7-1065G7                                           |
| GPU                    | Intel Iris Plus Graphics G7                                       |
| Builtin Screen         | 13.4"  Sharp 1920x1200 Non-Touch                                      |
| RAM                    | On Board 16G 3733MHz DDR4x                                |
| SSD                    | Hykvision 2TB                    |
| Audio                  | Realtek ALC289                                               |
| Wireless               | Killer ax1650                              |
| SD card reader         | Realtek rts525a                      |

### Working

* iGPU : working.
* Wireless : WiFi, handoff working.
* Bluetooth : working.
* Audio : speaker, headphone, mic working(AppleALC).
* Camera : working.
* KeyBoard : keyboard (PS2, support Fn key controll : mute F1, volume down/up F2/F3, video play/stop F4, keyboard brightness F5, 
                       brightness down/up F6/F7, disable touchpad F10) working.
* Touchpad : Touchpad (I2C GPIO interrupt, support Multi-touch gesture) working.
* USB : USB3.1 Type-C port (10 Gbps) working
* ThunderBolt 3 : ThunderBolt 3 (40 Gbps) testing on external GPU(Razer CoreX with AMD Radeon RX 5700XT) working.
* Brightness Controll : wokring.
* Sleep/Wake: partialy working(can sleep once, second sleep will cause kernel panic).
* SD card reader : working.

### Known Problem
* Second sleep will cause kernel panic
* can‘t disable cfg lock (will be appreciate if someone can help)
* poor headphone sound quality
* thunderbolt hotplug not working
* display may be very dark if wake immediately 

![hackintosh](./screenshot/hackintosh.png)

![usb2](./screenshot/usb2.png)

![audio2](./screenshot/audio2.png)
