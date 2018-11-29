# gh-pages

読んだ本の感想とかまとめていきます。

https://nsgeorge.github.io/gh-pages/

# Tips

## imageの作り方（

#### svgで作る

 1. keynoteでイメージを作る
 1. PDFで出力する
 1. PDFを編集して欲しい画像だけになるようにする
 1. [convert pdf to anything - CloudConvert](https://cloudconvert.com/pdf-to-anything)でsvgに変換する

#### Webで管理する

 1. https://docs.google.com/drawings/
 1. 図形を描く
 1. GoogleDrive上に保存する
 1. drawings上で`ファイル > ウェブに公開 > 埋め込む > サイズ大`でリンクを生成する
 1. md上で参照する
 1. サイズを変えたときは`width="60%" height="60%"`等追加する
 1. 枠を消したいときは`style="border:0;box-shadow:0 0 0 0"`を追加する
 1. `alt="Sample"`でタイトルも忘れずに

## references

 - [benbalter/jekyll-relative-links： A Jekyll plugin to convert relative links to markdown files to their rendered equivalents](https://github.com/benbalter/jekyll-relative-links)
 - [pages-themes/slate： Slate is a Jekyll theme for GitHub Pages](https://github.com/pages-themes/slate)
 - [GitHub Pages でのSEO対策について - @netchira](https://netchira.github.io/blog/githubpages/SEOsono2.html)
 - [jekyll-seo-tag/usage.md at master · jekyll/jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md)
