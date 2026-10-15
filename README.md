# tukuruapps の公式サイト（GitHub Pages 用）

アプリのプライバシーポリシー・利用規約と、AdMob の app-ads.txt を置くためのサイトです。
公開すると次のURLになります（GitHub のユーザー名が `tukuruapps` の場合）。

| ページ | URL |
|---|---|
| トップ（Play Console の「ウェブサイト」に登録） | https://tukuruapps.github.io/ |
| エイリアン探し プライバシーポリシー | https://tukuruapps.github.io/alienfinder/privacy.html |
| エイリアン探し 利用規約 | https://tukuruapps.github.io/alienfinder/terms.html |
| app-ads.txt | https://tukuruapps.github.io/app-ads.txt |

## 公開のしかた
1. GitHub アカウントを作る（ユーザー名 `tukuruapps`、メールは tukuruapps@gmail.com）。
2. 新しいリポジトリを作る。名前は必ず `tukuruapps.github.io`（Public）。
3. 「Add file → Upload files」で、このフォルダの中身（index.html・app-ads.txt・alienfinder フォルダ）をドラッグしてアップロード。
4. 数分待って https://tukuruapps.github.io/ を開き、表示されれば完了。

## app-ads.txt
AdMob に登録したら、`pub-0000000000000000` を自分のパブリッシャーID（AdMob の「設定」→「アカウント情報」）に置き換えて、もう一度アップロードする。

## アプリを増やしたら
`alienfinder` フォルダをコピーして名前を変え、index.html にリンクを追加する。
規約・ポリシーの本文は、アプリ本体（index.html の docHTML）から作り直したものを使う。
