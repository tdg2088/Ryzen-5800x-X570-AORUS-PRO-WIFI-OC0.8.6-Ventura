## Ryzen-5800x-X570-AORUS-PRO-WIFI-OC0.8.6-Ventura
## 前言
什么时候AQC107可以驱动了，什么时候再更新。

## 软硬件配置
- OpenCore: 0.8.6
- CPU: AMD Ryzen 7 5800X
- GPU: RX 560 4G
- Motherboard: 技嘉X570 AORUS PRO WIFI
- RAM: 十铨 DDR4 3200MHz 16GB * 2
- OS: MacOS Ventura 13.0
- HardDrive:三星  SSD 970 EVO Plus 250GB （MacOS），三星  MZVPW256HEGL-00000 256G(windows11)
- Wifi/Bluetooth: 主板自带
## 功能
- 4K解码 正常
- 蓝牙 正常
- WIFI 正常
- 有线网卡 使用USB口的Realtek网卡正常
- imessage/apple store/hand off 正常
- USB 正常
- 睡眠唤醒 正常
- HiDPI/165HZ：使用一键脚本无效，最后用了Hackintool定制解决
- 音量/显示器亮度调节：使用第三方软件MonitorControl
## 缺陷
- 板载网卡无法驱动，AQC107万兆网卡无法驱动
## 注意事项:
- BIOS: "Above 4G XXX" 关闭 (这里重点，和其他主板不一样，我这里需要关闭，自己在启动参数加0x200才可以)
- BIOS: CMS 关闭
- BIOS: fast boot 关闭
- BIOS: Secure boot 关闭
- OC: 填写你的机器型号 "Platform Info"
