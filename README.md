# Lenovo Legion Y7000P IRX9 Hackintosh

当前 SYSTEM_DRV 上 OpenCore EFI 的脱敏快照，制作日期：2026-11-05。

## 使用前

请在 `EFI/OC/config.plist` 的 `PlatformInfo → Generic` 中填写你自行生成的 `SystemSerialNumber`、`MLB`、`SystemUUID` 和 `ROM`。当前值均为占位，不能直接用于日常启动或 Apple 服务。`SystemProductName` 保留原配置。

`itlwm.kext` 中保存的 Wi-Fi 名称和密码已清空。旧配置、驱动回退备份、文件系统元数据以及 Microsoft Windows 引导目录未包含在本仓库。

该目录保留当前配置及驱动，未对其他电脑验证兼容性；请先备份自己的 EFI。原启动分区未修改。
