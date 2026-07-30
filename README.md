# ZyDownload

[Official website](https://zydownload.zyravo.store) · [Documentation](https://github.com/zyravo-store/zydownload/wiki) · [Issues](https://github.com/zyravo-store/zydownload/issues) · [Support](mailto:support@zyravo.store)

## Current release

| Item | Value |
| --- | --- |
| Version | Version 1.0.0 (2607291817) |
| Release notes and assets | [GitHub Release](https://github.com/zyravo-store/zydownload/releases/tag/v1.0.0) |
| Checksums | Included with the assets in the same Release |

## Features

- Discover images, media, documents, styles, scripts, and page resources.
- Filter and preview resources before downloading.
- Package supported resources into organized downloads.

## Downloads and installation

- [Download the verified Release assets](https://github.com/zyravo-store/zydownload/releases/tag/v1.0.0)
- [English installation guide](https://github.com/zyravo-store/zydownload/wiki/Installation)
- [简体中文安装指南](https://github.com/zyravo-store/zydownload/wiki/ZH-CN-Installation)
- Prefer the official browser store or Mac App Store listing when available.

### Package verification

- Windows ZIP and Linux ZIP files are browser-extension bundles, not native
  EXE, MSI, AppImage, DEB, or RPM applications. They have no operating-system
  code signature; verify the SHA-256 file from the same Release.
- Run checksum commands from the directory containing both files. Windows
  PowerShell can use `Get-FileHash <archive> -Algorithm SHA256`; Linux can use
  `sha256sum -c <checksum-file>`; macOS can use
  `shasum -a 256 -c <checksum-file>`.
- Extract the outer archive and then the package for your browser. Chrome,
  Chromium, Brave, and Edge use Developer mode → Load unpacked. Firefox manual
  packages use about:debugging → This Firefox → Load Temporary Add-on.
- Linux also supports command-line testing with Chromium-family
  `--load-extension=/absolute/path` or
  `npx web-ext run --source-dir /absolute/path`. Command-line loading is not a
  permanent installation channel.
- Public macOS DMG and PKG files are Developer ID signed, notarized, stapled,
  and Gatekeeper-validated before publication.
- Prefer the official browser store package when it becomes available.

This public repository contains release metadata and downloadable packages only.
Source code is maintained in a separate private repository.

---

## 中文

### 当前版本

| 项目 | 内容 |
| --- | --- |
| 版本 | Version 1.0.0 (2607291817) |
| 更新说明与安装包 | [GitHub Release](https://github.com/zyravo-store/zydownload/releases/tag/v1.0.0) |
| 校验文件 | 与安装包位于同一个 Release |

### 主要功能

- 发现网页中的图片、媒体、文档、样式、脚本和其他资源。
- 下载前筛选并预览资源。
- 将支持的资源整理并打包下载。

### 下载与安装

- [下载已验证的 Release 安装包](https://github.com/zyravo-store/zydownload/releases/tag/v1.0.0)
- [简体中文安装指南](https://github.com/zyravo-store/zydownload/wiki/ZH-CN-Installation)
- [英文安装指南](https://github.com/zyravo-store/zydownload/wiki/Installation)
- 浏览器商店或 Mac App Store 版本上线后，优先使用官方商店安装。

### 安装包校验

- Windows ZIP 与 Linux ZIP 是浏览器扩展合集，不是 EXE、MSI、AppImage、DEB
  或 RPM 原生程序，因此没有系统级代码签名；使用前请校验同一 Release 中的 SHA-256。
- 在安装包与校验文件所在目录执行校验。Windows PowerShell 使用
  `Get-FileHash <安装包> -Algorithm SHA256`；Linux 使用
  `sha256sum -c <校验文件>`；macOS 使用
  `shasum -a 256 -c <校验文件>`。
- 解压外层归档和对应浏览器扩展包后，Chrome、Chromium、Brave 与 Edge
  使用“开发者模式 → 加载已解压的扩展程序”；Firefox 手动包使用
  “about:debugging → 此 Firefox → 临时载入附加组件”。
- Linux 还可使用 Chromium 系浏览器的
  `--load-extension=/absolute/path` 或
  `npx web-ext run --source-dir /absolute/path` 进行命令行测试；命令行加载不是永久安装渠道。
- 公开 macOS DMG 与 PKG 在发布前必须通过 Developer ID 签名、Apple 公证、
  stapling 与 Gatekeeper 验证。

### 支持

- [问题反馈](https://github.com/zyravo-store/zydownload/issues)
- [使用文档](https://github.com/zyravo-store/zydownload/wiki)
- [官方网站](https://zydownload.zyravo.store)
- 技术支持：support@zyravo.store
- 使用反馈：feedback@zyravo.store
