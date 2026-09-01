# ChoiTimer v1.0.0 リリースノート

## 概要

ChoiTimer v1.0.0は、デスクトップ上で邪魔になりにくいWindows向けタイマー／ストップウォッチの初回リリースです。

## 主な機能

- 分・秒指定のカウントダウンとアプリ内終了通知音
- `00:00.00`形式のストップウォッチ
- コンパクトな通常表示と常に最前面のミニ表示
- 前回使用したタイマー設定の復元
- Enter／Space／Escのキーボード操作

## 配布ファイル

- `ChoiTimer.exe`: Windows x64 self-contained single-file版
- サイズ: 63,401,969 bytes
- SHA-256: `3A5FEBC3B207A46286C9E4DBB1B11014117A45C9EEF6B102E0C159175187C8A0`

## 動作環境

- Windows 10 / 11（x64）
- .NETランタイムの別途インストールは不要

## インストール

任意のローカルフォルダへ`ChoiTimer.exe`を保存して実行してください。

## 既知の注意点

- コード署名を行っていない場合、Windows SmartScreenの警告が表示される可能性があります。
- 設定は`%LocalAppData%\ChoiTimer\settings.json`に保存されます。

