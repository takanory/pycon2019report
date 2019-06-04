==============================
 US PyCon 2019レポート: 第3回
==============================

* 3回目の書き出し的なやつ。

ライトニングトーク
==================
* ビデオ: https://www.youtube.com/watch?v=bnxxoTx9Sko
* 朝8:40から開始...
* 高校生の発表

  * Code Our dreamsをシカゴで始めた
  * codeourdreams.org

* learn to program with minecraft

  * つなげられるけどone-way
  * websocketでつなぐ(へー
  * まだコンセプト段階らしい

* PySlackers

  * オープンコミュニティ
  * https://pyslackers.com/
  * 21352 members, 79 channels
  * メッセージライフタイムが一週間(うける

* conda-forge

  * conda-press: conda -> wheel
  * https://github.com/regro/conda-press

* Regional Python Conferences!

  * PyCon Africaの人もいた
  * terapyonがJPについて発表してた

.. admonition:: 5k Fun Run/Walk

   * Lina Katayose(`@selina787b <https://twitter.com/selina787b>`_)

   `5k Fun Run/Walk <https://us.pycon.org/2019/5k/>`_ はタイトルの通り、5kmを楽しく走るイベントです。
   いつかやってみたいと思っていたのですが、今年参加できました。

   参加者は朝6時にカンファレンス会場近くの集合場所に集まり、スクールバスでEdgewater Parkに移動し、公園内でレースをします。
   Fun Run開催時はとても寒く、11℃くらいだったと思います。
   朝早く起きて、寒い中に何でこんなことするんだと自問自答しながらも、レース会場に向かっていました。
   十分な防寒対策などはなく、レギンスとPyLadies Tシャツのみ。
   レース開催までガクガク震えながら待っていました。

   レース参加者はどうやら、受付で参加チケットを渡してレースTシャツとゼッケンを渡されているようでしたが、私の英語理解不足で、Tシャツとゼッケンを交換できていなく、当日、スクールバスの中で交換をしました。
   そのスクールバスもアメリカ映画で見た黄色のスクールバス、初めて乗りました。

   .. figure:: /images/us/schoolbus.jpg
      :width: 300

      黄色スクールバス

   バスの中では、隣に座った方とお話しました。いろいろ話しているうちにレース会場に着き、簡単な準備運動をしていました。レース会場は簡易的なものかと思いきや、設備もしっかりとしていて驚きました。

   .. figure:: /images/us/selina.jpg
      :width: 200

      PyLadies Tシャツ

   そして、レースが始まりました。はじめ私は先頭集団に何とかついていきましたが、途中から急激なペースダウン。筋トレはしていたものの走る練習をしていなかったため、ぜんぜんダメでした。それでも自分自身のはせっかく来たのだから走り切れという気持ちが働き、走り切りました。

   にしても疲れた！けど、走り切った！

   結果、私の記録は34分34秒。女性の部で5位(9人中)、全体では48位(62人中)でした。
   5kmレース自体も初めてだったので、自分なりには良いかな。と思っています。次回は23分を目指したい！

   詳細はこちらをご覧ください

   * `PyCon 5k Fun Runの結果 <https://www.hermescleveland.com/roadracing/results/2019/PYCON.htm>`_

     
* [ ] Day 3: Fan Run(se-lina)
* https://docs.google.com/document/d/1fmjgxNvYfnDd-RNQTFFEC0iCJx2wnuXM30-ZEtVVvEU/edit?usp=sharing  

    
Keynote: Python Steering Council
================================
* ビデオ: https://www.youtube.com/watch?v=8dDp-UHBJ_A
* Ewaが司会
* Barry, Brett, Carol, Guido, Nick
* Berry

  * 最初のPython workshopは20名の参加者
  * 25年ですごくでかくなった
* Brett

  * VSCodeの開発者
* Carol

  * 2016にフィリピンでキーノートやった
  * Pythonは科学、データサイエンス、組み込み、Webとかいろいろ使えるよね
* Guido

  * I was a programmer
  * 去年燃え尽きた
  * I nominated myself for steering committee
* Nick

  * ハードウェアとC++使ってた

* governance が変わってPythonは変化し続けていける?

  * Guido: PEPにyes/no, A/Bを選ぶのはちょっとストレスフルだった。steering councilによる投票は...PEP-13でguidelineをきめている。将来的には

* ewa: ここ3年でデータサイエンスとPythonはできあくなっている。科学コミュニティとの関係は?

  * Carol:

* EWA: PEP581 Mariattaがauthor。

  * Brett: bugs.python.orgに入った
  * https://www.python.org/dev/peps/pep-0581/
  * PEP-588 になっていく

* EWA: packaging workshopはmozillaからサポートを受けた。次のアクションは?

  * Nick: 

* EWA: PEP-1のPEPプロセスを変える?

  * PEPsは決定するためのプロセス
  * BDFL delegatesがあるよ
  * next generation of Python leaders
  * keep Python and community healty
  * next 25年

* Python全体を見ていく?

  * Guido: Pythonのインプリメンテーションを見ていく

* Python 2使っている人→結構手が上がる→思ったよりは少ない
* なにかプランはありますか?

  * Guido: パーティーしよう
  * Nick: 商用ベンダーPython 2を2020以降もサポートすると思う
  * Carol: Instagramが2から3に移行したキーノートがあった

* Ewa: diversityをひろげるのになにか考えはある?

  * Carol: Mariattaは最初の女性のcore開発者。楽しかったらSprintにも参加してね。
  * Barry: Paul Everett。彼はコミュニティでいろんな人をメンターした。

* pycon.us/panel: sli.doで質問を受け付け
* What is your favorite PEP?

  * Barry: 401
  * Brett 3100
  * Crarol 500
  * GUido: 343

* We hear a lot about burnout of core developers. Does the council have any plan to improve this? Is there anything that the community can d?o

  * Brett: PEP-581, 去年の私のキーノートをPoster
  
Poster Session
==============
* あとで書く
* いろんな人が話をきいてくれたよ
* Guidoもきてくれたよ
* Paulとも再開

Jobs Fair
=========
* [ ] Day 3: Jobs Fair(Kagesawa)
* https://docs.google.com/document/d/19LfDGT-wO3oE3ha1B1n273M5v8DYKMVrOBm2wuqKw0s/edit?usp=sharing

Python Software Foundation Community Report and Community Service Awards
========================================================================
* ビデオ: https://www.youtube.com/watch?v=P4IfFLAX9hY
* ewa
* いろんなコミュニティがあって、いろんな機会があるよ
* python.org/psf/annual-report/2019/
* PSFはいろんなコミュニティをサポートするよ
* PSFのサポートも尾根阿木

  * pycon.us/pbf からdonate
  * PyCharmのライセンスを買ってPSFに渡す?
* PSFチームの紹介。いつからPSFにいてなにやっているかとか。最近入った人もいれば、PSFで20年活動人とかもいる。
* Community Service Award Winners

  * Mario Corchero: Spain, Latin America UKでオーガナイザー
  * Chukwudi Nwachukwu: ナイジェリアのコミュニティ
  * Alex Gaynor: PSF Director, PyPIの移行とか
  * Mariatta Wijaya: CPythonとか
  * Mayela Snachez Miranda: PyCon Chalas 2018 Chair, PyCon Mexico, Django Girls Puebla
  * John Roa: founda and PyCon Colombia Chair
  * Stefan Behnel: CPython, XMLのmaintenar
  * Eric Ma: PyCon program member several year

Keynote - Nina Zakharenko
=========================
* ビデオ: https://www.youtube.com/watch?v=35mXD40SvXM
* 中にはいっているボードのプログラムの仕方
* ギャル電っぽい
* カメラで動作を見せながらやっていた
* printでデバッグ

Final Remarks and Conference Close
==================================
* ビデオ: https://www.youtube.com/watch?v=ADutU_sFXXA
* 3200名が参加
* Developer surbeyは100以上の国から8000名
* pycon.org
* pycon.us/regional
* 2020, 2021のChair Emilyの紹介

Dinner Party
============

開発Sprint
==========
* Development Sprints
* Packaging Summitに参加
* https://twitter.com/EWDurbin/status/1125414881363148800
* https://files.slack.com/files-pri/T02PZGMUG-FJH75G9JB/image_from_ios.jpg
* https://docs.google.com/document/d/19LfDGT-wO3oE3ha1B1n273M5v8DYKMVrOBm2wuqKw0s/edit?usp=sharing
