=========================
 PyCon Malaysia レポート
=========================

.. contents:: 目次
   :local:

鈴木たかのりです。
2019年の個人的な挑戦として「海外のPythonカンファレンスにトークやポスターを応募しまくって、採択されたら行く」ということを行っています。
今回レポートするPyCon Malaysiaは4カ国目です。
過去のレポートもgihyo.jpに掲載していますので、ぜひ興味のある国のレポートを読んでみてください。

* `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201>`_
* `世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019>`_
* `日本をはじめ各国のスピーカーが語るPythonのいま ―「PyCon Thailand 2019」レポート <https://gihyo.jp/news/report/2019/07/0501>`_
* `ヨーロッパのPythonコミュニティと交流できる3日間「EuroPython 2019」参加レポート <https://gihyo.jp/news/report/01/europython2019>`_

PyCon Malaysiaとは
==================
`PyCon <https://www.pycon.org/>`_ はプログラミング言語Pythonに関する国際カンファレンスです。
アメリカや日本をはじめ世界中で開催されています。

.. figure:: /images/my/pyconmy.jpg
   :width: 400

   PyCon Malaysia 2019 Webサイト

`PyCon Malaysia <https://pycon.my/>`_ は2014に第1回が開催されたました。
2017にはPyCon APA in MalaisiaCとして、アジア太平洋地域のPyConが開催されました。
そのときの模様は以下のレポートで確認できます。

* `「PyCon APAC 2017 in Malaysia」参加レポート <https://gihyo.jp/news/report/01/pycon-apac2017>`_

以下はPyCon Malaysia 2019の開催概要です。

:URL: https://pycon.my/
:日程: 2019年8月24日(土)、25日(日)
:場所: マレーシア、クアラルンプール
:会場: `iSpace TTDI <https://www.venuescape.my/venue/iSpace-TTDI/TTDI/337>`_
:参加費: 220リンギット(約5,500円)
:主催: PYCON MY PLT

日本からの大荷物
================
今回日本からの移動は思いがけない大荷物となりました。
きっかけは韓国の `Younngun氏 <https://twitter.com/scari_net/>`_ からの以下のようなメールでした(Younggun氏はPSF: Python Software Foundationの2016年の理事でPyCon KRの立ち上げメンバーでもあります)。

::

   The PSF will have a booth at PyCon MY (Aug 24-25), PyCon JP (Sep. 16-17), PyCon TW (Sep.20-22)
   I'll attend JP and TW but unfortunately, I can't make it to MY due to biz trip. So the problem is how to send the booth kit to MY from KR.
   I'm thinking if we can deliver the kit from/to countries we've scheduled for travels like below:

   KR -> JP (Arai)
   JP -> MY (Takanori)
   MY -> JP (Takanori)
   JP -> TW (Younggun, will attend both)

これはどういう内容かというと、PSFがスポンサーしているイベントではPSFがブースを出してPythonステッカーなどを参加者に配っています。
で、ブースには通常PSF Conference KitというPythonロゴが入ったバックパネルを設置しています。
そのKitは東アジアではYounggun氏が管理しているのですが「マレーシアに行けないのでtakanoriが持って行ってくれない?」というお願いでした。

.. figure:: /images/my/boothkit.jpg
   :width: 400

   PSF Conference Kit(イメージ)

「まぁ、やります」と返事をして、Iqbalさん(元PyCon JP理事)が韓国から日本に持ち帰ったKitが宅配便で自宅に届けられました。
そして、そのデカくて重たいKitを持って空港へと向かいました。

.. figure:: /images/my/kit-and-bag.jpg
   :width: 200

   Conference Kitとカバン

いつもは、現地での移動には(楽しいので)できるだけ公共交通を使うのですが、さすがにこの大荷物なのでGrab(配車サービス)を使って車で移動しました。

Conference Kitの設営、オープニング
==================================
次の日はカンファレンスの1日目です。
早めにConference Kitを持って会場に移動し、PyCOn Malaysia 2019のChairであるJames氏とあいさつをして会場に設営しました。

各国PyConでボランティアスタッフをしている(私には)おなじみのNoah氏と一緒にConference Kitを組み立てました。
そのときに衝撃の事実が発覚しました。
なんとバッグの中にキャリーが入っていたのです。
がんばって家から空港まで運んだあれはなんだったのか...。

.. figure:: /images/my/kit1.jpg
   :width: 400

   Noah氏とConference Kitを組み立て中

まぁ、悔やんでもしょうがないので、Conference Kitを組み立ててメイン会場に設置しました。
大仕事を終えたな!!という感じです。

.. figure:: /images/my/kit2.jpg
   :width: 400

   Conference Kitができあがった

その後時間となりイベントのオープニングとなりました。
さきほど挨拶したJames氏のあいさつでPyCon Malaysia 2019が始まりました。

.. figure:: /images/my/opening.jpg
   :width: 400

   PyCon Malaysia 2019のオープニング

自分の発表
==========
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20190824pyconmy

1日目の午前中にさっそく私の発表です。
発表の準備をしていたので、オープニングとキーノートはあまり聞けませんでした。

基本的な発表内容はフィリピンで開催されたPyCon APAC、PyCon Thailandのものと同じです。
しかし、トークの導入部分、Slackのメッセージ例やまとめなど、ちょこちょこ地域ごとにいじっています。

.. figure:: /images/my/takanory.jpg
   :width: 400

   発表の様子

今回は、発表の最初に「写真を撮ってTweetは大歓迎」と伝えたり、全スライドに自分のTwitter idを入れるという工夫をしました(PyCon MalaysiaでKatieさんが行っていたものをリスペクトしました)。
その甲斐あってか、Twitterにもいろいろとリアクションがもらえてうれしかったです。

* https://twitter.com/ariestiyansyah/status/1165099844387557378

2日目のキーノートスピーカーでもあるCarol氏が最前列で聞いていて、最初は少しプレッシャーを感じましたが、私の発表をうなずいて聞いていてくれているので、楽しく発表できました。
あとで確認すると、Carolさんも私の発表をTweetしてくれていました。とてもありがたいです。

* https://twitter.com/WillingCarol/status/1165099290211049472

質疑応答では「Botをどこで動かすのか?」という質問があり「EC2やHerokuなどのサーバー上で動かすのがおすすめ。開発時は自分のPCで動かすだけで試せるので簡単だよ」という回答をしました。
他の参加者から「サーバーを使わずにAWS Lambdaとかを使ってBotを作るのもありだよ」というフォローがありました。
「このSlackbotのフレームワークはLambdaでは動かないと思うけど、一般論としてはそういうのもありだと思う」という説明をして、なんとか今回も質疑応答をやり終えました。

ランチ
======
ランチはビュッフェスタイルです。基本的においしいものが多くいいですね。

.. figure:: /images/my/lunch1.jpg
   :width: 250

   ランチはビュッフェスタイル

ランチの料理はマレー、中華、インドの料理が混ざっている感じでしょうか。
デザートにスイカやメロンんどの果物があって、それもおいしかったです。

.. figure:: /images/my/lunch2.jpg
   :width: 400

   米、玉子、チキンカレー、野菜炒めなど

テーブルで隣に座った女性が日本語が少しできる方で、最近大阪と東京の旅行に行っていたそうです。
旅行中はすき家にばっかり行っていたそうです。
とはいえ、彼女はイスラム教なので牛丼は食べられません。もっぱら魚のメニューを食べていたそうです。

Django with GraphQL
===================
* スピーカー: Manuel Riel

.. figure:: /images/my/manuel.jpg
   :width: 400

   Manuel Riel氏

この発表はPython製のWebフレームワークであるDjangoにGraphQLを加えていく手法や、具体的にGraphQLの内容について説明がありました。
最初に `REST <https://ja.wikipedia.org/wiki/Representational_State_Transfer>`_ APIの課題について説明がありました。
REST APIはゆるい標準化がされており、複数のモデル間の関係を表すことが難しいという課題があげられていました。
また、Over Fetchingという必要もないフィールドの情報を全て取ってきてしまったり、逆にUnder Fetchingといって必要な情報を取得するために何回もREST APIを呼び出さないといけないことも課題であると説明していました。

それに対して `GraphQL <https://en.wikipedia.org/wiki/GraphQL>`_ では必要な情報を問い合わせるための、検索用の言語(QL: Query Language)を提供しています。
GraphQLでリクエストを投げれば、必要な情報が1回でまとめて返ってくるということで便利そうです。

次にGraphQLの基本的な以下のコンセプトとその文法が紹介されていました。

* Types: データベースのモデルを反映するもの。String、Intなどの型が指定できる
* Queries: デフォルトの操作。指定したデータを取得する
* Mutations: データを変更する
* Arguments: クエリの再利用とデータの受け渡し
* Nesting: ネストした属性が要求できる
* Subscriptions: Subscribeしたデータの更新をリアルタイムに受け取る
* Fragments: 複数のクエリで同じフィールドを使うときに使い回せる

次にVue.jsとDjangoを使用したデモを行いました。
Django側の実装は `Graphene-Python <https://docs.graphene-python.org/projects/django/en/latest/>`_ というパッケージを利用しています。
そして以下のようなコードを書くことでGraphQLで検索できるようになるそうです。

.. code-block:: python

   class Query(graphene.ObjectType):
       all_persons = graphene.List(PersonType)

       def resolve_all_persons(self, info):
           return Person.objects.all()

ただこれだけだと誰でもどんなデータにでもアクセスできてしまうので、認証などの仕組みが必要になるとのことでした(確かに)。

DjangoにGrapheneを導入すると確かに簡単にGraphQLには対応できそうです。
実際に使ってみないとどういう苦労があるかはわかりませんが、試してみるのもありかなと思いました。

ティーブレイクで日本人と遭遇
============================
午後のティーブレイクではおやつとミルクティーで休憩です。
コーヒーとティーが提供されていますが、どちらも最初からミルクと砂糖が入っており、東南アジアだなーと感じました。
写真の餃子っぽい物は、中がカレーでカレーパンっぽい食べ物でした。

.. figure:: /images/my/teabreak.jpg
   :width: 400

   おやつとミルクティー

Twitterで私の発表に対するリアクションを見ていると、日本から参加しているっぽい人(`kzfm (@fmkz___) <https://twitter.com/fmkz___>`_)がいました。

* https://twitter.com/fmkz___/status/1165104151006601216

Twitterで声をかけてみると日本の方のようです。
ランチの時には見つけられなかったのですが、ティーブレイクに会うことができました。
以前は静岡に住んでいたそうで、共通の知り合いに `@aodag <https://twitter.com/aodag>`_ がいました。
世間は狭いですね。

.. figure:: /images/my/kzfm.jpg
   :width: 400

   kzfmさんと会えた

Scaling AirAsia 3.0
===================
* スピーカー: Tevanraj Elengoe

PyCon MalaysiaのスポンサーであるAirAsiaのエンジニアによるトークです。
そもそも「なんでAirAsiaがPyConのスポンサーしているんだろう?」と思って企業ブースで少し話したんですが、AirAsiaはシステムを内製しておりエンジニアは結構いるようです。
このスポンサーもよいエンジニアを採用したいために行っているそうです。
ちなみにスピーカーのTevanraj Elengoe氏はRubyConf MY 18のOrganizerだそうです。

