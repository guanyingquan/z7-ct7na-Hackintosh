# z7-ct7na-Hackintosh-OC

# 当前版本

- OpenCore v0.8.7-release
- MacOs Monterey 12.6

# 摘要

- 平台：神舟z7-ct7na

|        项目         |               型号                | 支持MacOs版本 |
| :-----------------: | :-------------------------------: | :-----------: |
|         CPU         |          Inter i7-9750H           |   10.12.6~    |
|     Motherboard     | Clevo NH5x_7xRCx,RDx(Inter HM370) |   10.12.6~    |
|        iGPU         |           Inter UDH 630           |   10.12.6~    |
|         GPU         |         Nvidia GTX 1660Ti         |      N/A      |
|  Wired Networking   |       Realtek RTL8168/8111        |       ~       |
| Wireless Networking |     Intel(R) Wireless-AC 9462     |      N/A      |
|       Storage       |      WDC PC SA530 SDASN8Y512      |       ~       |
|     Audio Codec     |          Realtek ALC293           |       ~       |

舍弃Clover，并重新基于Opencore创建，更新系统版本，当前已支持macOs Monterey 12.6(已测)。

- 编译SSDTs,已修复电源支持；

- Usb 已定制，已修复摄像头；

- 无线网卡已驱动，支持无线网、蓝牙连接

  > ❗​暂不支持隔空投送；

- 修复miniDP，支持外接显示器

  > ❗若要使用miniDP（核显驱动）外接显示器，请勿加载`SSDT-dGPU-Off`，默认关闭；如无外接显示器需求，建议加载`SSDT-dGPU-Off`。

- 加载usb总线睡眠唤醒功能，支持键盘鼠标等usb设备睡眠唤醒

  > ❗盒盖长时间会出现无法唤醒情况，不建议盒盖睡眠。

# :bookmark: Note

 假定已大致了解黑苹果及Opencore的相关知识

- 直接下载Release压缩包

- 使用前请务必修改三码！！！！使用前请务必修改三码！！！！使用前请务必修改三码！！！！