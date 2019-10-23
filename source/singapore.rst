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

この前夜祭での重要なタスクの一つに、 `Python Boot Camp <https://www.pycon.jp/support/bootcamp.html>`_ Tシャツを神谷さんに渡すということがありました。

.. figure:: /images/sg/kamiya.jpg
   :width: 300

   Tシャツを受け取ってご満悦の神谷さん

オープニング
============

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
