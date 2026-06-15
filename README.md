# 🖥️ Lenovo ThinkCentre M6600q-N000 · OpenCore Hackintosh

<p align="center">
  <img src="https://img.shields.io/badge/CPU-Intel_Core_i3_6100-0071C5?logo=intel&logoColor=white" alt="CPU" />
  <img src="https://img.shields.io/badge/GPU-Intel_HD_530-0071C5" alt="GPU" />
  <img src="https://img.shields.io/badge/RAM-16GB_DDR4_3200MHz-8B5CF6" alt="RAM" />
  <img src="https://img.shields.io/badge/Chipset-B150-00A3E0" alt="Chipset" />
  <img src="https://img.shields.io/badge/Status-Working-success" alt="Status" />
</p>

<div align="center">
  <i>Lenovo ThinkCentre M6600q-N000 小主机黑苹果 OpenCore 配置方案。<br>支持 macOS Ventura ~ Sonoma 全系系统。</i>
</div>

---

## 💻 硬件规格

| 项目 | 规格 |
|------|------|
| **型号** | Lenovo ThinkCentre M6600q-N000 |
| **CPU** | Intel Core i3-6100 @ 3.70GHz（双核）|
| **主板** | Lenovo 30D2 (B150 芯片组) |
| **显卡** | Intel HD Graphics 530 (128 MB) — 仿冒 HD620 |
| **内存** | 16 GB（Hynix DDR4 3200MHz 8GB × 2）|
| **硬盘** | Samsung MZNLN256HCHP-000L2 (256 GB SSD) |
| **网卡** | Intel Ethernet I219-V |
| **声卡** | Realtek @ Intel HD Audio |

---

## 🍏 macOS 信息

| 项目 | 说明 |
|------|:----:|
| **支持版本** | macOS Ventura ~ Sonoma 全系 |
| **核显仿冒** | HD620 |
| **ig-platform-id** | `00001B19` |
| **Device ID** | `1B190000` |

> ⚠️ 如需安装 Ventura 以下版本，需修改显卡参数：
> - `AAPL,ig-platform-id`：`00001B19`（DATA 类型）
> - `Device ID`：`1B190000`（DATA 类型）

---

## ✅ 驱动情况

| 功能 | 状态 |
|:----:|:----:|
| 核显 | ✅ HD620 仿冒 |
| 网卡 | ✅ |
| 声卡 | ✅ |
| USB | ✅ |
| 睡眠 | ✅ |

---

<div align="center">
  <img src="https://img.shields.io/badge/Built_with_❤️_for_the_Hackintosh_Community-FF6B6B" alt="Built with love">
</div>
