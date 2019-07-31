=================================
 EuroPython 2019 レポート: 第2回
=================================

.. contents:: 目次
   :local:

EuroPython2日目と3日目の様子をお伝えします。

Python 1994
===========
* スピーカー: Paul Everitt

.. figure:: /images/euro/python1994.jpg
   :width: 400

   Python 1994
   
Paul氏は現在はPyCharmのDeveloper Advocateですが、以前はZope Corporationの共同創業者だったりと、Pythonの黎明期から活動している方です。
そのPaul氏によって1994年頃のPythonコミュニティについてジョークを交えて面白おかしく発表していました。

最初に「EuroPythonが一番好きなカンファレンスです」と言ってから、突然クリーブランドとピッツバーグ(どちらもUS PyConの開催地)disを挨拶代わりにトークがはじまりました(冗談でしょうが)。
会場に「EuroPython 1に参加したことある人?」と聞いたところ3名いました。はじめてのEuroPythonは2002年に開催されました。

まずは1994年(25年前)がどんな年だったかを振り返ってみます。1994年は以下のような年でした。

* アメリカの大統領はビル・クリントン(1993年に就任)
* Amazonが設立した年
* HTMLのバージョンは3.2
* そしてPython Communityがはじまった年

1994年にPythonの初めてのイベントが会ったそうで、初回は20名が集まりそこで会話をしたそうです。
当然現在のようなイベントサイトもないので、メーリングリストで告知して集まったようです。

Paul氏はその頃からPythonのコミュニティに参加し、現在までにPSFやPlone Foundationの立ち上げメンバーだったり、Zope Corporationの共同創業者などを歴任してきたそうです(すごい)。
なぜPaul氏がPythonを使うようになったかというと、当時はスクリプト言語としてはPerl、Tcl/Tk、Pythonが選択肢としてあったが、勉強するために本屋にいったがいい本がなかったそうです。
Pythonにはオンライン上に `チュートリアル <https://docs.python.org/ja/3/tutorial/>`_ があったため、そこで学んで使い始めるようになったそうです。

他にもいろいろと歴史的な資料(Webサイトやメール)を引用しながら、当時のコミュニティの話が語られていました。
Pythonの歴史を感じる発表でした。

Poster Session
==============
* 日本でPythonってどんくらい盛り上がってんの？みたいな話が多いな
* あと、バーゼル在住の日本の人がいた。Rとか使ってるらしい
* PyCon JPとTWのスピーカーになってるSebastianさんが来た。日本と台湾であおーねって話した。私も両方で発表するよって言ったら「世界は狭いね」って言われた。ウケる
* Remiさんって人が、わざわざこのPoster見に来てくれたらしい。(うれしい
* 日本ではPythonどうなの?って質問が多いかな。→Pythonは普通に人気あるよ。PyCon JPもこんな感じで人数増えてるしねー、みたいな説明をしている
* あとはUDONPyにウケた人が2名いた
* 女性から資金どうしてるって質問があった。
* あとは日本に一ヶ月くらい旅行するから、そんときにPythonイベントに参加したいって人がいたので、メールちょうだいって名刺わたしといた
* https://twitter.com/takanory/status/1149311468246130693

EPS General Assembly 2019 & EuroPython 2019
===========================================
* https://ep2019.europython.eu/talks/DSiopdm-eps-general-assembly-2019/
* `Invitation to the EuroPython Society General Assembly 2019 <https://www.europython-society.org/post/185868682920/invitation-to-the-europython-society-general>`_
* 233名のメンバー
* Annual Report
* 2019年の活動を報告
* Ticket sales development
* EPSはEuroPythonの登録商標を持っている
* 会計報告を回覧→銀行に34万EURあるの!!?
* 2019のBoard候補がなんかしゃべる
* 最後にそれぞれを承認するかを参加者に確認して終了

Day 2 ライトニングトーク
========================
2日目のライトニングトークです。
この日のライトニングトークから接続が2系統となり、人の入れ替えがスムーズになりました。

最初に抽選コーナーがあり、書籍のプレゼントがありました。
抽選方法はJupyter Notebookに書いてあるコードでランダムにキーワードを選んで、それに合致する人が勝ち残るという方式です。
誕生日が偶数/奇数、名前に含んでいる文字などで抽選していましたが、レアな文字が出ると全員がはずれになってやり直しになるなど、いい感じのグダグダ感でした。

.. figure:: /images/euro/random.jpg
   :width: 400

   Jupyter Notebookを使用した抽選の様子

* binder

  このサービスでGitのリポジトリを指定すると、Web上でJupyter Notebookが参照できるようになります。
  Buildに少し時間がかかりますが、便利そうだなと思いました。
* inspectモジュールを使用したクラス置き換え

  Pythonの `inspectモジュール <https://docs.python.org/ja/3/library/inspect.html>`_ を使用して、動作中のクラスを別のクラスに置き換えて、振る舞いを動的に変更するというデモです。
  全てライブコーディングで説明しながら実装して入れ替えていて、すごいなーと感じました。

Day 3
=====

Keynote
=======
* いろんなPython高速化プロジェクトが頓挫した
* PyPyはあるよ

  * 大量のメモリ
  * 起動が遅い
* GIL問題
* multiprocessing
* Cython
* Numba
* https://speed.python.org/

  * 変更によって速くなったか遅くなったかをベンチマーク
* PyHandle, tracing GC, subinterpreter?

The Story of Features Coming in Python 3.8 and Beyond
=====================================================
* http://blog.pirx.ru/media/files/2019/python3.8/#1
* Otter使ってみる
* Good docs on what's new
* New Syntax
* PEP 572
  
  * PEP 572(:=)
  * initial PEPでは ``(expr as x)`` だった。Sublocalスコープだった(へー
  * PEPがSimpleになっていった。
  * スコープは複雑→オリジナル作者はこういうスコープがいいなってしてた
  * PEP 13: Python Language Governance

    * GuidoはBDFLをやめた
    * Python Steering Council
  * COns: 複雑なケースだと読みにくい。2種類の方法がある
* PEP 570: Positional-ony paramaters

  * C-API関数用にあった
  * なぜ `/` なのか

    * すでにPEP 436 があった
    * 組み込み関数のdocstringにあった
    * すでに ``*`` もあるよ
  * なぜキーワードオンリーが ``*`` なのか?

    * PEP3102に理由があるよ
    * `*args` のあとにキーワードオンリーが書けるからだよ
* New Types: Protocol, Literal, Final, TypedDict

  * Literal(str or int)
  * Final: cannot re-assign, cannot override
  * どこからきたの?

    * github.com/python/typing
    * Typing summits, sprints
    * mypy_extensions -. typing_extensions -> typing
  * Cons: Python typesを学ぶのが難しくなる。 typing vs typing_extensions
* Beyond Python 3.8
* Typing

  * PEP 560, 585
* async/await

  * Structured concurrency for asyncio tasks
* Mypyc

  * https://github.com/mypyc/mypyc
  * 型が決まるので速いらしい
  * Cythonと似ているけどPythonのデータ型がつかえる
* PEP544 Sub-iterpreters

  * マルチコアでのパフォーマンス向上
* リリースプラン

  * 3.8: 2019010-21
  * 3.9: 9ヶ月のサイクルを18ヶ月にする?
* まとめ

  * Python 3.8b2を入れてためしてみて
  * PyCharm 2019.2 は 3.8 サポートしているよ
  * Pythonの開発に参加してね

Enhancing Angklung Music Rehearsals with Python
===============================================
* https://ep2019.europython.eu/talks/YRihXWF-enhancing-angklung-music-rehearsals-with-python/
* アンクルンというインドネシアの楽器。1つで1つの音しか出ない
* 一人で何個も持って一度にならしたりするらしい
* openpyxlでスプレッドシートのデータを作る
* Collision Tableで同時に演奏する音の数を数える
* アンクルンの重さもあるので、そこを考えて割り振りする必要がある

  * 組み合わせ最適化問題っぽいやつ?

Sprint Orientation
==================
* 明日どういうSprintがあるかをオーナーが説明するやつ
* https://wiki.python.org/moin/EuroPython2019/Sprints
* CPython, pewpew、PyPy、Best Python LTs, EuroPython website, ゲームができるようなデバイス, PyGame, Bokeh, pytest, MoinMoin Wiki, pandas, scikit-learn,

ライトニングトーク
==================
* 20時から川で泳ぐよ

  * https://www.basel.com/en/rhine-swimming
* PyWeek(ゲームを作るやつ)

  * 数学的な計算をして波の状態を出す
* Tour de Snake over the mountains edition

  * MilanoからBaselまで自転車で3人で来た
* What you an do in 10 minutes

  * Python Pizza Nightがあるよ。10分トークにきてね
  * ハンブルクでもやるよ
* The Pad

  * 参加者にまわしてたけどサウンドがならなかったw
* A Protocol for Python Schemas?
* Why I/You nee to go to EuroPython!(noah)

  * Noah安定のタイムオーバーww
* PyCon Turkey

  * https://pycon.istanbul
* flynt

  * https://pypi.org/project/flynt/
  * f-stringに書き換えるツール
  * (便利そう


Closing
=======
* 明日はSprintだよ
* 16名で運営
* ボランティア壇上へ
* 2020、アクティブなwork group memberを募集

  * 12ヶ月で100時間くらいの作業が必要
* code of conductの報告→2軒報告があった
* 新boardメンバーを紹介して終了

