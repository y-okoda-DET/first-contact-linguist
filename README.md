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
| _headers | Cloudflare Pages 用の設定（キャッシュなど） |
| robots.txt | 検索エンジン向けの設定 |

## 公開先のURLについて

`index.html` には、公開先を `https://first-contact-linguist.pages.dev/` として書き込んであります。
Cloudflare Pages のプロジェクト名を `first-contact-linguist` にすれば、書き換えは不要です。

プロジェクト名やドメインを変える場合は、`index.html` の中の `https://first-contact-linguist.pages.dev/` を、すべて新しいURLに置き換えてください（4か所）。
