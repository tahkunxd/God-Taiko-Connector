# WiiのタタコンをWindows PCで使う方法 — Bluetooth接続とキー割当

神 TAIKO CONNECTOR は、Wii用タタコンをWiiリモコン経由でPCにつなぎ、ドン・カッをキーボード入力として使うための無料・広告なしの非公式ツールです。

[最新版をダウンロード](https://github.com/TakaLabo-Official/God-Taiko-Connector/releases/latest) ｜ [機能・動作環境](../README.md)

## 必要なもの

- Windows 10 / 11のPC、.NET Framework 4.x、Windows標準Bluetooth
- 純正WiiリモコンとWii用タタコン

WiiリモコンPlusや2台同時接続は実機未検証です。ほかの機種・すべてのゲームでの動作を保証するものではありません。

## BluetoothでタタコンをPCにつなぐ

1. 最新版のReleaseのAssetsから配布ZIPをダウンロードし、すべて展開します。自動生成のSource codeではありません。
2. タタコンをWiiリモコンに接続し、PCのBluetoothをONにします。
3. GodTaikoConnector.exeを起動します。
4. アプリの「接続（1＋2）」を選び、Wiiリモコンの1と2を同時に押します。SYNC接続を使う場合はアプリの「SYNC接続」を選んでからSYNCボタンを押します。
5. 4箇所を叩き、ドン（赤）・カッ（青）の反応を確認します。

## 太鼓の打撃をキーボード入力にする

ゲーム側を次の標準キーに合わせ、「入力 ON/OFF」で入力を有効にしてゲームを前面にします。

| | 左カッ | 左ドン | 右ドン | 右カッ |
|---|---|---|---|---|
| P1 | D | F | J | K |
| P2（設計上） | C | V | B | N |

キーは変更でき、ゲーム別のプロファイルとして保存できます。2台同時の実機確認は未実施です。

## Wiiリモコンが接続できない・反応しない場合

電池・Bluetooth・タタコンの接続を確認し、1＋2またはSYNC接続をやり直します。必要ならWindowsのBluetooth設定から対象のWiiリモコンの登録を削除して再接続します。接続時に未接続のWiiリモコンの登録を整理するため、ほかのWiiリモコンも再登録が必要になる場合があります。

ゲーム側で入力を受け取れないときは、入力が有効か、ゲームが前面にあるか、キー設定が一致しているかを確認してください。ゲームが管理者権限で動作している場合はキーを送信できないことがあります。

未署名のためWindowsの警告が出る場合があります。正規配布元とREADME掲載のハッシュを確認し、セキュリティソフトで検査してください。診断ログを共有する前には個人情報や機器識別情報を伏せてください。

細かな設定・更新方法は同梱README.txtを参照してください。

[公式ダウンロード](https://github.com/TakaLabo-Official/God-Taiko-Connector/releases/latest) ｜ [お問い合わせ](mailto:takalabo.support@gmail.com) ｜ [任意の開発支援](https://buymeacoffee.com/takalabo)

Copyright © 2026 Taka Labo. All rights reserved.
