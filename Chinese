> 2019年底我分享了10.15.2的Clover引导的帖子，由于平时工作原因比较少维护，有看到很多小伙伴留言说链接失效了，非常抱歉。>>>[**点击前往**](http://bbs.pcbeta.com/viewthread-1837084-1-1.html)

最近我开始尝试使用OpenCore引导，目前已经折腾完毕，现在分享给大家。还是原来的配置，不过硬盘有小更新，同时增加了无线网卡。经过本人测试，**该OpenCore引导EFI适用于Catalina 10.15.7（Github上截图就是Catalina的），也适用Big Sur。**



### 硬件配置：

> - 主板：技嘉Z390 Aorus Elite
> - CPU: i7 9700K (***黑果下面CPU型号识别错误，可自行修正***)
> - 显卡： 蓝宝石RX 590
> - 内存：芝奇 8G DDR4 3200GHz *4
> - SSD1: Intel 760p >>>Windows 10 Pro
> - SSD2:WD SN750 512G >>>**Big Sur 11.1**
>
> - 电源：振华LEADEX G850 850W 金牌Plus
> - 散热器：九州风神 堡垒240 一体式水冷
> - 机箱：乔思伯 UMX4 RGB幻彩版
> - 显示器： LG UL850 4K

### BIOS设置：

> 1. Vt-d: disabled
> 2. Windows8/10 features:other os
> 3. CSM suport:disabled
> 4. XHCI hand-off:Enabled
> 5. About 4G Decoding:Enabled
> 6. Network stack configuration->Network stack：Disabled
> 7. Internal Graphics:Enabled
> 8. Secure Boot:Disabled

### 所有硬件正常工作：![image-20210113201134029](https://i.loli.net/2021/01/13/71mJSWnAcDGe84U.png)

1. 显卡工作正常![image-20210113201410060](https://i.loli.net/2021/01/13/oEZw7XQDWHtaqsg.png)

2. 声卡工作正常![image-20210113201458113](https://i.loli.net/2021/01/13/hZvNEtbJqm5OuCM.png)![image-20210113201439473](https://i.loli.net/2021/01/13/l5IrBxh4OFyZ2nU.png)

3. 蓝牙、WIFI、随航以及隔空传送正常

4. NVRAM工作正常

5. 显卡硬解正常![image-20210113201342075](https://i.loli.net/2021/01/13/zhFsS9RWf31P2bC.png)

6.  Geekbench 5 （Version 5.3.1 503690）跑个分：![image-20210113201531446](https://i.loli.net/2021/01/13/2KdhqWTZ4YuRAkr.png)![image-20210113201541485](https://i.loli.net/2021/01/13/9WIEYBbrHmcaegX.png)

   ![image-20210113201514983](https://i.loli.net/2021/01/13/ElWVeCIMDbznpSF.png)![image-20210113201755949](https://i.loli.net/2021/01/13/k9Hx5hzFG2aov1u.png)![image-20210113201843280](https://i.loli.net/2021/01/13/UYWu257xfwbMRGs.png)

   

### 致谢：

1. [**OpenCore Vanilla Guide**](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
2. [**Opencore Official**](https://github.com/acidanthera/OpenCorePkg)
3. **[Mount EFI](https://github.com/corpnewt/MountEFI)**

### EFI分享及下载

- **Github>>>****[点击前往](https://github.com/AdonisCroft/Gigabyte-Z390-Aorus-Elite-Hackintosh-OpenCore-Clover) （同时分享了Catalina 10.15.7的Clover引导和OpenCore引导的EFI，链接应该不会再次失效了。）**

- **链接文字版：**https://github.com/AdonisCroft/Gigabyte-Z390-Aorus-Elite-Hackintosh-OpenCore-Clover

