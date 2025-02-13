# OpenCore EFI - Dell Precision Tower 5810
- OpenCore (v1.0.3)
- macOS Seqoiua (15)
  
*If you notice that something is working or not working write on Issues*

[Get latest release](https://github.com/Klubuntu/EFI-Dell-T5810/releases/latest)

## ⚠️ Important
- Required minimum BIOS version is **A12**
- If you need access to Apple Account (generate required values)
- Generate using OCAT, Open config.plist and go to ``(PI>Generic>SystemProductName)`` and click **Generate**

## ✅ What's works ?
- Audio
- Network (Ethernet)
- External NVME Adapter
- Restart/Power off device
- VM Support (You can create Virtual Machines)
- GPU Acceleration (with Opencore Legacy Patcher)
- Custom USB Maps Port
- Reset TSC Before start
- DualBoot with Windows (with created FAT32/NTFS partition from Disk Utility macOS)

## ❌ What's not working ?
- Sleep/Wake up
- External Bluetooth Adapter

## Sources:
- Original EFI: https://github.com/BillDH2k/Hackintosh-DELL-T5810-OpenCore
- OpenCore v1.03: https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.3
- OCAT (OpenCore Auxilary Tools): https://github.com/ic005k/OCAuxiliaryTools/releases
- OpenCore Legacy Patcher: https://github.com/dortania/OpenCore-Legacy-Patcher/releases/latest

