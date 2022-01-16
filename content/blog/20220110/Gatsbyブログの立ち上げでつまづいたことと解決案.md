---
# path: /
title: Gatsbyブログの立ち上げでつまづいたことと解決案
date: 2022-01-10
modified_date: 
description: Gatsbyブログの立ち上げに際し、つまづいた時に参考にさせてもらった記事をまとめました。
category: blog
thumbnail:
tags: ["ブログ", "Gatsby", "JavaScript"]
publised: true
---

以下につまづいたことと解決法をまとめています。（随時更新）
## お名前.comで取得したドメインを、Netlify に設定する方法
以下リンク先のKoushi Kagawaさんのnoteを参考に設定しました。<br>
（とてもわかりやすかったです！ありがとうございます！）<br>
[お名前.comで取得したドメインを、Netlify に設定する方法｜Koushi Kagawa｜note](https://note.com/koushikagawa/n/n407cde93bdca)

また、SSL化も記事を出されているのでNetlifyがSSLになっていない！となった方は参考にしてみてください。<br>
[Netlifyで公開しているサイトをSSL化する方法｜Koushi Kagawa｜note](https://note.com/koushikagawa/n/n23c0783bf05e)

## AdobeFontsを読み込む方法
こちらの記事を参考に読み込みました。<br>
[Gatsby.jsでAdobe Fonts（Web Font）を読み込んで使う方法｜アベンチャーズ｜エンジニア × プログラミング × ビジネス × キャリア = クリエイター](https://aventures.io/posts/87)

### 補足
`kitId: '${process.env.TYPEKIT_ID}',`とHelmet内に記述されていますが、ここを含めfunction内はType Kit IDを取得するときに出てくる`(function(d) {`以下をコピペで大丈夫でした。

## Google Analyticsの登録
こちらの記事を参考に登録しました。<br>
その後そのままサチコンにも登録可能でした！<br>
[GatsbyJSで作っているブログで gatsby-plugin-google-analytics から gatsby-plugin-google-gtag に移行した \| キクナントカドットコム](https://kikunantoka.com/2021/01/01--update-google-analytics/)

