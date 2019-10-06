===============
 PyCon Taiwaan
===============

Day 1
=====

オープニング
------------
* 中国語だけどスライドが英語なのでわかった

Honey, There is a Python in my Android Phone!
---------------------------------------------
* Jason(MY Chair)
* Android PhoneとPCは違うよね
* 古くなったAndroidどうするか
* プログラムはJava/Kotlinで
* Once upon a time  

  * 2016年のクリスマスに、自分の本のカタログ作りたいって思った
  * ISBNからメタデータを取得するPythonスクリプトを書いた
  * ISBNバーコードスキャナーを持っていなかった
* Googleで検索した結果

  * Android Scripting ENvironment(ASE)
  * Scripting Languages for Android(SL4A)
* 以下のコードでAndroid APIとはなせる

  `self._rpc("scanBarcode")`
* QPython3: Python3 for Android
  * https://play.google.com/store/apps/details?id=org.qpython.qpy3&hl=ja
* QPythonでTraffic Loggerを作ってみた
  * audroidhelper+ flask + vue.js
* androidのジャイロスコープを使って、立方体を回転させるデモ

Python Profilers we Build for Efficiency
----------------------------------------
* スピーカー: Jimmy Lai
* スライド: https://github.com/jimmylai/talks  
* Instagramの人
* スライドがJupyter Notebookのなにか
* プログラムの効率化の話
* 関数を順番に呼ぶやつをasyncioにする
* ncallsとtottimeでチェックする
* cProfileの結果をグラフ化?

  * cProfileはasyncioをサポートしていない
* ujsonってのが速いらしい

  * https://pypi.org/project/ujson/
* 文字列生成でどれが速いか
* InstagramでPython2.7 -> 3.5
* Facebook Singapore, Instagramで人を募集してるよ

Dustin
------
* PEP572
* その前にPython Governance

  * BDFL Guide
  * PEP
  * PEP8: style guide
  * PEP 566: Author Dustin(一番好きなPEPらしい
  * Draft -> Accept -> Implementation
  * BDFL Delegates
* PEP 572 Assignment expression

  * `:=`
  * コードのサンプルを使用して、 := を使っていい感じに書ける例を紹介
* Why?

  * 行が少ないのはより良い
  * 行が少ないのは効率的?
  * := は連続できない
  * := はリストの中には使用できない
  * := は self.rest とかにも使えない
  * いくつか使えない例を紹介
* PEP 572

  * 後方互換性
  * きたないとかいってすごいながい議論になった
  * その後GuidoがAccept
  * そのあとに Transfer of power というメールを送信
  * いろんな人がそのことについてTweet
* PEP 8000

  * PEP 8001, 8002
  * 2018年12月1日-16日に投票
  * PEP 8016

Day2
====

朝食
----
* テーブルで同席したら同席した大学生と会話
* どういう仕事をしているのか?
* Excelをみんな使っている→うちではMacだし使ってないよ

Keynote: Paul Ivanov
--------------------
* Programming Language Tourism
* モスクワ生まれ。冬はすごく寒い
* Jupyter の Counsil
* 台北ははじめて
* PythonがStackoverflowでトップになった
* 育っているしHappy
* GitHubのデータでもPythonはだいたい3番目くらい(JS, Java)
* Goodbye, Python 2: なんか面白い詩のようなものがあった
* Scratch

  * MakeCode Arcade→JSに変換できる

Lightning Talks
---------------

Day 3
=====

Keynote: Dr.Yves J.Hilpisch
---------------------------
* https://hackmd.io/@PyConTW/2019/%2F%40pycontw%2Frk0ESjn8B
* Title: Artificial Intelligence in Finance
* Slide:
* https://twitter.com/dyjh/status/1175570485846798337
* Python Wuants, The AI Machine

  * Python Quants: 16 week program, 1200 page PDF, 150+hours
  * The AI Machine: Trading platform? http://aimachine.io
  * Python for Financeとかの著者
* JP Morganがプログラミングについてスタッフに教育を始めた
* Financial Markets, Finance History, AI in Finance = finaince
* scikit-learn, nVIDIA, TensorFlow, Keras
* Jupyter Notebookを使って説明
* AI Machine

自分の発表
----------
* HackMD: https://hackmd.io/@PyConTW/2019/%2F%40pycontw%2FB1i3ro2UB
* Slide: https://gitpitch.com/takanory/slides?p=20190922pycontw#/
* 無事発表終了
* 30分なので結構はしょりぎみに説明した。コードとかは細かく話せない感じ
* 質疑応答は3分間

  * How to avoid the 3 second response time limit from slack api when using slack bot?

    * BotではRTM APIが推奨されている。Botの場合は手でコマンドを送ってそれに反応しているので、あまり3秒のリミットは気にならない
  * もう一個思い出せない。

OpenSpaces
----------
* 10個くらいのテーブルで議論をしてた
* PyCon [A-Z]{2}という海外PyCon 参加についてのテーブルに行ってみた
* Wei LeeがPyCon JPを写真を使って紹介
* そのあとPyCon JPとTaiwanの違い(Sprintあるなし)とか、みんなUS PyConを参考にしているしお互いを参考にしあってるよねって話をした

Keynote: Tracy Osborn
---------------------
* https://tracyosborn.com/
* https://speakerdeck.com/tracymakes/keynote-the-different-paths-we-take-as-programmers
* 高校生くらいのときにすごいシンプルなHTML書いてた

  * 先生はそれを見て「おお、Webサイト作れるの」みたいに驚いてくれた
  * CSでCalPolyという大学に入った
* CSC 101

  * 最初の10分でぜんぜんわけわからんかった
  * Javaでプログラミングを学んだ
* CSC 103という別のCSコースに参加
* 大学でグラフィックデザインもまなんだ

  * その後卒業して、フロントエンドエンジニアとして働き始めた
  * そこでjavaScriptをはじめて使う
* そのあとにPythonと出会った

  * Co-FunderとしてWeddingXXをたちあげた
  * Djangoと出会った
  * 6週間でDjangoを学んでWebサイトをリリースした
* CSの学生の女性比率下がっているのか

  * CS関連の仕事をしている女性はだんだん減っている
* デザイナーがPython使ってフォント作ったりできる
* Beginner/intermediate/Advancedじゃなくて、Beginner + Developmentみたいな言い方がよいのでは
* いろんなチャンネルあるからそこから勉強できるよ
* beginnerのように教えることができるか?  
* まとめ
* 持ってきた本をプレゼントするよ

Lightning Talks
---------------
* Gogoro
* SSE using Django channels

  * Ajax -> WebSocket -> Server-Sent events
* PyCon TaiwanのWebサイトを永続化するとかそういう話かな?
* キーボードの配置を換える話(Sebastian)

  * Karabinier elements
  * dotfiles(https://github.com/switowski/dotfiles)
  * I hate a touchbar
  * BetterTouchTool
  * @SebaWitowski

Closing
-------
* 3x3友達できた?
* Tote bag, 冊子は電子のみ
* Financial Aidの報告
* 地図の引用
* スポンサー、そしてPSFの紹介

うちあげParty
-------------
* タイ料理

ビール
------
* 日本人1人+台湾人6人
* すてきなロケーション

