# KiokuYomi (记忆读) - 原生 iOS 漫画阅读器

<p align="center">
  <a href="https://kiokuyomi.com/"><img src="assets/app-icon.png" alt="KiokuYomi Logo" width="108" height="108" style="border-radius: 22px;" /></a>
</p>

<p align="center">
  <strong>专为 iPhone 与 iPad 打造的高性能原生漫画与图集阅读器。</strong><br>
  <em>App Store 离线本地 CBZ/CBR/ZIP/PDF 隐私阅读 • TestFlight 公测支持 Keiyoushi & Mihon 扩展规则沙盒。</em>
</p>

<p align="center">
  <a href="https://apps.apple.com/app/kiokuyomi/id6795781367"><img src="https://img.shields.io/badge/App%20Store-Download%20Free-black?logo=apple&style=flat-square" alt="App Store" /></a>
  <a href="https://testflight.apple.com/join/Mujc89bD"><img src="https://img.shields.io/badge/TestFlight-Public%20Beta-007AFF?logo=testflight&style=flat-square" alt="TestFlight Beta" /></a>
  <a href="https://kiokuyomi.com/"><img src="https://img.shields.io/badge/Official%20Site-kiokuyomi.com-0284c7?style=flat-square" alt="Official Site" /></a>
  <a href="https://discord.gg/JVS4az867f"><img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?logo=discord&style=flat-square" alt="Discord" /></a>
  <a href="https://www.reddit.com/r/kiokuYomi"><img src="https://img.shields.io/badge/Reddit-r%2FkiokuYomi-FF4500?logo=reddit&style=flat-square" alt="Reddit" /></a>
</p>

<p align="center">
  <a href="README.md">English</a> | <a href="README.ja.md">日本語</a> | 🌐 <strong>简体中文</strong>
</p>

---

## 📖 项目概述

**KiokuYomi（记忆读）** 是一款专为 iPhone 与 iPad 打造的高性能原生漫画与图集阅读器。全量采用 Swift、SwiftUI 与 UIKit 原生开发，针对苹果 120Hz ProMotion 高刷屏幕与 iPad 横屏双页排版进行了深度定制，坚持本地优先、零数据收集、无账号体系。

如果您正在从 Android 的 **Tachiyomi** 或 **Mihon** 迁移至 iOS，并希望在 iPhone/iPad 上获得类似的开放规则沙盒与 Keiyoushi 扩展源支持，KiokuYomi 是您的理想选择。

---

### 📱 版本区别对比（App Store 正式版 vs. TestFlight 公测版）

为严格遵守苹果 App Store 审核准则，同时满足核心漫画读者的进阶需求，KiokuYomi 采用双版本分发体系：

| 功能与特性 | App Store 官方正式版 | TestFlight 公开测试版 |
| :--- | :---: | :---: |
| **核心定位** | 纯净离线本地书库与隐私安全 | 进阶规则沙盒与扩展源支持 |
| **支持格式** | CBZ, CBR, ZIP, RAR, PDF | CBZ, CBR, ZIP, RAR, PDF |
| **导入方式** | 系统「文件」、隔空投送、Wi-Fi 快传 | 系统「文件」、隔空投送、Wi-Fi 快传 |
| **扩展源沙盒** | ✕ *(合规屏蔽外部扩展)* | ✅ **支持 Mihon / Keiyoushi 仓库** |
| **在线多源检索** | ✕ | ✅ 多站点聚合浏览与更新 |
| **账号与隐私** | 零账号体系，端侧数据安全 | 零账号体系，端侧数据安全 |
| **获取途径** | [**App Store 官方下载**](https://apps.apple.com/app/kiokuyomi/id6795781367) | [**加入 TestFlight 公测**](https://testflight.apple.com/join/Mujc89bD) |

---

### 🚀 从 Android (Mihon / Tachiyomi) 迁移至 iOS 操作指南

从安卓切换到苹果设备的老玩家，可参考以下指引：

1. **通过 TestFlight 安装测试版**:
   在 iOS 设备上打开 [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD) 接受邀请并安装。
2. **添加第三方模块化仓库**:
   进入 KiokuYomi「设置」/「源管理」→ 点击「添加仓库」，粘贴兼容 Mihon 或 Keiyoushi 格式的第三方仓库地址。
3. **浏览与启用扩展源**:
   在站点列表中按需安装扩展源。所有规则解析与请求均在 iPhone/iPad 本地沙盒中独立运行，不依赖任何中心化代理服务器。
4. **导入已有本地漫画文件**:
   利用 KiokuYomi 内置的 **Wi-Fi 局域网快传** 功能，直接在电脑或安卓手机浏览器中打开 IP 地址，免数据线批量拖拽 CBZ/CBR/ZIP 压缩包进书库。

---

### 🌟 核心功能亮点

- **⚡ 原生 120Hz ProMotion 引擎**: 超低延迟渲染，页面推拉与滑动无比跟手。
- **📖 智能双页跨页拼接**: iPad 横屏智能合并双页阅读，智能识别单双页跨页大图与封面偏移。
- **📜 丰富阅读模式**: 支持连续垂直滚屏（条漫/韩漫）、从右向左翻页（日漫）、从左向右翻页（美漫/欧漫）。
- **📂 便捷文件导入**: 原生支持「文件」应用原地读取、AirDrop 隔空投送、局域网 Wi-Fi 浏览器快传。
- **☁️ 私密 iCloud 同步**: 无需注册任何第三方账号，借助 Apple 官方 iCloud 自动在多台设备间同步阅读进度与书架。
- **🎨 丰富个性化定制**: 阅读方向预设、切边留白调整、亮度与对比度滤镜调节、暗黑模式支持。

---

### ❓ 常见问题解答 (FAQ)

#### Q1: Keiyoushi / Mihon 扩展源在哪个版本可用？
**A**: 目前 Mihon / Keiyoushi 等第三方扩展源与规则沙盒仅在 **TestFlight 公共测试版** 中提供；App Store 正式版专注于本地离线书库（CBZ/CBR/ZIP/PDF）。

#### Q2: 如何把电脑里的 CBZ、CBR 或 ZIP 漫画导入到 iPhone/iPad？
**A**: 支持三种极速导入方式：
1. **Wi-Fi 网页快传**：打开 KiokuYomi「Wi-Fi 传输」，在电脑浏览器中输入屏幕上的 IP 地址，直接拖拽文件即可上传。
2. **系统「文件」App**：将文件放入 iCloud Drive 或「我的 iPhone」，在 KiokuYomi 中原地浏览打开。
3. **隔空投送（AirDrop）**：在 Mac 或其他 iOS 设备上直接分享文件至 KiokuYomi。

#### Q3: KiokuYomi 是免费的吗？是否有广告？
**A**: KiokuYomi 的核心本地阅读与 TestFlight 规则功能完全免费，全 App 零广告植入。

---

### 🔗 官方链接与社区支持

- **官方网站**: [https://kiokuyomi.com/](https://kiokuyomi.com/)
- **App Store 下载**: [https://apps.apple.com/app/kiokuyomi/id6795781367](https://apps.apple.com/app/kiokuyomi/id6795781367)
- **TestFlight 公测邀请**: [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD)
- **使用指南**: [https://kiokuyomi.com/getting-started/](https://kiokuyomi.com/getting-started/)
- **扩展源与规则说明**: [https://kiokuyomi.com/getting-started/extensions/](https://kiokuyomi.com/getting-started/extensions/)
- **本地书库说明**: [https://kiokuyomi.com/getting-started/library/](https://kiokuyomi.com/getting-started/library/)
- **Discord 官方频道**: [https://discord.gg/JVS4az867f](https://discord.gg/JVS4az867f)
- **Reddit 官方社区**: [https://www.reddit.com/r/kiokuYomi](https://www.reddit.com/r/kiokuYomi)
- **隐私政策**: [https://kiokuyomi.com/privacy/](https://kiokuyomi.com/privacy/)
- **使用条款**: [https://kiokuyomi.com/terms/](https://kiokuyomi.com/terms/)

---

### ⚖️ 免责与法律声明

KiokuYomi 是本地离线阅读与开放规则执行沙盒工具，不提供、不托管、不镜像、也不分发任何受版权保护的第三方漫画或媒体内容。所有第三方扩展源与规则仓库均由开源社区及用户自行维护与添加。用户需自行遵守其所在地区的版权法规与平台政策。
