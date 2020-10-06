## XPS13-9300

中文/[English](README.md)


**OpenCore 版本**: [0.6.2](https://github.com/acidanthera/OpenCorePkg/releases)

**macOS 版本**: macOS Catalina 10.15.7

### 硬體配置

| Key                | Value                                                        |
| ------------------ | ------------------------------------------------------------ |
| SKU                | [XPS13-9300](https://www.dell.com/en-us/shop/cty/pdp/spd/xps-13-9300-laptop) |
| CPU                | Intel Core i7-1065G7                                          |
| 顯卡               | Intel Iris Plus Graphics G7                                       |
| 內建螢幕            | 13.4"  1080p 夏普 霧面 非觸控螢幕                                         |
| RAM                | 板載 16G 3733MHz DDR4x                                   |
| SSD   | 海康威視 2TB                         |
| Audio              | Realtek ALC289                                               |
| 無線網卡           | Killer ax1650                               |

### 正常工作

* iGPU : 正常
* Wireless : WiFi, 接力 正常
* 藍芽 : 正常
* 聲音 : 喇叭, 耳機, mic 正常(AppleALC).
* 相機 : 正常（紅外相機不工作）
* 輸入設備 : 鍵盤(PS2) & 觸控板正常(I2C GPIO 中斷)
* USB : USB3.1 Type-C port (10 Gbps) 正常
* 雷電3 : 雷電3 (40 Gbps) 外接顯卡 (Razer CoreX with 5700XT) 正常工作
* 亮度(快捷鍵) 控制 : 正常
* 睡眠 : 部分正常(只能一次睡眠, 第二次睡眠系統會重啟)
* SD 讀卡機 : 正常

### 已知問題
* 第二次睡眠系統會重啟
* cfg lock沒法解鎖（目前無解,希望有人能分享方法）
* 耳機音質差
* 雷電3沒辦法熱插拔
* 若快速從睡眠狀態恢復,顯示器會非常暗(應該是背光面板關閉)

![hackintosh](./screenshot/hackintosh.png)

![usb2](./screenshot/usb2.png)

![audio2](./screenshot/audio2.png)
