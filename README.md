# ひとナビ LP

社員プロフィール管理SaaS「ひとナビ」のランディングページです。

ひとナビは、社員プロフィール、スキル、部署、稼働状況、プロジェクト情報を組織単位で一元管理し、AIチャットで人材検索やアサイン候補の確認まで行えるWebアプリです。このLPは、デモ誘導とポートフォリオ掲載を目的に制作しています。

## 概要

- サービス名: ひとナビ
- メインコピー: 社員情報を、探せる人材データベースへ。
- 目的: デモ誘導、GitHub/ポートフォリオ掲載
- トーン: 業務SaaS寄りの落ち着いた信頼感

## 主な訴求

- 社員情報を一箇所に集約し、検索・閲覧・更新の手間を減らす
- スキル、部署、プロジェクト、稼働状況から必要な人材を探しやすくする
- 社員自身がプロフィールを更新し、管理者は承認と品質管理に集中できる
- AIチャットで「Reactが得意で今動ける人は？」のような自然言語検索ができる
- Googleログインと組織単位のデータ分離で安全に運用できる

## ページ構成

`src/pages/index.astro` で以下のセクションを読み込んでいます。

1. Hero
2. Problem
3. Solution
4. Features
5. Use Cases
6. Security / Architecture
7. CTA

## 技術スタック

- Astro 6
- TypeScript
- Tailwind CSS v4
- Vercel adapter

## ディレクトリ構成

```text
/
├── public/                  # 画像、faviconなどの静的アセット
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   └── sections/        # LP各セクション
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── LPsetting.md             # LP制作ブリーフ
├── astro.config.mjs
└── package.json
```

## セットアップ

Node.js 22.12.0 以上を使用します。

```sh
npm install
```

## 開発

```sh
npm run dev
```

ローカル開発サーバーは通常 `http://localhost:4321` で起動します。

## ビルド

```sh
npm run build
```

本番用ファイルは `dist/` に生成されます。

## プレビュー

```sh
npm run preview
```

## デプロイ

Vercel adapter を利用しています。Vercel に接続してデプロイする想定です。

## 差し替え予定

- デモURL
- GitHubリポジトリURL
- お問い合わせ先
- 本番用スクリーンショット
- 正式ロゴ/アイコン
