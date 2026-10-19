# PasteShot

macOS 剪贴板、截图、标注、OCR 与 Apple 本地翻译工具。

**本仓库仅用于发布安装包和使用说明，不包含应用源码。**

## 下载

[下载最新 Release](https://github.com/Master-Sword-Ext/pasteshot/releases/latest)

请下载 Assets 中的 `PasteShot-0.4.8-macOS-arm64.zip`。压缩包内包含应用和安装说明，不包含任何个人历史、截图或设置。

## 系统要求

- Apple 芯片 Mac（M 系列）。
- macOS 26.4 或更高版本。
- 不支持 Intel Mac 或更早版本的 macOS。
- 无需安装 Xcode、Swift 开发工具或本项目源码。

## 安装

1. 下载并解压 ZIP，将 `PasteShot.app` 拖入“应用程序”。
2. 双击打开。此版本使用 ad hoc 本地签名，未使用 Developer ID，也未经过 Apple 公证。
3. 首次打开若被系统阻止，确认来源可信后，可按 [Apple 官方说明](https://support.apple.com/en-us/102445) 在“系统设置 → 隐私与安全性”中选择“仍要打开”。
4. 在应用设置中按需开启后台记录和快捷键，并按系统提示授予剪贴板、屏幕录制或辅助功能权限。
5. 本地翻译如果提示语言模型未准备，请点击“准备语言…”完成系统流程。

## 功能

- 本地剪贴板历史、搜索、收藏与快捷弹窗。
- 区域／窗口截图，截图后工具条，悬挂图片。
- 图像标注、裁剪、遮盖和 PNG 导出。
- 本地 OCR 与 Apple 本地翻译。
- 中英混排自动选源，保留原文与译文关联。

## 数据与已知边界

数据保存在当前用户的 `~/Library/Application Support/PasteShot`。新安装默认关闭记录和快捷键，可由用户自行开启。默认保留 30 天／2 GB，收藏不自动删除。

技术文本的译文仍可能存在术语或语义错误，请结合原文核对。本版本已完成本机功能验证，尚未完成其他接收方 Mac 的实测。

## 校验

Release 附带同名 `.sha256` 校验文件，可用于确认下载的 ZIP 未损坏。
