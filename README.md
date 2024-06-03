# 电脑配置

- **型号:** 联想 ThinkCentre M6600q-N000 台式电脑
- **操作系统:** Windows 10 64位（版本 22H2 / DirectX 12）
- **处理器:** 英特尔 Core i3-6100 @ 3.70GHz 双核
- **主板:** 联想 30D2（100 系列/C230 系列芯片组系列 (B150) - A148）
- **显卡:** 英特尔 HD Graphics 530 ( 128 MB / 联想 )
- **内存:** 16 GB ( 海力士 DDR4 3200MHz 8GB x 2 )
- **主硬盘:** 三星 MZNLN256HCHP-000L2 (256 GB / 固态硬盘)
- **声卡:** 瑞昱@英特尔High Definition Audio控制器
- **网卡:** 英特尔以太网连接 I219-V / 联想

## macOS Sonoma 14.5 仿冒配置

- **核显:** HD620（仿冒）
- **支持系统:** Ventura- Sonoma 全系系统

如果需要装 Ventura 以下版本的系统，系统需要修改一下核显参数。参考下面参数修改：

- `AAPL,ig-platform-id`: 00001B19 (DATA类型)
- 设备 ID: 1B190000 (DATA类型)
