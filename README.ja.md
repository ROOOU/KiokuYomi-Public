# KiokuYomi (記憶読み) - iOS 向けネイティブマンガリーダー

<p align="center">
  <a href="https://kiokuyomi.com/"><img src="assets/app-icon.png" alt="KiokuYomi Logo" width="108" height="108" style="border-radius: 22px;" /></a>
</p>

<p align="center">
  <strong>iPhone および iPad 向けの高パフォーマンスなネイティブコミック・マンガリーダー。</strong><br>
  <em>App Store でのローカル CBZ/CBR/ZIP/PDF 読込 • TestFlight での Keiyoushi & Mihon 拡張機能サンドボックス実行。</em>
</p>

<p align="center">
  <a href="https://apps.apple.com/app/kiokuyomi/id6795781367"><img src="https://img.shields.io/badge/App%20Store-Download%20Free-black?logo=apple&style=flat-square" alt="App Store" /></a>
  <a href="https://testflight.apple.com/join/Mujc89bD"><img src="https://img.shields.io/badge/TestFlight-Public%20Beta-007AFF?logo=testflight&style=flat-square" alt="TestFlight Beta" /></a>
  <a href="https://kiokuyomi.com/ja/"><img src="https://img.shields.io/badge/Official%20Site-kiokuyomi.com-0284c7?style=flat-square" alt="Official Site" /></a>
  <a href="https://discord.gg/JVS4az867f"><img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?logo=discord&style=flat-square" alt="Discord" /></a>
  <a href="https://www.reddit.com/r/kiokuYomi"><img src="https://img.shields.io/badge/Reddit-r%2FkiokuYomi-FF4500?logo=reddit&style=flat-square" alt="Reddit" /></a>
</p>

<p align="center">
  <a href="README.md">English</a> | 🌐 <strong>日本語</strong> | <a href="README.zh-CN.md">简体中文</a>
</p>

---

## 📖 概要

**KiokuYomi（記憶読み）** は、iPhone および iPad 向けに Swift、SwiftUI、UIKit を用いてゼロから開発された高パフォーマンスなネイティブマンガ・コミックリーダーです。Apple の 120Hz ProMotion ディスプレイや iPad の横向き見開き 2 ページ表示に最適化されており、アカウント登録不要・トラッキングなしのローカル最優先設計を実現しています。

Android の **Tachiyomi** や **Mihon** から iOS に移行し、同様のモジュラー拡張機能（Keiyoushi ルール互換）を利用できるリーダーをお探しの方に最適です。

---

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

---

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

---

### 🌟 リーダーの主な特長

- **⚡ 120Hz ProMotion 対応**: ページめくりやスクロールが驚くほど滑らかです。
- **📖 スマート見開き表示**: iPad や iPhone の横画面で、単ページ漫画を自動的に美しい見開き 2 ページとして合成表示します（表紙オフセット対応）。
- **📜 多彩な読書モード**: Webtoon の連続縦スクロール、右開き（日本の伝統マンガ）、左開き（アメコミ等）に対応。
- **📂 直感的なファイル読み込み**: Apple 純正「ファイル」アプリでのインプレース閲覧、AirDrop、Wi-Fi 転送に対応。
- **☁️ プライベートな iCloud 同期**: 読書進捗やしおりは、個人アカウント登録なしで Apple 公式の iCloud 経由で同期可能。
- **🎨 自由なカスタマイズ**: 読み方向プリセット、余白トリミング、明度・コントラスト調整、ダークモード対応。

---

### ❓ よくある質問（FAQ）

#### Q1: Keiyoushi 拡張機能はどちらの版で使えますか？
**A**: Keiyoushi や Mihon 互換の拡張機能は **TestFlight パブリックベータ版** でのみ利用可能です。App Store 正式版はローカルファイルの閲覧に特化しています。

#### Q2: CBZ や ZIP ファイルを取り込むには？
**A**: アプリ内の「Wi-Fi 転送」を使って PC のブラウザから直接転送するか、純正「ファイル」アプリから開く、あるいは Mac/iPad から AirDrop で送信してください。

---

### 🔗 公式リンクとリソース

- **公式サイト**: [https://kiokuyomi.com/ja/](https://kiokuyomi.com/ja/)
- **App Store ダウンロード**: [https://apps.apple.com/app/kiokuyomi/id6795781367](https://apps.apple.com/app/kiokuyomi/id6795781367)
- **TestFlight パブリックベータ**: [https://testflight.apple.com/join/Mujc89bD](https://testflight.apple.com/join/Mujc89bD)
- **ユーザーガイド (日本語)**: [https://kiokuyomi.com/ja/getting-started/](https://kiokuyomi.com/ja/getting-started/)
- **拡張機能ガイド**: [https://kiokuyomi.com/ja/getting-started/extensions/](https://kiokuyomi.com/ja/getting-started/extensions/)
- **Discord コミュニティ**: [https://discord.gg/JVS4az867f](https://discord.gg/JVS4az867f)
- **Reddit コミュニティ**: [https://www.reddit.com/r/kiokuYomi](https://www.reddit.com/r/kiokuYomi)
- **プライバシーポリシー**: [https://kiokuyomi.com/privacy/](https://kiokuyomi.com/privacy/)
- **利用規約**: [https://kiokuyomi.com/terms/](https://kiokuyomi.com/terms/)

---

### ⚖️ 免責事項・法的表示

KiokuYomi はローカルファイルリーダーおよびオープンルール実行サンドボックスです。著作権で保護されたマンガやメディアコンテンツを提供、配信、中継することはありません。外部拡張機能およびリポジトリはコミュニティおよび利用者自身によって管理されます。利用者は各地域の著作権法および規約を遵守してご利用ください。
