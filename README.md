# Presentation Timer

Presentation Timer is a small Windows overlay timer for presentations.

It stays on top of your slides so you can keep track of the remaining time without interrupting your presentation flow. The timer is designed as a compact, borderless overlay that can be moved freely and switched between standard and compact display modes.

## Features

- Always-on-top overlay timer
- Borderless compact window
- Standard and compact display modes
- Drag-and-drop window positioning
- Start, pause, resume, and reset controls
- Minute and second time configuration
- Visual warning when the remaining time is low
- Strong time-up indication with a pulsing red highlight and `TIME UP` label
- Saved timer duration, warning threshold, display mode, topmost setting, and window position

## System Requirements

- Windows
- .NET Framework 4.8 Runtime

## Usage

1. Launch `PresentationTimer.exe`.
2. Set the timer duration using the minute and second fields.
3. Press the play button to start the timer.
4. Move the overlay to a position that does not cover important slide content.
5. Use pause, resume, or reset as needed.

When the timer reaches zero, the display changes to a clear time-up state so it is easier to notice during a presentation.

## Distribution

This repository distributes compiled binary releases only.

The source code is not published in this repository.

## License

Distributed binaries are proprietary software and are subject to the terms in BINARY-LICENSE.txt.

See [BINARY-LICENSE.txt](./BINARY-LICENSE.txt) for details.

---

# Presentation Timer

Presentation Timer は、プレゼン中に残り時間を確認するための Windows 向け小型オーバーレイタイマーです。

発表資料の上に常時表示できるため、プレゼンの流れを止めずに残り時間を確認できます。枠なしのコンパクトなオーバーレイとして動作し、表示位置の移動や通常モード・コンパクトモードの切り替えに対応しています。

## 主な機能

- 常時前面のオーバーレイタイマー
- 枠なしの小型ウィンドウ
- 通常モードとコンパクトモードの表示切り替え
- ドラッグによる表示位置の移動
- 開始、一時停止、再開、リセット操作
- 分・秒による時間設定
- 残り時間が少なくなったときの視覚的な警告表示
- タイムアップ時の赤いパルス演出と `TIME UP` 表示
- タイマー時間、警告閾値、表示モード、常時前面設定、ウィンドウ位置の保存

## 動作環境

- Windows
- .NET Framework 4.8 Runtime

## 使い方

1. `PresentationTimer.exe` を起動します。
2. 分・秒の入力欄でタイマー時間を設定します。
3. 再生ボタンを押してタイマーを開始します。
4. 発表資料の邪魔にならない位置へオーバーレイを移動します。
5. 必要に応じて、一時停止、再開、リセットを行います。

残り時間が 0 になると、タイムアップに気づきやすいように表示が強調されます。

## 配布について

このリポジトリでは、ビルド済みバイナリのみを配布しています。

このリポジトリではソースコードは公開していません。

## ライセンス

Distributed binaries are proprietary software and are subject to the terms in BINARY-LICENSE.txt.

詳細は [BINARY-LICENSE.txt](./BINARY-LICENSE.txt) を参照してください。