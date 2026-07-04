# wamii — Portfolio

[https://wamiiiiiii.github.io](https://wamiiiiiii.github.io)

Python・GAS・Claude Code を使った業務自動化を専門とする、フリーランスエンジニアのポートフォリオサイトです。

## サイト構成

- **Capabilities** — Web スクレイピング / データ加工・集計 / ブラウザ操作自動化 / GAS連携 / AI組み込み / ツール開発
- **Selected Work** — 納品済み実案件、出品中サービス、技術検証の制作例（クリックで詳細モーダル表示）
- **Approach** — 受注〜納品の進め方
- **Services** — ココナラ出品中のサービスメニュー
- **Contact** — CrowdWorks / ココナラへの導線

## 技術構成

- 素の HTML / CSS / JavaScript（ビルド不要・フレームワーク不使用）
- フォント: [Inter](https://fonts.google.com/specimen/Inter) / [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) / Noto Sans JP（Google Fonts）
- GitHub Pages でホスティング（`main` ブランチ直下の `index.html` を配信）

## ローカルで確認する

ビルド手順は不要です。`index.html` をブラウザで直接開くか、簡易サーバーを立てて確認してください。

```bash
git clone https://github.com/wamiiiiiii/wamiiiiiii.github.io.git
cd wamiiiiiii.github.io
python3 -m http.server 8000
# http://localhost:8000 を開く
```

## 更新方法

`index.html` を直接編集して `main` ブランチに push すると、GitHub Pages に自動反映されます。
