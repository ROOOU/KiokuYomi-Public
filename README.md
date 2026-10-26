# KiokuYomi (记忆读) - Native iOS Manga Reader & Mihon / Keiyoushi Migration Guide

<p align="center">
  <a href="https://kiokuyomi.com/"><img src="https://kiokuyomi.com/assets/brands/kiokuyomi-logo.svg" alt="KiokuYomi Logo" width="100" height="100" /></a>
</p>

<p align="center">
  <strong>A high-performance, native comic & manga reader for iOS and iPadOS.</strong><br>
  <em>Offline local reading for CBZ/CBR/ZIP/PDF on the App Store • Keiyoushi & Mihon modular extension runtime in public TestFlight.</em>
</p>

<p align="center">
  <a href="https://apps.apple.com/app/kiokuyomi/id6795781367"><img src="https://img.shields.io/badge/App%20Store-Download%20Free-black?logo=apple&style=flat-square" alt="App Store" /></a>
  <a href="https://testflight.apple.com/join/Mujc89bD"><img src="https://img.shields.io/badge/TestFlight-Public%20Beta-007AFF?logo=testflight&style=flat-square" alt="TestFlight Beta" /></a>
  <a href="https://kiokuyomi.com/"><img src="https://img.shields.io/badge/Official%20Site-kiokuyomi.com-0284c7?style=flat-square" alt="Official Site" /></a>
  <a href="https://discord.gg/JVS4az867f"><img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?logo=discord&style=flat-square" alt="Discord" /></a>
  <a href="https://www.reddit.com/r/kiokuYomi"><img src="https://img.shields.io/badge/Reddit-r%2FkiokuYomi-FF4500?logo=reddit&style=flat-square" alt="Reddit" /></a>
</p>

---

## 📖 English Overview

**KiokuYomi (记忆读)** is an open-rule, native iOS and iPadOS comic and manga reader crafted with pure Swift, SwiftUI, and UIKit. Engineered specifically for 120Hz ProMotion displays and iPad dual-page layouts, KiokuYomi delivers a lightning-fast, privacy-first reading experience with zero user tracking and no required accounts.

If you are migrating from Android's **Tachiyomi** or **Mihon** and looking for an iOS reader with comparable modular flexibility and Keiyoushi extension source support, KiokuYomi is designed for you.

### 📱 Edition Comparison (App Store vs. TestFlight)

To balance strict Apple App Store guidelines with the power user needs of the manga community, KiokuYomi is maintained in two distinct distributions:

| Capability | App Store Official Edition | TestFlight Public Beta Edition |
| :--- | :---: | :---: |
| **Primary Focus** | Offline Local Library & Privacy | Advanced Rule Sandbox & Extensions |
| **Local Archives** | CBZ, CBR, ZIP, RAR, PDF | CBZ, CBR, ZIP, RAR, PDF |
| **Import Methods** | Apple Files, AirDrop, Local Wi-Fi | Apple Files, AirDrop, Local Wi-Fi |
| **Extension Sandbox** | ✕ *(Disabled for Store Review)* | ✅ **Mihon & Keiyoushi Repositories** |
| **Online Source Search** | ✕ | ✅ Multi-source browsing & updates |
| **Privacy & Accounts** | 100% On-device, No Accounts | 100% On-device, No Accounts |
| **Download Link** | [**Download on App Store**](https://apps.apple.com/app/kiokuyomi/id6795781367) | [**Join Public TestFlight**](https://testflight.apple.com/join/Mujc89bD) |

---

## 🚀 Migrating from Android (Mihon / Tachiyomi) to iOS

For users transitioning from Mihon or Tachiyomi on Android to iPhone or iPad:

1. **Install KiokuYomi Beta via TestFlight**:
   Open [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD) on your iOS device to install the latest beta build.
2. **Add Modular Extension Repositories**:
   In KiokuYomi, navigate to Settings / Sources → Add Repository. Paste your trusted third-party repository URL (compatible with standard Keiyoushi / Mihon indexes).
3. **Browse & Install Extensions**:
   Explore available modular extensions directly on your device. All parsing rules run inside an isolated, on-device Swift sandbox without proxying through third-party servers.
4. **Local Backup & Transfer**:
   Use KiokuYomi's built-in **Wi-Fi Transfer** to upload your existing CBZ/CBR manga archives from your PC, Mac, or Android device directly over your local home network without iTunes cables.

---

## 🌟 Key Reader Features

- **⚡ Native 120Hz ProMotion Engine**: Smooth, fluid rendering with near-zero latency scrolling and page flips.
- **📖 Intelligent Dual-Page Spread**: Automatically pairs consecutive pages into seamless two-page spreads in landscape orientation on iPad and iPhone, with smart first-page cover offsets.
- **📜 Multi-Directional Layouts**: Continuous vertical Webtoon scroll, right-to-left (RTL) traditional manga, and left-to-right (LTR) comic modes.
- **📂 High-Speed Local Importer**: Directly read files in-place using the native Apple Files app, receive files via AirDrop, or drag-and-drop through browser-based local Wi-Fi transfer.
- **☁️ Private iCloud Sync**: Optional iCloud sync for reading progress, bookmarks, and preferences across all your Apple devices.
- **🎨 Deep Customization**: Reading direction presets, custom crop/borders, brightness/contrast filters, and dark mode support.

---

## 🇨🇳 中文说明与迁移指南

**KiokuYomi（记忆读）** 是一款专为 iPhone 与 iPad 打造的原生漫画与图集阅读器，采用纯 Swift 与 UIKit/SwiftUI 原生技术开发，针对苹果 120Hz ProMotion 高刷屏幕与 iPad 横屏双页排版进行了深度优化。

对于从 Android（Mihon / Tachiyomi）迁移至 iOS 系统的用户，KiokuYomi 提供了无缝的过渡体验：

### 核心版本说明：
1. **App Store 官方正式版（App ID: 6795781367）**：
   - 聚焦于纯净的本地离线书库阅读与最高级别隐私。
   - 无任何账号体系、无数据追踪、不收集任何个人信息。
   - 高性能解析 CBZ、CBR、ZIP、RAR、PDF 文件，支持密码压缩包与 Wi-Fi 局域网免数据线快传。
   - 商店下载地址：[App Store 官方下载](https://apps.apple.com/app/kiokuyomi/id6795781367)
2. **TestFlight 公开测试版（支持 Keiyoushi 扩展规则）**：
   - 针对老玩家与进阶用户，内置了端侧沙盒规则解析运行时。
   - 支持添加兼容 Mihon / Keiyoushi 规范的第三方扩展源仓库链接，在 iOS 端直接检索和订阅。
   - 规则与网络请求均在 iPhone/iPad 本地沙盒环境独立执行，不经过任何中转服务器。
   - 公开测试邀请：[加入 TestFlight 公测](https://testflight.apple.com/join/Mujc89bD)

---

## ❓ Frequently Asked Questions (FAQ)

#### Q1: Does KiokuYomi support Keiyoushi extensions on iOS?
**A**: Yes! The **TestFlight Public Beta** includes a dedicated sandboxed runtime capable of loading and parsing third-party modular extension repositories compatible with Keiyoushi and Mihon. The App Store release focuses on local files.

#### Q2: How can I import CBZ, CBR, or ZIP files into KiokuYomi?
**A**: You can import files via:
1. **Wi-Fi Transfer**: Open KiokuYomi → Start Wi-Fi Transfer → Open the displayed local IP address in any browser on your computer to drag-and-drop archives.
2. **Files App**: Open any CBZ/CBR/ZIP/PDF from iCloud Drive or On My iPhone directly in KiokuYomi.
3. **AirDrop**: Share files from your Mac or another iOS device directly into KiokuYomi.

#### Q3: Is KiokuYomi completely free?
**A**: Yes, KiokuYomi offers core local reading, file import, and TestFlight features for free with zero advertisements.

---

## 🔗 Official Links & Resources

- **Official Website**: [https://kiokuyomi.com/](https://kiokuyomi.com/)
- **App Store Download**: [https://apps.apple.com/app/kiokuyomi/id6795781367](https://apps.apple.com/app/kiokuyomi/id6795781367)
- **TestFlight Beta**: [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD)
- **Getting Started Guide**: [https://kiokuyomi.com/getting-started/](https://kiokuyomi.com/getting-started/)
- **Extensions Guide**: [https://kiokuyomi.com/getting-started/extensions/](https://kiokuyomi.com/getting-started/extensions/)
- **Local Library Guide**: [https://kiokuyomi.com/getting-started/library/](https://kiokuyomi.com/getting-started/library/)
- **Discord Community**: [https://discord.gg/JVS4az867f](https://discord.gg/JVS4az867f)
- **Reddit Community**: [https://www.reddit.com/r/kiokuYomi](https://www.reddit.com/r/kiokuYomi)
- **Privacy Policy**: [https://kiokuyomi.com/privacy/](https://kiokuyomi.com/privacy/)
- **Terms of Service**: [https://kiokuyomi.com/terms/](https://kiokuyomi.com/terms/)

---

## ⚖️ Disclaimer

KiokuYomi is a local file viewer and open-rule execution sandbox. It does not provide, host, mirror, or distribute any copyrighted manga, comic, or media content. All third-party extension repositories and sources are managed independently by community contributors and the user. Users are responsible for complying with the legal requirements, copyright licenses, and platform policies of their respective regions.
