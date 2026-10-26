# Winter Campus Expo — Campus Guide

滋賀大学彦根キャンパスで開催予定の **Winter Campus Expo** 向け来場者案内サイトです。

## 公開までの手順

1. GitHub リポジトリの **Settings → Pages** を開く
2. **Build and deployment → Source** を **GitHub Actions** にする
3. **Actions** タブで `Deploy campus map to GitHub Pages` の実行結果を確認する
4. 公開後の想定URL: https://minato-ai-dev.github.io/WinterCampusExpo_SchoolMap/

※公開URLはGitHub Pagesが有効化され、デプロイが成功してからアクセスできます。

## 主な機能

- 大学公式の彦根キャンパスマップ PDF の埋め込みと別画面表示
- 講堂（公式マップNo.1）の強調
- 16施設の検索、カテゴリ絞り込み、施設説明
- モバイル対応、Googleマップ／交通アクセスへのリンク
- フレームワーク・ビルド作業なしの静的HTML

## 編集方法

`index.html` を編集してください。公開後は main ブランチへのpushで自動更新されます。

**イベント情報について**：2026年12月2日17:00の予定表記です。会場内の受付場所、出演団体、当日の入構動線、催しの最終時刻は未確定のため記載していません。確定後に追記してください。

**構内図・施設名の出典**：滋賀大学公式 https://www.shiga-u.ac.jp/information/campus-access/campusmap/

公式PDFは大学サイトのURLを参照しています。大学のサイトが外部埋め込みを制限する環境では、サイトの「地図を別画面で開く」を使用してください。施設番号からマップ内の位置を確認する方式であり、GPS誘導や屋内ナビゲーションではありません。

本サイトはイベント主催側が作成した非公式の案内サイトです。
