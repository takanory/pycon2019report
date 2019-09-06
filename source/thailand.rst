========================
 PyCon Thailandレポート
========================

.. contents:: 目次
   :local:

PyCon Thailandとは
==================
`PyCon <https://www.pycon.org/>`_ はプログラミング言語Pythonに関する国際カンファレンスです。
アメリカや日本をはじめ世界中で開催されています。
近年はアジアでの開催も活発で、そのうちの一つが今回レポートするPyCon Thailandです。

`PyCon Thailand <https://th.pycon.org/en/>`_ はタイで開催されるPyConで、今回が2018年に続き2回目の開催です。
筆者はこのイベントにスピーカーとして参加してきました。
他にも日本からスピーカーやブース出展で参加した人がいるので、その方からの視点も交えてレポートします。

.. figure:: /images/th/pyconth.png
   :width: 300

   PyCon Thailand 2019 Webサイト

以下はPyCon Thailand 2019の開催概要です。

:日程: 2019年6月15日(土)、16日(日)
:場所: タイ、バンコク氏
:会場: `True Digital Park <https://www.truedigitalpark.com/>`_
:参加費: 1,600タイバーツ(約5,600円)
:主催:

    Python Phiillines

前夜祭
======
カンファレンス前日の夜にスピーカーなどを招待した簡単なパーティーがありました。
事前にWebサイトに「前の日のPartyを計画中」と書いてあったので期待していたのですが、まったく連絡がありません。
するとその日の18:45分に「Nowhereという店で20:30から飲むよ」というメールが来ました。
「ゆるいな」と思いましたが、誘われたら飲みに行く人なので、当然いきました。

そこでスタッフやスピーカー数名と交流しました。
スタッフのFrancoisさんと、次の日のキーノートスピーカーのDavidさんは日本語もすこし話せるので、日本語でも交流などしました。

このパーティー、最初の1杯が無料だったんですが、そのビールがなんとアサヒスーパードライ。
私はあんまり好きじゃないのと、なぜタイに来てまでアサヒビールという気持ちでしたが、まぁ飲みました。
ちなみにアサヒビールは結構海外進出しているようです。
   
.. figure:: /images/th/asahi.jpg
   :width: 200

   ビールはアサヒスーパードライ

タイのローカルクラフトビールも飲みたかったので、駅からNowhereに歩いて行く途中にあった `Ekamai Beer House <http://www.ekamaibeerhouse.com/>`_ という店に寄り道して、Ekamai IPAを飲んで帰りました。
ちなみにこの店にもアサヒビールは置いてあり、他に常陸野ネストビールも置いてありました。

.. figure:: /images/th/ekamai.jpg
   :width: 300

   Ekamai Beer Houseでタイのクラフトビールを飲む

オープニング
============
カンファレンス1日目のオープニングです。
最初にアイスブレイクがあり、よくある「まわりの席の人と挨拶しましょう」といったものです。
面白かったのが、このホールの席は階段状になっているのですが「奇数列の人が立って後ろを向いて話してね」というものでした。
確かにお互いに目線がちょうどあって良い感じです。
私の後ろの席の人は偶然にも台湾からの参加者でした。
「私は今年のPyCon Taiwanにもトークしに行くので、また会いましょう」といった話をしました。

.. figure:: /images/th/opening.jpg
   :width: 300

   オープニングの様子

なお、写真の右側がPyCon ThailandのChairのDylan Jay(`@djay75 <https://twitter.com/djay75>`_)氏で、左側が最初のキーノートスピーカーのDavid Cournapeau氏です。

自分の発表
==========
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20190615pyconth#/

1日目のランチタイムの前に私の発表がありました。
このトーク自体は `PyCon APAC 2019 <https://pycon.python.ph/>`_ で行ったものと同じでしたが、いくつかスライドを手直ししたり、スライド中のAPAC用のネタをタイ用のネタに変えたりして発表に臨みました。

会場の中に電源のあるファミレスっぽい席があって、集中して直前の準備作業ができました。
この席に、他の2名の日本人スピーカー(2人は明日が発表)もやってきてもくもくと作業を進めていました。

.. figure:: /images/th/famires.jpg
   :width: 300

   ファミレス席

さて、実際に発表です。
最初にタイに初めて来たよということと、いくつか簡単な質問をすることでアイスブレイクとしました。
「日本に来たことある人?」と質問すると50%くらいの人が手を上げてくれました。
「まだ来たことがなかったら、ぜひPyCon JPに来てください。PyCon JPで再開しましょう。」という話をしたら少し笑ってもらえました。

.. figure:: /images/th/takanory.jpg
   :width: 300

   「日本にきたことある人ー」と聞いているところ

担当スタッフから「発表が30分で質疑応答が15分で」と言われて「えー、まじかー」と思いつつ、全体的に早口でしゃべっていたら、時間配分を間違えて28分くらいで発表が終わってしまいました。
自分的にはちょっと巻いた感じで40分くらいしゃべろうかと思っていたんですが、ペース配分を完全にミスしました。

とはいえ、時間がきてしまったのでしょうがないので質疑応答に入ります。
質問は結構な数がでて、そこをなんとかこなすことができたので、筆者自身の自信にもつながりました。
いくつか質疑応答の内容を紹介します。

* LINEBotを作りたいんだけど、この仕組みでできますか?

  * 基本的にはメッセージを受け取って、なにか処理をして返すので LINEBot でもプログラムの考え方は同じです。
  * ただし、 Slackbot は Slack に特化したフレームワークなので、LINEBotの場合は別のフレームワークを使用してください。 `errbot <http://errbot.io/>`_ は汎用のbotエンジンと各チャットのアダプターを持っているので、こっちの方が用途には合っているかも知れません。
* このbotはどこで動かしていますか?

  * PyCon JPではWeb用にサーバーを借りているので、そこで動かしています。
  * Slackbotは動作させ続ける必要があるので、EC2とかHerokuとかを使用するのが楽です。
* Googleカレンダーと連携する機能を作ってみたいが、どうすればよいですか?

  * この例ではGoogleスプレッドシートを出しましたが、同様にGoogle カレンダーのAPIが提供されているので、そのAPIを使うとよいと思います。私も別のツールでCalendar APIを使っています。カレンダー上のイベントの取得や変更など、一通りの操作ができます。
* このBotはあなたの発言にしか反応しないのでしょうか?

  * いえ、そうではありません。BotをSlackのチャンネルに招待したら、そのチャンネルの全メッセージに反応します。どのチャンネルでBotが反応するかは、Botをチャンネルに招待するかどうかなので、プログラムではなくSlack側での設定となります。

他に発表に関するネタとしては、発表の中でSlackで送信するメッセージの例として「私はタイのクラフトビールバーを探しています。」と書いて「本当に探しています」と言いました。
すると参加者の1人が「俺知ってる知ってる!!」というリアクションをしてくれて「じゃあ、あとで教えてね!!」とやりとりできたのは楽しかったです。
その方は実際に1日目のパーティー中に「ここの店がいいよ」と教えてくれました。
ただ、2日目の夜にそこに行こうとしたら、残念ながら日曜は営業していませんでした...

また、質疑応答で一名どうしても質問が聞き取れない方がいましたが、他の人が言い直してくれて無事質疑応答ができました。
参加者のサポートに感謝です。

.. figure:: /images/th/audience.jpg
   :width: 300

   発表前に参加者を撮影(このあとさらに増えました)

発表後にBot作ってみるよというフィードバックや、一緒に写真を撮ろうみたいに言われたりしました。
私の発表を楽しんでくれたようでよかったです。

会場の様子とランチ
==================
会場となったTrue Digital Parkはタイの通信会社trueが運営する、スタートアップのインキュベートオフィスのようです。
広々とした会場に、あちこちにいろんな形のイスがあって休憩もしやすくて、すごい易い場所でした。

企業ブースも結構賑わっており、抽選で賞品が当たるAWSのブースは気合いも入っており、かなりの人だかりでした。

.. figure:: /images/th/aws.jpg
   :width: 300

   AWSの企業ブース

ランチは2日間とも5種類の中から選ぶスタイルです。
開けてみてびっくりしたんですが、ご飯の色がすごいです。
このご飯、バタフライピーというタイでは一般的な食用の花を使って色をつけているそうです。
あとは普通っぽく見えるおかずが、結構辛かったりしてタイは侮れないなと感じました。

.. figure:: /images/th/lunch.jpg
   :width: 300

   ご飯の色がすごい

ちなみにTrue Digital Parkには日本食のお店もたくさん入っており、一瞬「私はどこにいるんだ?」と思いました。

.. figure:: /images/th/japanese-food.jpg
   :width: 200

   たくさんの日本食レストラン(ロゴもほぼそのまま)

.. admonition:: Python EDのブースを設置

   * 寺田 学(`@terapyon <https://twitter.com/terapyon>`_)

   `Python ED <https://www.pythonic-exam.com/exam>`_ (一般社団法人Pythonエンジニア育成推進協会)はPyCon Thailandのシルバースポンサーとなり、日本で行っているPython認定試験の紹介をブースで行いました。
   当協会は、日本国内のみでサービスを行っておりますが、アジア圏への展開やニーズを探るためにブースを設置しました。

   来場者からは、以下のような質問を受けました。

   - 英語版の試験提供予定はあるのか?
   - 日本以外で試験を受けられないのか?
   - 教育プログラムは提供しているのか?

   現状は、いずれもNoと答えるしかないのですが、興味を持っている人が多いことは間違いなささそうです。

   .. figure:: /images/th/booth.jpg
      :width: 300

      ブースで説明している様子

   また、マスコットの人形がすごく人気があり、どうやどうやったら手に入るのかと聞かれました。なおこのマスコットはプレゼントして最終日のクロージングで参加者にプレゼントしました。

   .. figure:: /images/th/prize.jpg
      :width: 300

      クロージングでぬいぐるみが当たった参加者と

E-commerce for Django
=====================
* スピーカー: Jonghwa Seo
* スライド: https://github.com/pincoin/thaipycon2019

.. figure:: /images/th/jonghwa.jpg
   :width: 300

   Jonghwa Seo氏

午後は、こちらも昨日のパーティーで知り合ったJonghwa Seo氏による発表を見に行きました。
韓国からの参加で、PyCon KRの立ち上げメンバーの一人であるKwon-Han Bae氏は同じ大学出身の友達だそうです。
この発表では会社で開発しているDjango製のE-commerceサイトについて発表していたようです。

「ようです」と書いたのは、この発表がタイ語だったためです。
Jonghwa氏はタイに4年ほど住んでいたことがあり、奥さんがタイ人だそうで、タイ語での発表にチャレンジしていました。
おそらくPyCon Thailand全体で唯一のタイ語の発表(LTを除く)が、韓国人によって行われるという、不思議な空間でした。

ライトニングトーク
==================
1日目のライトニングトークです。印象に残ったトークを紹介します。

1つ目はNoah氏によるPythonコミュニティとアジアのPyConの紹介です。
Noah氏は台湾在住ですが、フィリピンのPyCon APACや今回タイなど世界中にPyConでスタッフとして活動しています。
5月に開催された `PyCon Kyushu in Okinawa <https://kyushu.pycon.jp/2019/>`_ なども含めて、アジア圏のさまざまなPyConなどのイベントを紹介していました。
Noah氏はいったいいくつのPyConに参加するのでしょう、そして私と会うのでしょう。

.. figure:: /images/th/noah.jpg
   :width: 300

   Noah氏

2つ目は写真を撮影すると、ディープラーニングで絵画っぽい感じに変換してプリントするカメラの紹介です。
日本のMaker Faireなどでも出展していて人気があったようです。
内部的にTensorFlowを使って画像処理を行っているそうですが、驚きなのはネットワークを使っておらず、すべてこのカメラの中で処理をしているそうです。

.. figure:: /images/th/camera.jpg
   :width: 300

   ディープラーニングで画像を変換するカメラ

.. admonition:: 無茶振りされたライトニングトーク

   * 寺田 学(`@terapyon <https://twitter.com/terapyon>`_)

   PyCon ThailandのリーダーであるDylanから、14:30頃(LT開始の2時間半前)に「今日のLTで枠がまだ余っているあるから、何かお願い」と無茶ぶりされました。
   そのリーダーとは古い友人なので、一言で「OK」と回答して、LTをすることにしました。
   その後の2時間は、LTのネタを考えたり、スライドを作り、無事にLTを行うことができました。

   スライドは非公開ですが、以下のような内容で発表しました。
   
   - 日本から来ました
   - 10年前のイベントで(PyCon Thailand 2019)リーダーのDylanと出会ったので、その時の写真を紹介
   - PyCon Thailandはすばらしいイベントですね
   - PyCon JPは2019年9月に開催予定だよ
   - SciPy Tokyo 2019を開催しました。2020も春に実施予定です
   - 毎月 `Python mini Hack-a-thon <http://pyhack.connpass.com/>`_ というイベントを東京でやっているので、遊びに来てください

   .. figure:: /images/th/terada-lt.jpg
      :width: 300

      LTの様子

パーティー
==========
1日目のカンファレンスが終了すると、全員参加のパーティーです。
発表会場から外に出るとすでに料理やビールが用意されており、スムーズにパーティーモードに移行できます。
しかもビールはタイのクラフトビール(`Bootleg Brothers <http://bootlegbrothers.co.th/>`_)のボトルが3種類と、生ビールが2種類用意されていました。完璧すぎます。

.. figure:: /images/th/party1.jpg
   :width: 300

   タイのクラフトビールでパーティー

パーティーの中盤にバンド演奏があり、あまり気に留めていませんでしたが、なにやらすごく盛り上がっています。
なんだろうと思って見に行ってみると、なんとスタッフの女性の方が急遽ボーカルとして参加して歌っています。
これにはPyConのスタッフやボランティアも大盛り上がり。しかもこの方、結構歌が上手です。
あとで聞いたらリハーサルなしでいきなり歌うことになったそうです。すごい。
私はその場にはいなかったんですが、以下のTweetのように大盛り上がりだったようです。

* https://twitter.com/georgically1/status/1141057364444925952

.. figure:: /images/th/band.jpg
   :width: 300

   バンドと女性スタッフのコラボ
   
Keynote: Dr Russell Keith-Magee
===============================
* タイトル: Python Everywhere

2日目のキーノートはUS PyConでもキーノートスピーカーだったRussell Keith-Magee氏です。
あちこちでキーノートで発表するという、ものすごい人ですね。

.. figure:: /images/th/russel.jpg
   :width: 300

   Russell Keith-Magee氏のキーノート
   
内容は「Python Everywhere」というタイトルで、PythonはPCだけではなくさまざまな環境で動作するという話でした。
まず前提知識として **Python** は言語仕様であり、PCなどで使用している ``python`` コマンドはC言語で書かれているリファレンス実装であるという説明がありました。
そのためこのリファレンス実装は **CPython** とも呼ばれます。
そして他にPythonで実装した `PyPy <https://pypy.org/>`_ や.Netで動作する `IronPython <https://ironpython.net/>`_ などが紹介されました。
また、CPythonにはGIL(`グローバルインタプリタロック <https://ja.wikipedia.org/wiki/%E3%82%B0%E3%83%AD%E3%83%BC%E3%83%90%E3%83%AB%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%97%E3%83%AA%E3%82%BF%E3%83%AD%E3%83%83%E3%82%AF>`_)が存在するが、PyPy、IronPython、 `Stackless Python <https://github.com/stackless-dev/stackless/wiki>`_ などには存在しないという説明がありました。
次に、Pythonを実装するためには、以下のパーサー、コンパイラ、evalループ、標準ライブラリの4つの要素が必要であるという説明がありました。

そして、Russell氏も所属する `BeeWare <https://beeware.org/>`_ プロジェクトで開発している、他のPython実装について紹介がありました。
BeeWareは、単一のPythonコードからiOS、Android、Windows、macOS、Linux、Webアプリケーションを生成するということを目標としています。

* `VOC <https://beeware.org/project/projects/bridges/voc/>`_:
  VOCはPythonのバイトコードをJavaのバイトコードに変換するトランスパイラです。
  現在はPython 3.4に対応しているそうです。

* `Batavia <https://beeware.org/project/projects/bridges/batavia/>`_: 
  BataviaはJavascript上で動作するPythonのバーチャルマシンです。
  現在はPython 3.4.4に対応しているそうです。

今後はWebAssemblyによってブラウザ上でPythonが直接動作するようになるであろうという話がありました。
`Pyodide <https://github.com/iodide-project/pyodide>`_ というプロジェクトでWebブラウザ上でPythonが動作するようです。

* Pyodideのデモページ: https://alpha.iodide.io/notebooks/300/

私も試してみましたが、最初に ``pyodide.js`` を読み込んだ後はオフラインでも実行できるので、実際にブラウザ上でPythonが動作しているようです。
なんだか不思議な感覚です。

.. figure:: /images/th/pyodide.png
   :width: 300

   Pyodideのデモページ

日本から参加した2人のトーク
===========================
このカンファレンスには私以外に2人の日本人が参加してトークで発表していました。
2人とも海外での登壇は初めてとのことで、どんな感じだったかをそれぞれレポートしてもらいました。

.. admonition:: はじめての海外PyCon参加及び登壇

   * 林田千瑛(`@chie8842 <https:/twittercom/chie8842>`_)
   * タイトル: Understanding of distributed processing in Python
   * スライド: https://speakerdeck.com/chie8842/understanding-distributed-processing-in-python
  
   今回のPyCon Thailandはわたしにとってはじめての海外PyCon参加でした。
   もともと2017年にPyCon JPに初登壇したときに、別の登壇者の方から「海外のPyConで登壇することでグローバルなエンジニアのつながりができた」という話をきいたことを印象的に覚えていて、そのときからいつかチャレンジしてみたいと思っていました。
   自社のサービス（クックパッド）がタイでも展開されていることもあり、今回初めてトークを応募しました。

   発表では、PythonによるDistributed Computingについて話しました。
   わたしが話す会場は一番大きいホールだったので、下手な発表はできない。。と、発表前はとても緊張しました。
   機械学習やWebの話が多い中で、少しニッチな内容となりましたが、発表後も多くの参加者に質問を頂き、議論を行ったり、勉強になったと言っていただけました。
   また、「クックパッド使うよ！」とも言ってもらえました。登壇してよかったな、と思いました。40分のトークを英語でやりきったことは、グローバルに挑戦するための自信にも繋がりました。

   .. figure:: /images/th/chie.jpg
      :width: 300

      発表の様子
     
   参加者としての感想は、PyCon JPと比べると参加者の国際色が高かったこと、フレンドリーに話しかけてくれる人が多かったことが印象的でした。
   海外カンファレンスにチャレンジしてみたい方にはぜひおすすめしたいと思いました。

   .. figure:: /images/th/famires2.jpg
      :width: 300

      登壇準備の様子
     
.. admonition:: PyCon Thailandで初の海外トーク

   * 片寄 里菜(`@selina787b <https://twitter.com/selina787b>`_)
   * タイトル: PyLadies and importance of community participation
   * スライド: https://www.slideshare.net/LinaKatayose/pyladies-and-the-importance-of-community-participation

   5月のPyCon Clevelandに続き、今年2回目の海外PyConに参加しました。
   今回は参加だけでなく、英語でのトーク(40分)にも挑戦しました。

   今回は女性のPythonユーザーが活動しているPyLadiesの活動に関してトークをしました。
   主な内容は以下の3点です。

   * 私がPyLadies Tokyoのスタッフをしていること
   * アジアの女性Pythonistaと連携を深めたいこと
   * タイにはPyLadiesグループがないので広めたいこと

   PyLadies Tokyoのスタッフを始めて3年ほど活動してきました。
   その中で大まかな流れがわかり、それらの経験を元に、今までの活動を写真などでまとめ発表をしました。

   私は5年ほど前にタイでタイ語を勉強していた経験があるので、自己紹介だけはタイ語で話したいと決めていました。
   英語自体でトークするのも初めてなのですが、何とかやり切った感があります。
   質疑応答では、英語での質問をうまく聞き取れないこともあり、この点は改善していきたいと思いました。
   また日本語を少ししゃべれる方から日本語の質問もあり、とても嬉しかったです。

   トークの終了後は、発表に興味を持ってくれた方と個別にお話をして、連絡先を交換しました。その方は近いうちに日本に来るらしいです。
   まだ、改善の余地もありますが、PyCon Thailandと来年もつながっていきたいと思っています。

   .. figure:: /images/th/selina.jpg
      :width: 300

      発表の様子

ライトニングトーク
==================
2日目のライトニングトークからもいくつか面白かった話題を紹介します。

* Python "OS" for hackers

  https://python-os.github.io/ にあるPython製のOS用のコンポーネント集です。
  以下のようなツールが揃っており、それぞれをデモを交えて紹介していました。
  Pythonでここまでできていてすごいなと感じました。

  * Qtile: Window Manager
  * Kitty: Terminal Emulator
  * Xonsh: Shell
  * Qutebrowser: Borwser
  * Ranger: FIle Manager

* Pythonの数値の話
  
  2つの変数に数値を設定して ``print(a == b, a is b)`` でどこまでが ``True True`` となるか?という話です(注: オブジェクトが同一の場合は ``is`` の結果が ``True`` となります)。
  会場に答えさせて、答え合わせをしながら進んでいきましたが、筆者もうろ覚えなので結構間違えました。
  みなさんもぜひ手元の環境で255、256、257のときやマイナスのときにどうなるかを確認してみてください。

.. figure:: /images/th/numbers.jpg
   :width: 300

   数値を比較

Keynote: Katie McLaughlin
=========================
* タイトル: How Python Can Excel
* スライド: https://glasnt.com/talks/2019_06_PyConTH.podium/

Katie McLaughlin(`@glasnt <https://twitter.com/glasnt>`_)氏はPSFフェローであり、PyCon AU(オーストラリア)のカンファレンスDirectorやPSF(Python Software Foundation)やDSF(Django Software Foundation)のDirectorを務める方で、さまざまなカンファレンスでキーノートもするスピーカーでもあります。

トークを始める前に画面トラブルでうまく表示がされないときに、ステージ上で陽気に踊り始めたときには「この人、大丈夫か?」と一瞬思いましたが(笑)、いざトークが始まってみるとスライドの見やすさや、トークの展開など、ものすごく上手に構成されていて個人的にとても勉強になるなと思いました。

トークは「How Python Can Excel」と題して「PythonはどうやったらExcelのようになれるのか?」という内容で進みました。
まず、Excelは多くの人に使われいてとてもパワフルであること、また協力なカスタマイズも可能で例として `Excelで作られたデジタル時計 <https://github.com/Jonahss/Spreadsheets-Without-Macros/blob/master/digitalClock.xls>`_ があげられていました(そんなものがあるんですね...)。
次にPythonの利用者は約2,500万人、それに対してExcelは約8億人とのことで、この32倍nの差をどのように埋めていくことができるか、と問いかけながら話は進んでいきます。

そして http://humanedevelopment.org/ の以下の言葉が繰り替えし引用されました。
日本語訳すると「私たちは、人と一緒に働いて、人々の利益のための、ソフトウェアを開発する、人間です」といった感じでしょうか。

  | We are **humans**
  | working with **humans**
  | to develop software
  | for the benefit of **humans**.

次に具体的な例として、科学者、教育者、クリエイター、求道者という4つの職種に対して、Pythonでどのような役に立つソフトウェアが提供されているかを語りました。

**科学者** に対しては、Jupyter Notebookやpandasなどのデータ分析用のライブラリが紹介されました。
ここで紹介されている、グラフを手書きっぽくする `XKCD plots <https://nbviewer.jupyter.org/url/jakevdp.github.com/downloads/notebooks/XKCD_plots.ipynb>`_ や、 `music21 <http://web.mit.edu/music21/doc/about/what.html>`_ でNotebook上に楽譜が描けるのは面白いなと思いました。

**教育者** に対しては `micro:bit <https://microbit.org/guide/>`_ や `CircuitPython <https://circuitpython.org/>`_ といった、小さな基板上でPythonプログラミングする例が紹介されていました。

**クリエイター** に対しては事例として `RasPiで制御できる編み機 <https://www.technology.org/2018/09/25/raspberry-pi-networked-knitting-machine-not-your-average-knit-one-purl-one/>`_ を使って巨大な編み物を作った話を紹介しました。
他にはゲームを作成するフレームワークの `pygame <https://www.pygame.org/news>`_ や、ゲームプログラミングの課題を出す `PyWeek <https://pyweek.org/>`_ が紹介されていました。

**求道者** の例としては2019年に話題となったブラックホールの可視化が例としてあげられました。
この可視化には `achael/eht-imaging <https://github.com/achael/eht-imaging>`_ というプログラムが使用されています。このプログラムはPython製で、たくさんのパッケージに依存しています。
直接のコントリビューター(コードに貢献した人)は14名ですが、関連するパッケージのコントリビューター21,715人とものすごい数になります。

最後に「ぜひみなさんもライブラリなどを使ってバグを見つけたら、レポートしてほしい。バグに対して修正して貢献をしてほしい」と呼びかけていました。

* 参考: `史上初、ブラックホールの撮影に成功 ― 地球サイズの電波望遠鏡で、楕円銀河M87に潜む巨大ブラックホールに迫る | 国立天文台(NAOJ) <https://www.nao.ac.jp/news/science/2019/20190410-eht.html>`_

.. figure:: /images/th/katie.jpg
   :width: 300

   Katie McLaughlin氏

クロージング
============
クロージングでは参加者の内訳などが示されていました。
全体の参加人数は初回から2倍以上で400名を軽く超えていたようです。
参加者の年齢層が若いこと、女性の比率は約17%であること、タイ以外に9カ国以上から参加者がいることがわかります。
日本からの参加者数はタイ、シンガポールについで3番目だったようです。

.. figure:: /images/th/attendees.jpg
   :width: 300

   参加者の分類

このクロージングでChairのDylan氏から **Regime Change** (政権交代)というスライドで「次のPyCon ThailandのChairを募集する」という話がありました。
無事新しい主催者が出てきて、来年もPyCon Thailandが開催されることを期待します。

.. figure:: /images/th/organizers.jpg
   :width: 300

   主催者、ボランティア、キーノートスピーカーの集合写真
   
まとめ
======
以上でPyCon Thailandのレポートは終わりです。
初めてのタイで2日間のカンファレンスを非常に楽しく過ごすことができました。
英語でのトーク発表はフィリピンでのPyCon APACに続き2回目ですが、質疑応答をガッツリできたことが大変ではありましたが自信にもつながりました。

.. figure:: /images/th/fromjapan.jpg
   :width: 300

   日本からの参加メンバー

私以外にも2名も日本からスピーカーがいたことも、とてもよいことだと思います。
こんな感じで、いろんな人が海外のカンファレンスでの発表に挑戦してくれるといいなと思っています。

さて、次はどこのPyConに行こうかな(まぁ、すでに次の予定は決まっているんですが)?

.. figure:: /images/th/group.jpg
   :width: 300

   PyCon Thailand参加者の集合写真
