=================================
 EuroPython 2019 レポート: 第1回
=================================

.. contents:: 目次
   :local:

EuroPythonとは
==============
`EuroPython <https://ep2019.europython.eu/>`_ はヨーロッパ地域で開催されるPythonに関するカンファレンスです。
EuroPythonは毎年ヨーロッパの各地域で開催され、今年はスイスのバーゼルで開催されました。過去にイギリスのエジンバラ、イタリアのリミニ、スペインのビルバオなどで開催されています。
ヨーロッパでは各国でもPyConが開催されているので、PyCon JPとPyCon APACと似たような関係です。

このEuroPythonですが、2002年に第1回が開催された歴史あるカンファレンスで、USのPyCon(2003年が第1回)よりも歴史が古いです。

.. figure:: /images/euro/europython.png
   :width: 400

   EuroPython 2019 Webサイト

以下はEuroPython 2019の開催概要です。

:URL: https://ep2019.europython.eu/
:日程:
    - トレーニング: 2019年7月8日(月)、9日(火)
    - カンファレンス: 2019年7月10日(水)-12日(金)
    - スプリント: 2019年7月13日(土)、14日(日)
:場所: スイス、バーゼル
:会場:

   - カンファレンス: `Congress Center Basel <https://www.congress.ch/>`_
   - トレーニング、スプリント: `FHNW Campus Muttenz <https://www.fhnw.ch/en/about-fhnw/locations/muttenz>`_
:参加費: 1,600タイバーツ(約5,600円)
:主催: `EuroPython Society <https://www.europython-society.org/>`_

筆者はポスターセッションでの発表のために、今年初めてEuroPythonに参加しました。
カンファレンスにのみ参加したので、キーノートやトーク発表などを中心にレポートしていきたいと思います。

日本からバーゼルへ
==================
日本からバーゼルへは直行便がないため、乗り換える必要があります。
筆者は最近就航された羽田→ウィーン便で移動しましたが、ウィーンに現地時間の朝6時に到着します。その後乗り換えてバーゼル到着が9時前、バスと路面電車を乗り継いでホテルに着いたのが12時くらいでした。
ここで、到着時間が早すぎたためまだホテルには入れません。移動でヘトヘトなのとちょっと体調が悪かったのですが、しょうがないのでホテルに荷物を預けてバーゼル市内を観光しました(誤算でした)。
ただ、おかげでバーゼル大聖堂を見学できて(中も見学できました)、プチ観光気分が味わえました。

.. figure:: /images/euro/muenster.jpg
   :width: 300

   バーゼル大聖堂

15時前にホテルに戻ってチェックインして、少し作業をしてから仮眠をとると19時過ぎに目が覚めました。
疲れていたのでホテルの近所のスーパーで買い物をして夕食にしようと思ったら、なんとスーパーは18:30に閉店していました(早い!!)。
急いで今開いているスーパーマーケットを検索し、徒歩10分くらいの店でなんとかサンドイッチやビールなどを購入し、食事にありつきました。
いきなりヨーロッパの洗礼を浴びた1日目となりました。

オープニング
============
カンファレンス1日目、会場に到着すると会場外にEuroPythonの案内が出ていました。
テンションがあがります!!

.. figure:: /images/euro/sign.jpg
   :width: 400

   会場の外にEuroPythoの表示が!

受付を済ませて3Fのメイン会場に移動します。
オープニングでは基本的なイベントの案内などがありました。
主催者が会場に「初めて参加する人ー?」と声をかけると、かなりの手が上がりました。
そして次に「EuroPythonに来たことがある人は、初めての人をサポートしてあげてね、自分の家のように」と伝えていたことが印象的でした。
このコメントからEuroPythonは来場者みんなで作っている温かいコミュニティなんだなと感じられました。

.. figure:: /images/euro/opening.jpg
   :width: 400

   オープニング

またオープニングではグッズとして参加者全員に配布している **PewPew** デバイスの紹介がありました。
このデバイスはPythonでプログラムができて、コントローラーや8×8のディスプレイを備えています。
また、グッズとしてEuroPython電池も同梱しているので、すぐに試せるよといっていました。
ちなみにこれは、Pythonの `"バッテリー同梱(batteries included)" <https://docs.python.org/ja/3/tutorial/stdlib.html#batteries-included>`_ という哲学にかけたジョークです。

キーノート: Lynn Cherny
=======================
* タイトル: Getting Your Data Joie De Vivre Back!
* https://ep2019.europython.eu/talks/UVUSRHk-getting-your-data-joie-de-vivre-back/
* スライド: ghostweather.slides.com

.. todo:: スライドURL
          
「Joie De Vivre」とは「生きている幸せ」という意味のフランス語です。
データを使っていろいろとLynn氏自身が楽しんで行っているプロジェクトが紹介されていました。

.. todo:: 写真を入れる

1つ目のプロジェクトは **BoschBot** です。
これはオランダのHieronymus Boschという人が描いた「快楽の園」という超巨大な絵画のパーツを投稿するBotプログラムです。
プログラムはTwint、Pandas、image segments、leaflet.jsを使用しているそうです。
Twitterの `@boschbot <https://twitter.com/boschbot>`_ でこのBotの投稿が見られます。

* 参考: `快楽の園 - Wikipedia <https://ja.wikipedia.org/wiki/%E5%BF%AB%E6%A5%BD%E3%81%AE%E5%9C%92>`_

このBotプログラムは画像からなんらかの特徴のある場所をとりだし、その画像の座標を投稿しています。
最も見られている画像は魚の上に人が乗っていてお尻をこちらに見せている画像だそうです。

* 該当画像のツイート: https://twitter.com/boschbot/status/1122195031648026625

このBoschBotは多くの人(35,000人以上!)にフォローされており、投稿された画像にキャプションをつけたりコラージュしたりして、楽しまれているようです。

次のプロジェクトは **Word2Vec Toys** です。
Word2Vecはテキストデータを解析して、単語の意味をベクトル化して似た単語を計算したり、単語に意味を足したり引いたりできるようにするものです。
元となるテキストデータには `Gutenberg <https://www.gutenberg.org/>`_ から取得したsそうです(日本で `青空文庫 <https://www.aozora.gr.jp/>`_ が使われるのとよく似ていますね)。

単語のマップを `plotly <https://plot.ly/python/>`_ で可視化していましたが、いくつかのクラスターがありました。
また、似た単語を探すというデモをしていましたが、元の文章の種類によって似た単語が変わってくる例が興味深かったです。

そして、ここで作成したWord2Vecを使って詩をコラージュするサイトを紹介していました。
詩の文章を表示し、似た単語が存在する場合は適当に入れ替えていって、詩を異なる物にしていくというものです。
その場で即興で新しい詩を作っていましたが、会場から笑いが出ていました。

最後にデータセットの楽しい活用の例として、アメリカでビッグフットが目撃された場所を地図にプロットしたもの、オズの魔法使いのビデオを単語順にしたものが紹介されていました。

* 参考: `Finding Bigfoot (Data) <http://ryrobes.com/visual-analytics-and-data-porn/finding-bigfoot-data-visualize-the-squatch/>`_
* 参考: `Every Word In 'The Wizard Of Oz,' Recut Alphabetically <http://digg.com/video/wizard-of-oz-alphabetical>`_

面白いデータセットを見つけて、自分なりのアウトプットをしてみたいなと思う発表でした。

Python for Realtime Audio Processing in a live music context
============================================================
* 明日のsocial eventでコンサートやるよ
* なんでPython使うの、狂ってんじゃない?

  * 狂ってるよ。Pythonは楽しい
* ルネッサンス期の音楽を演奏したり、コンピューターのアルゴリズムで作曲とかしているよ
* telemannのCanonを一人で演奏する
* DELAYするのを4つつける→どうやってコントロールするんだ???
* State machineとLooper

  * すごい
* Additional Effects

  * LooperにさらにWAH FXをつける
* いろんなオープンソースを組み合わせて作っているよ

  * 壁にぶつかる
  * SETLIST→曲によって設定を変える必要がある
* PYO

  * https://github.com/belangeo/pyo
  * 音声を扱うにはPythonは遅いけど、これは大丈夫らしい
  * フットペダルから時間をとって PYO で delay する
  * まだセットリストは作れない

    * GIGモデルとSCHENEモデルを作った
    * 別なフットペダルを使ってシーンを切り替える

ランチ
======
ランチは基本的に肉系とヴィーガン用の2種類があって選ぶスタイルのようです。
この日のランチは謎の塊を食べるものでした。キッシュかなにかなんですかね?

`attendify <https://attendify.com/>`_ というスマートフォンのアプリでカンファレンスのスケジュールを確認したり、内容がよかったか星をつけることができるのですが、このランチは5点満点で2点でした...
ちなみにグラスの中身はお酒ではなくてリンゴジュースです。

.. figure:: /images/euro/lunch1.jpg
   :width: 400

   謎のランチ
!Eo7kKxYf8uyQmTv
Publish a (Perfect) Python Package on PyPI
==========================================
* https://ep2019.europython.eu/talks/JpKkHY7-publish-a-perfect-python-package-on-pypi/
* hellowold.py
* setup.py
* localでpip install

Do we have a diversity problem in Python community?
===================================================
* https://ep2019.europython.eu/talks/i6us9Yt-do-we-have-a-diversity-problem-in-python-community/
* Rは女性開発者が多いけどPythonは遅れているらしい
* R-Ladiesってのがあって、PyLadiesよりたくさんあるらしい https://rladies.org/
* 女性で大学卒業している人は統計学が44%でCSは19%
* 小さいカンファレンスだと休憩で男性トイレだけ長蛇の列で女性トイレはガラガラとかるよね
* ビデオで録画されているカンファレンスを調べた
* PyCon UKを除くと男性が75%
* 劇場の話(ロンドン

  * あるステージだと22名の俳優が全員白人
  * ナイジェリア出身のシンガーのFelaの公演を、ナイジェリアのminicabドライバーが見に来るようになった
* PyConでの女性スピーカーの割合は増えて言ってる

  * 2011は1%、2016は40%
  * NumFOCUSは2017からDiversity in Scientific Computing(DISC)をはじめている
  * Django Girlsは12言語に翻訳、36の国の77の都市で開催
* Tシャツに性別をつけない→体の形は性別じゃないから(そう言われるとそうかー
* http://bit.ly/python_diversity →アンケートがあるから答えてね

Keynote: Yenny Cheung
=====================
* Why You Should Pursue Public Speaking and How to Get There
* https://ep2019.europython.eu/talks/ojGVzoG-why-you-should-pursue-public-speaking-and-how-to-get-there/  
* 2年前にPyCon DEで初めて発表した
* Yelpのいろんなスピーカーにインタビューしたビデオを再生

  * ちゃんとビデオ編集している
  * Tipsは?→dry run
* public speakingして得た物

  * 企業の前でプレゼンとかが楽になった
  * 重大な会話でよくなった
  * 内向的な人に向いている?
* 心臓が早くなった

  * 港を見つめる
  * Power pose
  * Humor
* いろんな問題をリハーサル

  * スライドがなしで発表
  * スピーカーノートにあまり頼らないでしゃべる
  * ビデオとかのローカルリンクを用意
* なにを言うか忘れたら

  * ここは今は飛ばします
  * 水を飲む
* Not being good enough

  * Imposter syndrome
* トークをどうよくしていくか

  * Lean start up model
  * Building the proposal

    * rejectされても他の煮出そう
  * Rubber-ducking, feedback crew, audienceにあわせて微調整する
  * How to get better

    * Dry-run
    * Measure: feedback crew, audience, watch video, note questions.
  * Learn

    * brace yourself for taking feedback
    * action items
  * Repeat

    * reuse
* 発表する機会を探す
* まとめ
* 2週間以内に発表する機会を探してください

ライトニングトーク
==================
* Pewpew device

  * PCにつなげるとファイルがあって、ドキュメントのURLとかが見れる
  * 金曜にワークショップがあるらしい
  * Bouncing Ball Tutorial→実際に作ってみたやつを見せてた
* PewPewで3Dの迷路ゲームをやる
* foxdotのデモ

  * stand by meの伴奏にあわせてハーモニカで演奏
* 英語だけじゃなくてsk, de, cs, fr, es, pl, it, sv, fu, eo, tr

  * Compose keyで入力するよ
  * URL見れなかった
* コミュニティ、イベント紹介

  * PyLadies Berlin
  * PyGerlinも立ち上がったらしい
  * PyCon Africa
  * PyCon Latam
  * PyCon.DE, PyData Berlin
* tour de pycon?

  * いろんなところにバイクとかでいってて天気が悪い
  * baselには自転車で来た
  * 車椅子の友達が山に登りたいという夢があって、背負って登った
    
* 最後にセッションボランティア募集の話


