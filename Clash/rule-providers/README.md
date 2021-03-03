# 简介

本项目适用于 [**Clash Premium 内核**](https://github.com/Dreamacro/clash/releases/tag/premium) 的规则集（RULE-SET），同时适用于所有使用 Clash Premium 内核的 Clash GUI 客户端。

## 说明

本项目的规则集（RULE-SET）只适用于 Clash **Premium** 版本。Clash Premium 相对于普通版，增加了 **TUN 增强模式**，能接管设备所有 TCP 和 UDP 流量，类似 [Surge for Mac](https://nssurge.com) 的增强模式。更多高级特性请看[官方 wiki](https://github.com/Dreamacro/clash/wiki/premium-core-features)。

### Clash Premium 各版本下载地址

- Clash Premium **命令行**版（适用于 Windows、macOS、Linux、OpenWRT 等多种平台）：[https://github.com/Dreamacro/clash/releases/tag/premium](https://github.com/Dreamacro/clash/releases/tag/premium)
- Clash Premium **图形用户界面**版：
  - [ClashX Pro](https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public)（适用于 macOS）
  - [Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg/releases)（适用于 Windows、macOS）
  - [Clash for Android](https://github.com/Kr328/ClashForAndroid/releases)（适用于 Android）

## 规则文件地址及使用方式

### 在线地址（URL）

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址（`cdn.jsdelivr.net`），但是内容更新会有 12 小时的延迟。以下地址填写在 Clash 配置文件里的 `rule-providers` 里的 `url` 配置项中。

- **直连域名列表 direct.yaml**：
  - [https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/direct.yaml](https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/direct.yaml)
  - [https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/direct.yaml](https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/direct.yaml)
- **代理域名列表 proxy.yaml**：
  - [https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/proxy.yaml](https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/proxy.yaml)
  - [https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/proxy.yaml](https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/proxy.yaml)
- **广告域名列表 reject.yaml**：
  - [https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/reject.yaml](https://raw.githubusercontent.com/HWN4/Rules/master/Clash/rule-providers/reject.yaml)
  - [https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/reject.yaml](https://cdn.jsdelivr.net/gh/HWN4/Rules@master/Clash/rule-providers/reject.yaml)

### 使用方式

关于 Clash Premium 使用方式，请查看[官方文档](https://github.com/Dreamacro/clash/wiki/premium-core-features) 或 [Lancellc's GitBook](https://lancellc.gitbook.io/clash/)。
