# Seamtile

写真から継ぎ目のないリピート素材（テクスチャ・ノーマルマップ・高さマップ）を作る Mac アプリです（無料）。
Seamtile makes seamless repeating textures, normal maps and height maps from photos. Free.

製品ページ / Website: https://www.ultrawarp.jp/seamtile/ ・ [English](https://www.ultrawarp.jp/seamtile/en/)

## ダウンロード / Download

[最新のリリース / Latest release](https://github.com/satoo3/Seamtile-releases/releases/latest) から `Seamtile-<version>-mac.zip` をダウンロードし、
出てきた Seamtile.app を「アプリケーション」フォルダに入れてください。

Download `Seamtile-<version>-mac.zip` from the [latest release](https://github.com/satoo3/Seamtile-releases/releases/latest)
and move Seamtile.app to your Applications folder.

- macOS 11 Big Sur 以降、Apple シリコン搭載の Mac / macOS 11 or later on Apple silicon
- Apple の公証済み / Notarized by Apple

## App Store 版との違い / Differences from the App Store version

ここで配っている版では、アプリの機能に加えて**コマンドラインからの一括処理**が使えます。
App Store 版は App Store の決まり（サンドボックス）により、コマンドラインからは使えません。

This version also supports **batch processing from the command line**.
The App Store version cannot be used from the command line because of App Store sandboxing rules.

```bash
# seamtile コマンドを使えるようにする / Make the seamtile command available
mkdir -p ~/.local/bin && ln -sf /Applications/Seamtile.app/Contents/MacOS/Seamtile ~/.local/bin/seamtile

# 使い方 / Usage
seamtile --help
seamtile --cli -d out photos/*.jpg
```

## お問い合わせ / Contact

support@ultrawarp.jp

このリポジトリは配布専用です（ソースコードは含みません）。
This repository is for distribution only and does not contain source code.
