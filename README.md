# Windows 10 compatible driver for Pinnacle Dual Hybrid Pro PCIe 3010ix
## Notice
These steps are required in order to get this card working with Windows Media center from mydigitallife forums. 
If you want to use the official app [it should be possible](https://github.com/Destroyer/pinnacle-pctv-dual-hybrid-pro-pcie-3010ix/issues/1) with this version [ftp://ftp.pctvsystems.com/TV/application/TVC6/PCTVSystems_TVCenter_Setup_6.4.9.1033.exe](ftp://ftp.pctvsystems.com/TV/application/TVC6/PCTVSystems_TVCenter_Setup_6.4.9.1033.exe) .

## Installation
1. Remove the current driver via the Device manager.
2. Download the repo and extract it
3. Right click on BGTCap.inf and click Install
4. Reboot PC

Although you won't see Pinnacle driver anymore there'll be BGT 3540 driver instead. Because this driver is compatible with the card and works well on Windows 10 it can be used with this card. It may also work with Windows (8 / 8.1) but I didn't test it. Also the fact that it works for me doesn't mean it will work for you, so use it at your own risk.

Tested on Windows 10 Insider build 14332. 

Source: http://home.btconnect.com/blackgold/Downloads/BGT3540_6.0.0.49_64bit.zip
