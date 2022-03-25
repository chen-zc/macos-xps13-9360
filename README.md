# Dell XPS 9360 Hackintosh
# 戴尔XPS9360 黑苹果安装


Device : Dell XPS 13 9360

CPU : Intel i7-8550U

GPU : Intel UHD 620

RAM : 8 GB

Sound : Realtek ALC256 (ALC3246)

SSD : Sumsung PM961 256 gb

Display : FHD (1920x1080), non touch

Wireless Card : Swapped the original Killer 1535 with DW1830 (原网卡更换DW1830，三天线只用了两根)

## Existing problems 存在问题
 
- Bluetooth problem 蓝牙不工作: fixed in EFI V2.0，在EFI2.0中得到修复
- Earphone does not work 耳机孔不工作 : see below 见下面解决
- USB-C not recognize iPhone, but can be used as HDMI output and charging
- SD card reader: turned off in BIOS, I am not going to fix this temporarily since I don't use it


## 2022-03-25 Update

EFI-3.0

Update kext versions

 
## 2022-03-18 Update

EFI-2.0 successful

Fixed bluetooth problem by adding kexts 

Earphone problem: use ComboJack-master (https://github.com/hackintosh-stuff/ComboJack)

----------

BIOS : 2.9.0

OpenCore version : 0.7.8

MacOS version: Big Sur 11.2.3


## 2022-03-17 Update

 
EFI-1.0 successful

BIOS : 2.9.0

OpenCore version : 0.7.8

MacOS version: Big Sur 11.2.3
 
 


## Acknowledgement 致谢

 
OpenCore: 

https://dortania.github.io/OpenCore-Install-Guide/

Chinese Version OpenCore Tutorial 
中文版搭建教程by国光，视频教程:

https://apple.sqlsec.com

https://www.bilibili.com/video/BV1yq4y1o7cT

GitHub Contributors 参考EFI:

https://github.com/hoanX/xps13-9360-Hackintosh

https://github.com/theQuert/XPS-9360-macOS

