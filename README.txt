SGフラッシュカード（GitHub Pages 用）

ファイル
- index.html : フラッシュカード本体（同じフォルダの cards.tsv を自動読み込み）
- cards.tsv  : 用語データ（タブ区切り）
  - 2列：表[TAB]裏
  - 3列：表[TAB]裏[TAB]タグ（任意）

GitHub Pages 公開手順（最短）
1) GitHubで新規リポジトリ作成
2) index.html と cards.tsv をリポジトリのルートにアップロードしてCommit
3) Settings → Pages
4) Source: Deploy from a branch
5) Branch: main / Folder: /(root) → Save
6) “Visit site” で表示確認

URL例：
https://<GitHubユーザー名>.github.io/<リポジトリ名>/
