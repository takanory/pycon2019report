=========================
 PyCon Indonesiaレポート
=========================

.. contents:: 目次
   :local:

鈴木たかのりです。
2019年の個人的な挑戦「海外のPythonカンファレンスに応募しまくって、採択されたら行く」も最後の旅となりました。
今回レポートするPyCon Indonesiaは9カ国目です。
過去のレポートもgihyo.jpに掲載していますので、ぜひ興味のある国のレポートを読んでみてください(PyCon JPのみ運営スタッフによるレポートです)。

* `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201>`__
* `世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019>`_
* `日本をはじめ各国のスピーカーが語るPythonのいま ―「PyCon Thailand 2019」レポート <https://gihyo.jp/news/report/2019/07/0501>`_
* `ヨーロッパのPythonコミュニティと交流できる3日間「EuroPython 2019」参加レポート <https://gihyo.jp/news/report/01/europython2019>`_
* `データサイエンスの実践に必要な4つの柱とは？ ―「PyCon Malaysia 2019」レポート <https://gihyo.jp/news/report/2019/09/0901>`_
* `PyCon JP 2019 カンファレンスレポート <http://gihyo.jp/news/report/01/pyconjp2019>`_
* `日本と台湾のPythonコミュニティの架け橋に ―「PyCon Taiwan 2019」レポート <http://gihyo.jp/news/report/01/pycon-tw2019>`_
* `Zappa作者が語る“何でも作ってみよう！”―「PyCon Singapore 2019」レポート <https://gihyo.jp/news/report/2019/10/2901>`_

PyCon Indonesia
===============
インドネシアは2017年に初めてPyConを開催し、今回は3回目です。
会場は毎年変わっており、初回と今回はインドネシア第2の都市スラバヤで、前回は首都ジャカルタで開催されました。

筆者自身は初めてのPyCon Indonesia参加となります。
スラバヤは日本から直行便がないので、ジャカルタ乗り換えで行きました。

.. figure:: /images/id/pyconid.png
   :width: 300

   PyCon Indonesia 2019 Webサイト

以下はPyCon Indonesia 2019の開催概要です。

:URL: https://pycon.id/
:日程: 2019年11月23日(土)
:場所: インドネシア、スラバヤ
:会場: `Universitas Ciputra Surabaya <https://www.uc.ac.id/>`_
:参加費: 150,000インドネシアルピー(約1,200円)

カンファレンス前夜
==================
カンファレンス前日は同じく日本から参加した `jbking <https://twitter.com/jbking>`_ がPyCon Indonesia座長(Chair)のDoniがディナーに誘われており、それに私も混ぜてもらいました。
他に日本から参加した `Iskandar(@freedom_holicx) <https://twitter.com/freedom_holicx>`_ とも連絡をとりあって現地に向かいました(Iskandarはスピーカーであり、Indonesia出身です)。

場所は `Boncafe <http://boncafe.co.id/>`_ というスラバヤでステーキが有名なお店のようです(あとで日本語のガイドブックを見てみたら載ってました)。
会場に行くと現地PyConスタッフの他に海外PyConではおなじみのNoah(彼は各国のPyConでボランティアスタッフをしています)や、PyCon APACで会った `Josef <https://twitter.com/josefmonje/>`_ (彼は台湾でLTもしていました)がいました。

ステーキの他にいろんな物が乗っかっている「おつまみセット」のようなものが頼まれていました。こういうのを「バランバラン」とインドネシアでは言うらしいです。
調べてみると「品々」みたいな意味らしいです。
聞いたときには「バラバラだからバランバラン?」とか思ってました。

ちなみに「おつまみセット」みたいなものやステーキを頼んでいますが、ビールはありません。
インドネシアはイスラム教の人が多いのでビールには期待していませんでしたが、想像通りジュースしたありませんでした。
とはいえ、よくわからない名前の果物のジュースを頼みましたが、おいしかったです。

.. figure:: /images/id/balanbalan.jpg
   :width: 150

   バランバラン(奥がNoah)

そのあとは軽く飲みに行きたいなーと思いましたが現地スタッフはみんな帰ってしまい、Iskandarがお店を探してくれてビールを飲みに行きました。
外国からの参加者6人で南国特有の薄味のビールを飲みながら、各国PyConなどの話をしてその日は別れました。

.. figure:: /images/id/foreigners.jpg
   :width: 300

   外国からの参加者だけで二次会

オープニング
============
次の日はカンファレンス当日です。
早起きしてきちんと開始前に会場に到着しました。
会場に着いたら「前の席が妙に空いてるなー」と思ったんですが、前方の席はスピーカー用に空けているそうです。ありがたいですが、なんだか申し訳ない気持ちになりました。

まもなくオープニングがはじまりました。オープニングはこの写真の2名で英語も交えて行われました。

.. figure:: /images/id/opening.jpg
   :width: 300

   オープニング

オープニングの途中でChairのDoni氏からメンバー紹介やPyCon Indonesiaの歴史について紹介がありました。
今年のロゴはPythonのヘビがよく見るとワニとサメになっています。
これはスラバヤの語源がスラ=サメとバヤ=ワニだからだそうです(へー)。

.. figure:: /images/id/opening2.jpg
   :width: 300

   PyCon Indonesia ChairのDoni氏

オープニングとしては他に、会場となった大学の教授からのWelcomeスピーチや、Platinum Sponsorであるalterra社のトーク(インドネシア語)がありました。
キーノートの前にスポンサートークを入れるのは変わってるなと個人的には思いました。

キーノート
==========
1つ目のキーノートはInggriani Liem博士によるトークでした。
内容はよりよいソフトウェア開発者になるための学び方や現在の状況などのようです。
「ようです」と書いたのは、スライドは英語だったのですが発表がインドネシア語だったためまったくわかりませんでした。
写真の通り小柄な女性ですが、すごいパワフルなトークと、場内がものすごい楽しそうに話を聞いていたのが印象的でした。
あとでIskandarが教えてくれたんですが、インドネシアではすごい有名な先生で、Iskandar自身も彼女に教わったそうです。

.. figure:: /images/id/keynote1.jpg
   :width: 300

   Inggriani Liem博士

2つ目のキーノートはFauzan Erich Emmerling氏による「How Python Changed My Life」です(このトークは英語でした)。
Fauzan氏は2000年からプログラミングをはじめ2010年にPythonを使い始め、現在はGojekのモバイル部門のリードエンジニアだそうです。

.. figure:: /images/id/keynote2.jpg
   :width: 300

   Fauzan Erich Emmerling氏

`Gojek <https://ja.wikipedia.org/wiki/GO-JEK>`_ はライドシェア、配送、出前、決済など統合的なサービスを提供するインドネシアのベンチャー企業です。
最近、創業者がインドネシアの閣僚となるというニュースでも話題となっている企業です。

* 参考: `ゴジェックのマカリムＣＥＯが退任、インドネシアで入閣 - Bloomberg <https://www.bloomberg.co.jp/news/articles/2019-10-21/PZPLRS6TTDS201>`_

まずはPythonに出会う前の暗黒時代(The Dark Ages」から話がはじまります。
1999年にインターネットと出会いHTMLコードを書いてGeocitiesでWebサイトを公開していたそうです。次にVB6の本を読んだがあまり理解ができず、2002年に大学に入ってCのプログラミングを学び始めたそうです。当時は今と違い学習のためのリソースも限られていました。

その後はVB6でビジュアルプログラミング、JavaとJSPでWebアプリケーション、PHPを習得していったそうです。
PHPは氏にとって初めてのインタプリター言語で、JSPや.Netに比べてPCが軽く、Webにリファレンスがあり、軽いサーバーで動作するなどいろいろ楽しかったそうです。
しかし、PHPは自分をインスパイアする部分がなく、IRCコミュニティで質問すると厳しく扱われ、よいコーディング哲学がないと感じたそうです。
とはいえ、他の言語より早く開発できるので、PHPのプログラムで卒業し、PHPのWebで仕事をはじめたそうです。

つぎに悟りの時代(The Age of Enlightment)の話になりました。
最初にPHPとZENDで作成したサービスをGoogle App Engineに載せ替えることとなり、そこでPythonと出会ったそうです。
Pythonを使ってみるとシンプルでわかりやすく、簡単に学習でき、コード量も少なく書けたそうです。
また、多くのプログラミングのコンセプトを学び、テストやセキュリティなどを学ぶモチベーションとなったそうです。

他にもIRCのコミュニティはとてもあたたかく、豊富な標準ライブラリ、ネット上のチュートリアル、BDFL(Python作者のGuido van Rossum氏のこと)はとてもクールだと感じたそうです。

Pythonを使用してから参加したハッカソンで賞を取り、スタートアップに名前を知られるようになったそうです。
その後、さまざまなスタートアップで仕事をし現在はGojekにいるそうです。

現在はモバイル部門のためPythonはメインでは使用してないが、Pythonの哲学は現在も生きているそうです。
現在も学習を続けており、iOS、Androidの開発を学んだ後は他の言語やDevOps、スタートアップの立ち上げなどについても学んでいるそうです。

最後にGuido van Rossum氏の `King's Day Speech <http://neopythonic.blogspot.com/2016/04/kings-day-speech.html>`_ の一節を引用していました。
意味としては「プログラミング言語はプログラマーがアイデアを表現、伝えるための方法であり、その聞き手はコンピューターではなく他のプログラマーです。」といった内容になります。

  In reality, programming languages are how programmers express and communicate ideas - and the audience for those ideas is other programmers, not computers.

また自身が2013年からPython Indonesiaに参加している話をして、コミュニティへの参加を呼びかけていました。

Pythonを知ってまさに人生が変わった人という感じで、刺激的な内容でした。
キーノートの発表が終わった後は質問タイムがあるのですが、スピーカー2名がソファに座って質問を受けるという変わった趣向でした。
キーノートスピーカー同士の対話などもあるので、これはこれで面白いなと思いました。

.. figure:: /images/id/keynote3.jpg
   :width: 300

   キーノートスピーカーへの質問タイム

Lunch
=====
* Josefとかと食べた。Josefは台湾でのLTがはじめてだったらしい
* 今回は発表者じゃなくて参加者

rest in peace REST, The rise of GrpahQL
=======================================
* speaker: Abhishek Mishra
* PyCon Indiaの人っぽい
* はじめてのPyCon Indonesia
* Abhishek
* REST
  * ステートナシのアーキテクチャースタイル
  * リソースをURIで取得
  * JSONを取得
  * GET/POST/PUT/DELETE
* RESTはリソースを返すので
  * 複数のエンドポイントがある
* BFF: Backend for Frontends
* RESTのよくないところ
  * Over/Under-fetching
  * エンドポイントがたくさん
  * Queryの複雑化(N+1)
  * 型がない
* 解決策
  * json:api, OData, FALCOR?, GraphQL
* サンドイッチの注文を例にRESTとGraphQLの違い(わかりやすい
  * RESTだと全部入りがきて不要な食材を抜く。GraphQLは注文時にほしい食材を言う
* GraphQL
  * Single request, endpoint
  * Specification
  * More contron over data
  * Relational queries
  * 強い型
* Schemaが一番大事だよ
* デモでGraphQLで問い合わせて返すところを見せた with Graphene
* GraphQLの経験が15年以上必要w

自分の発表
==========
* スライド: https://gitpitch.com/takanory/slides?p=20191123pyconid#/
* そこそこウケかな。ビール飲みたいのところは「インドネシアの人は飲まないの知ってるので、あなたはお茶を飲んで私はビールを飲みます」みたいなこと言ったらウケてた。
* Slack(80%)、JIRA(90%)を知らない人が多かった。こういうものだよって他の例を挙げたけど伝わったのかは不明
* 質疑応答
  * 誰が実行できるかの権限設定とかあるの?(聞き取れなくてIskandarが日本語でフォローしてくれた
    * Slackbotとしてはないので、例えばgadminコマンドだと私のGoogleアカウントの権限でなんでもできちゃう。それだと危険なので、gadminコマンドでは「SlackのAdminか」をプログラムでチェックしている
  * サーバーはどこで動かすのか?ローカルでもよいのか?    
    * Incoming WebhookもSlackbotも開発時に自分のPC上で開発して動かすことが可能。PyCon JPではWebサーバーを持っているのでそこでbotも動かしている。サーバーがない場合はEC2とかHerokuとかで動かすことになると思う。
  * ピザを注文するときに、ピザ→サイズは何?→サイズ→トッピングは?みたいなBotを作ることはできるか?
    * Slackbotのやりとりは状態を持っていないので、基本的には `$pizza サイズ 種類 住所` みたいなコマンドを作るしかない。Slack自体はボタンを表示して複数のやり取りをするような機能はあるので、その機能を使うと良さそう。Slack社が提供するライブラリだと対応しているかも?

Getting Fast Feedback While Coding Python
=========================================
* Hans Sebastian
* 7年アメリカで働いて最近3年はインドネシアで働いている
* QAエンジニア?
* バックエンドってなにがある?みたいにして、いろんな人から聞いてまとめていくスタイル
* 実際にテストコードを書いていく感じ

Lightning Talks
===============
* Visualizing High-Dimensional Data
  * PCAで2時苦にする→でもいまいち
  * t-SNE: 遅いらしい
  * UMAP
  * Fashion MNISTでやってみる→UMAPよさそう?
  * 名前とニュースの分類はそこまでうまくいかない
* BPS Surabayaからデータを抜き出す
  * 場所ごとの人口?
  * Foliumで可視化
* How easy programming to kids: Dima
  * Blocks Programmingがなぜいいのか?
  * AsomeBotってのがあるらしい
  * http://asomeit.com/product/
  * Demoでうまく表示できない。操作している画面をカメラで撮って写すという荒技ww
* Python is all You need for Speech Recognition
  * librosa, Kera, TensorFlow, PyTorch
  * https://librosa.github.io/librosa/
  * インドネシア語のデータセットもあるよとのこと
* pandas
  * pandasの基本的な機能の紹介
  * 他の可視化ライブラリと連携できるよ
  * いろんなファイル形式を読み書きできるよ
* 5 minutes style transfer
  * input image + style image = generated image
  * transfer learning: VGG
  * 時間切れで途中で終わった
* Smart Ecosystem with Mozilla IoT: Rizky
  * Alexaとかあるけど音声盗んでるよね的な
  * iot.mozilla.org
* Python dan Hardware
* Call and Responceみたいなの気になる

Closing
=======
* Doni
* 500+
* 2年前は学生が80%だったけど、60%になった
* Male 80%
* 85 Speakers Submission
* 2020の場所はBandungが人気らしい
* bit.ly/pyconid2019→インドネシア語だったから読めないww
* なんかdoniに渡してた

Party
=====
* おしゃれな場所
* ゴルフ場のレストランだけど、外なので気持ちいい
* 2種類のスープの鍋
* バンド演奏していたら女性オーガナイザーが一緒に歌っていた。PyConの伝統?
* 日本で働きたい学生とかもいた。
* アニメの話をふられても、最近アニメとか見てないんですよね...ごめんね
