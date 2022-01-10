---
title: マークダウン記法
date: "2015-05-30T22:40:32.169Z"
description: This is a custom description for SEO and Open Graph purposes, rather than the default generated excerpt. Simply add a description field to the frontmatter.
---

以下につまづいたことと解決法をまとめています。（随時更新）
## お名前.comで取得したドメインを、Netlify に設定する方法
以下リンク先のKoushi Kagawaさんのnoteを参考に設定しました。
（とてもわかりやすかったです！ありがとうございます！）
[お名前.comで取得したドメインを、Netlify に設定する方法｜Koushi Kagawa｜note](https://note.com/koushikagawa/n/n407cde93bdca)

また、SSL化も記事を出されているのでNetlifyがSSLになっていない！と
なった方は参考にしてみてください。
[Netlifyで公開しているサイトをSSL化する方法｜Koushi Kagawa｜note](https://note.com/koushikagawa/n/n23c0783bf05e)

## AdobeFontsを読み込む方法
こちらの記事を参考に読み込みました。
[Gatsby.jsでAdobe Fonts（Web Font）を読み込んで使う方法｜アベンチャーズ｜エンジニア × プログラミング × ビジネス × キャリア = クリエイター](https://aventures.io/posts/87)

### 補足
`kitId: '${process.env.TYPEKIT_ID}',`とHelmet内に記述されていますが、ここを含めfunction内はType Kit IDを取得するときに出てくる`(function(d) {`以下をコピペで大丈夫でした。