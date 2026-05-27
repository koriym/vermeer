# フェルメールの作品（来日履歴付き）

フェルメール作品一覧を、画像・作品ページリンク・来日履歴・出典リンク付きでまとめた静的HTMLページです。

## 公開URL

- https://koriym.github.io/vermeer/
- https://github.com/koriym/vermeer

## ファイル

- `vermeer.html` — メインページ。作品一覧、画像、作品ページリンク、来日履歴を掲載。
- `sources.html` — 来日履歴の出典一覧。
- `vermeer.md` — Markdown版の作品一覧。
- `vermeer.alps.json` — ALPSプロファイル。
- `vermeer.alps.html` — ALPSプロファイルから生成したHTML。

## 見る方法

ブラウザで `vermeer.html` を開きます。

```bash
open vermeer.html
```

## リンク仕様

- 作品名をクリックすると、対応するWikipedia作品ページへ移動します。
- 画像をクリックすると、Wikimedia Commons上のフルサイズ画像へ移動します。
- 来日履歴の `[出典]` をクリックすると、`sources.html` の該当出典へ移動します。

## ALPS

`vermeer.html` は以下でALPSプロファイルを参照しています。

```html
<link rel="profile" href="vermeer.alps.json">
```

ALPSのHTML表現は公式仕様に合わせ、独自の `data-alps-*` 属性ではなく、`class` 属性で意味名を示しています。

## ライセンス

このリポジトリ内のHTML・Markdown・ALPSファイルはMIT Licenseで公開します。外部リンク先の画像、Wikipedia本文、各出典ページの内容は、それぞれの提供元のライセンスに従います。
