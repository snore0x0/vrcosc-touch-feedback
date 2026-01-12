# Touch Feedback (VRCOSC Module)
## 🇯🇵 日本語

### 概要
**Touch Feedback** は、VRChat 内でのアバター同士の接触を検知し、  
**PCVR コントローラの振動（触覚フィードバック）**として再現する  
**VRCOSC 用モジュール**です。

- アバター接触 → 手元に振動
- 心音（Heartbeat）と身体接触（Body）を自動判別
- 強度が大きい方のみを振動として出力
- VRChat 側スライダーで振動の大きさを調整可能
- 左右コントローラ対応

---

### 必須環境
- Windows PC
- **VRChat（PCVR）**
- **SteamVR**
- **VRCOSC v2025.1216.0 以上**

#### 非対応
- Quest 単体（スタンドアロン）
- VRChat 公式機能のみでの使用

---

### 動作仕様
- 左右のコントローラは独立して振動
- **心音 / 身体接触は同時に発生しません**
  - 強度が大きい方を自動的に採用
- Attack / Release による自然なフェード付き振動
- SteamVR（OpenVR）の振動機能を使用

#### 接触判定部位

- **心音フィードバック**：アバターの胴体部への接触で発生します
- **身体接触フィードバック**：頭部・両手・両足への接触で発生します

---

### 注意事項
- 本ツールは VRChat 非公式の拡張機能です
- 振動の体感はコントローラ機種により異なります
- VRCOSC / SteamVR の仕様変更により動作しなくなる可能性があります

---

## 🇺🇸 English

### Overview
**Touch Feedback** is a **VRCOSC module** that converts  
**VRChat avatar contact and heartbeat parameters into controller haptics** for PCVR.

- Avatar contact → controller vibration
- Automatically selects **body touch or heartbeat** (stronger one wins)
- Adjustable vibration strength via VRChat sliders
- Independent left / right controller support

---

### Requirements
- Windows PC
- **VRChat (PCVR)**
- **SteamVR**
- **VRCOSC v2025.1216.0 or later**

#### Not Supported
- Quest standalone
- VRChat official features only

---

### Behavior
- Left and right controllers vibrate independently
- **Body and heartbeat vibrations never play at the same time**
  - The stronger signal is automatically selected
- Smooth fade-in / fade-out (attack & release)
- Uses SteamVR (OpenVR) haptics

#### Contact Areas

- **Heartbeat feedback**: Triggered by contact with the avatar’s torso area
- **Body contact feedback**: Triggered by contact with the head, both hands, and both feet

---

### Disclaimer
- This is an unofficial VRChat extension
- Vibration intensity depends on controller hardware
- Future VRCOSC / SteamVR updates may affect compatibility

---

## Credits
- VRCOSC
- VRChat
- SteamVR / OpenVR

---

## License

MIT License

---

## Author

snore0x0

---

## Changelog
### v1.0.0
- Initial release
