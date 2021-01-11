## OpenCore 0.6.5 EFI Files for Hackintosh with Gigabyte Z390 Arous Elite MB with Catalina 10.15.7

> This EFI files suitable for Gigabyte Z390 Arous Elite with macOS Catalina 10.15.7

### Hardware list

| Name              | Model                           |
| ----------------- | ------------------------------- |
| MotherBoard       | Gigabytes Z390 AUROS ELITE      |
| CPU               | Intel i7-9700k                  |
| Graphics          | Sapphire RX 590 8G D5           |
| Memory            | G.SKILL  DDR4 3200 8G * 4       |
| SSD1              | Intel 760P 512G (macOS 10.15.7) |
| SSD2              | WD SN750 512G (Windows 10)      |
| Bluetooth + Wi-Fi | Fenvi T919                      |
| Case              | JONSBO UMX4 RGB                 |
| Power             | Super Flower LEADEX G850 850W   |



### BIOS Setting:

- Vt-d: disabled
- windows8/10 features:other os
- CSM suport:disabled
- XHCI hand-off:Enabled
- About 4G Decoding:Enabled
- Network stack configuration->Network stack：Disabled
- Internal Graphics:Enabled
- secure Boot:Disabled

### All Works!

- External graphics card (with headless iGPU enabled)![截屏2021-01-11 12.04.28.png](https://i.loli.net/2021/01/11/3JpUOLwIoCFxW1Q.png)
- Audio:![截屏2021-01-11 12.03.37.png](https://i.loli.net/2021/01/11/3tMloYCUQTOwgHu.png)
- WiFi & AirDrop:![截屏2021-01-11 12.00.51.png](https://i.loli.net/2021/01/11/oXIqc3mGleuB8Qs.png)
- NVRAM : normal, available to select boot hard drive via system preference -> startup disk![截屏2021-01-11 12.02.03.png](https://i.loli.net/2021/01/11/HlYL8wgPR45sFQk.png)

### References

- [OpenCore Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
- [Opencore Official](https://github.com/acidanthera/OpenCorePkg)
- [Mount EFI](https://github.com/corpnewt/MountEFI)

