================
 PyCon Thailand
================

Day 1
=====

オープニング
============
* 奇数列の人が立って後ろの列の人と話す→階段状なのでよい感じ

Keynote: David Cournapeau
=========================
* スライドがうまく表示できないのでいろいろやって、なんとか出た→拍手
* 日本在住
* Pythonや機械学習のOSSに墾トリビュート。SciPyとか
* Matplotlibで音声のスペクトラムデータを表示
* 2006年にGSoCでMatplotlibへのコントリビュートをはじめた

自分のTalk
==========
* Automate the Boring Stuff with Slackbot
* Slide: https://gitpitch.com/takanory/slides?p=20190615pyconth#/
* 時間配分をちょっと間違えた
* 日本に来たことある人は半分くらい
* Slack知っている人は80%
* 質疑応答
* 聞き取れない英語を他の人がもう一度しゃべってくれて助かった
* LINEBot作りたいんだけど

  * 基本的にはメッセージを受け取ってなにかやって返すのでLINEBotでも考えは同じ
  * ただSlackbotはSlackに特化しているので、errbotなどのbotエンジンと各チャットのアダプターを持っている物を使った方がいいかも
* botはどこで動かすの

  * PyCon JPではサーバー借りているので、そこで。私にはそれが楽
  * EC2とかHerokuとかが楽かなー
* カレンダーと連携する機能とか作りたいけど

  * Google カレンダーのAPIがあるので、それを使えばいいよ。イベントの取得とか変更とか一通りできるよ
* このBotはあなたにしか反応しないの?

  * そうじゃないよ。BotをSlackのチャンネルに招待したら、そのチャンネルの全メッセージに反応するよ。そこを制御するのはBotプログラムじゃなくてSlack側の設定

E-commerce for Django
=================
* Jonghwa Seo
* スライド: https://github.com/pincoin/thaipycon2019  
* 韓国から参加
* 昨日一緒に飲んだ
* タイ語で発表
* タイに4年住んでいた。奥さんがタイ人

Lightning Talk
==============
* 寺田さんがChairのDylanにお願いされて発表
* いい感じだった
* 他の人はほとんどスライドがないスタイル
* NoahがLTしていた

  * Noahは台湾在住だけどフィリピン、タイでもスタッフとして参加。PyCon JPもスタッフとして参加予定
  * いろんなアジアのPyConの紹介。何カ所をスタッフとして参加するんだろうww
* 写真を撮るとディープラーニングで絵画っぽい感じにしてプリントするやつ作ったよ

  * Makerでやっているらしい
  * TensorFlow使ってるらしい
  * ネットワークコネクションいらない(へー
  * Makerムーブメント作ろうぜって話

Keynote: Adam Paszke
====================
* Title: PyTorch as a modern scientific computing environment?
* PythonのSciPyエコシステム
* GIL

Day 2
=====

Keynote: Dr Russell Keith-Magee
===============================
* @freakboy3742
* title: Python Everywhere
* Django, Python, BeeWareの紹介
* Python.. Everywhere?
* How

  * Pythonはspecification
  * CPythonはreference implementation
  * CPythonはGILがあるけどPyPy, IronPython, StacklessにはGILないいよ
  * ctypes

* Inside a Python

  * Parser
  * Compiler
  * Eval loop
  * Standard library
* CPython意外にもいろんな実装あるよ
* VOC: https://beeware.org/project/projects/bridges/voc/

  * Python -> Java
* Batavia: https://beeware.org/project/projects/bridges/batavia/

  * Python -> JavaScript
* asm.js(asmjs.org)
* Weeb Assembly

  * quakejs.com
* Pyodide: https://github.com/iodide-project/pyodide

  * ブラウザでPythonが動く

Understanding of distributed processing in Python
=================================================
* Chie Hayashida
* 並列プログラミング、並行プログラミング、マルチプロセッシング、マルチスレッドなどについて説明
* 結構難しい内容だよな  

PyLadies and importance of community participation
==================================================
* Lina KATAYOSE
* コミュニティの話
* InputしてOutputしよう

Any Code Formatter You Like - As Long As It's Black
===================================================
* Zsolt Dollenstein
* ハンガリー出身
* Facebookの人
* PyLint, Flake8でいろいろエラーが出るよね
* autopep8が助けてくれるよ
* 今はBlackがあるよ

  * single style, minimal configration
  * Simplicity

* Blockがどういう風にフォーマットするかを実例を交えて説明

  * 文字列はダブルクォート
* ASTとかは変わらないから、問題ないよ    

Lightning Talks
===============
* Iqbalさん

  * コミュニティの人たちに感謝を述べよう
  * 企業はお金を稼いで寄付しよう
* Python "OS" for hackers

  * https://python-os.github.io/
  * Qtile: Desktop Environment
  * Kitty: Terminal Emulator
  * Xonsh: Shell
  * Qutebrowser: Borwser
  * Ranger: FIle Manager
  * 面白そう
* odoo ERP

  * PythonベースのERP
* Pythonの数値の話
  * print(a == b, a is b) がどこまでTrueかのはなし
  * -5 から 256 らしい
  * LTなので解説はしないよ
* Regular Expression
* Gerrymandering

  * たいの選挙のPDFを読み込む
  * いろんなPDFから読み込むツールの紹介
  * https://elect.in.th/
* DevOps関連の用語を独自の切り口で説明するトーク

  * ものすごいテンポとチョイチョイこねたが挟まっておもしろかった
  * Cloud: 誰かがメンテナンスしているハードウェア
  * GCE: GoogleのAWS
  * Azure: MicrosoftのAWS

Keynote: Katie McLaughlin
=========================
* How Python Can Excel
* Slide: https://glasnt.com/talks/2019_06_PyConTH.podium/
