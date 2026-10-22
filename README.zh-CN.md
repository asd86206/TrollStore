[English](README.md) | [繁體中文](README.zh-TW.md) | **[简体中文](README.zh-CN.md)** | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 免费 IPA 资源**
> 　　免费 IPA 资源与 TrollStore 教程，可直接在手机上免费安装。
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 TrollStore 安装指南

**说明如何安装 TrollStore、哪些 iOS 版本受支持，以及哪种方式对应你的芯片。**

---

## 📖 什么是 TrollStore？

TrollStore 利用 CoreTrust 漏洞，永久签名并安装任何 IPA。它不是越狱。装好的 App 会保持签名，不会像普通侧载那样到期掉签。

### ✨ 核心优势

- ✅ **完全免费**：无需支付任何费用
- ✍️ **永久签名**：安装后的 App 不会过期
- 📱 **在设备上安装**：直接在 iPhone 上安装 IPA
- 🔓 **无需越狱**：不需要越狱系统

### 📱 支持的系统版本

| 状态 | 系统版本 | 说明 |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | 支持 |
| 🔴 | iOS `14.0 beta 1` 及更早版本 | 不支持 |
| 🔴 | iOS `16.7` – `16.7.11` | 不支持 |
| 🔴 | iOS `17.0.1` 及更高版本 | 不支持 |

> **💡 小提示**：不要更新 iOS。系统一旦更新，手机就可能离开这份列表，之后将无法安装 TrollStore。

`16.7 RC`（构建 20H18）可以安装，正式版 `16.7` 则不行。安装方式表依照 [Installing TrollStore](https://ios.cfw.guide/installing-trollstore)，该页也将 `16.7.12` – `16.7.16` 标为不支持。

### 🔧 按版本和芯片选择安装方式

在左侧栏找到 iOS 版本，在上方找到芯片，然后打开该方式的指南。「不适用」表示该芯片无法运行这个 iOS 版本。「不支持」表示 TrollStore 在那里无法使用。

| 起始版本 | 结束版本 | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | 不支持 | 不支持 | 不支持 |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | 不适用 |
| 16.0 beta 1 | 16.0 beta 5 | 不适用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | 不适用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | 不适用 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | 不适用 | 不支持 | 不支持 |
| 17.0 beta 1 | 17.0 beta 4 | 不适用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | 不适用 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | 不适用 | 不支持 | 不支持 |

资料来源：[ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore)。

### 📱 iPhone 型号与芯片

用这张表确认你的 iPhone 对应上方哪一个芯片栏。

| 型号 | 芯片 |
| :--- | :---: |
| iPhone 15 Pro / Pro Max | A17 Pro |
| iPhone 15 / 15 Plus | A16 |
| iPhone 14 Pro / Pro Max | A16 |
| iPhone 14 / 14 Plus | A15 |
| iPhone SE (3rd generation) | A15 |
| iPhone 13 / 13 mini / 13 Pro / 13 Pro Max | A15 |
| iPhone 12 / 12 mini / 12 Pro / 12 Pro Max | A14 |
| iPhone SE (2nd generation) | A13 |
| iPhone 11 / 11 Pro / 11 Pro Max | A13 |
| iPhone XS / XS Max / XR | A12 |
| iPhone X / 8 / 8 Plus | A11 |
| iPhone 7 / 7 Plus | A10 |
| iPhone SE (1st generation) / 6s / 6s Plus | A9 |
| iPhone 6 / 6 Plus | A8 |

A17 Pro 属于 **A12–A17 / M1–M2** 这一栏。iPhone 16 及后续机型未列入，因为出厂时的 iOS 版本不受 TrollStore 支持。

**iPad 型号**

| 型号 | 芯片 |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ 推荐工具

### 🎙️ **TrollRecorder**

TrollRecorder 是专为 TrollStore 设计的通话录音工具。不需要越狱，核心功能免费。

**下载**：[GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed 在状态栏显示当前的上传和下载速度。

**下载**：[GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 链接

- 🌐 资源站：[https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 本仓库：[https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ 免责声明

本指南仅供教育用途。请只安装你信任的 IPA。你需要自行负责所安装的 App，并遵守所在地的法律。
