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
オープニングに続いてDavid Cournapeau(`@cournape <https://twitter.com/cournape>`_)氏によるキーノートです。
最初はスライドがうまく表示できず、いろいろと会場スタッフの方とかがやってきたりして作業していました。少しじかんがたった後に画面が表示されると会場から拍手がわきおこりました。
このイベントがあたたかい雰囲気だなと感じる瞬間でした。

David氏は現在日本に住んでおり、2019年4月に開催された `SciPy Japan Conference 2019 <https://www.scipyjapan2019.scipy.org/?lang=ja>`_ にも参加していたそうです。
このキーノートでは自信が現在日本に住んでいることや、音声分析がバックグラウンドであることから話が始まりました。
Pythonや機械学習のOSS(NumPyなど)にもコントリビュートしているそうです。

そして、の
* 2006年にGSoCでMatplotlibへのコントリビュートをはじめた

自分の発表
==========
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20190615pyconth#/

1日目のランチタイムの前に私の発表がありました。
このトーク自体は `PyCon APAC 2019 <https://pycon.python.ph/>`_ で行ったものと同じでしたが、いくつかスライドを手直ししたり、スライド中のAPAC用のネタをタイ用のネタに変えたりして発表に臨みました。

会場の中に電源のあるファミレスっぽい席があって、集中して直前の準備作業ができました。
この席に、他の2名の日本人スピーカー(2人は明日が発表)もやってきてもくもくと作業を進めていました。

.. figure:: /images/th/famires.jpg
   :width: 400

   ファミレス席

さて、実際に発表です。
最初にタイに初めて来たよということと、いくつか簡単な質問をすることでアイスブレイクとしました。
「日本に来たことある人?」と質問すると50%くらいの人が手を上げてくれました。
「まだ来たことがなかったら、ぜひPyCon JPに来てください。PyCon JPで再開しましょう。」という話をしたら少し笑ってもらえました。

.. figure:: /images/th/takanory.jpg
   :width: 400

   「日本にきたことある人ー」と聞いているところ

担当スタッフから「発表が30分で質疑応答が15分で」と言われて「えー、まじかー」と思いつつ、全体的に早口でしゃべっていたら、時間配分を間違えて28分くらいで発表が終わってしまいました。
自分的にはちょっと巻いた感じで40分くらいしゃべろうかと思っていたんですが、ペース配分を完全にミスしました。

とはいえ、時間がきてしまったのでしょうがないので質疑応答に入ります。
質問は結構な数がでて、そこをなんとかこなすことができたので、筆者自身の自信にもつながりました。
いくつか質疑応答の内容を紹介します。

* 聞き取れない英語を他の人がもう一度しゃべってくれて助かった

* LINEBotを作りたいんだけど、この仕組みでできますか?

  * 基本的にはメッセージを受け取って、なにか処理をして返すので LINEBot でもプログラムの考え方は同じです。
  * ただし、 Slackbot は Slack に特化したフレームワークなので、LINEBotの場合は別のフレームワークを使用してください。 `errbot <http://errbot.io/>`_ は汎用のbotエンジンと各チャットのアダプターを持っているので、こっちの方が用途には合っているかも知れません。
* このbotはどこで動かしていますか?

  * PyCon JPではWeb用にサーバーを借りているので、そこで動かしています。
  * Slackbotは動作させ続ける必要があるので、EC2とかHerokuとかを使用するのが楽です。
* Googleカレンダーと連携する機能を作ってみたいが、どうすればよいですか?

  * この例ではGoogleスプレッドシートを出しましたが、同様にGoogle カレンダーのAPIが提供されているので、そのAPIを使うとよいと思います。私も別のツールでCalendar APIを使っています。カレンダー上のイベントの取得や変更など、一通りの操作ができます。
* このBotはあなたの発言にしか反応しないのでしょうか?

  * いえ、そうではありません。BotをSlackのチャンネルに招待したら、そのチャンネルの全メッセージに反応します。どのチャンネルでBotが反応するかは、Botをチャンネルに招待するかどうかなので、プログラムではなくSlack側での設定となります。

他に発表に関するネタとしては、発表の中でSlackで送信するメッセージの例として「私はタイのクラフトビールバーを探しています。」と書いて「本当に探しています」と言いました。
すると参加者の1人が「俺知ってる知ってる!!」というリアクションをしてくれて「じゃあ、あとで教えてね!!」とやりとりできたのは楽しかったです。
その方は実際に1日目のパーティー中に「ここの店がいいよ」と教えてくれました。
ただ、2日目の夜にそこに行こうとしたら、残念ながら日曜は営業していませんでした...

また、質疑応答で一名どうしても質問が聞き取れない方がいましたが、他の人が言い直してくれて無事質疑応答ができました。
参加者のサポートに感謝です。

.. figure:: /images/th/audience.jpg
   :width: 400

   発表前に参加者を撮影(このあとさらに増えました)

発表後にBot作ってみるよというフィードバックや、一緒に写真を撮ろうみたいに言われたりしました。
私の発表を楽しんでくれたようでよかったです。

ランチ
======
ランチは2日間とも5種類の中から選ぶスタイルです。
開けてみてびっくりしたんですが、ご飯の色がすごいです。
このご飯、バタフライピーというタイでは一般的な食用の花を使って色をつけているそうです。
あとは普通っぽく見えるおかずが、結構辛かったりしてタイは侮れないなと感じました。

.. figure:: /images/th/lunch.jpg
   :width: 400

   ご飯の色がすごい

E-commerce for Django
=====================
* スピーカー: Jonghwa Seo
* スライド: https://github.com/pincoin/thaipycon2019

.. figure:: /images/th/jonghwa.jpg
   :width: 400

   Jonghwa Seo氏

午後は、こちらも昨日のパーティーで知り合ったJonghwa Seo氏による発表を見に行きました。
韓国からの参加で、PyCon KRの立ち上げメンバーの一人であるKwon-Han Bae氏は同じ大学出身の友達だそうです。
この発表では会社で開発しているDjango製のE-commerceサイトについて発表していたようです。

「ようです」と書いたのは、この発表がタイ語だったためです。
Jonghwa氏はタイに4年ほど住んでいたことがあり、奥さんがタイ人だそうで、タイ語での発表にチャレンジしていました。
おそらくPyCon Thailand全体で唯一のタイ語の発表(LTを除く)が、韓国人によって行われるという、不思議な空間でした。

ライトニングトーク
==================
1日目のライトニングトークです。印象に残ったトークを紹介します。

1つ目はNoah氏によるPythonコミュニティとアジアのPyConの紹介です。
Noah氏は台湾在住ですが、フィリピンのPyCon APACや今回タイなど世界中にPyConでスタッフとして活動しています。
5月に開催された `PyCon Kyushu in Okinawa <https://kyushu.pycon.jp/2019/>`_ なども含めて、アジア圏のさまざまなPyConなどのイベントを紹介していました。
Noah氏はいったいいくつのPyConに参加するのでしょう、そして私と会うのでしょう。

.. figure:: /images/th/noah.jpg
   :width: 400

   Noah氏

2つ目は写真を撮影すると、ディープラーニングで絵画っぽい感じに変換してプリントするカメラの紹介です。
日本のMaker Faireなどでも出展していて人気があったようです。
内部的にTensorFlowを使って画像処理を行っているそうですが、驚きなのはネットワークを使っておらず、すべてこのカメラの中で処理をしているそうです。

.. figure:: /images/th/camera.jpg
   :width: 400

   ディープラーニングで画像を変換するカメラ

.. admonition:: 無茶振りされたライトニングトーク

   * 寺田 学(`@terapyon <https://twitter.com/terapyon>`_)

   PyCon ThailandのリーダーであるDylanから、14:30頃(LT開始の2時間半前)に「今日のLTで枠がまだ余っているあるから、何かお願い」と無茶ぶりされました。
   そのリーダーとは古い友人なので、一言で「OK」と回答して、LTをすることにしました。
   その後の2時間は、LTのネタを考えたり、スライドを作り、無事にLTを行うことができました。

   スライドは非公開ですが、以下のような内容で発表しました。
   
   - 日本から来ました
   - 10年前のイベントで(PyCon Thailand 2019)リーダーのDylanと出会ったので、その時の写真を紹介
   - PyCon Thailandはすばらしいイベントですね
   - PyCon JPは2019年9月に開催予定だよ
   - SciPy Tokyo 2019を開催しました。2020も春に実施予定です
   - 毎月 `Python mini Hack-a-thon <http://pyhack.connpass.com/>`_ というイベントを東京でやっているので、遊びに来てください

   .. figure:: /images/th/terada-lt.jpg
      :width: 400

      LTの様子

パーティー
==========
1日目のカンファレンスが終了すると、全員参加のパーティーです。
発表会場から外に出るとすでに料理やビールが用意されており、スムーズにパーティーモードに移行できます。
しかもビールはタイのクラフトビール(`Bootleg Brothers <http://bootlegbrothers.co.th/>`_)のボトルが3種類と、生ビールが2種類用意されていました。完璧すぎます。

.. figure:: /images/th/party1.jpg
   :width: 400

   タイのクラフトビールでパーティー

パーティーの中盤にバンド演奏があり、あまり気に留めていませんでしたが、なにやらすごく盛り上がっています。
なんだろうと思って見に行ってみると、なんとスタッフの女性の方が急遽ボーカルとして参加して歌っています。
これにはPyConのスタッフやボランティアも大盛り上がり。しかもこの方、結構歌が上手です。
あとで聞いたらリハーサルなしでいきなり歌うことになったそうです。すごい。
私はその場にはいなかったんですが、以下のTweetのように大盛り上がりだったようです。

* https://twitter.com/georgically1/status/1141057364444925952

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

.. admonition:: はじめての海外PyCon参加及び登壇

   * 林田千瑛(`@chie8842 <https:/twittercom/chie8842>`_)
  
   今回のPyCon Thailandはわたしにとってはじめての海外PyCon参加でした。
   もともと2017年にPyCon JPに初登壇したときに、別の登壇者の方から「海外のPyConで登壇することでグローバルなエンジニアのつながりができた」という話をきいたことを印象的に覚えていて、そのときからいつかチャレンジしてみたいと思っていました。
   自社のサービス（クックパッド）がタイでも展開されていることもあり、今回初めてトークを応募しました。

   発表では、PythonによるDistributed Computingについて話しました。
   わたしが話す会場は一番大きいホールだったので、下手な発表はできない。。と、発表前はとても緊張しました。
   機械学習やWebの話が多い中で、少しニッチな内容となりましたが、発表後も多くの参加者に質問を頂き、議論を行ったり、勉強になったと言っていただけました。
   また、「クックパッド使うよ！」とも言ってもらえました。登壇してよかったな、と思いました。40分のトークを英語でやりきったことは、グローバルに挑戦するための自信にも繋がりました。

   .. figure:: /images/th/chie.jpg
      :width: 400

      発表の様子
     
   参加者としての感想は、PyCon JPと比べると参加者の国際色が高かったこと、フレンドリーに話しかけてくれる人が多かったことが印象的でした。
   海外カンファレンスにチャレンジしてみたい方にはぜひおすすめしたいと思いました。

   .. figure:: /images/th/famires2.jpg
      :width: 400

      登壇準備の様子
     
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
* selina https://docs.google.com/document/d/1cz6YErm7nJQGiWolQUvyMVXuhhHIE2X2O0dWD2LBZ-k/edit?usp=sharing

まとめ
======
