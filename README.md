# HP-Zhan66-Pro14-G2-macOS

This repository provides Open Core configuration files for HP Zhan66 Pro14 G2. 

[![release](https://img.shields.io/badge/下载-release-blue.svg)](https://github.com/chiccheung/HP-Zhan66-Pro14-G2-macOS/releases) 

## 电脑配置

| 规格     | 详细信息 |
| -------- | ---------------------------------------- |
| 电脑型号 | HP-Zhan66 Pro 14 G2 |
| 处理器 | Intel i5-8265U |
| 内存     | Kingston 8GB DDR4 2400MHz |
| 硬盘     | SK hynix 512GB NVMExpress |
| 集成显卡 | Intel UHD Graphics 620 Whiskey Lake （8086:3EA0） |
| 独立显卡 | Nvidia MX250 |
| 显示器   | 内建显示器 13.9 - 英寸 (1920 x 1080) |
| 声卡     | Realtek ALC236  |
| 网卡     | Wireless USB Network Card |


## 详情

<b>系统版本：macOS Catalina 10.15 ｜ Open Core 版本：0.5.2</b>

<b>正常工作项说明</b>

- 亮度调解按键 FN+F3 | FN+F4
- SystemSerialNumber & MLB 请在config.plst相关条目下自行添加
- boot-args: `-v` 请按需选择是否保留
-  RtWlanU1827.kext & RtWlanU.kext USB无线网卡驱动
   - 参阅：[Wireless-USB-Adapter-Clover](https://github.com/chris1111/Wireless-USB-Adapter-Clover) 

<b>不正常工作项说明</b>

- 独立显卡
  - 注入设备属性 `disable-external-gpu` 禁用此设备以减少电量消耗
- 读卡器
- 指纹传感器
- Intel 无线网卡&蓝牙

## 资料

-  Open Core
   - 参阅：[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)

-  ACIP hotpatch 修补
   - 参阅：[OC-little](https://github.com/daliansky/OC-little)

## 许可证声明

- Copyright (c) 2016-2017, The HermitCrabs Lab
- Copyright (c) 2016-2019, Download-Fritz
- Copyright (c) 2017-2019, savvas
- Copyright (c) 2016-2019, vit9696