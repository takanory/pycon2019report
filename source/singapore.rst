=========================
 PyCon Singaporeレポート
=========================

.. contents:: 目次
   :local:

鈴木たかのりです。
2019年の個人的な挑戦「海外のPythonカンファレンスに応募しまくって、採択されたら行く」も終盤戦です。
今回レポートするPyCon Singaporeは8カ国目です。
過去のレポートもgihyo.jpに掲載していますので、ぜひ興味のある国のレポートを読んでみてください。

* `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201>`_
* `世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019>`_
* `日本をはじめ各国のスピーカーが語るPythonのいま ―「PyCon Thailand 2019」レポート <https://gihyo.jp/news/report/2019/07/0501>`_
* `ヨーロッパのPythonコミュニティと交流できる3日間「EuroPython 2019」参加レポート <https://gihyo.jp/news/report/01/europython2019>`_
* `データサイエンスの実践に必要な4つの柱とは？ ―「PyCon Malaysia 2019」レポート <https://gihyo.jp/news/report/2019/09/0901>`_
* (TBD: Taiwanのレポートへのリンク)

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

* 参考: `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート：レポート <https://gihyo.jp/news/report/2019/03/1201>`_

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

発表しながら会場をみているとうなずいている方とかはいたので、ある程度伝わっているのかなと感じました。
ビールについての小ネタもそこそこウケたので個人的には満足です。
質疑応答の時間がとれなかったのですが、終了後に「シンガポールのビールの場所教えるよ」と声をかけてくれる方がいました(スライドの中に「おいしいビールのお店を教えてください」というメッセージを入れてあります)。
以下がその人(Joshさん)からのメッセージです。

* https://twitter.com/joshourisman/status/1182186293075353601

.. * 青木さんコラム https://docs.google.com/document/d/1Lv6AgAXMhN3wCM3s0xVcS9mL9qGgwii8w08OFRJ2GLc/edit?fbclid=IwAR3mDQvU87qU8sZ1PGiOd8LHecmFbjE_p-sr0U9NoARaEAgjTIC-QKIzCCo

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
   また、今回Apache Beamによるストリーム処理をテーマに登壇した人との繋がりもでき、情報交換することが出来ました(彼からは、KafkaやSparkも良いけど一緒にApache BeamにPRあげてcontributeしよう！と熱烈に誘われました笑)。

   参加者としての所感としては、今回参加したPyConでは機械学習に関するセッションが充実していたように思います。
   シンガポールでは政府がAI人材の育成に力を入れていますし、企業での経験を経て大学院にて機械学習やデータサイエンスを学ぶ人達が増えている環境なので、PyCon SGでもこのような傾向が出ているのかなと想像しました。
   他にもPlatinum SponsorsであるDBS銀行のセッションでは、社内でどのように機械学習モデルの開発やデプロイをしているかについての話がありました。
   DBSはPh.D持ちのData Scientistを多く雇い、シンガポール国内でも有数のデータ分析チームを持つ企業なので、その取り組みについて興味深く拝聴しました。

   Python情報のインプット・アウトプットの場としてPyCon SGはとても良い場だったので、今後も当地や他国で開催されるPyConで積極的に登壇していけたらと思います。

.. nikkieコラム https://docs.google.com/document/d/1dcDg6e3m_chaPGt32Xy98OpLadtAO14DvPZpjLmOC7Y/edit

.. admonition:: 機械学習のチュートリアルに参加して

   * nikkie(`@ftnext <https://twitter.com/ftnext>`_)

   PyCon SGでは、3日目の10/12(土)がチュートリアルDayでした。
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
