# react-makes-you-sad
もう一度あなたを幸せにするフローチャートです!

## <a href='https://cdn.rawgit.com/kuy/react-makes-you-sad/39238dcc16f80abfa092df181591d261e44623e2/fatigue.svg' target='_blank'>新しいタブで開く</a>

<img src='https://cdn.rawgit.com/kuy/react-makes-you-sad/39238dcc16f80abfa092df181591d261e44623e2/fatigue.svg'>

## 謝辞

https://github.com/petehunt/react-howto にヒントを得て作成しました。

## リンク集

* React のエコシステムに不慣れだったり何からはじめたらいいのかわからないときは
  <a href="https://github.com/petehunt/react-howto" target="_blank">Pete Hunt 氏の react-howto ガイド</a>を読んでみてください。

* Flux ライブラリ (または Redux) を使っていて、たくさんの用途のはっきりしないひな形 (ボイラープレート) を追加しているのであれば、
  それを削除して素の React で状態管理する方法を公式ドキュメントの
  <a href="https://facebook.github.io/react/docs/thinking-in-react.html" target="_blank">Thinking in React</a> で学んでください。

* ES2015 の機能 (クラスや矢印のような関数定義) を使うことに慣れていなくて、JavaScript の知識をアップデートしたいと思っているのであれば 
  <a href="https://leanpub.com/understandinges6/read" target="_blank">Understanding ECMAScript 6</a> はすばらしい参考資料になるでしょう。
  <a href="https://babeljs.io/repl/" target="_blank">Babel</a> を使って自分の理解を確認できます。

* 純粋に React だけを学びたい人にとって webpack などの Javascript 依存関係解決ツール (bundler) の導入は混乱を招くだけです。
  <a href="https://github.com/jarsbe/react-simple" target="_blank">jarsbe/react-simple</a> をコピーしてビルド処理なしではじめてみてください。

* React をひと通り学んだら bundler などのデプロイ方法の学習に進むことができます。
  [Google Page Speed](https://developers.google.com/speed/pagespeed/) はコードをブラウザにうまく配信できているか確認するのに便利です。

## 貢献する

1. Edit the `.dot` file with https://atom.io/packages/graphviz-preview
2. Install `dot` from http://www.graphviz.org/Download.php
2. Install `dot`, a part of [Graphviz](http://www.graphviz.org/).
  * On OSX with [Homebrew](http://www.brew.sh), merely do `brew install graphviz`.
  * Otherwise, it's probably in your OS's package repositories as simply `graphviz`.
  * You can also get an installer from the [Graphviz downloads page](http://www.graphviz.org/Download.php).
3. Generate the `.svg` with `dot -Tsvg fatigue.dot > fatigue.svg`
4. Send a PR!

## 翻訳

- [Français](https://github.com/matteodelabre/react-vous-rend-triste)
- [Portuguese](https://github.com/brunogenaro/react-makes-you-sad)
- [Spanish](https://github.com/jvalen/react-makes-you-sad)
- [Tiếng Việt](https://github.com/petehouston/react-makes-you-sad)
- [简体中文](https://github.com/wyvernnot/react-makes-you-sad)
- [한국어](https://github.com/ehrudxo/react-makes-you-sad)
- [日本語](https://github.com/kuy/react-makes-you-sad)

## ライセンス

[CC0](https://wiki.creativecommons.org/wiki/CC0)
