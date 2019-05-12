==============================
 US PyCon 2019レポート: 第1回
==============================

US PyCon とは
=============
`PyCon <https://www.pycon.org/>`_ (Python Conference)はプログラミング言語Pythonに関する国際カンファレンスです。
アメリカで開催されるUS PyConや日本で開催されるPyCon JPを含め世界中で開催されています。

今回レポートするUS PyConは、PyConの発祥であり世界最大のもので、今回は約3,200人が参加しました。
筆者はこのイベントに初参加であり、Posterセッションのスピーカーとしても参加してきました。
日本を含めて各国のPyConに参加したことがありますが、USにはまた他とは異なる面白い部分がありました。
キーノートなどの発表を中心にしつつ、個人的に面白いなと思った部分についてもレポートしていきたいと思います。

.. figure:: /images/us/website.png
   :width: 600

   US PyCon 2019 Webサイト

以下はUS PyCon 2019の開催概要です。

:URL: https://us.pycon.org/2019/
:日程: 
   - 2019年5月1日(水)、2日(木): チュートリアル
   - 2019年5月3日(金)~5日(日): カンファレンス
   - 2019年5月6日(月)~9日(木): 開発スプリント
:場所: オハイオ州クリーブランド
:会場: `Huntington Convention Center <https://www.clevelandconventions.com/>`_
:参加費: 個人400ドル(学生125ドル、企業700ドル)
:主催: `Python Software Foundation <https://python.org/psf>`_

レポート1回目はPyConの全体像とカンファレンス1日目までの様子をお伝えします。

PyCon 会場と全体像
==================
* 会場図とかタイムテーブルを入れる
* ビデオ集: https://www.youtube.com/channel/UCxs2IIVXaEHHA4BtTiWZ2mQ/featured
* スライド集: https://speakerdeck.com/pycon2019

カンファンレンス前
==================

日本から移動してホテルに到着
----------------------------
* ワシントンで乗り換え
* ポスターがちゃんと届いた
* ホテルから地下鉄で移動してみたけどちょっと怖かった
* 2.5USD

受付してnewcomers参加
---------------------
* どんなイベントがあるかを詳細に説明

Opening Reception
-----------------
* ビール片手にブースを回る
* ここでグッズをもらいまくる人もいるらしい
* ブースが本格的だけどカジュアルでいい感じ
* 名札のバーコードで情報管理

カンファレンス1日目
===================

オープニング
============
* ビデオ: https://www.youtube.com/watch?v=iyV1NUaSt0k
* Thank Yous
* pycon.us/conduct
* しゃべっている内容がテキストになるのすごい!!!
* 基本的な説明はしている感じ
* 会場とかごはんとかブースとか
* スポンサーの数がすごい
* 5 talk tracks 95 sessisons
* Open Spaces pycon.us/os
* PyCon Hatchery: PyConを育てるためのアイデア

  * Las PyCon Charlas: スペイン
  * The Art of Python
  * Maintainers Summit
  * Menters Sprints
* Think Pac-Man
* Gender Neutral Restrooms
* Mother's Rooms
* Swag Bags

  * Digi-Key
  * T-shirts
* 写真に写りたくない人はネームタグに赤いリボンをつける(へー

Keynote: Russel Keith-Magee
===========================
* ビデオ: https://www.youtube.com/watch?v=ftP5BQh1-YM
* Survata: Data science company
* Django
* Pythonは28年でコミュニティが育ってきた
* このでかいカンファレンスがクリーブランドで開催されている
* Where do you see Python in 10 years?
* Black Swan events
* Python's Black Swan

  * Black Swan 1: Everyone uses laptop
  * Black Swan 2: Python can stay on the server
  * Black Swan 3: Installation is ...
  * Black Swan 4: Code distributuin doesn't matter
* BeeWareプロジェクト

  * https://beeware.org/
  * Mac, Linux, Win, iOS, Android, Djangoで動くらしい
    
* Burn out

  * 誰かがすごいプレッシャーをかけて燃え尽きちゃう
  * この人もDjangoプロジェクトで燃え尽きたらしい
  * The (hidden human cost of FLOSS

* 5 calls to action

  * 1. Start thinking about Black swans.
  * 2. Improve resourcinf of maintenance and R&D efforts.
  * 3. Value contributors and their contributions.
  * 4. Get out your wallets.

    * psf, django, numfocusなどにdonateする
  * 5. Contribute.

発表から
========

API Evolution the Right Way
---------------------------
* スピーカー: A Jesse Jiryu Davis
* ビデオ: https://www.youtube.com/watch?v=dqDnB6jKzcE
* APIを拡張するとキメラになってく
* Pytno 2, bool(datetime.time(0, 0)) == False
* Pytno 3, bool(datetime.time(0, 0)) == True
* Aboid Bad Features
* Minimisze Features
* Make Expreimental Features "Provisional"
* Whether to Delelte a Feature

  * Pros/Cons
* Delete Feature Gently

  * warinigでdeprecateメッセージを出す
  * PyChamrとかだと打ち消し線が出る→へー

* Maintain a Change Log
* Semantic Versioning(PEP 440)
* Write an Upgrade Guide
* Change a Behabior

  * without API changes

Migrating Piterest from Python 2 to Python 3
--------------------------------------------
* スピーカー: Jordan Adler, Joe Gordon
* ビデオ: https://www.youtube.com/watch?v=e1vqfBEAkNA
* スライド: https://speakerdeck.com/pycon2019/jordan-adler-joe-gordon-migrating-pinterest-from-python2-to-python3
* スライドごとに入れ替わってしゃべるスタイル(ちょっと面白い
* Approach
* Django, 250 million monthly active users
* 2.6 million of code
* 10 years
* 3,500 changes montyhy, 452 developers

* Gradual Py3 Rollout

  * Make Py3 available
  * Test under Py2 and Py3
  * Migrate
  * Drop Py2
  * add Py3 features

* Upgrade requirements

  * https://github.com/brettcannon/caniusepython3
* Python Future

  * Easy, clean, reliable Python 2/3 compatibility

* Dependency Graph

  * __import__() にmonky patch
  * Buld a list of modules that run under Py3

* The Good

  * lib2to3.fixes.fix_print
  * lib2to3.fixes.fix_except
  * lib2to3.fixes.fix_metaclass
  * lib2to3.fixes.fix_absoulte_import

* The Bad

  * Numbers

    * 割り算, round()
    * None > 1, 01

  * Bytes

    * Py2, 3で動作が違う

  * string

    * string.letters

  * Scopes
  * Dictionaries

    * 3.6+ で順番が維持される
    * keys() がリストじゃない

  * Unicode, StringIO

* Pythonコードクイズみたいになってきた

Making Music with Python, SuperCollider and FoxDot
--------------------------------------------------
* スピーカー: Jessica Garson
* ビデオ: https://www.youtube.com/watch?v=YUIPcXduR8E
* https://ja.wikipedia.org/wiki/SuperCollider
* http://foxdot.org/
* ライブでコーディングして曲を作っていく

ライトニングトーク
==================
* ビデオ: https://www.youtube.com/watch?v=yFcCuinRVnU
* 33分頃から
* 毎日ライトニングトークがある
* ボードに24名までサインアップできて、選ばれた10名程度に連絡がいくらしい
* 日本から参加したHirataさんがLT発表した
* [ ] Day 1: Lightning Talksで発表した(hirata)

まとめ
======
* 規模のでかさにびっくりした
* 日本から見知らぬ参加者がいた
* クラフトビールがたくさんある
