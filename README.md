# ながらノート 公式サイト

外部アプリのPiP動画を見ながらメモするiPhoneアプリ「ながらノート」の公式サイトです。

- 運営者：DAI
- お問い合わせ：dai.apps.support+nagaranote@gmail.com
- 公式サイト：https://daiai20240901.github.io/nagaranote-site/

## 構成

- index.html：紹介・機能・スクリーンショット・使い方・無料版とPro
- support.html：サポート・FAQ・お問い合わせ
- privacy.html：プライバシーポリシー
- terms.html：利用規約
- assets/css/style.css：共通スタイル
- assets/images/：アプリアイコン・実際のApp Store画像の軽量版
- .nojekyll：静的ファイルをそのまま配信

HTML/CSSのみの静的サイトで、追加ライブラリ・ビルドは不要です。アクセス解析は導入していません。

## ローカル確認

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

http://127.0.0.1:8765/ を開きます。

## 公開と更新

GitHub Pagesでmainブランチのルートを公開します。本文・FAQは各HTML、配色やレイアウトは共通CSSを編集してください。ヘッダー・フッターは4ページ共通の内容に保ちます。画像を差し替えた際はaltも更新します。

App Store公開後、ホームの「App Store 公開準備中」を確定したストアURLへのリンクに更新します。アプリの情報取扱いに変更があった場合はプライバシーポリシー・更新日も見直します。

このリポジトリには公式サイトのファイルだけを含めます。アプリのソース、認証情報、ローカルの検証資料は含めません。

© 2026 DAI
