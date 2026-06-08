# quiz-app

一般常識クイズアプリ。HTML/CSS/JavaScriptのみで構成されたフロントエンドアプリケーション。

## 技術スタック

- **HTML** — マークアップ・構造
- **CSS** — スタイリング
- **JavaScript** — ゲームロジック・DOM操作

バックエンド・ビルドツール・フレームワーク不使用。ブラウザで直接 `index.html` を開いて動作する。

## プロジェクト構成

```
quiz-app/
├── index.html       # エントリーポイント
├── style.css        # スタイル
├── script.js        # クイズロジック
└── questions.js     # 問題データ（または questions.json）
```

## 開発方針

- 外部ライブラリ・フレームワークは使用しない（バニラJS）
- `index.html` をブラウザで開くだけで動作すること
- モバイル対応（レスポンシブデザイン）を意識する

## アプリの主な機能

- 問題の表示・選択肢の提示
- 回答の正誤判定
- スコアの集計・結果表示

## GitHubリポジトリ

https://github.com/kotaronoadress3-cloud/quiz-app
