# FSY 管理ページ付きパッケージ

## 含まれるファイル
- `index.html` 表示用ページ
- `admin.html` 管理ページ
- `data.json` 編集対象データ
- `.nojekyll`

## 運用方法
1. この4ファイルを GitHub Pages リポジトリへアップロード
2. `admin.html` を開く
3. プログラム名、時間、説明を編集
4. `Export data.json` を押してダウンロード
5. GitHub 上の `data.json` をその新しいファイルで置き換える
6. 数十秒〜数分後に `index.html` 側へ反映

## 重要
GitHub Pages は静的サイトなので、管理ページから公開中サイトを直接保存更新はできません。
必ず最後に `data.json` の差し替えが必要です。
