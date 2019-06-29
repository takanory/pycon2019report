================
 PyCon Thailand
================

.. contents:: 目次
   :local:

PyCon Thailandとは
==================
`PyCon <https://www.pycon.org/>`_ はプログラミング言語Pythonに関する国際カンファレンスです。
アメリカや日本をはじめ世界中で開催されています。
近年はアジアでの開催も活発で、そのうちの一つが今回レポートするPyCon Thailandです。

`PyCon Thailand <https://th.pycon.org/en/>`_ はタイで開催されるPyConで、今回が2018年に続き2回目の開催です。
筆者はこのイベントにスピーカーとして参加してきました。
他にも日本からスピーカーやブース出展で参加した人がいるので、その方からの視点も交えてレポートします。

.. figure:: /images/th/pyconth.png
   :width: 400

   PyCon Thailand 2019 Webサイト

以下はPyCon Thailand 2019の開催概要です。

:日程: 2019年6月15日(土)、16日(日)
:場所: タイ、バンコク氏
:会場: `True Digital Park <https://www.truedigitalpark.com/>`_
:参加費: 1,600タイバーツ(約5,600円)
:主催:

    Python Phiillines

前夜祭
======
カンファレンス前日の夜にスピーカーなどを招待した簡単なパーティーがありました。
事前にWebサイトに「前の日のPartyを計画中」と書いてあったので期待していたのですが、まったく連絡がありません。
するとその日の18:45分に「Nowhereという店で20:30から飲むよ」というメールが来ました。
「ゆるいな」と思いましたが、誘われたら飲みに行く人なので、当然いきました。

そこでスタッフやスピーカー数名と交流しました。
スタッフのFrancoisさんと、次の日のキーノートスピーカーのDavidさんは日本語もすこし話せるので、日本語でも交流などしました。

このパーティー、最初の1杯が無料だったんですが、そのビールがなんとアサヒスーパードライ。
私はあんまり好きじゃないのと、なぜタイに来てまでアサヒビールという気持ちでしたが、まぁ飲みました。
ちなみにアサヒビールは結構海外進出しているようです。
   
.. figure:: /images/th/asahi.jpg
   :width: 300

   ビールはアサヒスーパードライ

タイのローカルクラフトビールも飲みたかったので、駅からNowhereに歩いて行く途中にあった `Ekamai Beer House <http://www.ekamaibeerhouse.com/>`_ という店に寄り道して、Ekamai IPAを飲んで帰りました。
ちなみにこの店にもアサヒビールは置いてあり、他に常陸野ネストビールも置いてありました。

.. figure:: /images/th/ekamai.jpg
   :width: 400

   Ekamai Beer Houseでタイのクラフトビールを飲む

オープニング
============
カンファレンス1日目のオープニングです。
最初にアイスブレイクがあり、よくある「まわりの席の人と挨拶しましょう」といったものです。
面白かったのが、このホールの席は階段状になっているのですが「奇数列の人が立って後ろを向いて話してね」というものでした。
確かにお互いに目線がちょうどあって良い感じです。
私の後ろの席の人は偶然にも台湾からの参加者でした。
「私は今年のPyCon Taiwanにもトークしに行くので、また会いましょう」といった話をしました。

.. figure:: /images/th/opening.jpg
   :width: 400

   オープニングの様子

なお、写真の右側がPyCon ThailandのChairのDylan Jay(`@djay75 <https://twitter.com/djay75>`_)氏で、左側が最初のキーノートスピーカーのDavid Cournapeau氏です。


Keynote: David Cournapeau
=========================
オープニングに続いてDavid Cournapeau(`@cournape <https://t.co/pACSle46fX>`_)氏によるキーノートです。
最初はスライドがうまく表示できず、いろいろと会場スタッフの方とかがやってきたりして作業していました。少しじかんがたった後に画面が表示されると会場から拍手がわきおこりました。
このイベントがあたたかい雰囲気だなと感じる瞬間でした。

* 日本在住
* Pythonや機械学習のOSSに墾トリビュート。SciPyとか
* Matplotlibで音声のスペクトラムデータを表示
* 2006年にGSoCでMatplotlibへのコントリビュートをはじめた

自分の発表
==========
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20190615pyconth#/

  
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

コラム
======
* terada: https://paper.dropbox.com/doc/PyCon-TH-2019--Afq3grxNTZ4CStQ2R_erMHEUAQ-vpxuT1axJ3Gxxuf0b0XMb
* Chie https://paper.dropbox.com/doc/PyCon--Af~aWGV3kHF_gImE8L967G6OAg-62KWI8SGKGyy0nNFieN0R

まとめ
======
