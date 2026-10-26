# KiokuYomi (记忆读 / 記憶読み) - Native iOS Manga Reader

<p align="center">
  <a href="https://kiokuyomi.com/"><img src="assets/app-icon.png" alt="KiokuYomi Logo" width="108" height="108" style="border-radius: 22px;" /></a>
</p>

<p align="center">
  <strong>High-performance, native comic & manga reader for iOS and iPadOS.</strong><br>
  <em>Offline reading for local CBZ/CBR/ZIP/PDF archives on the App Store • Keiyoushi & Mihon extension runtime in public TestFlight.</em>
</p>

<p align="center">
  <a href="https://apps.apple.com/app/kiokuyomi/id6795781367"><img src="https://img.shields.io/badge/App%20Store-Download%20Free-black?logo=apple&style=flat-square" alt="App Store" /></a>
  <a href="https://testflight.apple.com/join/Mujc89bD"><img src="https://img.shields.io/badge/TestFlight-Public%20Beta-007AFF?logo=testflight&style=flat-square" alt="TestFlight Beta" /></a>
  <a href="https://kiokuyomi.com/"><img src="https://img.shields.io/badge/Official%20Site-kiokuyomi.com-0284c7?style=flat-square" alt="Official Site" /></a>
  <a href="https://discord.gg/JVS4az867f"><img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?logo=discord&style=flat-square" alt="Discord" /></a>
  <a href="https://www.reddit.com/r/kiokuYomi"><img src="https://img.shields.io/badge/Reddit-r%2FkiokuYomi-FF4500?logo=reddit&style=flat-square" alt="Reddit" /></a>
</p>

<p align="center">
  <a href="#-english-default"><strong>English</strong></a> •
  <a href="#-日本語-japanese"><strong>日本語</strong></a> •
  <a href="#-简体中文-simplified-chinese"><strong>简体中文</strong></a>
</p>

---

## 🌐 English (Default)

**KiokuYomi (记忆读 / 記憶読み)** is an open-rule, native iOS and iPadOS comic and manga reader crafted with pure Swift, SwiftUI, and UIKit. Engineered specifically for 120Hz ProMotion displays and iPad dual-page layouts, KiokuYomi delivers a lightning-fast, privacy-first reading experience with zero user tracking and no required accounts.

If you are migrating from Android's **Tachiyomi** or **Mihon** and looking for an iOS reader with comparable modular flexibility and Keiyoushi extension source support, KiokuYomi is designed for you.

### 📱 Edition Comparison (App Store vs. TestFlight)

To balance strict Apple App Store guidelines with the power-user needs of the manga community, KiokuYomi is maintained in two distinct distributions:

| Capability | App Store Official Edition | TestFlight Public Beta Edition |
| :--- | :---: | :---: |
| **Primary Focus** | Offline Local Library & Privacy | Advanced Rule Sandbox & Extensions |
| **Local Archives** | CBZ, CBR, ZIP, RAR, PDF | CBZ, CBR, ZIP, RAR, PDF |
| **Import Methods** | Apple Files, AirDrop, Local Wi-Fi | Apple Files, AirDrop, Local Wi-Fi |
| **Extension Sandbox** | ✕ *(Disabled for Store Review)* | ✅ **Mihon & Keiyoushi Repositories** |
| **Online Source Search** | ✕ | ✅ Multi-source browsing & updates |
| **Privacy & Accounts** | 100% On-device, No Accounts | 100% On-device, No Accounts |
| **Download Link** | [**Download on App Store**](https://apps.apple.com/app/kiokuyomi/id6795781367) | [**Join Public TestFlight**](https://testflight.apple.com/join/Mujc89bD) |

### 🚀 Migrating from Android (Mihon / Tachiyomi) to iOS

For users transitioning from Mihon or Tachiyomi on Android to iPhone or iPad:

1. **Install KiokuYomi Beta via TestFlight**:
   Open [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD) on your iOS device to install the latest beta build.
2. **Add Modular Extension Repositories**:
   In KiokuYomi, navigate to Settings / Sources → Add Repository. Paste your trusted third-party repository URL (compatible with standard Keiyoushi / Mihon indexes).
3. **Browse & Install Extensions**:
   Explore available modular extensions directly on your device. All parsing rules run inside an isolated, on-device Swift sandbox without proxying through third-party servers.
4. **Local Backup & Transfer**:
   Use KiokuYomi's built-in **Wi-Fi Transfer** to upload your existing CBZ/CBR manga archives from your PC, Mac, or Android device directly over your local home network without iTunes cables.

### 🌟 Key Reader Features

- **⚡ Native 120Hz ProMotion Engine**: Smooth, fluid rendering with near-zero latency scrolling and page flips.
- **📖 Intelligent Dual-Page Spread**: Automatically pairs consecutive pages into seamless two-page spreads in landscape orientation on iPad and iPhone, with smart first-page cover offsets.
- **📜 Multi-Directional Layouts**: Continuous vertical Webtoon scroll, right-to-left (RTL) traditional manga, and left-to-right (LTR) comic modes.
- **📂 High-Speed Local Importer**: Directly read files in-place using the native Apple Files app, receive files via AirDrop, or drag-and-drop through browser-based local Wi-Fi transfer.
- **☁️ Private iCloud Sync**: Optional iCloud sync for reading progress, bookmarks, and preferences across all your Apple devices.
- **🎨 Deep Customization**: Reading direction presets, custom crop/borders, brightness/contrast filters, and dark mode support.

---

## 🇯🇵 日本語 (Japanese)

**KiokuYomi（記憶読み）** は、iPhone および iPad 向けに Swift、SwiftUI、UIKit を用いてゼロから開発された高パフォーマンスなネイティブマンガ・コミックリーダーです。Apple の 120Hz ProMotion ディスプレイや iPad の横向き見開き 2 ページ表示に最適化されており、アカウント登録不要・トラッキングなしのローカル最優先設計を実現しています。

Android の **Tachiyomi** や **Mihon** から iOS に移行し、同様のモジュラー拡張機能（Keiyoushi ルール互換）を利用できるリーダーをお探しの方に最適です。

### 📱 エディションの比較（App Store 版 vs. TestFlight ベータ版）

Apple の App Store ガイドラインを遵守しつつ、コミュニティの高度なニーズに応えるため、KiokuYomi は 2 つの配信形態を用意しています：

| 機能・特徴 | App Store 正式版 | TestFlight パブリックベータ版 |
| :--- | :---: | :---: |
| **主な用途** | オフラインのローカル書庫・プライバシー | 拡張機能サンドボックス実行 |
| **対応ファイル** | CBZ, CBR, ZIP, RAR, PDF | CBZ, CBR, ZIP, RAR, PDF |
| **ファイル追加** | ファイル共有、AirDrop、Wi-Fi 転送 | ファイル共有、AirDrop、Wi-Fi 転送 |
| **拡張機能サンドボックス** | ✕ *(審査規約のため無効化)* | ✅ **Mihon / Keiyoushi リポジトリ対応** |
| **オンラインソース検索** | ✕ | ✅ 複数ソースの検索と更新 |
| **アカウント・個人情報** | 不要（完全端末内完結） | 不要（完全端末内完結） |
| **ダウンロード** | [**App Store で入手**](https://apps.apple.com/app/kiokuyomi/id6795781367) | [**TestFlight ベータに参加**](https://testflight.apple.com/join/Mujc89bD) |

### 🚀 Android（Mihon / Tachiyomi）からの移行手順

Android から iPhone や iPad に乗り換えたユーザーのための利用ステップ：

1. **TestFlight で KiokuYomi をインストール**:
   お使いの iOS デバイスで [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD) を開き、ベータ版を導入します。
2. **拡張機能リポジトリを追加**:
   KiokuYomi の設定画面から「リポジトリの追加」を選択し、Keiyoushi や Mihon 互換の外部リポジトリ URL を登録します。
3. **拡張機能のインストールと利用**:
   登録したリポジトリから拡張機能を直接インストールします。ルール解析処理はすべて端末内の安全なサンドボックスで完結し、外部サーバーを中継しません。
4. **ローカル書庫の Wi-Fi 転送**:
   PC や Android に保存してある CBZ / CBR などのコミックアーカイブは、アプリ内の **Wi-Fi 転送機能** を使ってブラウザから直接ドラッグ＆ドロップで高速取り込みが可能です。

### 🌟 リーダーの主な特長

- **⚡ 120Hz ProMotion 対応**: ページめくりやスクロールが驚くほど滑らかです。
- **📖 スマート見開き表示**: iPad や iPhone の横画面で、単ページ漫画を自動的に美しい見開き 2 ページとして合成表示します（表紙オフセット対応）。
- **📜 多彩な読書モード**: Webtoon の連続縦スクロール、右開き（日本の伝統マンガ）、左開き（アメコミ等）に対応。
- **☁️ プライベートな iCloud 同期**: 読書進捗やしおりは、個人アカウント登録なしで Apple 公式の iCloud 経由で同期可能。

---

## 🇨🇳 简体中文 (Simplified Chinese)

**KiokuYomi（记忆读）** 是一款专为 iPhone 与 iPad 打造的高性能原生漫画与图集阅读器。全量采用 Swift、SwiftUI 与 UIKit 原生开发，针对苹果 120Hz ProMotion 高刷屏幕与 iPad 横屏双页排版进行了深度定制，坚持本地优先、零数据收集、无账号体系。

如果您正在从 Android 的 **Tachiyomi** 或 **Mihon** 迁移至 iOS，并希望在 iPhone/iPad 上获得类似的开放规则沙盒与 Keiyoushi 扩展源支持，KiokuYomi 是您的理想选择。

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

### 🌟 核心功能亮点

- **⚡ 原生 120Hz ProMotion 引擎**: 超低延迟渲染，页面推拉与滑动无比跟手。
- **📖 智能双页跨页拼接**: iPad 横屏智能合并双页阅读，智能识别单双页跨页大图与封面偏移。
- **📜 丰富阅读模式**: 支持连续垂直滚屏（条漫/韩漫）、从右向左翻页（日漫）、从左向右翻页（美漫/欧漫）。
- **📂 便捷文件导入**: 原生支持「文件」应用原地读取、AirDrop 隔空投送、局域网 Wi-Fi 浏览器快传。
- **☁️ 私密 iCloud 同步**: 无需注册任何第三方账号，借助 Apple 官方 iCloud 自动在多台设备间同步阅读进度与书架。

---

## ❓ Frequently Asked Questions (FAQ)

#### Q1: Which edition supports Keiyoushi extensions?
- **English**: The **TestFlight Public Beta** edition supports Keiyoushi and Mihon-compatible extension repositories in an isolated sandbox. The App Store release focuses on local archive reading.
- **日本語**: Keiyoushi や Mihon 互換の拡張機能は **TestFlight パブリックベータ版** でのみ利用可能です。App Store 正式版はローカルファイルの閲覧に特化しています。
- **中文**: Mihon / Keiyoushi 扩展源目前仅在 **TestFlight 公共测试版** 中提供沙盒支持；App Store 正式版专注于本地离线书库（CBZ/CBR/ZIP/PDF）。

#### Q2: How can I import CBZ, CBR, or ZIP files?
- **English**: Use browser-based local Wi-Fi Transfer, Apple Files app, or AirDrop.
- **日本語**: Wi-Fi 転送機能（PC ブラウザからドラッグ＆ドロップ）、Apple 純正「ファイル」アプリ、または AirDrop で瞬時に取り込めます。
- **中文**: 支持使用 Wi-Fi 局域网网页快传、苹果系统自带「文件」应用原地读取、或 Mac/iPad 隔空投送（AirDrop）。

---

## 🔗 Official Links & Resources

- **Official Website**: [https://kiokuyomi.com/](https://kiokuyomi.com/)
- **App Store Download**: [https://apps.apple.com/app/kiokuyomi/id6795781367](https://apps.apple.com/app/kiokuyomi/id6795781367)
- **TestFlight Public Beta**: [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD)
- **User Guide (English)**: [https://kiokuyomi.com/en/getting-started/](https://kiokuyomi.com/en/getting-started/)
- **ユーザーガイド (日本語)**: [https://kiokuyomi.com/ja/getting-started/](https://kiokuyomi.com/ja/getting-started/)
- **使用指南 (中文)**: [https://kiokuyomi.com/getting-started/](https://kiokuyomi.com/getting-started/)
- **Extensions Guide**: [https://kiokuyomi.com/getting-started/extensions/](https://kiokuyomi.com/getting-started/extensions/)
- **Reddit Community**: [https://www.reddit.com/r/kiokuYomi](https://www.reddit.com/r/kiokuYomi)
- **Discord Community**: [https://discord.gg/JVS4az867f](https://discord.gg/JVS4az867f)
- **Privacy Policy**: [https://kiokuyomi.com/privacy/](https://kiokuyomi.com/privacy/)
- **Terms of Service**: [https://kiokuyomi.com/terms/](https://kiokuyomi.com/terms/)

---

## ⚖️ Legal & Disclaimer

KiokuYomi is a local file reader and open-rule execution sandbox. It does not provide, host, mirror, or distribute any copyrighted manga, comic, or media content. All third-party extension repositories and sources are managed independently by community contributors and the user. Users are responsible for complying with the copyright licenses, platform policies, and local regulations in their respective regions.
