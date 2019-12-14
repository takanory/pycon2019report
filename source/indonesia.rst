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

ランチ
======
ランチは1Fにあるダイニングルームでとりました。
ポップな大学のカフェテリアという感じです。

.. figure:: /images/id/dining.jpg
   :width: 300

   ランチ会場

昨日も一緒だったフィリピンのJesefらと一緒に昼食をとりました。
Josefはスピーカーではないそうです、PyCon TaiwanでのLTがはじめての外部での発表だったそうです。
ランチはシンプルなお弁当で味はおいしかったです。
ただ、骨付きチキンをスプーン1本で食べないといけなかったので、なかなか難しかったです。

.. figure:: /images/id/lunch.jpg
   :width: 300

   ランチのお弁当

rest in peace REST, The rise of GrpahQL
=======================================
* スピーカー: Abhishek Mishra
* スライド: https://slides.com/abhishek-mishra/rest-in-peace-rest#/title

午後はGraphQLの発表を聞きました。
スピーカーのAbhishek Mishra(`@StalwartCoder <https://twitter.com/StalwartCoder>`_)はインドの方でPyCon Indiaでも発表をしているようです。
また、初めてのPyCon Indonesia参加だそうです。

.. figure:: /images/id/abhishek.jpg
   :width: 300

   Abhishek氏

内容はREST APIとGraphQLを比較したもので、前半はRESTの課題と後半はGraphQLの概要を説明するというものでした。

RESTのよくない点としてOver/Under-fetching、エンドポイントが増えること、Queryの複雑化(N+1)、データの型がないことがあげられていました。
その解決策として `json:api <https://jsonapi.org/>`_ 、 `OData <https://www.odata.org/>`_ 、 `FALCOR <https://netflix.github.io/falcor/>`_ 、 `GraphQL <https://graphql.org/>`_ があげられ、ここではGraphQLをおすすめとして説明がされて行きました。

このあとにレストランにAPIでサンドイッチを注文する例がわかりやすくて面白いなと思いました。
REST APIでサンドイッチを注文すると全部入りのサンドイッチが返されるので、不要なレタスは自分で抜く必要があります。
GraphQLの場合は注文時に「パンとサラミとトマトのサンドイッチ」と注文するので、必要な具材だけが入ったサンドイッチが返されるといった具合です。
GraphQLの特徴として1つのリクエスト、1つのエンドポイント、仕様があること、強い型チェックがあることなどが上げられていました。
また、PythonでGraphQLを使用する場合はGrapheneというライブラリがおすすめされており、コード例が提示され、実際にデモで動作を見せていました。

GraphQLは興味があり、概要がコンパクトにまとまっているトークだなと感じました。
個人的には、実際にやってみてここがつらかったみたいな話がもうちょっと聞きたかったなと思いました。

自分の発表
==========
* スライド: https://gitpitch.com/takanory/slides?p=20191123pyconid#/

2019年のPyConツアーの締めくくりとなる発表です。
内容としてはいつものSlackbotを拡張して自分の作業を楽する方法です。
話した感じではそこそこ笑いもとれており、いつも「ビールを飲みにいきましょう」みたいな話をいれているのですが、そこでは「インドネシアの人はお酒を飲まないの知ってるので、あなたはお茶を飲んで私はビールを飲めればハッピーです。」みたいなことを言ってウケました。

.. figure:: /images/id/takanory.jpg
   :width: 300

   筆者の発表の様子

発表をしていて結構びっくりしたのが、Slack、JIRAを知らない人が多いことです。
Slackは80%、JIRAは90%の人が知らないそうで、他のツール(Telegram、LINE、Github Issue、Asana)などを例に挙げて説明しましたが、伝わったかはちょっと不安です。
質疑応答は以下のようなものがありました。1つ目の質問はうまく聞き取れず、Iskandarが日本語で質問の意味を教えてくれました。ありがとうIskandar、助かりました。

* 誰がBotでコマンドを実行できるかの権限設定はあるのか?

  * Slackbotとしては権限設定はできない。例えばここで説明したgadminコマンドは、私のGoogleアカウントの権限でなんでもできてしまいます。そのままでは危険なので、gadminコマンドでは「SlackのAdminユーザーか」をプログラム側でチェックしています。
* サーバーはどこで動かすのか?ローカルでもよいのか?    

  * Incoming WebhookもSlackbotも、開発時に自分のPC上で開発して動作させることが可能です。PyCon JPではWebサーバーを持っているのでそこでbotを動かしています。サーバーがない場合はEC2とかHerokuとかで動かすことが一般的だと思います。
* ピザを注文するときに、ピザ注文→サイズは何?→トッピングは何?みたいな対話をするようなBotを作ることは可能か?

  * Slackbotのやりとりは状態を持っていないので、基本的には `$pizza サイズ 種類 住所` のようなコマンドを作るしかありません。SlackのAPI自体はボタンを表示して複数のやり取りを行う機能はあるので、その機能を使うと良いと思います。Slack社が提供するPythonのライブラリだと対応しているかも知れません?

ティーブレイク
==============
夕方にはティーブレイクがあり、コーヒー紅茶とおやつが提供されました。
ただ、場所が廊下しかなくあまり座ることころもないため、みんな床に座って食べている感じがゆるい感じでいいなと思いました。
おやつ自体は謎のプルプルした甘いもので、不思議な食べ物でした。

.. figure:: /images/id/break.jpg
   :width: 150

   おやつに群がる人々

Lightning Talks
===============
イベントの最後はライトニングトークです。いろいろなトークがありました。

.. figure:: /images/id/lt1.jpg
   :width: 300

   ライトニングトーク

* Visualizing High-Dimensional Data

  * 多次元のデータをどのように2次元で可視化するかというトークです。PCAだと全然いい感じにならないのでt-SNE、UMAPなどで表示した例で比較していました。
* BPS Surabaya

  * BPS Surabayaから地域ごとの人口(?)のデータを取得し、Foliumを使用して地図上に可視化する発表でした。
* Programming for Kids as Easy as Building Blocks

  * 子ども向けのブロックを使ったプログラミング環境として、 `AsomeBot <http://asomeit.com/product/>`_ の紹介をしていました。DemoでPCからうまく表示できず、PCの画面をビデオカメラで撮影してそれを投影するというローテクを使っていたのが印象的でした。

* Python is all You need for Speech Recognition

  * `librosa <https://librosa.github.io/librosa/>`_ 、Keras、TensorFlow、PyTorchを使用して音声認識をしたことについて発表していました。インドネシア語のデータセットもあるそうです。

* pandas

  * pandasの基本的な機能の紹介でした。他の可視化ライブラリと連携できることや、いろんな形式のファイルを読み書きできることが説明していました。
* 5 minutes style transfer

  * 画像のスタイルをAIで学習し、普通の写真をゴッホ風にするみたいな話でした。VGGを使用しているそうです(時間切れで途中で発表が終わりました)。

LTの数人のスピーカーが何かを言うと会場のみんなが返すという、コールアンドレスポンスみたいなことがありました。
それがなんなのかを聞いてみると、イスラム圏では共通の挨拶だということを教えてくれました。
ぜひイスラム圏でプレゼンする機会がある人は、試してみてください。

* 参考: `全世界のイスラム圏で使える、便利なあいさつの言葉「アッサラーム・アレイコム」を覚えておこう <https://www.ab-road.net/asia/bangladesh/dhaka/guide/nation/06424.html>`_

クロージング
============
クロージングはChairのDoni氏により行われました。
参加者は500人超、割合は学生が60%で一般が40%だそうです(学生多い!)。
2年前は学生は80%だったそうで、一般の比率が上がってきているようです。
男性が80%、85のトークの申し込みがあったそうです。

また、2020の開催場所としてジャカルタ、バンドン、ジョグジャカルタが候補だそうですが、会場ではバンドン(Bandung)が人気のようでした。

.. figure:: /images/id/pyconid2020.jpg
   :width: 300

   PyCon Indonesia 2020の場所は?

パーティー
==========
終了後はスタッフ、スピーカーでバスで移動して打ち上げパーティーです。
会場はゴルフ場の併設のレストランで、外にテーブルが用意されており素敵なロケーションで、風も気持ちよかったです。

.. figure:: /images/id/party.jpg
   :width: 300

   パーティーの様子

バンドの演奏を聴きながら2色のスープの鍋を食べていたんですが、後半になってくると女性オーガナイザーのFarah Clara(`@sosispanggang <https://twitter.com/sosispanggang>`_)が歌っていました。
女性オーガナイザーが歌うのはPyConの伝統なんですかね(タイに続いて2回目)?

* https://twitter.com/takanory/status/1198219912788840448

いろんな人と話をしました。
最後に記念写真をとってお開きです。

.. figure:: /images/id/party2.jpg
   :width: 300

   最後に記念写真

おわりに
========
これで2月からはじまった、私のPyCon Tour 2019が終わりました。
さまざまな国でPythonに興味がある、Pythonコミュニティを運営している人たちと知り合うことができました。
1年間で9カ所のPyConに参加することはとてもハードでしたが、各国でもてなしてもらったり、いろいろと得がたい経験ができたと思います。

私のレポートを読んで、海外PyConなどのカンファレンスに参加するのが楽しそうだなと思った人がいたらうれしいです。
ぜひ機会があったら勇気を出して参加してみてください。

海外PyConで出会った人たちと、またいつかどこかで再会できるとうれしいなと思っています。
その場所が日本の場合はホストとしてもてなしたいと思います。
See you at PyCon somewhere!

.. figure:: /images/id/groupphoto.jpg
   :width: 300

   PyCon Indonesiaの集合写真
