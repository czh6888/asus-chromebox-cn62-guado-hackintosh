# Asus-chromebox-cn62-guado-hackintosh
opencore efi partition（osx catalina 10.15.7 with opencore 0.6.1 ）

## update2020.11.01
 - Fix 3.5mm audio jack, supports a headphone with mic now.
 - New Folder “EFI-fakesmc” replace the Virtualsmc with Fakesmc to get Fan-control（via ssd fan control https://exirion.net/ssdfanctrl/ ）
 - Opencore's Installation guide says it is not recommand to use fakesmc with opencore, and fakesmc is out of date. so if you want Virtualsmc back, pls use folder “EFI”, but you will lose fanctrl.

### System configuration
 - BIOS：mrchromebox COREBOOT 4.12 
 - CPU: Intel Core i7-5500U
 - Graphic: Intel HD5500
 - WiFi&BT: Intel AC7260
 - Audio: Realtek ALC283
 - Ethernet: Realtek RTL8111

### What's working
 - IGPU
 - Audio
 - Ethernet(set EN0-interface-preferences-hardware to manual , or it will not wired)
 - SD card reader
 - Original WIFI module(use heliport to connect wifi)
 - BLUETOOTH
 - Native Power Management （patched）
 - HDMI + Audio
 - Fan control （via ssd fan control https://exirion.net/ssdfanctrl/ ）

### Credits & Sources (in no particular order and maybe missing some)
 - Apple INC.
 - https://github.com/MrChromebox
 - https://github.com/acidanthera
 - https://github.com/RehabMan
 - https://github.com/corpnewt
 - https://www.insanelymac.com/
 - https://www.tonymacx86.com/
 - https://reddit.com/r/hackintosh
 - https://reddit.com/r/chrultrabook
 - https://dortania.github.io/vanilla-laptop-guide/
 - https://blog.daliansky.net/
 - https://blog.xjn819.com/
 - https://github.com/OpenIntelWireless
 - https://github.com/Mieze/RTL8111_driver_for_OS_X
 
——————————————————————————————————————————————————
# 华硕-chromebox-cn62-guado-黑苹果
OPENCORE efi分区所有文件（osx catalina 10.15.7 with opencore 0.6.1）

## 更新2020.11.01
 - 修复3.5mm音频接口，现支持耳麦。
 - 新文件夹 “EFI-fakesmc” 使用fakesmc替换Virtualsmc以获得完整的风扇控制和传感器读数（通过使用 ssd fan control https://exirion.net/ssdfanctrl/ ）。
 - Opencore的安装手册中不建议将fakesmc与opencore一起使用, 并且fakesmc已经停止开发,所以如果您想使用持续更新的Virtualsmc，请使用“EFI”文件夹,但是您将失去风扇控制。

### 系统配置
 - BIOS：mrchromebox COREBOOT 4.12 
 - 中央处理器: Intel Core i7-5500U
 - 显卡: Intel HD5500
 - 无线网卡及蓝牙: Intel AC7260
 - 声卡: Realtek ALC283
 - 网卡: Realtek RTL8111

### 正常工作
 - 显卡
 - 声卡
 - 网卡(需要到网络偏好设置中将EN0的硬件选项调至手动，否则显示网线未插好)
 - 读卡器
 - 原生无线网卡（使用heliport连接Wi-Fi）
 - 蓝牙
 - 原生电源管理（已打补丁） 
 - HDMI及声音
 - 风扇控制（通过使用 ssd fan control https://exirion.net/ssdfanctrl/ ）

### 感谢及出处 (没有特定顺序，并且可能遗漏)
 - 美国苹果电脑公司
 - https://github.com/MrChromebox
 - https://github.com/acidanthera
 - https://github.com/RehabMan
 - https://github.com/corpnewt
 - https://www.insanelymac.com/
 - https://www.tonymacx86.com/
 - https://reddit.com/r/hackintosh
 - https://reddit.com/r/chrultrabook
 - https://dortania.github.io/vanilla-laptop-guide/
 - https://blog.daliansky.net/
 - https://blog.xjn819.com/
 - https://github.com/OpenIntelWireless
 - https://github.com/Mieze/RTL8111_driver_for_OS_X
