# Lenovo ThinkCentre M6600q-N000 · OpenCore Hackintosh

Intel Core i3-6100 | HD 530 → HD 620 | 16 GB DDR4 | B150

![CPU](https://img.shields.io/badge/CPU-Intel_Core_i3_6100-0071C5)
![GPU](https://img.shields.io/badge/GPU-HD_530_→_HD_620-0071C5)
![RAM](https://img.shields.io/badge/RAM-16_GB_DDR4_3200_MHz-8B5CF6)
![macOS](https://img.shields.io/badge/macOS-Ventura_~_Sonoma-0071BC)
![Status](https://img.shields.io/badge/Status-Working-success)

---

## Hardware

| Component | Specification |
|:----------|:--------------|
| Model | Lenovo ThinkCentre M6600q-N000 |
| CPU | Intel Core i3-6100 @ 3.70 GHz (Dual-core) |
| Motherboard | Lenovo 30D2 (B150 Chipset) |
| GPU | Intel HD Graphics 530 (128 MB) → Fake HD 620 |
| RAM | 16 GB (Hynix DDR4 3200 MHz 8 GB × 2) |
| Storage | Samsung MZNLN256HCHP-000L2 (256 GB SSD) |
| Ethernet | Intel I219-V |
| Audio | Realtek @ Intel HD Audio |

## macOS Compatibility

- **Supported**: Ventura & Sonoma (full range)
- **Fake GPU**: HD 620
- **ig-platform-id**: `00001B19` (DATA)
- **Device ID**: `1B190000` (DATA)

> For systems below Ventura, modify graphics parameters as shown above.

## Driver Status

| Feature | Status | Feature | Status |
|:--------|:------:|:--------|:------:|
| GPU (Fake HD 620) | ✅ Working | Ethernet | ✅ Working |
| Audio | ✅ Working | USB | ✅ Working |
| Sleep | ✅ Working | | |

## Installation

1. Configure BIOS: SATA → AHCI, Secure Boot → Disabled
2. Copy EFI to USB EFI partition
3. Boot from USB → OpenCore → Install macOS


---

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE)

> ⚠️ 本教程仅供学习和研究使用


