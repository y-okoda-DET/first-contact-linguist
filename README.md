# ファーストコンタクト・リンギスト

言葉の通じない8つの来訪者と対話する、言語学の謎解きゲーム。
1枚のHTMLで動くので、ビルドは不要です。

## ファイル

| ファイル | 役割 |
|---|---|
| index.html | ゲーム本体 |
| og-image.png | Xなどに出るカード画像（1200×630） |
| favicon-32.png | ブラウザのタブのアイコン |
| apple-touch-icon.png | スマホのホーム画面に追加したときのアイコン |
| _headers | Cloudflare 用の設定（キャッシュなど） |
| wrangler.jsonc | Cloudflare Workers に「このフォルダをそのまま公開する」と伝える設定 |
| .assetsignore | 公開しないファイルの一覧（設定ファイルとREADME） |
| robots.txt | 検索エンジン向けの設定 |

## 公開先のURLについて

`index.html` には、公開先を `https://first-contact-linguist.yhiokd.workers.dev/` として書き込んであります。
独自ドメインなどに変える場合は、`index.html` の中のこのURLを、すべて新しいURLに置き換えてください（4か所）。
