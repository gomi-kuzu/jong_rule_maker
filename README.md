# 麻雀ルールメーカー

静的な 1 ページ構成の Web アプリです。
公開ページ：https://gomi-kuzu.github.io/jong_rule_maker/

## ローカル確認

`index.html` をブラウザで直接開くだけで動作確認できます。

## 補足

- `.github/workflows/deploy-pages.yml` は静的ファイルをそのまま GitHub Pages に配備します。
- `.nojekyll` により、GitHub Pages 側の Jekyll 処理を無効化します。
- 現状は CDN から `html2canvas` を読み込んでいるため、外部 CDN に接続できる環境で動作します。

## ライセンス

このプロジェクトは MIT License で公開しています。改変、再配布、商用利用を含めて 2 次利用可能です。詳細は `LICENSE` を参照してください。