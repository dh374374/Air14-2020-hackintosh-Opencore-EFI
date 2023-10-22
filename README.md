# **小新Air14 2020锐龙版 黑苹果EFI**

## 可用系统

### macOS 14 Sonoma

## **配件情况**

| 配件 | 型号 |
| --- | --- |
| cpu | AMD Ryzen 5 4600U |
| 内存 | 8G x 2 |
| 显卡 | AMD Radeon(TM) Graphics ( 2GB / 联想 ) |
| 硬盘 | 西数 WDC PC SN730 SDBPNTY-512G-1101 ( 512GB) |
| 网卡 | 英特尔 Intel Wi-Fi 6E AX210 160MHz 【自己换的】 |

## **安装前准备**

1. bios关闭安全启动 disable secure boot
2. 安装之前把下载的efi文件里的EFI\OC文件夹下的配置文件config.plist的“NootedRed.kext”禁用，安装好了之后再开启
3. 可以使用 [UMAF](https://github.com/DavidS95/Smokeless_UMAF) 增加显存（可选，不加也可用）
4. 不同型号的电脑可能需要自己定制UTBMap.kext，参考链接如下：[usb定制](https://apple.sqlsec.com/6-%E5%AE%9E%E7%94%A8%E5%A7%BF%E5%8A%BF/6-1.html)

## **存在的问题**

1. 安装完成后，chrome浏览器需要关闭硬件加速，不然会卡的怀疑人生，需要等[NootedRed](https://github.com/ChefKissInc/NootedRed)作者解决
2. 风扇转速没法控制
3. 原本的螃蟹网卡无法驱动，请自行更换适合的网卡，比如AX200、AX210等

## 截图

![image](https://raw.githubusercontent.com/dh374374/Air14-2020-hackintosh-Opencore-EFI/main/img/WX20231022-153038.png)
![image](https://raw.githubusercontent.com/dh374374/Air14-2020-hackintosh-Opencore-EFI/main/img/WX20231022-153136.png)

---

## 致谢，参考了

https://github.com/longluuly/Ryzentosh-Acer-aspire-7-A715-42G-R6ZR-Opencore-EFI

https://github.com/PIut02/ROG-Zephyrus-G14-GA401-Hackintosh/blob/main/README_cn.md
