=================================
 EuroPython 2019 レポート: 第3回
=================================

.. contents:: 目次
   :local:

EuroPython3日目の様子をお伝えします。

この日のキーノートであったPythonの高速化についての深い話や、Python 3.8以降の新機能についてのトークなどについてレポートします。

キーノート: Victor Stinner
==========================
* タイトル: Python Performance: Past, Present and Future
* スライド: https://github.com/vstinner/talks/blob/master/2019-EuroPython/python_performance.pdf
* ビデオ: https://www.youtube.com/watch?v=T6vC_LOHBJ4&t=1895s  

Victor Stinner氏はRedHatで働いており、2010年からCPythonのメンテナンスを行っているそうです。
このトークではPythonのパフォーマンスについて過去、現在、未来について語られました。

**過去**

CPython(C言語で書かれたPython実装)は1989年から開発されています。
他に以下のような

* 1997: Jython
* 1998: Stackless Python
* 2006: IronPython
* 2014: MicroPython

そしてPythonを高速化するプロジェクトとして以下が紹介されました。
これらの多くはJITコンパイラーを使用して高速化を目指しています。

* 2002-2012: psyco(Armin Rigo)
* 2007: PyPy
* 2009-2010: Unladen Swallow(Google)
* 2014-2017: Pyston(Dropbox)
* 2016-2017: Pyjion(Microsoft)

Pythonを高速化するにはCPythonをフォークする場合と、1から実装する2つの方法があります。
CPythonからフォークする場合は古いCPythonの実装によるパフォーマンスの限界や、GIL(`グローバルインタプリタロック <https://ja.wikipedia.org/wiki/%E3%82%B0%E3%83%AD%E3%83%BC%E3%83%90%E3%83%AB%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%97%E3%83%AA%E3%82%BF%E3%83%AD%E3%83%83%E3%82%AF>`_)の制限があります。
1から実装する場合はGILの制限などがありませんが、C拡張はサポートされなかったり遅いという問題があります。
CPythonには30名のアクティブなコア開発者がおり、最新の機能は最初にCPythonに実装されます。

ここからは2つの終了したプロジェクトについての説明がありました。

* Unladen Swallow(2011): Googleのプロジェクト。多くのGoogleのPythonコードではパフォーマンスは重要な問題ではないため終了。
* Pyston(2017): Dropboxのプロジェクト。パフォーマンスに関するコードはGoのような他の言語に切り替えた。互換性の維持に多くの時間を割いた。

**現在**

`PyPy <https://pypy.org/>`_ はCPythonと置き換え可能で、4.4倍速くなるそうです。
しかしPyPyにも課題はあります。C拡張はCPythonよりは遅い、JITのためにより多くのメモリと起動時間が必要であることです。
そのためPyPyはサーバーサイドでずっと起動しているサービスなどに向いています。

次に図を使用してGILについての説明がありました。
CPUバウンドの処理の場合はマルチスレッドでもGILの制限によって1つのスレッドしか実行されません。
そこでマルチプロセッシングでGILの制限を受けない方法があります。
Python 3.8から共有メモリがここで使用できるようになるそうです。

別の解決策として `Cython <https://cython.org/>`_ も紹介されていました。
CythonはC拡張をPythonと似た言語で簡単に記述する方法です。
複数のPythonバージョンで動作します。

`Numba <https://numba.pydata.org/>`_ はPythonとNumPyの一部処理をJITで高速化するツールです。GPUなどを使用して高速化が可能です。

また https://speed.python.org/ というサイトでCPythonの実行速度を計測しているそうです。
ある変更によってCPythonが速くなったか、遅くなったかを確認できるようになっています。
このサイトはよくできているなと感じました。

.. figure:: /images/euro/speedpython.png
   :width: 400

   https://speed.python.org/

**未来**

今後のPythonのパフォーマンス向上についていくつか紹介されていました。

現在のC APIにはいくつか課題があるため、Python 3.8でC APIを3つのレベルに分類するそうです。
また安定版のABI(Application Binary Interface)がPython 3.8以降でサポートされるそうです。

CPythonのGCをTracing GCに変更するそうです。Tracing GCは多くのモダンなプログラミング言語やPyPyで採用されています。
ただし、既存のC APIはリファレインスカウントを継続して使用するそうです。

サブインタープリターは `PEP 554 -- Multiple Interpreters in the Stdlib <https://www.python.org/dev/peps/pep-0554/>`_ で提案されたものです。
1つのCPythonプロセスの中で複数のインタープリターを動作させることにより、GILの制限を回避するというアイデアです。

Pythonは遅いとよく言われますが、過去にいくつかのプロジェクトが失敗したこと、現在いくつかの対策があること、そして今後も継続的にPythonのパフォーマンスについて改善が継続していくことがわかるトークでした。

The Story of Features Coming in Python 3.8 and Beyond
=====================================================
* スピーカー: Andrey Vlasovskikh
* スライド: http://blog.pirx.ru/media/files/2019/python3.8/#1

.. figure:: /images/euro/andley.jpg
   :width: 400

   Andrey Vlasovskikh氏

Andrey Vlasovskikh(`@vlasovskikh <https://twitter.com/vlasovskikh>`_)氏によるPython 3.8や今後のPythonについてのトークを聞いてきました。
Andrey氏は2016年のPyCon JPのキーノートスピーカーでもあり、そのときはPython 3.6について語ってくれました。
Andrey氏はPyCharmのテクニカルリードでもあり、PEP484、561などのPythonのtypeシステムに対して貢献しています。

* 参考: `2日目 Andrey Vlasovskikh氏基調講演「Pythonのこれから」 <https://gihyo.jp/news/report/01/pyconjp2016/0002>`_

話のメインとなるPytnon 3.8ですが2019年10月21日にリリース予定で、すでに機能は確定したベータバージョンがリリースされています。
新機能を知るためには `What's New <https://docs.python.org/ja/3.8/whatsnew/3.8.html>`_ がよいドキュメントです。
このトークではいくつかの新しい機能や言語仕様について、その歴史やメリットデメリットについて紹介していきました。

まずは `PEP 572 -- Assignment Expressions <https://www.python.org/dev/peps/pep-0572/>`_ です。PEP 572は以下のように ``:=`` という演算子で代入式を実現します。

.. code-block:: python

   >>> if m := re.search('[abc]', 'spam'):
   >>>    print(m.group())
   a

このPEP最初は ``x := expr`` ではなく ``(expr as x)`` という書き方で提案されていたそうです。全体を ``()`` で囲んで変数がサブローカルスコープになるという複雑なものだったが、現在のようにシンプル中たちになったそうです。知りませんでした。

また、このPEP572の採択後Guido氏がBDFLを辞任し、その後 `PEP 13 -- Python Language Governance <https://www.python.org/dev/peps/pep-0013/>`_ でPython言語をどのように運営していくかが議論され、5名のPython Steering Councilが選ばれたという話がありました。
Python Steering Councilについては筆者もUS PyConのレポートで紹介しています。

* 参考: `第3回　3日目朝のLT紹介，キーノートはPython仕様策定のキーパーソンによるパネル <https://gihyo.jp/news/report/01/us-pycon2019/0003>`_

次に紹介したのは `PEP 570 -- Python Positional-Only Parameters <https://www.python.org/dev/peps/pep-0570/>`_ です。
これは関数を ``def pow(x, y, z=None, /):`` のように定義すると ``/`` の前の引数は位置指定しかできなくなります(``pow(x=10, y=20)`` と呼ぶとエラーになります)。
なぜ区切り記号が ``/`` なのかというと、すでに `PEP 436 -- The Argument Clinic DSL <https://www.python.org/dev/peps/pep-0436/>`_ によってC APIの関数の引数用に用いられていたためです。

また、新しいTypeとして ``Protocol``、``Literal``、``Final``、``TypedDict`` が紹介されました。
新しいTypeは https://github.com/python/typing で定義されており、Typing summits、開発Sprintなどで進められているそうです。

Python 3.8の先の話としていくつか紹介されていましたが、興味深かったのは `Mypyc <https://github.com/mypyc/mypyc>`_ です。
Cythonに似ているけどPythonの型を使い、シングルコアでのパフォーマンスが速くなるそうです。
また `PEP 554 -- Multiple Interpreters in the Stdlib <https://www.python.org/dev/peps/pep-0554/>`_ も興味深いです。こちらはマルチコア上でのパフォーマンスを上げる取り組みだそうです。

Python 3.8の新機能の詳しい紹介や、Python 3.9以降の取り組みについて興味深い発表でした。

この日の帰りにAndreyに声をかけたことろ、私のことを覚えてくれていました。
PyCon JP 2016のトートバッグがノートPC入れにちょうどいいらしく、愛用しているそうです(この日も肩から下げていました)。
「またどこかのPyConで会いましょう」と話して別れました。

* Tweet: https://twitter.com/vlasovskikh/status/1149827595346857986

Enhancing Angklung Music Rehearsals with Python
===============================================
* スピーカー: Trapsilo Bumi

Trapsilo Bumi氏はインドネシア出身で日本の `HENNGE <https://hennge.com/jp/>`_ で働いている開発者です。
私はTrapsilo氏と面識はないのですが、日本からのスピーカーと楽器関連ということで発表を聞きに行きました。

.. figure:: /images/euro/hennge.jpg
   :width: 400

   Trapsilo Bumi氏

`アンクルン <https://ja.wikipedia.org/wiki/%E3%82%A2%E3%83%B3%E3%82%AF%E3%83%AB%E3%83%B3>`_ というインドネシアの民族楽器を演奏するときの、楽譜を生成するツールを作成したという話です。
アンクルンは1つの楽器で1つの音しかだせません。そのため一曲を演奏するためには1人が何個も持ち替えたりして演奏する必要があります。ときには1人で複数個を持って演奏することもあるそうです。

で、楽譜からどのように演奏者にどの音を割り振るかということをPythonで計算して出力しているようです。
`openpyxl <https://openpyxl.readthedocs.io/en/stable/index.html>`_ で最終的なスプレッドシートを作成したり、Collision Tableを作成して同時に演奏する音の数を考えたりとかするそうです。
なかなか計算は大変そうだなと思いました。

トークの終了後は当然音楽に興味のある参加者が多く、アンクルンを演奏させてもらったりしていました。

Sprint Orientation
==================
最後のライトニングトークの前に、明日以降のSprintの説明がありました。
Sprintは短期の開発イベントです。以下のようなテーマでSprintが開催されるよということが、各Sprintオーナーから説明されていました。

* CPython、pewpew、PyPy、Best Python LTs, EuroPython Webサイト、PyGame、Bokeh、pytest、MoinMoin Wiki、pandas、scikit-learn

Day 3 ライトニングトーク
========================
* ビデオ: https://youtu.be/T6vC_LOHBJ4?t=30599
  
3日目のライントニングトークで面白かった物をいくつかピックアップして紹介します。

* 20時からライン川で泳ぐよというお知らせ

  Baselでは `Rhine swimming in Basel <https://www.basel.com/en/rhine-swimming>`_ というWebサイトも用意しており、ライン川を泳いで下るというアクティビティがあるそうです。
  荷物を入れる専用のフロートも売っているそうです。

.. figure:: /images/euro/swim.jpg
   :width: 400

   Go with the flow

* Tour de Snake: over the mountains edition

  Day 1のライトニングトークと同じ人かと思っていたら別の人でした。MilanoからBaselまで自転車で3人で来たそうです。
* Why I/You need to go to EuroPython!

  世界中のPyConでスタッフをしているNoah氏による、アジアを中心としたPyConの紹介です。
  Noah氏安定のタイムオーバーで「あと10秒」と司会に言われ、そこから超早口で話し始めると場内は大ウケでした。
* flynt

  ``.format()`` や ``%`` で書かれている文字列をf-stringsに書き換えるツールです。 https://pypi.org/project/flynt/ で公開されています。
  普通に便利そうだなと思いました。

.. admonition:: Otterは海外カンファレンスで超便利そう

   イベントとは直接関係ないのですが、 `@komo_fr <https://twitter.com/komo_fr>`_ に教えてもらったOtterというサービスが海外カンファレンスでは便利そうだなと感じました。

   * `Otter Voice Notes - Otter.ai <https://otter.ai/login>`_

   このサービスはカンファレンスなどの音声を録音して自動的に文字起こしをしてくれるノートサービスです。
   私のように英語の聞き取りが苦手な人には、あとで振り合えるときにかなり便利そうだなと感じました。
   AndroidやiOSのアプリもあり、ログインして録音を開始するとほぼリアルタイムで文字起こしがされていきます。
   実際に使ってみるとサーバー側で翻訳などを行っているため、スマートフォンの電池はそれほど消耗しませんでした。

   ノートの途中に写真なども挿入できるので、あとで見返したときに「この部分の話だ」とわかりやすいのも便利です。
   無料プランでも600分/1カ月まで使用できるので、英語のヒアリングに自信がない人は一度試してみることをおすすめします。

   .. figure:: /images/euro/otter.png
      :width: 400

      Otter上のライトニングトークのログ

Closing
=======
最後はクロージングです。明日からSprintがあるという説明がありました。
EuroPythonは1,100~1,200名ほどの参加で、16名で運営をしていたそうです。
次に、EuroPython 2020のアクティブなメンバーを募集しているという話がありました。
12カ月で100時間くらいの作業が必要だそうです。
そして最後に新しいboardメンバーを紹介してイベントが終了しました。

.. figure:: /images/euro/closing.jpg
   :width: 400

   主催者とボランティアスタッフ

アフターパーティー
==================
このあとパーティーがないかなと情報を探していると、kiwi.comが主催するパーティーに参加できました。
彼らが宿泊しているアパートの屋上にプールがあり、そこでBBQパーティーが行われていました。素晴らしいロケーションです。

ここでもいろいろな参加者と話をしました。「今度彼女と日本に行くんだ」という人にはおすすめのラーメン屋を聞かれました。最近ラーメンを食べてないので答えられませんでしたが...

後半になるとテンションの上がった参加者がプールで泳ぎ始めたのですが、「ウェーイ」「ヒャッハー」と騒いでいたらオーナーらしき人がきてガッツリ怒られていました。すぐ隣に住宅があるので、確かに怒られるなと...そのあとは多少静かに騒いでいました。

.. figure:: /images/euro/kiwi-party.jpg
   :width: 400

   屋上にプールのある会場でパーティー

ロケーションは最高なのですが用意されているビールは普通の缶ビールしかなかった(贅沢)ので、クラフトビールを扱っている `Bierrevier <https://www.bierrevier.ch/>`_ に向かいました。
ただ、やはりスイスではあまりクラフトビールは作られていないようで、クラフトビール的にはクリーブランドが圧勝だなと思いました。

.. figure:: /images/euro/bierrevier.jpg
   :width: 400

   ヨーロッパを中心にたくさんのクラフトビールを扱っている

次の日はスプリントには行かず買い物やパレードを見たり、 `Basel Tattoo <https://www.baseltattoo.ch/>`_ というコンサートを見て過ごしていました。
夕方に「スプリントを終えた人たちでKlaraというフードコートで飲んでいる」とNoah氏に連絡をもらったので、 `Volta Bräu <https://www.voltabraeu.ch/>`_ というブルーパブでビールを飲んでから移動して合流しました。
そこにはさまざまなメンバーがいました。
最後の方は何を話したかあんまり覚えていませんがw、EuroPython Societyの新Boardメンバーが集まっているテーブルでイベント運営とかの話をしていたような気がします。
一度だけの出会いだとお互い忘れてしまうので、またどこかで彼ら彼女らと再会できるといいなと思いました。

.. figure:: /images/euro/klara.jpg
   :width: 400

   EuroPython SocietyのBoardメンバーと

まとめ
======
はじめて参加したEuroPythonのレポートは以上で終了です。
ポスターを一人でやりきったり、スイスに引っ越した知り合いに久しぶりに会って元気な顔を見たりと、楽しく刺激的に過ごすことができました。

来年のEuroPythonの開催地は未定ですが、また参加していろいろな人と再会したいなと思うイベントでした。
次回開催地はビールが盛んな地域がいいなー。

.. figure:: /images/euro/spalen.jpg
   :width: 300

   Gate of Spalen(よく見ると下にいる人がEuroPython Tシャツを着ています)
