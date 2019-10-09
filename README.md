# Sora Unity SDK

**現在開発中で、公開は 2019 年 10 月末を予定しています**

Sora Unity SDK は WebRTC SFU Sora の Unity クライアントアプリケーションを開発するためのライブラリです。

## 対応予定機能

- カメラから映像を取得し Sora で配信
- カメラから映像を取得し Unity アプリに出力
- マイクから音声を取得し Sora で配信
- マイクから音声を取得し Unity アプリに出力
- マルチストリームへの対応
- シグナリング通知への対応
- サイマルキャスト対応
- ソフトウェアエンコード/デコード VP8 / VP9 への対応
    - ソフトウェアエンコード/デコードの H.264 へは非対応
- Opus への対応

## 対応予定プラットフォーム

- Windows 10 x86_64
- Windows 10 ARM64
- macOS x86_64

## オープンソースでの公開を前提とした有償による機能追加

**これら機能は継続的なメンテナンスの対象外となり、メンテナンスは有償での対応となります**

### NVIDIA NVENC を利用したハードウェアエンコーダ対応

- H.264 のハードウェアエンコードへの対応

### NVIDIA NVDEC を利用したハードウェアデコーダ対応

- VP8 のハードウェアデコードへの対応
- VP9 のハードウェアデコードへの対応

### AMD 対応

**TBD**

### INTEL 対応

**TBD**

### iOS 対応

### Android 対応

## About Support

Support for Sora Unity SDK by Shiguredo Inc. are limited
**ONLY in JAPANESE** through GitHub issues and there is no guarantee such
as response time or resolution.

## サポートについて

Sora Unity SDK に関する質問・要望・バグなどの報告は Issues の利用をお願いします。
ただし、 Sora のライセンス契約の有無に関わらず、 Issue への応答時間と問題の解決を保証しませんのでご了承ください。

Sora Unity SDK に対する有償のサポートについては現在提供しておりません。

## ライセンス

Apache License 2.0

```
Copyright 2018-2019, Shiguredo Inc, melpon and kdxu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
