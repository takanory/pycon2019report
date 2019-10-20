=============================
 PyCon Taiwanレポート: 2回目
=============================

.. contents:: 目次
   :local:

PyCon Taiwanの2日目と3日目の様子についてレポートします。
キーノートスピーカーによる発表、筆者自身の発表、PyNight、Open Spacesなどについて紹介します。

カンファレンス2日目
===================

Keynote: Paul Ivanov
--------------------
* タイトル: Programming Language Tourism: Leave Python and see the world!

Paul Ivanov氏(`@ivanov <Programming Language Tourism>`_)はJupyterの `Steering Counsil <https://jupyter.org/about>`_ メンバーであり、Bloombergのシニアエンジニアです。

.. figure:: /images/tw/ivanov.jpg
   :width: 400

   Paul Ivanov氏

「私たちはどこにいますか?いま私たちはPyCon Taiwanにいます。」と問いかけたあとに「『どこからきましたか?』と参加者に問えば、それぞれ異なったスケールで回答があるよ」といいました。Jupyterの人に聞いたら「地球(笑)、アメリカ、カリフォルニア、サンフランシスコ、ベイエリア」のようにさまざまな尺度で答えるだろうと言っていました。
余談ですが、「私は台湾ははじめてで、日本やドイツには行ったことはないんだけど...」というくだりで「Have you heard of PyCon JP?(PyCon JPのことを聞いたことがありますか?)」と1日目のLTのネタにかぶせて笑いを取っていました。

次にプログラミングを自分の場所と考えたときにPythonはどこにいるかという話になりました。
そこでStack Overflowの質問の数のグラフを紹介し、この10年間でPythonは上位のタグになったそうです(上にはJavaScriptがいますが)。
GitHubを見てみると、作成されたリポジトリの数は上位からJavaScript、Java、Pythonという順番だそうです。

Pythonは素晴らしい言語だが、仕事でPythonを使用している場合は、たまにプログラミングの休暇を取ることを参加者に勧めました。
休暇というのは、プログラミング言語を場所と考えると、別の場所に行くようなことを指しています。
またプログラミング以外のことを行って気分転換をしようという話がありました。

また自身が主催しているイベント「Jupyter Open Studio Day」について触れました。
このイベントは2日間開催されプログラミングについて、普段の仕事ではなく自分自身のために学んで向上することができます。
そこにはPyCon MalaysiaのキーノートスピーカーでもあるCarol Willingもいるそうです。
そこにはさまざまな年齢やバックグラウンドの人が参加しており、その人たちの別の場所となっていると述べていました。

私は `Python mini Hack-athon <https://pyhack.connpass.com/>`_ というイベント主催者の1人ですが、このイベントが誰かの別の場所になるといいなと思いました。


自分の発表
----------
* タイトル: Automate the Boring Stuff with Slackbot
* スライド: https://gitpitch.com/takanory/slides?p=20190922pycontw

いつものSlackbotを開発する内容で発表をしてきました。
スライドで大きく変更した箇所は以下です。

* 自己紹介のところでPyCon JPとPyCon TWの交流があるという話を追加
* 今年の自分の各国PyConへの参加を地図で表示
* 書籍が台湾でも出版されていることを紹介
* Block Kitを使用したサンプルコードを追加

.. figure:: /images/tw/takanory.jpg
   :width: 400

   筆者の発表の様子

発表時間が30分と短めなため、はしょり気味に説明しました。
具体的には細かいコードの説明をあまりしないことで、発表時間を調整しました。

PyCon Taiwanでは質疑応答は `sli.do <https://www.sli.do/>`_ というサービスで質問を受け付けています。
文字で表示されるので質問を聞き取れないという問題がない反面、質問者に直接「今の回答でよかったか」といったことが確認できないため、メリットデメリットがあるなと思いました。

以下は質疑応答の内容です。

* SlackのAPIでは3秒のリミットがあるが、slackbotではどのようにして防いでいるのか?

  * SlackbotではRTM APIの使用が推奨されているので3秒の制限はないはず。Botの場合は手でコマンドを送ってそれに反応しているので3秒のリミットは関係ないはず(後で調べてみたところ、これはEvents APIに対してレスポンスを返すリミットなので、botの場合は関係がなさそうです)。

* Slack APIを使用してメッセージを送信したが表示されないときに、どのようにデバッグをしているのか?
  
  * ``slackbot_settings.py`` の ``ERRORS_TO`` にチャンネル名またはユーザー名を設定すると、エラー時にそこにエラーメッセージが表示されます。
  
ライトニングトーク
------------------
カンファレンス2日目のライトニングトークでもいろいろな発表がありました。いくつか紹介します。

.. figure:: /images/tw/students.jpg
   :width: 400

   高校生たちによる発表

* 高中生做點事

  * 言葉がわからないので意味は全くわかりませんでしたが、元気な高校生4人組の発表でした。あとで調べてみたところソフトウェア関係の部活のようで、小学生にプログラミングを教えることもしているようです。発表の中では自分たちの活動とLINEBotを紹介していました。

* 個人発起的小小小社群

  * PyCon JPにも参加していたKK氏による発表です。小さいコミュニティを作って継続しようということを参加者に勧めていました。

* 高雄發大財

  * Kaohsiung(高雄).pyの主催者による発表です。高雄は台湾の南にある都市で、将来的にPyCon Taiwanを高雄で開催したいという発表をしていました。また、LTの冒頭に「Do you know Kaohsiung.py」と1日目のLTのネタをかぶせてきました。

* My PyCon diary in 2019

  * 日本から参加したLina KATAYOSE氏(`@selina787b <https://twitter.com/selina787b/>`_)の発表です。今年US、Thailandにも参加している自身の体験を共有して、みんなも海外PyConに行ってみると楽しいよという話をしていました。今年は5回参加しているけど、筆者とNoah氏がさらにたくさん参加しているよと言及されていました。またこの発表の後にインドからの参加者に「PyCon Indiaにも来てね」と誘われていたようです。

* SprintSeoul

  * 韓国のYounggun氏(`@scari_net <https://twitter.com/scari_net/>`_)による発表です。ソウルでは2カ月ごとに `SprintSeoul <https://www.sprintseoul.org/>`_ という開発イベントを継続的に開催しているそうです。内容もPythonのみに限らず様々な言語で行っているようです。他の地域でもぜひやってみてねと促していました。

PyNight
-------
カンファレンス2日目の夜はオフィシャルのパーティーであるPyNightでした。
ピザなどの軽食とドリンクが振る舞われたカジュアルな会でした。

PyCon Taiwanのいつものパターンだとアルコールはないだろうなぁと思っていましたが、なんとサングリアやカクテルなど数種類のアルコールが提供されていました(しかしビールはありません)!!

奥の方でなにやら演奏がはじまりましたが、チェロの五重奏です。
写真の一番左に写っているのはPyCon Taiwan 2019のChairであるTaihsiang Ho氏です。
彼はチェロやピアノが演奏できるそうです。多才ですね。

.. figure:: /images/tw/cellos.jpg
   :width: 400

   チェロの演奏

PyNightのあとはいつものようにビールが飲みたくなったので、友人数名と `Redpoint Brewing Co. <https://www.redpointbrewing.com/>`_ に行きました。
この店には「台.P.A.」という名前のIPAスタイルのビールがあります。なかなかいいネーミングですね。
写真の真ん中に写っているのが韓国のYounggun氏で、私がPyCon MalaysiaにPSFのBooth Kitを持って行く原因となった人物です。

.. figure:: /images/tw/redpoint.jpg
   :width: 400

   naoy、Younggun、selinaとビール

カンファレンス3日目
===================

Open Spaces
-----------
カンファレンス3日目の夕方はトークセッションはなく **Open Spaces** が行われました。
Open Spacesとはその名の通り「オープンなスペース」で、場所を確保しているのでそこで「こんな話がしたい」とカンファレンス中に申し込んでディスカッションなどが行われるものです。

10個くらいのテーブルが用意されており、例として以下のようなテーブルがありました。

* asyncio
* PyCon Taiwan 2020 @ 高雄
* Health care
* Numeric software
* PyCon [A-Z]{2}

私は一通りみて回ったあとに「PyCon [A-Z]{2}」という海外PyCon参加についてディスカッションしているテーブルに入ってみました。
主催者はWei Lee(`@clleew <https://twitter.com/clleew>`_)氏で、PyCon JP参加時のさまざまな写真をスライドショーで紹介していました。

.. figure:: /images/tw/openspaces.jpg
   :width: 400

   Open Spacesの様子(奥の白いTシャツがWei Lee氏)

Wei Lee氏が他の参加者に私のことを「彼は日本から参加していて、各国のPyConで発表している」といったことを説明していました。
その後、他の参加者から「日本と台湾のPyConはどう違うのか?」という質問があったので「開発Sprintのありなしとか、チュートリアルが別の日だったりとかの細かい違いはあるけど、みんなUSのPyConやお互いを参考にしあっているのでそこまでの違いはないと思います。」という説明をしました。

ここにいた人が他国のPyConに興味を持って参加してくれるとうれしいなと思いました。

Keynote: Tracy Osborn
---------------------
* タイトル: The Different Paths We Take As Programmers 
* スライド: https://speakerdeck.com/tracymakes/keynote-the-different-paths-we-take-as-programmers

カンファレンス3日目は夕方にもTracy Osborn氏(`@tracymakes <https://tracymakes>`_)によるキーノートがありました。

現在はDjangoの書籍(`Hello Web App <https://hellowebbooks.com/learn-django/>`_)なども執筆しているスピーカーが、自身がプログラミングを学んでいった険しい道について語りました。

.. figure:: /images/tw/tracy.jpg
   :width: 400

   Tracy氏と著作

氏は現在35歳だそうですが、高校生の頃にシンプルなHTML(h1とpタグしかないような)を書いてWebサイトを作り始めたそうです。それを見て先生は「おお、Webサイトが作れるなんてすごいね」と驚いたそうです(笑)。
コンピューターやWebサイトが好きなので大学に入ってコンピューターサイエンスを学ぶことにしたそうです。
大学に入ってプログラミングを学べると興奮して「コンピューターサイエンス基礎」を受講し、10分経つとわけがわからなくて呆然としたそうです。
その後JavaやGUIなどを学びましたが、途中でデザインなどのクラスをとり、最終的には真逆の芸術の学位をとって卒業したそうです。

卒業後はデザイナーとしてWebのフロントエンドを作成するようになり、そこでJavaScriptを使い始めたそうです。
その後自分のスタートアップを起業し、技術に強い共同創業者を探します。
そしてDjangoを学び6週間でWebサイトを立ち上げたそうです。以下がその経験を書いたBlogです。

* `I'm a designer who learned Django and launched her first webapp in 6 weeks - Tracy Osborn <https://tracyosborn.com/articles/im-a-designer-who-learned-django-and-launched-her-first-webapp-in-6-weeks/>`_

このように、プログラミングを学ぶときには初心者→中級者→上級者という一本道ではなく、さまざまな道があるという話がありました。
そして自身がDjangoを学んでWebサイトを作成できるようになった経験をもとに書籍を執筆したそうです。
また、現在は大学以外にもさまざまなPython等のプログラムを学ぶためのWebサイト、サービス、動画などが提供されています。そういう大学などとは異なったパスからプログラミングを学ぶこともできるという話がありました。

さまざまなバックグラウンドを持った人がプログラミングを学ぶことに対して背中を押す、素晴らしい発表でした。
トークの終了後に「持ってきた著書をプレゼントする」と言うと、参加者が一斉に群がり即席サイン会がはじまって面白かったです。

クロージング
------------
カンファレンスの最後はChairであるTaihsiang Ho氏によるクロージングです。
スポンサーへの感謝などが述べられたあとに、TaiwanメンバーがPyCon JPに参加したときの写真を引用して、今年はツアーを行ったことが紹介されました。
また「Do you know PyCon JP?」にかけて、PyCon JP以外にもアジアや各国のPyConがあるので、ぜひ知って参加してみてほしいという話がありました。

.. figure:: /images/tw/friends.jpg
   :width: 400

   PyCon JPに参加したTaiwanメンバー

最後に壇上に主催者とボランティアが集合し、参加者から感謝の拍手が送られました。
このあと参加者全員が壇上に集合して記念撮影を行い、PyCon Taiwan 2019は終了しました。

.. figure:: /images/tw/taiwanstaff.jpg
   :width: 400

   PyCon TaiwanのOrganizerとVolunteer

打ち上げ
--------
カンファレンス後はスタッフ打ち上げに参加させてもらいました。
打ち上げ会場へはみんなでバスで移動です。
バスに乗るとJames(PyCon MalaysiaのChair)一家がいました。どうやら今回は家族旅行を兼ねていたようです。
息子さんはLEGOが好きらしく、移動のバス中で先日沖縄のパルコシティで撮影してきたLEGOの写真を見せてあげたら、興味深く見ていました。
LEGOは国や言語を超えますね。

.. figure:: /images/tw/noah-and-james.jpg
   :width: 400

   左からJames氏、筆者、息子さん、Noah氏

打ち上げ会場は台北のほど近くにあるタイ料理中心のビュッフェです。
ここのビュッフェには生ビールが付いていました。すばらしい!!!
ここでもデブ活に励みながら、いろんなスタッフやキーノートスピーカーと交流しました。

.. figure:: /images/tw/taipei101.jpg
   :width: 300

   台北101

打ち上げが終わって何人かはNight Marketに行くそうですが、私はクラフトビールが飲みたいのでそのチームとは分かれて台湾メンバー数名と一緒に飲みに行きました。
別れ際にキーノートスピーカーのPaul Ivanovが「Do you know?」と私にフリを入れてきたので「PyCon JP!!」と答えて別れました。Paulさんめっちゃ面白い人だ。

ビールのお店はZhang Men BreweryのBreezeSongGao店です。
この店は屋上に出られて、その屋上から台北101が見えるというとてもシャレオツなロケーションにあります。
心地よい夜風に吹かれながら、台湾のみなさんと楽しく過ごしました(何を話したかほぼ覚えていない)。

.. figure:: /images/tw/beer-with-taipei101.jpg
   :width: 300

   クラフトビールと台北101

おわりに
========
以上でPyCon Taiwanのレポートは終了です。
振り返ってみると私を含めて4名の日本人がトークを行い、LTでも5名が登壇しました。
「Do you know PyCon JP?」はキーフレーズとなって、参加者のみなさんに浸透したんじゃないかなと思っています。

今後もこの日本と台湾の関係性が継続して、たくさんの人が行き来するといいなと思います。
ご飯もおいしいし、漢字の意味がなんとなくわかるので、初めてのPyConとしてとてもおすすめです。

.. figure:: /images/tw/fromjapan.jpg
   :width: 400

   日本からの参加メンバー

私の次のPyConツアーはシンガポールです。
次はどんな出会いがあるでしょうか(実はこの原稿を書いている時には、すでにPyCon Singaporeは終わっているんですけどね...)。

