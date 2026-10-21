# KiokuYomi

> 适用于 iPhone 与 iPad 的本地优先漫画阅读器。

KiokuYomi 是一款原生 iOS 漫画与文档阅读器：导入自己的文件、用规则驱动来源、按需下载，并自行决定是否通过 iCloud 同步阅读进度与偏好。

- 官网：[kiokuyomi.com](https://kiokuyomi.com)
- 使用指南：[kiokuyomi.com/getting-started](https://kiokuyomi.com/getting-started/)
- 公开测试：[TestFlight](https://testflight.apple.com/join/Mujc89bD)

## 功能

- **本地书库**：导入 CBZ、CBR、ZIP、RAR 与 PDF，离线阅读。
- **规则驱动来源**：浏览、搜索、详情、章节与图片由规则包描述，按需启用。
- **阅读器**：分页与连续阅读、双页跨页、阅读方向、图像处理与阅读偏好。
- **书库管理**：分类、筛选、排序、批量操作与阅读进度。
- **下载与备份**：离线下载，支持导出与恢复备份。
- **可选同步**：可选用 iCloud 同步书库、进度与偏好，默认本地优先。
- **追踪与小组件**：可选的第三方追踪（如 Bangumi）与继续阅读小组件。
- **多语言与无障碍**：中文 / 英文界面，支持动态字体与 VoiceOver。

## 规则源

KiokuYomi 的规则源以加密包形式分发，订阅地址保持稳定：

| 用途 | 地址 |
| --- | --- |
| 通用来源（非成人内容） | `https://sources.kiokuyomi.com/general.json` |
| 全部来源 | `https://sources.kiokuyomi.com/all.json` |
| 公开镜像 | [kiokuyomi-Community/sources](https://github.com/kiokuyomi-Community/sources) |

规则包由 App 校验后加载。公开文件中不包含明文规则、密钥、Cookie 或账户凭据。

## 文档与支持

- [使用指南](https://kiokuyomi.com/getting-started/)
- [常见问题](https://kiokuyomi.com/faq/)
- [社区与反馈](https://kiokuyomi.com/getting-started/support/)
- Discord：<https://discord.gg/JVS4az867f>
- Reddit：<https://www.reddit.com/r/kiokuYomi>
- [隐私政策](https://kiokuyomi.com/privacy/) · [使用条款](https://kiokuyomi.com/terms/)

## 关于本仓库

本仓库仅公开项目说明与基础文档。应用源码、构建流水线以及加密规则发布仓库不在本仓库公开。

## 法律声明

KiokuYomi 是本地优先的阅读与来源管理工具，不提供、镜像、托管或销售任何第三方漫画、文章或视频内容，也不保证任何第三方来源持续可用。用户只能导入、访问和保存自己有权使用的规则与内容。
