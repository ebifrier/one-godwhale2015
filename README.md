# 大分神クジラちゃん2015 #

これはWCSC25に出場した大合神クジラちゃんのクライアントソフトです。
ソースの一部を使用するとUSIで動く沙夜ちゃんとしてコンパイルできます。

### バイナリファイル ###

沙夜ちゃん単体のwindows用バイナリファイルはこちらになります。  
http://garnet-alice.net/shogiengine/saya_chan/index.html

### ビルドと実行方法 ###

1. cd src/client
2. make
3. ./run_client.sh

対局時間などの必要な設定はparam.txtから行ってください。

### 沙夜ちゃんのビルド方法 ###

1. cd src/saya_chan
2. make

作成されたsaya_chan.exeは通常のUSIエンジンとして使用できます。

### ライセンス ###

* GPL v3.0に従います。

### 謝辞 ###

* 沙夜ちゃんは公開されている将棋ソフト「なのはmini」を修正したものです。作者の川端氏に深く感謝致します。
