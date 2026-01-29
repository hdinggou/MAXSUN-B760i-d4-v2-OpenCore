# 铭瑄-终结者 B760ITX D4 V2 WIFI 黑苹果 OpenCore EFI


## macOS

- macOS Tahoe   26.2
- （其他版本未尝试）

## 硬件

- 芯片组: B760
- Bios 版本: 1.4D（2025/05/16）
- 处理器: 英特尔13代 i5-13490f
- 内    存: 玖合 32G*2 DDR4 3200MHz
- 硬    盘: 金士通 m.2 NVME 1TB
- 独    显: 蓝宝石 AMD Radeon RX6600 白金版
- 声    卡: 瑞昱 ALC897
- 有线网卡: 瑞昱 8125 2.5GbE
- 无线网卡: 英特尔 AX211 （系统安装完成后，请打[OCLP-Mod]([https://github.com/ic005k/OCAuxiliaryTools](https://github.com/laobamac/OCLP-Mod)) 补丁使用）
- 机    箱:  Rider R2
- 电    源: 利民SGFX 650-W

## 工作情况

- 睡眠、唤醒正常
- 有线网卡正常
- Wi-Fi、蓝牙功能正常（但不好用）
- 隔空投送（单方面）
- 接力不可用

## BIOS设置

```

|-- VT-d：开启
|-- Above 4G decoding：开启
|-- Resizable Bar：关闭
|-- EHCI/XHCI Hand-off：开启
|-- CSM Support：关闭
|-- Fast Boot：关闭
|-- Secure Boot：关闭
|-- CFG LOCK：关闭

```

## 注意事项

 - 安装成功后必须使用 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS


