# OpenCore 0.5+ 部件补丁

## 说明

依据 OpenCore 0.5+ 的要求和建议，制作本部件补丁。 **黑体** 部分为新增内容或有重要改动。

## 主要内容

- **总述** 
- ACPI 二进制更名
- 预置变量法
- **仿冒设备** 
- **操作系统补丁** 
- 注入 X86
- 仿冒 `EC` 
- OC-`PNLF` 注入方法
- `SBUS(SMBU)` 补丁
- PS2 键盘映射 @OC-xlivans
- 键盘无法输入的应急解决方案 `PS2N` 
- **添加丢失的部件** 
- OC `I2C-TPXX` 补丁方法
- OC `GPIO` 补丁
- OC -Thinkpad电池补丁
- **OC其他电池补丁** 
- 禁用 EHCx
- **`PTSWAK` 综合补丁和扩展补丁** 
- **`PNP0C0E` 睡眠修正方法** 
- `0D6D` 补丁
- **仿冒以太网和重置以太网BSD Name** 
- 亮度快捷键补丁
- CMOS重置补丁
- Dell机器补丁方法
- ACPIDebug
- 为了方便使用，整理了部分驱动列表，仅供参考：

  - config-Lilu-SMC-WEG-ALC 驱动列表
  - config-PS2 键盘驱动列表
  - config-I2C 禁止原生驱动列表
  - config-I2C 驱动列表
  - config-BCM 无线和蓝牙驱动列表

### Credits

- 特别感谢：
  - @宪武 制作的适用于 **[OpenCore](https://github.com/acidanthera/OpenCorePkg)** 的 ACPI 部件补丁
  - @Bat.bat, @黑果小兵 审核完善

- 感谢：@冬瓜-X1C5th, @OC-xlivans, @Air 13 IWL-GZ-Big Orange (OC perfect), @子骏oc IWL, @大勇-小新air13-OC-划水小白 等等

- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), ~~[AptioFixPkg](https://github.com/acidanthera/AptioFixPkg)~~(Achieved), [MacInfoPkg](https://github.com/acidanthera/MacInfoPkg), [OCSupportPkg](https://github.com/acidanthera/OCSupportPkg) and [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg).
