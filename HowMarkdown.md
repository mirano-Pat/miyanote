# マークダウン記法

## 基本編 - できること
マークダウン記法は多くのことができるが，最低限の修飾だけで済ませるのであれば，すべてを使いこなす必要はない．  
研究室の引継資料を義務として作る程度であれば，次の記述だけで十分．
* 見出し
* リスト（箇条書き）
* 改行
* webリンク，内部リンク，画像リンク
* ソースコード
* チェックボックス（VSCodeではまだ標準化していない !2022/3/29現在）

====

特に忘れやすいものについてだけ，tipsとして残す．

## リンク

### webリンク
```md
[筆者のgithub](https://github.com/mirano-Pat)
```
[筆者のgithub](https://github.com/mirano-Pat)

### 内部リンク
```md
[Hello World](sample.md)
```
[Hello World](sample.md)

## 画像
基本markdown記法で良い．
しかし，サイズの指定や，右寄せなどが指定できない．
そこで，html記法のサンプルを追記した．

### markdown記法
```md
![画像](ワタシハリナックスチョットデキル.jpg)
```

### html記法
```html
<img src="ワタシハリナックスチョットデキル.jpg" alt="Linus Benedict Torvaldsの有名なシーン" title="Linus Benedict Torvalds">
```
サイズ指定なし
<img src="ワタシハリナックスチョットデキル.jpg" alt="Linus Benedict Torvaldsの有名なシーン" title="Linus Benedict Torvalds">

サイズをpxベースで指定  
<img src="ワタシハリナックスチョットデキル.jpg" alt="代替テキスト" width="150" height="100">
<img src="ワタシハリナックスチョットデキル.jpg" alt="代替テキスト" width="150">

サイズを縮尺で指定
<img src="ワタシハリナックスチョットデキル.jpg" alt="代替テキスト" width="100%">

## 参考url
* [Markdown: 画像を表示する <image>](https://step-learn.com/article/markdown/md-image.html)
* [Markdownで画像のサイズ指定をしたい場合](https://step-learn.com/article/markdown/ht-image.html)

## TODOリスト
- [] チェックボックス1
- [x] チェックボックス2

