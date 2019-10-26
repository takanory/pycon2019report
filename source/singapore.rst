=========================
 PyCon Singaporeレポート
=========================

.. contents:: 目次
   :local:

鈴木たかのりです。
2019年の個人的な挑戦「海外のPythonカンファレンスに応募しまくって、採択されたら行く」も終盤戦です。
今回レポートするPyCon Singaporeは8カ国目です。
過去のレポートもgihyo.jpに掲載していますので、ぜひ興味のある国のレポートを読んでみてください(PyCon JPのみ運営スタッフによるレポートです)。

* `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201>`__
* `世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019>`_
* `日本をはじめ各国のスピーカーが語るPythonのいま ―「PyCon Thailand 2019」レポート <https://gihyo.jp/news/report/2019/07/0501>`_
* `ヨーロッパのPythonコミュニティと交流できる3日間「EuroPython 2019」参加レポート <https://gihyo.jp/news/report/01/europython2019>`_
* `データサイエンスの実践に必要な4つの柱とは？ ―「PyCon Malaysia 2019」レポート <https://gihyo.jp/news/report/2019/09/0901>`_
* `PyCon JP 2019 カンファレンスレポート <http://gihyo.jp/news/report/01/pyconjp2019>`_
* `日本と台湾のPythonコミュニティの架け橋に ―「PyCon Taiwan 2019」レポート <http://gihyo.jp/news/report/01/pycon-tw2019>`_

Pycon Singapore
===============
シンガポールは2010年からPyConを開催しており、日本よりも歴史のあるカンファレンスです(アジアではインドが最も歴史があるようです)。
この2010年のPyCon APAC(初回はAPACという名前でした)に日本から参加した4名が出会ったことがきっかけとなって、2011年にPyCon JPが初開催されました。

.. figure:: /images/sg/pyconsg.jpg
   :width: 400

   PyCon Singarepo 2019 Webサイト

以下はPyCon Singapore 2019の開催概要です。

:URL: https://pycon.sg/
:日程: 2019年10月10日(木)-12日(土)
:場所: シンガポール
:会場: `Republic Polytechnic <https://www.rp.edu.sg/>`_
:参加費: 180シンガポールドル(約14,000円)

筆者自身は2014年に訪れて以来、5年ぶり2度目のPyCon Singaporeです。

カンファレンス前夜
==================
カンファレンス前夜は、シンガポール在住の元PyCon JPスタッフと食事に行きました。
せっかくなので私以外の日本人スピーカー2名(どちらもシンガポール在住)と、日本から参加する他のメンバーとも一緒に交流しました。

店はChin Chin Eating Houseというローカルに人気の中華料理店です。
お昼は結構混んでいるそうです。
特に名物の蒸し鶏はとてもおいしく、結局丸々1羽を7人で食べました。

.. figure:: /images/sg/eve-party.jpg
   :width: 400

   おいしい中華で前夜祭

この前夜祭での筆者の重要なタスクの一つに、「 `Python Boot Camp <https://www.pycon.jp/support/bootcamp.html>`_ Tシャツ」を神谷さんに渡すというものがありました。
神谷さんは2016年に私と一緒にPython Boot Campの立ち上げてくれたスタッフです。
しかし、Tシャツを作り始めた2018年にはすでにシンガポールに住んでおり、ずっとこのTシャツを渡せずにいました。
今回こうしてTシャツを直接渡すことができて、3年越しで立ち上げの恩に少しだけ報いることができたかなと思います。
本当にありがとうございました。

.. figure:: /images/sg/kamiya.jpg
   :width: 300

   Tシャツを受け取ってご満悦の神谷さん

オープニング
============
会場はシンガポールの北部にあり、マレーシアの国境に近いWoodlandsという地区にあります。
中心部のホテルからGrabで30分ほど移動して会場に到着しました。
会場のRepublic PolytechnicはPyCon Singaporeの立ち上げメンバーであるLiew Beng Keat氏の職場でもあります。
ちなみに氏は今年のPyCon APACのキーノートスピーカーでもありました。

* 参考: `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート：レポート <https://gihyo.jp/news/report/2019/03/1201>`__

さて、会場に着くとすでに参加者が朝食を食べながら交流していました。
私も朝食をとってマレーシアから参加した知人などとあいさつをしました。

.. figure:: /images/sg/breakfast.jpg
   :width: 400

   朝食をとりながら交流する参加者

時間となったのでオープニング会場に移動です。
オープニングの進行はOrganizerのMartin氏です。
Martin氏は以前参加したPyCon Singaporeでも見た記憶があり、継続的にイベントを主宰しているんだなと思いました。
オープニングでスポンサー一覧と合わせてスピーカーの一覧も表示されました。
私も左下の方にいます。

.. figure:: /images/sg/speakers.jpg
   :width: 400

   オープニングでスピーカーも紹介された
   
Keynote: Laurence Liew
======================
* タイトル: Accelerating AI in Singapore
  
Laurence Liew氏は `AI Singapore <https://www.aisingapore.org/>`_ というプロジェクトDirectorです。
AI Singaporeとは、シンガポールでAIの人材を育成してエコシステムを構築するという国家プロジェクトです。

.. figure:: /images/sg/liew.jpg
   :width: 400

   Laurence Liew氏

最初に「RかPythonか」という問いかけがあり、Googleトレンドによると世界的にもシンガポールでもPythonの人気が高まっているということが示されました。
また、2017年にデータ分析、データサイエンスなどの分野でPythonを利用している人がRを超えたそうです。

次にある人の生活を例にして、AIはすでに生活の中に溶け込んでいるという話をしました。
その内容は、AIスピーカーで音楽をかけ、Googleマップで会社までのルートを調べ、顔認証でオフィスに入り、メールではSPAMをはじき、ランチを食べて安全にカードで支払いをし、家に帰っておすすめリストから映画を見るというものです。
ちなみに、このときに例として「OK Google...」と言ったら、参加者のスマートフォンが反応してました(笑)。

次に「AIは魔術ではない」と題して、その元となる理論について解説しました。
線形回帰、ニューロン、ニューラルネットワーク、深層学習、自然言語処理、音声認識などについて概要が語られました。

次に「AIとJob(仕事)」と題して、AIは仕事を置き換えるのではなく作業(Task)を置き換えるものだと説明がありました。
例えば「ある人が1日に6個の作業ができるとしたら、そのうち2つの作業をAIができるようになれば、その人は別の2つの作業ができるようになる。」という説明です。
この説明は、AIが職を奪わないという説明として、とてもわかりやすいなと感じました。

最後にAI Singaporeの紹介や今後のビジョンについて説明がありました。
現在はPhase Iで2020年からPhase IIが始まるそうです。
またAI人材を開発するプロジェクトを2017年から進めており、最初はプロフェッショナル向けだったものからだんだん初級者向けと裾野を広げているそうです。
今後は学生や子ども向けなども進めていくそうです。

最後に「AIは私たちをより人間らしくする」と述べて発表を終わりました。

シンガポールが国をあげてAIに力を入れているということと、その方向性が感じられる発表でした。
首相がC++でプログラムを書く国はすごいなと感じました。

ランチ
======
ランチはビュッフェスタイルです。
PyCon Singaporeでは朝食、ランチ、午後のおやつが提供されます。
ランチは中華系でおいしいです。
相変わらずPyConに行くとデブ活が捗ります。
コーヒーや紅茶に砂糖がデフォルトで入っていないのがせめてもの救いです。

.. figure:: /images/sg/lunch.jpg
   :width: 400

   ランチ

自分の発表
==========
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20191010pyconsg

いつものSlackbotについての発表です。
基本的な構成は台湾から変えていませんが、時間が45分あるのでコードの説明を丁寧にしました。

.. figure:: /images/sg/audience.jpg
   :width: 400

   発表を聞きに来てくれたみなさん

発表しながら会場を確認すると、うなずいて聞いている方かいらっしゃったので、ある程度は伝わっているのかなと感じました。
ビールについての小ネタもそこそこウケたので個人的には満足です。
質疑応答の時間がとれなかったのですが、終了後に「シンガポールのビールの場所教えるよ」と声をかけてくれる方がいました(スライドの中に「おいしいビールのお店を教えてください」というメッセージを入れてあります)。
以下がその人(Joshさん)からのメッセージです。

* https://twitter.com/joshourisman/status/1182186293075353601

.. * 青木さんコラム https://docs.google.com/document/d/1Lv6AgAXMhN3wCM3s0xVcS9mL9qGgwii8w08OFRJ2GLc/edit?fbclid=IwAR3mDQvU87qU8sZ1PGiOd8LHecmFbjE_p-sr0U9NoARaEAgjTIC-QKIzCCo

日本からの参加者との出会い、そしてビールへ
==========================================
日本からの参加メンバーは知り合いのnao_y(`@NaoY_py <https://twitter.com/NaoY_py>`_)とnikkie(`@ftnext <https://twitter.com/ftnext>`_)だけだと思っていましたが、午後に筆者が発表の準備をしていると日本語で声をかけられました。
それがKeisuke Nishitani(`@keinstn <https://twitter.com/keinstn>`_)さんです。
PyCon APACにも参加されていたそうですが、そのときは他の日本参加者に声をかけるタイミングがなかったそうです。
また、このレポートも読んでいて「自分もチーム・ジャパンとして出たい」と言ってました(笑)。
せっかくなので日本からの参加メンバーで写真を撮りました。

.. figure:: /images/sg/team-japan.jpg
   :width: 400

   チーム・ジャパン(左からKeisuke、nao_y、nikkie、筆者)

カンファレンス終了後はビールだよね!!ということで、他のアジアから参加したメンバーに声をかけて、Joshさんに教えてもらった `SGTaps <https://www.sgtaps.com/>`_ に向かいました。
お店に着くとJoshさんがお友達(シンガポール在住)とビールをすでに飲んでいました。
そこに日本人4名、インドのVaibhav(`@reach_vb <https://twitter.com/reach_vb>`_)、フィリピンのJosef(`@josefmonje <https://twitter.com/josefmonje>`_)も混ぜてもらってビールを楽しみました。
このお店、オーナーが日本人だそうで、オーナーが注文を取りに来ると急に日本語で話しかけられたりするので、なんかだ不思議な気分でした。

* https://twitter.com/takanory/status/1182465891209859072

ビールのあとnao_y、nikkie、Josefと歩いて近くのホーカーセンターに向かいました。
3人はシンガポールチキンライスを食べていましたが、私はさすがにお腹いっぱいなのでアイスカチャン(かき氷)を食べてカンファレンス1日目が終了しました。

Building a Data Pipeline using Apache Airflow(on AWS/GCP)
=========================================================
* スピーカー: Yohei Onishi
* スライド: https://www.slideshare.net/legoboku/building-a-data-pipeline-using-apache-airflow-on-aws-gcp

.. figure:: /images/sg/yohei.jpg
   :width: 400

   Yohei Onishi氏

日本人スピーカーの発表です。Yohei Onishi(`@legoboku <https://twitter.com/legoboku>`_)s氏はシンガポール在住のデータエンジニアです。
彼とはPyCon APACで知り合って「私がシンガポールに行ったときには、また会いましょう」と言っていたんですが、無事再会できました。

* 参考: `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201?page=3>`_

発表の内容は `Apache Airflow <https://airflow.apache.org/>`_ を使用してデータパイプラインをAWS、GCP上に構築するという話です(タイトルのままですね)。
実務で使用している例がベースとなっており、具体的なAirFlowのコードもでてくる発表でした。
またAWSとGCP両方で構築した経験を元に、GCPが環境としておすすめされていました。

発表が早めに終わったため、そのあとはかなりたくさんの質疑応答が行われていたのが印象的でした。

.. admonition:: 青木さんコラム
    
   私は普段はシンガポールにてData Scientistの仕事をしています。
   フォローしているmeetupグループ(`Singapore Python User Group <https://www.meetup.com/Singapore-Python-User-Group/>`_)にてPyCon SGの主催者がスピーカーを募集していたのを見て、プロポーザルを提出しました。
   世界各地で開催されているPythonの技術カンファレンスとしてPyConの存在は元々知っていたのですが、今回が初めての参加でした。

   .. figure:: /images/sg/aoki.jpg
      :width: 400

      発表の様子

   私が仕事で取り組んでいるデータサイエンスや機械学習に関するセッションは他にも数多くありそうだと思い、折角なので最近趣味で勉強しているストリームデータ処理について紹介しようと思いプロポーザルをまとめました。
   対象となる聴き手の想定を「Pythonでの開発経験はあるけれどストリーム処理については未経験」と置いて全体像を固めました。
   私がセッションにて紹介したApache KafkaやSpark Structured Streamingについては、それぞれ既にWeb上でそれなりに情報が出揃っています。
   そこで今回のプレゼンテーションでは作成したデモコードを基に実際のPythonでのコーディング例を併せて紹介することで、どのようにストリーム処理を実装するかのイメージを持ってもらうことを目標にしました。

   他の勉強会の発表と時期が重なってしまうなど直前に慌ただしくなってしまい、作成予定だったデモプログラムの一部の機能については実装・検証が間に合わなかった事が心残りでした。
   また、全体を通したリハーサルを１度も出来なかった事もあり、Q＆Aの時間があまり取れない時間配分になってしまったことも反省点です。

   伝えやすい話し方や技術的内容そのものについて等まだまだ改善すべき点はありますが、初のPyCon登壇を楽しむことが出来ました。
   また、今回Apache Beamによるストリーム処理をテーマに登壇した人との繋がりもでき、情報交換することが出来ました(彼からは「KafkaやSparkも良いけど一緒にApache BeamにPRあげてcontributeしよう！」と熱烈に誘われました笑)。

   参加者としての所感としては、今回参加したPyConでは機械学習に関するセッションが充実していたように思います。
   シンガポールでは政府がAI人材の育成に力を入れていますし、企業での経験を経て大学院にて機械学習やデータサイエンスを学ぶ人達が増えている環境なので、PyCon SGでもこのような傾向が出ているのかなと想像しました。
   他にもPlatinum SponsorsであるDBS銀行のセッションでは、社内でどのように機械学習モデルの開発やデプロイをしているかについての話がありました。
   DBSはPh.D持ちのData Scientistを多く雇い、シンガポール国内でも有数のデータ分析チームを持つ企業なので、その取り組みについて興味深く拝聴しました。

   Python情報のインプット・アウトプットの場としてPyCon SGはとても良い場だったので、今後も当地や他国で開催されるPyConで積極的に登壇していけたらと思います。

2FA, WTF
========
* Phil Nash
* スライド: https://speakerdeck.com/philnash/2fa-wtf-at-pycon-singapore

タイトルがちょっとアレですが、2FA(2要素認証)についての発表です。
スピーカーのPhil Nash(`@philnash <https://twitter.com/philnash>`_)氏はtwilioのエンジニアです。

まず最初にパスワードのみの認証は危険だという例として、Mat Honanさんの悲劇について触れました。
この事件知らなかったんですが、悪意のあるユーザーにiPhone、MacBook、Twitter、Googleアカウント、Gmailなどが乗っ取られデータが削除されたそうです。
恐ろしすぎます...

* 参考: `WIRED記者の悲劇から学ぶ「セキュリティ9つの常識」 <https://wired.jp/2012/08/14/how-not-to-become-mat-honan/>`_

また、Ashley Madisonというサイトから数100万のアカウントが盗まれ、そこにはパスワードが平文で入っていたそうです。で、最も使用されているパスワードは「123456」だそうです。120,511ユーザーが使用しているそうで、これはひどい...

* 参考: `Ashley Madisonのアカウント盗難事件が明かす‘愚かなパスワードは不滅です’ <https://jp.techcrunch.com/2015/09/08/20150907stupid-passwords/>`_

まとめとしては当然ですが、難しいパスワードは覚えられないので1Password、LastPassなどのパスワードマネージャーを使いましょうというものでした。

次に2要素認証の話です。
2要素認証の主な手法としてSMS、トークン、プッシュの3つがあげられていました。
それぞれコードの例と利点、欠点があげられていました。

SMS

* SMSで認証コードを送信する仕組み
* 利点: 多くの人が使用できるみんなが使える
* 欠点: SMS送信にお金がかかる。電波が必要。SMSは壊れている(SIMを盗まれたりなど簡単になりすませる

トークン

* HOTP、TOTPといったワンタイムパスワードを生成。 `pyauth/pyotp <https://github.com/pyauth/pyotp>`_ を使用したトークン生成のデモを実施していました。
* 利点: 無料、オフラインでも利用可能
* 欠点: スマートフォンが必要、リカバリー用のバックアップコードが必要
  
プッシュ

* Webで操作すると専用のスマートフォンアプリケーションに通知がくる仕組み
* 利点: よりよいユーザー体験、最も安全
* 欠点: スマートフォンとネイティブアプリが必要。オフランでは利用できない

.. figure:: /images/sg/phil.jpg
   :width: 400

   Phil Nash氏によるpyotpのデモ

最後に「2要素認証を使おう」というまとめで発表は終わりました。

TOTPなどのワンタイムパスワードを生成するために **pyotp** を使用してると簡単そうだなと思いました。

Keynote: Rich Jones
===================
* スライド: https://github.com/Miserlou/Talks/tree/master/pycon-sg-2019

Rich Jones氏はPython製のサーバーレスフレームワーク `Zappa <https://github.com/Miserlou/Zappa>`_ の作者です。

.. figure:: /images/sg/rich.jpg
   :width: 400

   Rich Jones氏

この「Hello」から始まるスライドは400枚を超えており、終始ハイテンションでしゃべりまくるエネルギッシュなキーノートでした。
50分間1人でライトニングトークをし続ける、といった感じでした。
ただ、しゃべっている内容はスライドにだいたい書いてあるので、英語を聞き取るのが苦手な私もわかりやすい発表でした。

前半は「Zappaでサーバーレスにしよう」と題して、AWS LambdaとAPI Gatewayを使用して、超スケーラブルなサービスを作ろう、という話をしていました。
Zappaを使えばVPSに比べてコストも安く済み、メンテナンスも不要になる(その結果運用チームを解雇できるよ)とのことでした。
基本的なZappaが提供しているコマンドの紹介や、様々なケーススタディでZappaを使用する例について紹介していました。

しかし後半の「なぜZappaを使うべきではないのか」というところから、話の方向が変わっていきます。
Amazonがコミュニティに対して何度も敵対しているという話から始まります。
AWSはOSSコミュニティと敵対し、結果としてMongoDB、Redis、ElasticSearchのライセンスが変更になりました。

* 参考: `Redis、MongoDB、Kafkaらが相次いで商用サービスを制限するライセンス変更。AWSなどクラウドベンダによる「オープンソースのいいとこ取り」に反発 <https://www.publickey1.jp/blog/19/redismongodbkafkaaws.html>`_

またAmazonは税金を払っていない、アメリカの小さな街を破壊した、従業員を低賃金で働かせすぎているとすごい勢いで批判を続けます。
ここで「AmazonはPyCon Singaporeのスポンサーじゃないよね?」と確認していました(笑)。

そこで「自分たちのLambdaを作ろう!」ということで `OpenFaaS <https://github.com/openfaas/faas>`_ の紹介をしました。
PLONK(Prometheus、Linkerd、OpenFaas、NATS、Kubernetes)というスタックでオープンなAWS Lambda、API Gatewayの代わりとなるものを作っているそうです。
そしてOpenFaasを使用して実際にファンクションを作成して動作させる手順について説明がありました。

そして自身のプロジェクトである `Fashion <https://github.com/Miserlou/Fashion>`_ の紹介です。
FashionはOpenFaasの機能をPython的に使用できるライブラリだそうです。
使い勝手などを知りたいので、ぜひ利用してみてほしいと呼びかけていました。

最後に「新しいインターネットを作ろう」というタイトルで、ピアツーピア(P2P)のWeb技術を紹介しました。
いくつかP2PのWeb技術があるそうですが、ここでは `dat:// <https://dat.foundation/>`_ を紹介していました。
datはgitとBitTorrentとHTTPを併せたようなもので、データサイエンティストが大きなデータセットを共有するために設計されたそうです。
「Google、Twitter、Facebook、Netflix、Slackなどを置き換えなければならない」と呼びかけていました。
そして「広告のない世界で生きていきたい!」と語っていました。

いわゆる **ハッカー** だなという感じのRichさんのキーノートでした。
一部過激な内容もありましたが、個人的にも頷ける部分があるなと思いました。

Rich氏も交えてビールへ
======================
カンファレンス2日目が終了しました(PyCon Singaporeの3日目はチュートリアルデーです)。
ライトニングトークやカチッとしたクロージングもなかったのですが、それがSingapore流のようです(以前もそんな感じでした)。

終了後はキーノートスピーカーのRich氏や知り合い、その場にいた人に声をかけてビールを飲みに行きました。
Rich氏(帽子をかぶっている人)はアメリカ、タイ在住のロシア人、マレーシア、イスラエル、シンガポール在住の日本人と様々なメンツで一緒に楽しくビールを飲みました。
会計を担当してくれたイスラエルの女性が、誰がなにを頼んだかを確認してセント単位まで細かく金額計算をしていたのが印象的でした。

.. figure:: /images/sg/brewerkz.jpg
   :width: 400

   Brewerkzにて

ちなみにこの店は、2018年にSlackで寺田さん(`@terapyon <https://twitter.com/terapyon>`_)から「どこかいいビールの店をたのむ」と言われて、参加していない私が検索してよさそうなので紹介した店でした。
一年越しで来られて満足しました。

* 参考: `Day2：今すぐ始められる機械学習，“Pythonic”なコードを書くには？：「PyCon APAC 2018 in Singapore」参加レポート <https://gihyo.jp/news/report/01/pycon-apac2018/0002?page=3>`_

.. nikkieコラム https://docs.google.com/document/d/1dcDg6e3m_chaPGt32Xy98OpLadtAO14DvPZpjLmOC7Y/edit

.. admonition:: 機械学習のチュートリアルに参加して

   * nikkie(`@ftnext <https://twitter.com/ftnext>`_)

   PyCon Singaporeでは、3日目の10/12(土)がチュートリアルDayでした。
   午前と午後の2部構成で、 `3時間のチュートリアルが合計6本 <https://pycon.sg/tutorials/>`_ がありました。
   機械学習、スクレイピングといった馴染みのあるものから、ゲーム、ブロックチェーン、Kubernetes、ドローンといった幅広いチュートリアルがありました。
   これらは `プロポーザルを募集して <https://twitter.com/pyconsg/status/1140599350986330112?s=20>`_ 採択されたものです。

   チュートリアルにはカンファレンスとは別にチケットが必要でした。
   1本あたり70シンガポールドル(約5,500円)で、午前・午後1本ずつ受けるなら11,000円程度かかります。
   今回は **午前の機械学習のチュートリアルにだけ参加** し、午後は同行者とシンガポールを観光していました。

   チュートリアルの日もカンファレンスの2日間と同じく、朝食、ランチ、おやつがありました。
   参加者はカンファレンスの半分くらいという印象で、食べ物の量も減らしていました。
   スポンサーブースはなく、こじんまりと運営されていました。

   .. figure:: /images/sg/tutorial-breakfast.jpg
      :width: 400

      チュートリアルの朝ごはん(バナナケーキやサンドイッチ)

   機械学習のチュートリアルは、小さめのレクチャールームで20〜30人くらいで行われました。
   スピーカーのTimothy Liu氏は、NVIDIAの学生インターンで、過去にもTensorFlowのハンズオンを開いているそうです。
   扱った内容は、10月にリリースされたTensorFlow 2.0のアップデートと、モデルの学習に要する時間を縮める手法の紹介でした。
   機械学習が初めての方にも配慮されていましたが、参加者は機械学習経験者が多かったと思います。
   小刻みに質問タイムをはさみながら、インタラクティブに進みました。

   TensorFlow 2.0のアップデートの中では、 **Dataset** が印象に残っています。
   CPUとGPUを交互に動かすと、一方が動いている間、他方は待ち状態になります。
   Datasetを用いると、CPUの処理のパイプラインを組んで、CPUとGPUを並列で動かすことができ、学習に要する時間を短縮できます(`スライド <https://docs.google.com/presentation/d/17vqWDODxWg-AMX6U_3oI0_qFRzA8Tl5hVlLxyRuOt8E/edit#slide=id.g62e869bebe_0_236>`__)。
   また、Datasetとして共通のインターフェースを持つため、Datasetの名前を変えるだけで、別のデータでもコードを動かせるそうです！
   TensorFlowには `100を超えるDataset <https://www.tensorflow.org/datasets/catalog/overview>`_ があるそうで、扱いが揃うのは便利だと思いました。
   なお、手元のデータからもDatasetを作れるそうです。

   .. figure:: /images/sg/liu.jpg
      :width: 400

      TensorFlow 2.0のアップデートについて解説するLiu氏

   モデルの学習に要する時間の短縮については、XLA(Accelerated Linear Algebra Compiler)という計算グラフのコンパイラ(`スライド <https://docs.google.com/presentation/d/1F7hBey7m7bKSmLB4-Ipe9KvZl--TkaJGi69wRzzpAGM/edit#slide=id.g62ec196882_0_55>`__)や、AMP(Automatic Mixed Precision)という複数の精度を混ぜた計算を自動化する手法(`スライド <https://docs.google.com/presentation/d/1dVkpmttGWf49_3wk0PSY97Wgqfc4TEJczzwEtsbmzXQ/edit#slide=id.g62fcf57699_0_129>`__)について、紹介とハンズオンがありました。
   これらは全く知らなかったのですが、簡単な設定で有効にできたので、実務でも試しやすそうです。
      
   資料は以下で公開されていますので、興味のある方はご覧ください。
   ソースコードはGoogle Colaboratoryで開け、すぐに試すことができます。

   * 全スライド: `PyCon SG219 Tutorial <https://drive.google.com/drive/folders/1RR0UhnvJ3PHL4sGRe2du4_w66Kg9KNVr>`_
   * ソースコード: `NVAITC/pycon-sg19-tensorflow-tutorial <https://github.com/NVAITC/pycon-sg19-tensorflow-tutorial>`_

   海外のPyConのチュートリアルに参加してみたい方には、「自分の知っていること + α」のチュートリアルへの参加をオススメします。
   今回の私の場合、機械学習やTensorFlowは多少経験があり、学習のパフォーマンスというトピックは初めてでした。
   すでに知っている点（「機械学習とは」など）については「そういう説明もあるのか」と別の視点に気づけます。
   また、初めて聞く概念（XLAやAMP）も知っている概念をもとにすることで理解しやすいと思います。
   長時間の英語の聞き取りに不安がありましたが、 `過去のレポート <https://gihyo.jp/news/report/01/europython2019/0002>`_ で紹介された `Otter <https://otter.ai/>`_ を使って、手元で書き起こしを見ていました。

   受講方針やOtterが功を奏し、3時間みっちりのチュートリアルを最後までついていくことができました。
   スピーカーのLiu氏や参加者の皆さま、ありがとうございました。

スタッフ打ち上げに合流
======================
PyCon Singapore 3日目はチュートリアルデーのため、私はこちらには参加せずに日帰りで `LEGOLAND Malaysia <https://www.legoland.com.my/>`_ に行ってきました。
チュートリアル終了後のスタッフ打ち上げにnikkie氏が誘われており、私もMalaysiaから戻って合流しました。
会場はDin Tai Fung(鼎泰豊)です。
まさか台北で行けなかった鼎泰豊にシンガポールで行くことになるとは(笑)。

.. figure:: /images/sg/welldone.jpg
   :width: 400

   スタッフ打ち上げに合流

参加者はMartin氏をはじめとしたスタッフ4名、キーノートのRich氏と日本から参加した4名です。
すでにひととおり注文をしていたようですが、ものすごい量の料理が一気に来てテーブルにまったく乗り切らず、一時小籠包などの入った蒸籠(せいろ)が6段くらい積み上がっていました。
おいしい中華料理を「これはなにかの大会か?」と思いながら、一心不乱に食べました。

スタッフに話を聞いてみたところ、イベントの主催者として動いているのはだいたいここにいるメンバーが全員で、Martin氏(右奥)がメールとのやりとりなどをほとんどしていたそうです。
Martin氏はオープニング、キーノート紹介、クロージングを行っており、写真撮影もしていたので「大変そうだなぁ」と思って見ていました。
確かに、私がスピーカーとしてメールをやりとりしていた相手もMartin氏でした。
今後イベントを主催するスタッフが増えて、PyCon Singaporeが継続的に開催されることを期待します。

鼎泰豊のあとはMartin氏、Rich氏と一緒に近くのドイツビールの店でビールを飲み、私はそのあとさらに `Little Creatures Singapore <https://www.littlecreatures.sg/>`_ に移動してクラフトビールを楽しみました。
Little Creaturesはオーストラリアが発祥で、現在は東南アジアや東アジアに支店があるようです。

おわりに
========
以上でPyCon Singaporeのレポートは終了です。
知り合いと数年ぶりに再会したり、新しい出会いもあったりというカンファレンスでした。
ちなみに、このレポートにたびたび登場しているNoah氏ですが、当然PyCon Singaporeにもボランティアスタッフとして参加していました。
彼はカンファンレンス1日目(10月10日)の終了後に、 `PyCon India <https://in.pycon.org/2019/>`_ (10月12日~15日)のボランティアに向かいました。タフすぎます。

.. figure:: /images/sg/marlion.jpg
   :width: 400

   マーライオン

私の2019年のPythonカンファレンスツアーも残り1ヵ国(インドネシア)となりました。
初めて参加するPyCon Indonesiaはどんなカンファレンスなのか楽しみです。
