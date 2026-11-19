# ゼミ図鑑（zemi-app）

宮城学院女子大学 現代ビジネス学科のゼミ紹介サイトです。`index.html` 1枚で動きます。

## VS Code でローカル確認
1. VS Code で、このフォルダ（zemi-app）を開く（ファイル → フォルダーを開く）。
2. 拡張機能「Live Server」を入れる。
3. `index.html` を右クリック → 「Open with Live Server」。

## VS Code から GitHub Pages で公開（無料）
1. VS Code 左の「ソース管理」（枝分かれのアイコン）を開く。
2. 「リポジトリを初期化する」→ 変更をすべてステージ → メッセージを入れて「コミット」。
3. 「Publish Branch」（または「GitHub に公開」）を押し、リポジトリ名を `my-first-app`、Public を選ぶ。初回は GitHub へのサインインを求められます。
4. GitHub のリポジトリページ → Settings → Pages → Branch を `main`、フォルダを `/ (root)` にして Save。
5. 1〜2分後、`https://（あなたのユーザー名）.github.io/my-first-app/` で見られます。

更新するときは、`index.html` を直して、ソース管理で「コミット」→「同期」を押すだけです。

## 注意
- この公開版は、編集内容が「その人のブラウザ」にしか保存されません。みんなに見せる変更は、`index.html` を直して公開し直してください。
- 編集パスワードはページ内のコードに入っているため、強いセキュリティではありません。
- `robots.txt` で検索エンジンに載らないようにしています（URLを知っていれば誰でも開けます）。
