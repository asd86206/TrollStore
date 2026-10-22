[English](README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | **[Tiếng Việt](README.vi.md)** | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 Tài nguyên IPA miễn phí**
> 　　Tài nguyên IPA miễn phí và bài hướng dẫn TrollStore. Cài trực tiếp trên điện thoại, miễn phí.
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 Hướng dẫn cài TrollStore

**Cách cài TrollStore, phiên bản iOS được hỗ trợ, và cách cài phù hợp với chip của máy.**

---

## 📖 TrollStore là gì?

TrollStore dùng lỗi CoreTrust để ký và cài vĩnh viễn bất kỳ IPA nào. Đây không phải jailbreak. Ứng dụng đã cài giữ chữ ký, nên không hết hạn như sideload thông thường.

### ✨ Lợi thế chính

- ✅ **Miễn phí**: không mất phí
- ✍️ **Ký vĩnh viễn**: ứng dụng đã cài không hết hạn
- 📱 **Cài trên máy**: cài tệp IPA trực tiếp trên iPhone
- 🔓 **Không cần jailbreak**: không jailbreak hệ thống

### 📱 Phiên bản được hỗ trợ

| Trạng thái | Phiên bản iOS | Ghi chú |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | Được hỗ trợ |
| 🔴 | iOS `14.0 beta 1` và cũ hơn | Không hỗ trợ |
| 🔴 | iOS `16.7` – `16.7.11` | Không hỗ trợ |
| 🔴 | iOS `17.0.1` và mới hơn | Không hỗ trợ |

> **💡 Mẹo**: Đừng cập nhật iOS. Bản mới hơn có thể đưa máy ra khỏi danh sách này, và sau đó bạn sẽ không cài được TrollStore.

`16.7 RC` (bản dựng 20H18) được hỗ trợ. Bản `16.7` chính thức thì không. Bảng cách cài theo [Installing TrollStore](https://ios.cfw.guide/installing-trollstore). Trang đó cũng ghi `16.7.12` – `16.7.16` là không được hỗ trợ.

### 🔧 Cách cài theo phiên bản và chip

Tìm phiên bản iOS ở cột bên trái và chip ở hàng trên, rồi mở hướng dẫn của cách đó. «Không áp dụng» nghĩa là chip đó không chạy được phiên bản iOS ấy. «Không hỗ trợ» nghĩa là TrollStore không hoạt động ở đó.

| Từ | Đến | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | Không hỗ trợ | Không hỗ trợ | Không hỗ trợ |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | Không áp dụng |
| 16.0 beta 1 | 16.0 beta 5 | Không áp dụng | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | Không áp dụng | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | Không áp dụng | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | Không áp dụng | Không hỗ trợ | Không hỗ trợ |
| 17.0 beta 1 | 17.0 beta 4 | Không áp dụng | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | Không áp dụng | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | Không áp dụng | Không hỗ trợ | Không hỗ trợ |

Nguồn: [ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore).

### 📱 Mẫu iPhone và chip

Dùng bảng này để xem iPhone của bạn thuộc cột chip nào ở trên.

| Mẫu máy | Chip |
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

A17 Pro nằm ở cột **A12–A17 / M1–M2**. iPhone 16 trở đi không có trong bảng vì máy xuất xưởng với iOS mà TrollStore không hỗ trợ.

**Mẫu iPad**

| Mẫu máy | Chip |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ Công cụ nên dùng

### 🎙️ **TrollRecorder**

TrollRecorder là công cụ ghi âm cuộc gọi cho TrollStore. Không cần jailbreak. Các chức năng chính miễn phí.

**Tải về**: [GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed hiện tốc độ tải lên và tải xuống ngay trên thanh trạng thái.

**Tải về**: [GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 Liên kết

- 🌐 Trang tài nguyên: [https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 Kho này: [https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ Tuyên bố miễn trừ

Hướng dẫn này chỉ nhằm mục đích giáo dục. Chỉ cài IPA mà bạn tin tưởng. Bạn tự chịu trách nhiệm về ứng dụng mình cài và về việc tuân thủ pháp luật nơi bạn sống.
