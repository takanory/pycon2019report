=========================
 PyCon Singaporeレポート
=========================

.. contents:: 目次
   :local:


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
