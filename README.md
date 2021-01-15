# HP-Zhan66-Pro14-G2-macOS


## 电脑配置
| 规格     | 详细信息                                       |
| -------- | ---------------------------------------------- |
| 电脑型号 | HP-Zhan66-Pro14-G2                             |
| 处理器   | Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz       |
| 核心显卡 | Intel UHD Graphics 620                         |
| 内存     | Kingston 8GB DDR4 2400MHz * 2                  |
| 硬盘     | Samsung PM981 256GB NVMExpress + Lenovo 1T SSD |
| 显示器   | 内建显示器 13.9 - 英寸                         |
| 声卡     | Realtek ALC236                                 |
| WiFi     | Intel AC9560                                   |
| 网卡     | Realtek 8168                                   |

## 详情
### 系统版本：macOS  （装在  1T SSD 上），可直接下载 EFI 使用。

### 正常工作项
- 显卡

  Hackintool 工具，及以下2个驱动 [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases)，[Lilu](https://github.com/acidanthera/Lilu/releases) 。

- 声卡

  注入 ID 14

- WiFi - 安装如下驱动 [itlwm](https://github.com/OpenIntelWireless/itlwm/releases)

- USB 正常驱动（包括蓝牙、摄像头）

  替换使用旧版，新版只能驱动右侧2个USB端口。

- 亮度调节

  注入 SSDT-PNLF.aml

- 键盘快捷键（默认驱动，亮度调节需自行设置）

### 暂未工作项
- 电池电量显示
- 网卡正常驱动有显示，但连接网线有时候不工作
- 触摸板手势驱动
- 读卡器
