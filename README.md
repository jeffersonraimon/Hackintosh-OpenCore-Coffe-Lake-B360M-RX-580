# Hackintosh OpenCore | Intel Core i5-8400 | Aorus B360M Gaming 3 | AMD RX-580 8GB


Hackintosh made in 2021 with OpenCore running macOS Big Sur and Windows 11 by @jeffersonraimon 

![image](https://user-images.githubusercontent.com/80064475/126728730-f0148d1e-a083-424d-9b63-9cbfe2fe0755.png)


## Specs

My Hardware Configuration

```
Motherboard: Gigabyte B360 Aorus Gaming 3 (rev 1.0)
BIOS Version: F15b

Processor: Intel Core i5-8400 (6 core, 6 Threat) 2.80Ghz - 4Ghz

Ram: HyperX 16GB DDR4 

SSD M.2 NVMe: Asgard AN2 250NVMe-M.2/80 250GB (macOS Big Sur)
SSD 2: Kingston 240Gb (Windows 11)
HDD: 320Gb APFS Backup

Graphics: AMD Shapphire RX 580 8GB

Audio codec: Realtek® ALC892 (Layout-id : 1)

Ethernet: Intel I219V7 PCI Express Gigabit- Ethernet

WiFi Card: Fenvi FV-A436CD Chipset: Broadcom BCM94360CD

```
## EFI Folder
 *after download my EFI, plz change SMBIOS*

![image](https://user-images.githubusercontent.com/80064475/126728749-a47bf060-b469-4f40-bfea-54fd8f55c5d5.png)


## Dual Boot - OS selection personalized by me
*I set HideAuxiliary to True to a clean screen* 

![image](https://user-images.githubusercontent.com/80064475/126728764-27513396-384f-463a-ac81-b37aca5d85d8.png)

## USB Mapping by me
*I used Hackintool*

![image](https://user-images.githubusercontent.com/80064475/126728786-cc054f9c-565a-4130-9e40-8f1bca8447bd.png)

## BIOS Settings

### Disable

```
* Fast Boot
* Secure Boot
* Serial/COM Port
* Intel Platform Trust
* CSM
* Intel SGX
* Intel Platform Trust
* CFG Lock

```
### Enable

```
* VT-d
* Above 4G decoding
* Internal Graphics - Option: Enabled
* XHCI Hand-off
* OS type: Windows 8.1/10 UEFI Mode
* SATA Mode: AHCI

```
## IMPORTANT!!! - Change the SMBIOS

After download my EFI, plz change SMBIOS [How to do here](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo)

## Guide that I used

[Open Core Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Credits

To all stuff of OpenCore and the channel YouTube [Dicas do Mateus](https://www.youtube.com/channel/UCPCUdJ9cRior4FZ1TEz6qdA)
