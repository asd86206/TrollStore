[English](README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | **[ไทย](README.th.md)** | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 แหล่ง IPA ฟรี**
> 　　แหล่งรวม IPA ฟรีและบทแนะนำ TrollStore ติดตั้งบนโทรศัพท์ได้โดยตรง ฟรี
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 คู่มือติดตั้ง TrollStore

**วิธีติดตั้ง TrollStore, เวอร์ชัน iOS ที่รองรับ และวิธีที่ตรงกับชิปของเครื่อง**

---

## 📖 TrollStore คืออะไร

TrollStore ใช้ช่องโหว่ CoreTrust เพื่อเซ็นและติดตั้ง IPA ใดก็ได้อย่างถาวร ไม่ใช่การเจลเบรก แอปที่ติดตั้งจะคงการเซ็นไว้ จึงไม่หมดอายุแบบการไซด์โหลดทั่วไป

### ✨ จุดเด่นหลัก

- ✅ **ฟรี**: ไม่มีค่าใช้จ่าย
- ✍️ **เซ็นถาวร**: แอปที่ติดตั้งไม่หมดอายุ
- 📱 **ติดตั้งบนเครื่อง**: ติดตั้งไฟล์ IPA บน iPhone ได้โดยตรง
- 🔓 **ไม่ต้องเจลเบรก**: ไม่ได้เจลเบรกระบบ

### 📱 เวอร์ชันที่รองรับ

| สถานะ | เวอร์ชัน iOS | หมายเหตุ |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | รองรับ |
| 🔴 | iOS `14.0 beta 1` และก่อนหน้า | ไม่รองรับ |
| 🔴 | iOS `16.7` – `16.7.11` | ไม่รองรับ |
| 🔴 | iOS `17.0.1` และใหม่กว่า | ไม่รองรับ |

> **💡 คำแนะนำ**: อย่าอัปเดต iOS เวอร์ชันที่ใหม่กว่าอาจทำให้เครื่องหลุดจากรายการนี้ แล้วจะติดตั้ง TrollStore ไม่ได้อีก

`16.7 RC` (บิลด์ 20H18) รองรับ ส่วน `16.7` ตัวจริงไม่รองรับ ตารางวิธีติดตั้งอ้างอิง [Installing TrollStore](https://ios.cfw.guide/installing-trollstore) ซึ่งระบุว่า `16.7.12` – `16.7.16` ไม่รองรับเช่นกัน

### 🔧 วิธีติดตั้งตามเวอร์ชันและชิป

หาเวอร์ชัน iOS ในคอลัมน์ซ้าย และหาชิปในแถวบน แล้วเปิดคู่มือของวิธีนั้น «ไม่เกี่ยวข้อง» หมายความว่าชิปนั้นรัน iOS เวอร์ชันนั้นไม่ได้ «ไม่รองรับ» หมายความว่า TrollStore ใช้ไม่ได้ในจุดนั้น

| จาก | ถึง | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | ไม่รองรับ | ไม่รองรับ | ไม่รองรับ |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | ไม่เกี่ยวข้อง |
| 16.0 beta 1 | 16.0 beta 5 | ไม่เกี่ยวข้อง | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | ไม่เกี่ยวข้อง | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | ไม่เกี่ยวข้อง | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | ไม่เกี่ยวข้อง | ไม่รองรับ | ไม่รองรับ |
| 17.0 beta 1 | 17.0 beta 4 | ไม่เกี่ยวข้อง | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | ไม่เกี่ยวข้อง | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | ไม่เกี่ยวข้อง | ไม่รองรับ | ไม่รองรับ |

ที่มา: [ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore)

### 📱 รุ่น iPhone และชิป

ใช้ตารางนี้เพื่อดูว่า iPhone ของคุณอยู่คอลัมน์ชิปใดด้านบน

| รุ่น | ชิป |
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

A17 Pro อยู่ในคอลัมน์ **A12–A17 / M1–M2** ไม่ได้ใส่ iPhone 16 ขึ้นไป เพราะออกมาพร้อม iOS ที่ TrollStore ไม่รองรับ

**รุ่น iPad**

| รุ่น | ชิป |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ เครื่องมือแนะนำ

### 🎙️ **TrollRecorder**

TrollRecorder เป็นเครื่องมืออัดเสียงการโทรสำหรับ TrollStore ไม่ต้องเจลเบรก ฟังก์ชันหลักใช้ได้ฟรี

**ดาวน์โหลด**: [GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed แสดงความเร็วอัปโหลดและดาวน์โหลดปัจจุบันบนแถบสถานะ

**ดาวน์โหลด**: [GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 ลิงก์

- 🌐 เว็บรวมทรัพยากร: [https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 ที่เก็บนี้: [https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ ข้อจำกัดความรับผิด

คู่มือนี้มีไว้เพื่อการศึกษาเท่านั้น ติดตั้งเฉพาะ IPA ที่คุณไว้ใจ คุณต้องรับผิดชอบแอปที่ติดตั้ง และปฏิบัติตามกฎหมายในพื้นที่ของคุณ
