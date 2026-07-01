# AIVERSE SLOT ENGINE

店舗向けデジタル抽選システム用のスロットゲームエンジンです。

## GitHub Pagesでの使い方

このフォルダの中身をGitHubリポジトリのルートへアップロードしてください。

必要な構成:

- `index.html`
- `LASPA-PREMIUM-SLOT/assets/laspa-premium-slot-official-frame.png`
- `LASPA-PREMIUM-SLOT/reels/*.png`
- `.nojekyll`

GitHub Pagesは `index.html` をトップページとして表示します。
画像パスは相対パスなので、上記フォルダ構成を維持してください。

## 注意

- ゲームロジック、抽選確率、チケット保存、1日1回制限は `index.html` 内に保持されています。
- 画像ファイル名やフォルダ構成を変更すると、GitHub Pages上で画像が表示されない場合があります。
- DEMO液晶は `#demoLcdContent` に後から動画、GIF、PNG、Canvas等を表示する想定です。