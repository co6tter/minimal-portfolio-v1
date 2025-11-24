# minimal-portfolio-v1

## Overview

夏をモチーフにしたミニマルなポートフォリオサイトです。IntersectionObserverを使ったスクロールアニメーション、ネストCSSによるスタイリング、GitHub Actionsによる自動デプロイ機能を実装しています。

## Tech Stack

- **HTML5**: セマンティックなマークアップ
- **CSS3**: Nested CSS、アニメーション
- **Vanilla JavaScript**: IntersectionObserver API によるスクロールアニメーション
- **GitHub Actions**: GitHub Pagesへの自動デプロイ

## Setup

このプロジェクトはシンプルな静的サイトです。セットアップは不要です。

```bash
# リポジトリをクローン
git clone <repository-url>
cd minimal-portfolio-v1
```

## Usage

ローカルで確認する場合は、[index.html](index.html) をブラウザで開くか、ローカルサーバーを起動してください。

```bash
# Python 3を使用する場合
python3 -m http.server 8000

# Node.jsのhttp-serverを使用する場合
npx http-server
```

ブラウザで `http://localhost:8000` にアクセスしてください。

### 自動デプロイ

mainブランチへのプッシュで、GitHub Actionsが自動的にGitHub Pagesへデプロイします。

## Directory Structure

```
minimal-portfolio-v1/
├── index.html              # メインHTML
├── css/
│   └── style.css          # スタイルシート
├── js/
│   └── main.js            # IntersectionObserver実装
├── img/                   # 画像ファイル
│   ├── person.png
│   ├── ice.jpg
│   ├── beach.jpg
│   ├── hiyashi-chuka.jpg
│   ├── speech.svg
│   └── photo.svg
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions設定
├── favicon.ico            # ファビコン
├── apple-touch-icon.png   # Appleタッチアイコン
├── android-chrome-*.png   # Android用アイコン
├── site.webmanifest       # Webマニフェスト
└── README.md
```

## License

This repository is for personal/private use only.
