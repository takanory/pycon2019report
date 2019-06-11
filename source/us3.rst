==============================
 US PyCon 2019レポート: 第3回
==============================

カンファレンス3日目と開発スプリントなど様子をお伝えします。
PyCon3日目のPython Steering Councilによるキーノートや私が発表したポスターセッションなどについてレポートします。

他にも、Fun Run、Job Fairなどにさまざまなトピックついてレポートします。

.. contents:: 目次
   :local:

ライトニングトーク
==================
* ビデオ: https://www.youtube.com/watch?v=bnxxoTx9Sko

3日目は朝8:40からライトニングトークです。朝早いですね...
いくつかの発表をピックアップして紹介します。

* Code Our Dreams
  
  最初は高校生の発表でした。シカゴの高校生で、 `Code Our Dreams <codeourdreams.org>`_ というXXXXについてのプロジェクトをすすめているそうです。
  高校生がこのPyCon場で堂々と発表してすごいなーと感じました。

.. figure:: /images/us/codeourdreams.jpg
   :width: 400

   Code Our Dreamsについての発表

* learn to program with minecraft

  PythonからMinecraftにつなげられるシステムはありますが、現状は片方向(Python→Minecraft)しかやりとりができません。
  それをWebSocketを使用して双方向でやりとりできる仕組みを開発中とのことです。
  現在はコンセプト段階とのことです。

* PySlackers

  Pythonユーザーが集まっているSlack上のオープンコミュニティの紹介です。
  https://pyslackers.com/ から参加できます。
  現在21,352のメンバーがおり、79のチャンネルがあるそうです。
  無料版のSlackは参照できるメッセージ数に上限があり、現在は一週間くらいで過去のメッセージが見れなくなるそうです。

* conda-forge

  Anacoda用のパッケージをwheelに変換するライブラリの紹介です。
  `conda-press <https://github.com/regro/conda-press>`_ を使うと変換できるそうです。

* Regional Python Conferences!

  各地域、各国のPython関連のカンファレンスを紹介するLTです。
  1イベント30秒くらいでテンポ良くつないでいきます。
  PyCon Africa(今年初めて開催される、アフリカ全域のPyCon)や、PyCon JPの紹介もありました。

  スライドはあっても発表する人がいないときに、その前のイベントの人が「このイベントのことはよく知らないけどー」とか言いながら、適当に説明するのが個人的には面白かったです。
    
.. figure:: /images/us/pycon-africa.jpg
   :width: 400

   PyCon Africaはガーナで8月に開催

.. figure:: /images/us/pycon-jp.jpg
   :width: 400

   寺田さん(`@terapyon <https://twitter.com/terapyon>`_)によるPyCon JPの紹介

.. admonition:: コラム: 5k Fun Run/Walk

   * Lina Katayose(`@selina787b <https://twitter.com/selina787b>`_)

   カンファンレンス3日目の朝にはFun Runというイベントがありました。
   
   `5k Fun Run/Walk <https://us.pycon.org/2019/5k/>`_ はタイトルの通り、5kmを楽しく走るイベントです。
   いつかやってみたいと思っており、今年初めて参加できました。

   参加者は朝6時にカンファレンス会場近くの集合場所に集まり、スクールバスでEdgewater Parkに移動し、この公園内でレースをします。
   Fun Run開始時はとても寒く、気温は11℃くらいでした。
   朝早く起きて「寒い中に何でこんなことするんだ」と自問自答しながらも、レース会場に向かっていました。
   十分な防寒対策などはなく、私はレギンスとPyLadies Tシャツのみ。
   レース開始までガクガク震えながら待っていました。

   レース参加者は事前に受付で参加チケットを渡して、レースTシャツとゼッケンを渡されているようでした。しかし、私の英語理解不足で、Tシャツとゼッケンを交換できておらず、当日スクールバスの中で交換をしました。
   スクールバスはアメリカ映画で見た黄色いもので、初めて乗りました。

   .. figure:: /images/us/schoolbus.jpg
      :width: 300

      黄色スクールバス

   バスの中では、隣に座った方とお話しました。いろいろ話しているうちにレース会場に到着し、簡単な準備運動をしてレースの開始を待ちます。レース会場は簡易的なものかと思いきや、設備もしっかりとしていて驚きました。

   .. figure:: /images/us/selina.jpg
      :width: 200

      PyLadies Tシャツ

   そして、レースが始まりました。はじめ私は先頭集団に何とかついていきましたが、途中から急激なペースダウン。筋トレはしていたものの走る練習をしていなかったため、ぜんぜんダメでした。それでも「せっかく来たのだから走り切ろう」という気持ちが働き、走り切りました。それにしても疲れた！けど、走り切った！

   結果、私の記録は34分34秒。女性の部で5位(9人中)、全体では48位(62人中)でした。
   5kmレース自体も初めてだったので、自分なりには良いかなと思っています。次回は23分を目指したいです！

   レースの結果は以下のページから参照できます。

   * `PyCon 5k Fun Runの結果 <https://www.hermescleveland.com/roadracing/results/2019/PYCON.htm>`_
    
Keynote: Python Steering Council
================================
* ビデオ: https://www.youtube.com/watch?v=8dDp-UHBJ_A

ライトニングトークに続けてPython Steering Councilによるキーノートがありました。
Python Steering Councilとは

Pythonの言語仕様の策定は、Guido氏が `BDFL <https://ja.wikipedia.org/wiki/%E5%84%AA%E3%81%97%E3%81%84%E7%B5%82%E8%BA%AB%E3%81%AE%E7%8B%AC%E8%A3%81%E8%80%85>`_ として最終決定を行ってきていました。
しかし、Guido氏が2018年7月12日にBDFLからの引退を表明したため、今後の仕様策定をどう決めていくかという議論があり、 `PEP 13 -- Python Language Governance <https://www.python.org/dev/peps/pep-0013/>`_ でPython Steering Councilという5名の組織で決定していくこととなりました。
その後、 `PEP 8100 -- January 2019 steering council election <https://www.python.org/dev/peps/pep-8100/>`_ で投票が行われ、メンバーが決定しました。

* 参考: 引退を表明したメール `[python-committers] Transfer of power <https://mail.python.org/pipermail/python-committers/2018-July/005664.html>`_

このキーノートでは、2日目のレポートのインタビューにも出ていた、PSF(Python Software Foundation)のExexutive DirectorのEwa Jodlowska氏が司会進行し、それに対して5名のCouncilメンバーが答える形で進行しました。

.. figure:: /images/us/council.jpg
   :width: 400

   Python Steering Council

* Ewa: 質問: まずは自己紹介をお願いします。

  * Berry Warsaw: 最初のPython workshopは20名の参加者だったけど、25年ですごく大きくなった。
  * Brett Cannon: VSCodeの開発者です。
  * Carol Willing: 2016にフィリピンでキーノートをやった。Pythonは科学、データサイエンス、組み込み、Webとかいろいろ使えるよね。
  * Guido van Rossum: 私はプログラマーです。去年燃え尽きたけど、自分でSteering Councilに立候補した。
  * Nick Coghian: 昔はハードウェアとC++を使ってた。

* 質問: governance(組織運営)が変わってPythonは変化し続けていける?

  * Guido: PEP(Pythonの拡張提案)に対してyes/no、A/Bを選ぶのはちょっとストレスフルだった。Steering Councilによる投票は...。PEP-13でguidelineをきめている。将来的には...

* Ewa: PEP581 Mariattaがauthor。

  * Brett: bugs.python.orgに入った
  * https://www.python.org/dev/peps/pep-0581/
  * PEP-588 になっていく

* Ewa: packaging workshopはmozillaからサポートを受けた。次のアクションは?

  * Nick: 

* Ewa: PEP-1のPEPプロセスを変える?

  * PEPsは決定するためのプロセス
  * BDFL delegatesがあるよ
  * next generation of Python leaders
  * keep Python and community healty
  * next 25年

* Ewa: Python全体を見ていく予定ですか?

  * Guido: Pythonのインプリメンテーションを見ていく。

* Ewa: Python2のサポートが2020年1月1日で終了予定ですが、何かプランはありますか?

  * ここで会場に対して「Python 2を使っている人」と質問して手が上がりました。「思ったよりは少ない」とのコメントでした。
  * Guido: パーティーしよう。
  * Nick: 商用ベンダーはPython 2を2020以降もサポートすると思う。
  * Carol: 去年のPyCconでInstagramが2から3に移行したキーノートがあったでの、参考にするとよさそう。

* Ewa: Diversity(多様性)をひろげるのになにか考えはありますか?

  * Carol: Mariattaは最初の女性のcore開発者。楽しかったらSprintにも参加してね。
  * Barry: Paul Everett。彼はコミュニティでいろんな人をメンターした。

* ここで、sli.doを使って会場からの質問を受け付けました。
* 質問: 好きなPEPはなに?

  * Barry: `PEP 401 -- BDFL Retirement <https://www.python.org/dev/peps/pep-0401/>`_ (エイプリルフールのジョークPEPです)
  * Brett: `PEP 3100 -- Miscellaneous Python 3.0 Plans <https://www.python.org/dev/peps/pep-3100/>`_
  * Crarol: `PEP 500 -- A protocol for delegating datetime methods to their tzinfo implementations <https://www.python.org/dev/peps/pep-0500/>`_
  * Guido: `PEP 343 -- The "with" Statement <https://www.python.org/dev/peps/pep-0343/>`_

* 質問: We hear a lot about burnout of core developers. Does the council have any plan to improve this? Is there anything that the community can d?o

  * Brett: PEP-581, 去年の私のキーノートをPoster
  
.. figure:: /images/us/council2.jpg
   :width: 400

   Councilメンバー

Poster Session
==============
* あとで書く
* いろんな人が話をきいてくれたよ
* Guidoもきてくれたよ
* Paulとも再開

.. admonition:: コラム: Job Fair

   * Masaki Kagesawa (影澤 正輝: `@Masakikage <https://twitter.com/Masakikage>`_)

   僕にとってPyConでの最大の収穫はJob Fairでした。普通アメリカ(筆者中: 影澤さんはニューヨーク大学の大学生)で大学生が行くJob Fairは各企業にリクルーターが1〜2人来て、人気企業は話すだけで30分待ちになるのが普通です。

   PyConの参加者の多くは仕事探しをしているわけではないためJob Fairは混んでなく、各ブースでエンジニアとリクルーターの両方からしっかりと話を聞けました。

   アメリカでの就職はオンラインでアプリケーション(日本のエントリーシートの様なもの)を提出するだけでは、なかなかインタビュー(面談)すらしてもらえません。
   よっぽど優れていなければ、人事に数秒目を通して落とされます。
   PyConでは人事の方としっかり話して名刺をゲットしたので、オンラインではなく直接メールして応募する予定です。
   15社くらい連絡先を入手したので就活にはものすごく役にたちました。

   .. figure:: /images/us/jobfair1.jpg
      :width: 300

      Job Fair参加企業のリスト


   .. figure:: /images/us/jobfair2.jpg
      :width: 400

      Job Fairブースの様子

   .. figure:: /images/us/jobfair3.jpg
      :width: 400

      Kenshoブース

   .. figure:: /images/us/jobfair4.jpg
      :width: 400

      Citadelブース


Python Software Foundation Community Report and Community Service Awards
========================================================================
* ビデオ: https://www.youtube.com/watch?v=P4IfFLAX9hY

ここではEwa Jodlowska氏により、PSF(Python Software Foundation)の報告と、Community Service Awardsの表彰が行われました。

Python関連の様々なコミュニティが世界中にあり、いろいろな機会が提供されているという説明がありました。
そして https://python.org/psf/annual-report/2019/ に年次事業報告書が公開されているという説明がありました。
PSFはさまざまなコミュニティをサポートしているということ、また、PSFもサポートをお願いしてるという説明がありました。PSFをサポートするには以下の方法があります。

* https://pycon.us/pbf から寄付する方法
* PyCharmのライセンスを購入すると、その一部がPSFに寄付されること
  
次にPSFチームの紹介がありました。現在PSFチームとしては8名のメンバーがフルタイムで活動しているようです。最近PSFに入った人もいれば、20年間活動している方もいらっしゃるそうです。

.. figure:: /images/us/psf-team.jpg
   :width: 400

   PSFチーム

   
最後に `PSF Community Service Awards <https://www.python.org/community/awards/psf-awards/>`_ の表彰が行われました。
複数のコミュニティのオーガナイザーや、PyPIの移行作業を行った人、複数年PyConのプログラムメンバーを務めた方などが表彰されていました。

いろいろな人に支えられて、PSFを中心としたPythonコミュニティが拡がっていることを感じました。表彰されたのは以下の方々です。

* Mario Corchero: PyCon ES、PyLondinium、2018年のPyCon Charlas(スペイン語)トラックの主催者
* Chukwudi Nwachukwu: ナイジェリアのPythonコミュニティの拡大
* Alex Gaynor: 2015-22016のPSF Director。PyPIの移行などを行う
* Mariatta Wijaya: CPythonのコントリビューター。PyCascadesのCo-Chair
* Maricela Sánchez Miranda: 2019のPyCon Chalas ChairやPyCon Day Mexico、Django Girls Pueblaの主催
* John Roa: PyCon Colombiaの創始者であり主催者
* Stefan Behnel: Cythonとlxmlのメンテナー
* Eric Ma: 複数年のFinancial AidのCo-ChairやPyConプログラム委員会のメンバー

Final Remarks and Conference Close
==================================
* ビデオ: https://www.youtube.com/watch?v=ADutU_sFXXA

カンファレンスの最後はクロージングです。
Closing Dinnerの案内や次の日から行われる開発Spritの説明などが行われました。

そして、ここで昨夜行われたPyLadiesオークションの収益金について報告がありました。
毎年寄付金額が増えており、今年はなんと41,000ドルでした。すごい金額です!!

.. figure:: /images/us/auction-result.jpg
   :width: 400

   寄付金額は41,000ドル!(約450万円)

また、各地域のPyConの情報をまとめた https://pycon.org/ をリリースしたので、各地域PyConの主催者は情報を更新してほしいという案内がありました。
筆者も `リポジトリ <https://github.com/python-organizers/conferences>`_ のコミット権をもらったので、更新する予定です。

今回のPyConには約3,200名が参加したそうです。
参加者に対して、自分の近くのPythonコミュニティに参加したり、開催をサポートしたり、主催してほしいというコメントがありました。

次に2020, 2021のPyConのChairである、Emily Morehouse-Valcarcel氏(`@emilyemorehouse <https://twitter.com/emilyemorehouse>`_)が紹介されました。
開催地はピッツバーグで日程は決まっており、2020年4月15日から23日、2021年5月12日から20日に開催されます。

最後にThanksというスライドでPyConを作ってきた人たちを会場全体で拍手で讃えました。
呼ばれた人は立ち上がって参加者からの感謝の拍手を受けます。
最初は各スタッフ、次いで、当日ボランティアなどが紹介されました。
筆者もポスタースピーカーと言われたときに立ち上がって、拍手を受けてこのコミュニティの一員になったような気がしました。
そして最後に会場の全員に対して感謝を述べて「2020年にピッツバーグで会いましょう」と締めくくってカンファレンスは終了しました。

.. figure:: /images/us/pittsburgh.jpg
   :width: 400

   PyCon 2020、2021の開催地はピッツバーグ

Dinner Party
============

開発Sprint
==========
* Development Sprints
* Packaging Summitに参加
* https://twitter.com/EWDurbin/status/1125414881363148800
* https://files.slack.com/files-pri/T02PZGMUG-FJH75G9JB/image_from_ios.jpg
* https://docs.google.com/document/d/19LfDGT-wO3oE3ha1B1n273M5v8DYKMVrOBm2wuqKw0s/edit?usp=sharing

.. admonition:: コラム: 初めてのSprint

   * Masaki Kagesawa (影澤 正輝: `@Masakikage <https://twitter.com/Masakikage>`_)

   僕は今までOpen Sourceに貢献したことがなく今回が初めてでした。最初はFlaskに参加しようと思いましたけど“Good First Issue”タグが付いたIssueがほぼなく、初心者歓迎で多くの人が使ってるpipチームに参加しました。メンターはなんと自分と同い年、インドの大学に通ってる学生でした。世界中のみんなに使われてるpipのコアメインテナーが２１歳とはびっくりしました。

   初日はコードのリファクタをしてPRを開きました。次の日マージされてると思ったらコミットのコメントがガイドと合ってないと注意されてました。git rebase後もう一度PRを開いてしっかりとマージしてくれました。

   今後も貢献したいならPRをテストして欲しいとメンターから言われ、言われてみればpipは８０個以上もPRが開いてました。貢献者はたくさんいてコードを書いてくれるけどメンテナーは人数少ないからなかなかPRをテストしてマージする時間がないと。

   自分でもコードを書くよりテストをしてマージに貢献する方がインパクトあるなと思いました。今後は週末など時間があるときにオープンソースやります。


   .. figure:: /images/us/packaging-summit.jpg
      :width: 400

      Sprint中PyPIチームはミニカンファレンスを実施した

   .. figure:: /images/us/sprints.jpg
      :width: 400

      Sprint会場の様子
         
まとめ
======
