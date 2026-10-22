[English](README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | **[한국어](README.ko.md)** | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 무료 IPA 자료**
> 　　무료 IPA 자료와 TrollStore 안내입니다. 휴대폰에서 무료로 바로 설치할 수 있습니다.
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 TrollStore 설치 가이드

**TrollStore 설치 방법, 지원되는 iOS 버전, 칩에 맞는 설치 방법을 정리했습니다.**

---

## 📖 TrollStore란

TrollStore는 CoreTrust 버그를 이용해 어떤 IPA든 영구적으로 서명하고 설치합니다. 탈옥이 아닙니다. 설치한 앱은 서명이 유지되어, 일반 사이드로드처럼 만료되지 않습니다.

### ✨ 핵심 장점

- ✅ **무료**：비용을 낼 필요가 없습니다
- ✍️ **영구 서명**：설치한 앱이 만료되지 않습니다
- 📱 **기기에서 설치**：IPA를 iPhone에서 바로 설치합니다
- 🔓 **탈옥 불필요**：시스템을 탈옥하지 않습니다

### 📱 지원 버전

| 상태 | iOS 버전 | 설명 |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | 지원 |
| 🔴 | iOS `14.0 beta 1` 및 그 이전 | 미지원 |
| 🔴 | iOS `16.7` – `16.7.11` | 미지원 |
| 🔴 | iOS `17.0.1` 및 그 이후 | 미지원 |

> **💡 팁**：iOS를 업데이트하지 마세요. 더 새 버전으로 올리면 이 목록에서 벗어날 수 있고, 그 뒤에는 TrollStore를 설치할 수 없습니다.

`16.7 RC`(빌드 20H18)는 지원됩니다. 정식 `16.7`은 지원되지 않습니다. 설치 방법 표는 [Installing TrollStore](https://ios.cfw.guide/installing-trollstore)를 따릅니다. 그 페이지는 `16.7.12` – `16.7.16`도 미지원으로 표시합니다.

### 🔧 버전과 칩별 설치 방법

왼쪽 열에서 iOS 버전을, 위쪽 행에서 칩을 찾은 뒤 해당 방법의 가이드를 여세요. 「해당 없음」은 그 칩이 해당 iOS를 실행할 수 없다는 뜻입니다. 「미지원」은 그곳에서 TrollStore가 동작하지 않는다는 뜻입니다.

| 시작 버전 | 끝 버전 | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | 미지원 | 미지원 | 미지원 |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | 해당 없음 |
| 16.0 beta 1 | 16.0 beta 5 | 해당 없음 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | 해당 없음 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | 해당 없음 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | 해당 없음 | 미지원 | 미지원 |
| 17.0 beta 1 | 17.0 beta 4 | 해당 없음 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | 해당 없음 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | 해당 없음 | 미지원 | 미지원 |

출처: [ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore).

### 📱 iPhone 모델과 칩

이 표로 자신의 iPhone이 위 표의 어느 칩 열에 해당하는지 확인하세요.

| 모델 | 칩 |
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

A17 Pro는 **A12–A17 / M1–M2** 열에 해당합니다. iPhone 16 이후 기기는 표에 없습니다. TrollStore가 지원하지 않는 iOS로 출시되었기 때문입니다.

**iPad 모델**

| 모델 | 칩 |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ 추천 도구

### 🎙️ **TrollRecorder**

TrollRecorder는 TrollStore용 통화 녹음 도구입니다. 탈옥이 필요 없고, 핵심 기능은 무료입니다.

**다운로드**：[GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed는 상태 막대에 현재 업로드와 다운로드 속도를 표시합니다.

**다운로드**：[GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 링크

- 🌐 자료 사이트：[https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 이 저장소：[https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ 면책 조항

이 가이드는 교육 목적입니다. 신뢰할 수 있는 IPA만 설치하세요. 설치하는 앱과 거주 지역의 법령을 지킬 책임은 본인에게 있습니다.
