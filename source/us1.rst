==============================
 US PyCon 2019レポート: 第1回
==============================

.. https://www.dropbox.com/sh/tiwmt0am6e1wv9j/AAArS0FcYAjfMw1HinTIbddna?dl=0

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
US PyConはHuntington Convention Centerという会場で開催されましたが、これがとにかく広いです。
企業ブース、ランチ会場などがあるメイン会場は幕張メッセのホールみたいな感じで、その横にキーノートやライトニングトークが行われる2,000人とかは入りそうなホールがあります。

.. figure:: /images/us/hall.jpg
   :width: 600

   メイン会場のホールB, C

それとは別に2~300名入れそうな部屋が5つあり、トークセッション用に使用されます。
さらに数10名~100名くらい入れる会議室が20以上(Open Spaces、託児室、スタッフ用などで使用)あり、それらがほぼワンフロアにあって横移動できるという、アメリカのデカさを感じる会場でした。
なお、カンファレンスのタイムテーブルは以下のリンクから参照できます。

* https://us.pycon.org/2019/schedule/talks/

またすべてはそろっていませんが、発表のビデオやスライドは下記のリンクから参照できます。

* ビデオ: https://www.youtube.com/channel/UCxs2IIVXaEHHA4BtTiWZ2mQ/featured
* スライド: https://speakerdeck.com/pycon2019

カンファンレンス前
==================

日本から移動してホテルに到着
----------------------------
私はカンファレンスの2日前(5月1日)に日本から移動しました。
日本からクリーブランドへは直行便がないため、行きはワシントンで乗り換えました。
乗り換え時間が短いため空港内でビールが飲めなかったのが非常に悔やまれます(良さそうな店がたくさんあった)。

私はカンファレンス3日目のポスターセッションで発表するため、ポスターを日本から持参しました。
乗り継ぎもあるしバッキバキになってないか心配だったんですが、空港のターンテーブルで無事なポスターを見てほっと一安心しました。

.. figure:: /images/us/poster-in-turntable.jpg
   :width: 450

   ポスターが折れずにちゃんと届いた

空港からホテルへの移動にはRTAという地下鉄を利用してみました。どこまで乗っても2.5ドル(約270円)です。
空港からホテル周辺のダウンタウンまで外を見ていると、田舎という感じなのと、やはりこのあたりで地下鉄に乗ってくる客層はちょっとお金がない人なのかな?という感じでした。
当然ですがアジア人の旅行者なんて誰も乗っていません(というか旅行者も私含めて3名くらいしか乗っていない)。
周りと目を合わさずに目的の駅に無事到着し、10分ほど歩いてホテルに到着しました。

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

カンファレンス中には毎日1時間程度のライトニングトークがあります。
ライトニングトークのスピーカーの選び方は少し変わっており、毎日話したい人が申し込みするボードが用意されます。
発表をしたい人はここに名前、メールアドレス、タイトルを記入します。
そして、選ばれた10名にメールで連絡が来るという形式のようです。

完全な早い者勝ちではなく、なおかつ多すぎる候補から選ばなくていいのでなかなかよい手法だなと思いました。

.. figure:: /images/us/lt-board.jpg
   :width: 400
   
   Lightning Talksの申し込みボード

そして1日目のライトニングトークで日本から参加したHirataさんが見事選ばれました。
以下はHirataさんのライトニングトークでの発表についての感想です。

.. admonition:: コラム: 初めてのライトニングトークでの発表

   * Tetsuya Hirata(`@JesseTetsuya <https://twitter.com/JesseTetsuya>`_)

   ステージに立つ前までは、とても緊張していました。
   なぜなら、ライトニングトークを日本でもやったこともなければ、他の人がやっていたのを実際に見るのも2、3回程度であったためです。
   こんな人数でこんなにもでかいスクリーンの前で話すのは、人生で一度もありません。
   また、US PyConのステージにアジア人(特に日本人)で登壇してる人が少ないということもあり、日本人である自分の考えや意見を自信を持って伝えることでUSのPythonコミュニティに何かまた新鮮な感覚をもたらすことができるのではと思っていました。そう思いながら、会場に向かいました。

   24人から選ばれる10人の発表者は、一列目の席に発表の順番に座ることになっていました。
   私は、緊張のあまり両脇に座っていた人に「I'm so nervoursssss. What should I do ?(とても緊張している。どうしたらいい?)」と言ってました。
   右側の人(僕のトークの前の人)は「おれ、全然準備してないから俺のスライドみたらもっと楽になるんじゃない？」と言われて見せてもらったら「スライド、めっちゃ準備してきてるじゃん」と思い、ここで自分のトークへの自信をなくしました。
   次に左側の女性(僕のトークの後の人)に聞いたら、「OMG, I'm getting more nervous(私も緊張してきたよ)」と言われて、「え、僕のせい？！ごめん」となっていました。

   いざ、ステージに上がるとみんなが温かい目でトークを聞いてくれている感覚があり、思っていた以上に緊張せずに話しきることができました。

   .. figure:: /images/us/hiratas-lt.jpg
      :width: 600
   
      Hirataさんの発表の様子

   発表が終わって、多くの人に名前と顔を覚えてもらえました。
   Guidoにも「君のトークを聞いてたよ、よかったよ」と言ってもらえました。
   他にも、いきなり知らない人(SprintでのPackaging Summitを仕切っていた人)に「君のトークよかったぜ」と言われて飲みに誘われて行きました。

   一番印象的だったのは、US PyConに参加していた何人かのアジア系の方々に「I'm impressed. Well done.(感動した。よくやった。)」と言い寄られたことでした。
   このとき、日本では感じ得られないようものを感じました。
   総じて、US PyConの多様性を重視する姿勢を感じることができ、これは現地にきてコミュニケーションをしないと感じ得られないことだと思いました。
   この多様性を受け入れる姿勢、この言語化できないような感覚は日本でもチームワークを上手く進める上で忘れずにコアな考えとして大事にしていきたいと思います。

   .. figure:: /images/us/hirata-and-guido.jpg
      :width: 600
   
      HirataさんとGuido氏

まとめ
======
* 規模のでかさにびっくりした
* 日本から見知らぬ参加者がいた
* クラフトビールがたくさんある
