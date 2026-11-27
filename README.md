# 神 TAIKO CONNECTOR — WiiタタコンをPCで使うWindows用ツール

Wii用タタコンを、WiiリモコンとBluetooth経由でWindowsのキーボード入力として使う無料ユーティリティです。

**Free Windows utility for using a Wii TaTaCon as keyboard input via a Wii Remote and Bluetooth.**

Wii用の太鼓型コントローラーをWindows 10/11で活用したい方向け。ドン・カッの4箇所をキーボードのキーに割り当て、キーボード操作対応のゲームで利用できます。無料・広告なしの非公式ツールです。

## Download / ダウンロード

**[ダウンロード / Download (Releases)](https://github.com/TakaLabo-Official/God-Taiko-Connector/releases/latest)**

リリースページの Assets にある `God_Taiko_Connector_v0.3.3.zip` をダウンロードし、展開して `GodTaikoConnector.exe` を起動してください。インストールやビルドは不要です。

Download `God_Taiko_Connector_v0.3.3.zip` under Assets, extract it, and run `GodTaikoConnector.exe`. No installation or build is required.

GitHub が自動生成する Source code (zip / tar.gz) はアプリ本体ではありません。
GitHub's automatically generated Source code archives are not the application.

[v0.3.3 ZIPを直接ダウンロード / Direct download](https://github.com/TakaLabo-Official/God-Taiko-Connector/releases/download/v0.3.3/God_Taiko_Connector_v0.3.3.zip)

SHA-256: `98ac210ca24315a771a23e39e11cf14a3e10ebe7ddeb9af40c57fa230f3addf2` (GitHub release asset digest)

## What's new in v0.3.3 / 更新内容

正式ブランド・著作権・公式リンク・バージョン情報画面・同梱説明書を更新し、アイコンの無線通信マークを一般的な図柄に変更しました。既存の入力機能・設定は維持しています。

Updated branding, copyright, official links, About dialog, documentation and generic wireless icon. Existing input functionality and settings are retained.

旧版をトレイから完全終了し、設定をバックアップしてから新版を別フォルダに展開してください。 / Exit the old version from the system tray, back up settings and extract the new version to a separate folder.

## Features / 主な機能

- 標準Bluetoothによる接続 / Windows Bluetooth connection
- 4箇所の打撃判定、キー割当の変更 / Four hit zones, configurable keys
- 打撃表示・入力間隔の計測 / Hit visualization and report interval statistics
- 2プレイヤー対応設計 / Designed for two players
- ゲーム別プロファイル / Game profiles
- 自動再接続・タスクトレイ常駐 / Reconnection and system tray
- 10言語対応 / 10 UI languages

## Requirements / 動作環境

Windows 10 / 11、標準Bluetooth、.NET Framework 4.x、純正Wiiリモコン、Wii用タタコン。
機器構成によって動作が異なります。WiiリモコンPlusと2台同時接続は実機未検証です。

Windows 10 / 11, Bluetooth, .NET Framework 4.x, a genuine Wii Remote and Wii TaTaCon. Compatibility may vary by hardware. Wii Remote Plus and simultaneous two-player use require further testing.

## Quick start / 接続方法

1. タタコンをWiiリモコンにつなぎ、PCのBluetoothをONにする。
2. アプリの「接続（1＋2）」を押し、リモコンの1と2を同時押しする。
3. タタコンの認識を確認し、「入力 ON/OFF」を押してゲームを前面にする。
4. ゲームのキー割当を合わせる（標準P1：D / F / J / K）。

Attach the drum, enable Bluetooth, click Connect (1+2), and press 1 and 2 on the Wii Remote. Enable input, focus the game and configure matching keys (default P1: D/F/J/K).

詳細は同梱のREADME.txtを参照してください。未署名のためWindows SmartScreenの警告が出ることがあります。正規配布元とハッシュを確認し、セキュリティソフトで検査してください。
See the included README.txt for details. Windows SmartScreen may warn because the executable is unsigned. Verify the official download source and checksum, and scan the file with security software.

## よくある質問 / FAQ

[WiiタタコンをWindows PCに接続する方法・トラブル対処（日本語）](docs/wii-tatacon-windows.md)

- **WiiのタタコンはPCに直接つなぐ？** タタコンをWiiリモコンにつなぎ、リモコンをPCにBluetooth接続します。
- **WiiリモコンPlusや2台同時接続は使える？** 実機未検証です。すべての機器・ゲームでの動作は保証していません。
- **ドン・カッを好きなキーに変更できる？** キー割当を変更してゲーム別プロファイルに保存できます。
- **接続できない場合は？** 電池・Bluetooth・接続操作を確認してください。詳しい手順は上記ガイドと同梱READMEをご覧ください。

## 関連機器 / Related hardware

**Amazon広告 / Ad**

- [TP-Link UB500 USB Bluetoothアダプター](https://www.amazon.co.jp/dp/B098K3H92Z/ref=nosim?tag=takalabo-22) — Windows PC向けUSB Bluetoothアダプター。
- [パナソニック エネループ 単3形4本・充電器セット K-KJ83MCD40](https://www.amazon.co.jp/dp/B0BY8VB78K/ref=nosim?tag=takalabo-22) — Wiiリモコン用の充電池・充電器。
- [任天堂 純正Wiiリモコン RVL-003](https://www.amazon.co.jp/s?k=Wii%E3%83%AA%E3%83%A2%E3%82%B3%E3%83%B3%20%E7%B4%94%E6%AD%A3%20RVL-003&tag=takalabo-22) — Amazonの商品検索。
- [Wii用 太鼓とバチ（タタコン）](https://www.amazon.co.jp/s?k=%E5%A4%AA%E9%BC%93%E3%81%AE%E9%81%94%E4%BA%BA%20Wii%20%E5%A4%AA%E9%BC%93%E3%81%A8%E3%83%90%E3%83%81%20%E3%82%BF%E3%82%BF%E3%82%B3%E3%83%B3&tag=takalabo-22) — Amazonの商品検索。

Amazonのアソシエイトとして、Taka Laboは適格販売により収入を得ています。
As an Amazon Associate, Taka Labo earns from qualifying purchases.

## Support / 開発支援

開発者 / Developer: **Taka Labo**

- 公式X / Official X: [@TakaLabo_](https://x.com/TakaLabo_)
- お問い合わせ / Contact: [takalabo.support@gmail.com](mailto:takalabo.support@gmail.com)

[Buy Me a Coffee](https://buymeacoffee.com/takalabo) — 任意の支援 / Optional support

本アプリは非公式の無料・広告なしのツールです。ソースコードは非公開です。開発支援は任意です。
This is an unofficial, free and ad-free utility. Source code is not publicly distributed. Donations are optional.

ソフトが役立ったら、任意の[開発支援（Buy Me a Coffee）](https://buymeacoffee.com/takalabo)をご検討ください。支援なしでも利用できます。

ほかのTaka Labo製品：[神 DOWNLOADER — Windows向け動画・再生リスト保存管理ツール](https://github.com/TakaLabo-Official/God-Downloader)

Copyright © 2026 Taka Labo. All rights reserved.
