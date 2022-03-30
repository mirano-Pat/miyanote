# Bashのすすめ

* シェルとは  
    * OSを操作するときに用いるコマンドインターフェイス
    * 絶対に見たことがある
    * 黒い画面に白い文字がびゃーって走る，プログラマーっぽい画面（Command Line Interface; CLI）で動くソフトのこと  
    * OSは根幹となる核（カーネル）と，カーネルを便利にするための殻（シェル）でできている．
* コマンドインターフェイスであるシェルの特徴
    * 組み込みコマンドと，外部コマンド呼び出しが可能
        * エクセルなどの外部アプリが起動できる
* シェルスクリプトとは
    * コンパイルが必要ないプログラミング言語（スクリプト言語）．PythonやRuby, Luaと同じ

## Bashとは？？？
* Bashはシェルの代表格
* Linuxの大半，MacOSには標準で装備されている．もちろんWindwosにも簡単に実装できる
    * WSLやGit Bashをインストールするだけ．

## 何ができるの？
* ファイルの書き換え，ログ取りなど，PC上での基本的な操作．
    * ファイルの移動，コピー，名前の変更など
* それを組み合わせた複雑な操作
    * 画像ファイルに日付で名前をつけるとか
* 外部のソフトと連携
    * 自作したpythonやCなどのツールやソフトの呼び出し
    * エクセルなどのソフトの呼び出し  



# Bashの基本

## 基本的な構成

```Bash:hello.sh
#! /bin/bash # シバン行 どのシェルを使うのか．今回はbashを使う

echo 'Hello world!' # pythonでいうところの print('Hello world!')
```



```Bash
chmod +x hello.sh
```



## 参考
* [bashとは？シェルの概要から他のシェルとの違いまで解説！](https://and-engineer.com/articles/YO0h2xIAACQASWs5)
* [シェルスクリプト(Bash)入門。できること、基礎文法、業務自動化の方法を解説【事例あり】](https://goworkship.com/magazine/shell-script-bash/)

* [安全に「危険シェル芸」ができるスタートアップスクリプトのご案内](https://www.youtube.com/watch?v=8TpiCi_YOz0)

* 植田隆一先生（千葉工大）のYoutubeチャンネル
    * April 2021 [第53回シェル芸勉強会](https://www.youtube.com/playlist?list=PLbUh9y6MXvjfpdJLZ3t10-tzXMliOKEyl) 