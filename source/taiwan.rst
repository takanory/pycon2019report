======================
 PyCon Taiwanレポート
======================

.. contents:: 目次
   :local:

鈴木たかのりです。
2019年の個人的な挑戦として「海外のPythonカンファレンスにトークやポスターを応募しまくって、採択されたら行く」ということを行っています。
今回レポートするPyCon Taiwanは7カ国目です(6カ国目は日本なのでレポートは他に譲ります)。
過去のレポートもgihyo.jpに掲載していますので、ぜひ興味のある国のレポートを読んでみてください。

* `アジアパシフィックのPyConユーザのつながりを感じた2日間「PyCon APAC 2019」レポート <https://gihyo.jp/news/report/2019/03/1201>`_
* `世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019>`_
* `日本をはじめ各国のスピーカーが語るPythonのいま ―「PyCon Thailand 2019」レポート <https://gihyo.jp/news/report/2019/07/0501>`_
* `ヨーロッパのPythonコミュニティと交流できる3日間「EuroPython 2019」参加レポート <https://gihyo.jp/news/report/01/europython2019>`_
* `データサイエンスの実践に必要な4つの柱とは？ ―「PyCon Malaysia 2019」レポート <https://gihyo.jp/news/report/2019/09/0901>`_

PyCon Taiwan
============
`PyCon <https://www.pycon.org/>`_ はプログラミング言語Pythonに関する国際カンファレンスです。
アメリカや日本をはじめ世界中で開催されています。

.. figure:: /images/tw/pycontw.png
   :width: 400

   PyCon Taiwan 2019 Webサイト

`PyCon Taiwan <https://tw.pycon.org/>`_ は2012年に第1回が開催されました。
2014年と2015年にはPyCon APAC in Taiwanとして、アジア太平洋地域のPyConが開催されました。
過去の台湾で開催されたPyConの模様は以下のレポートで確認できます。

* `台湾で開催された「PyCon APAC 2015」参加レポート <http://gihyo.jp/news/report/01/pycon-apac-2015>`_
* `台湾で開催された「PyCon APAC 2014」参加レポート <http://gihyo.jp/news/report/01/pycon-apac2014>`_
* `「PyCon Taiwan 2012」参加レポート <https://gihyo.jp/news/report/01/pycon-taiwan2012>`_

以下はPyCon Taiwan 2019の開催概要です。

:URL: https://tw.pycon.org/
:日程: 2019年9月20日(金)-22日(日)
:場所: 台湾、台北
:会場: `Academia Sinica <https://www.sinica.edu.tw/en>`_
:参加費: 3,500台湾ドル(約12,000円)

筆者自身は2012年、2013年、2015年に続いて4年ぶりにPyCon Taiwanに参加しました。
PyCon Taiwanは2012年に初めて参加した海外PyConであり、2013年に初めて海外で英語でライトニングトークを行った場所でもあるため、個人的に思い出深い地です(2012年から同じ会場で開催されています)。

またPyCon Taiwanは例年6月に開催されているのですが、今年は9月20日からとなり9月17日にPyCon JPが終了してすぐに移動というハードスケジュールでした。
9月16日週はさながらPyConウィークといった感じで非常にハードでした。

カンファレンス1日目
===================

オープニング
------------
PyCon Taiwan 2019のChairであるTaihsiang Ho氏(`@tai271828 <https://twitter.com/tai271828>`_)によるオープニングでPyCon Taiwan 2019が始まりました。
説明は中国語でしたがスライドが英語だったので、なんとなくなにについて話しているかはわかりました。

.. figure:: /images/tw/opening.jpg
   :width: 400

   オープニング

ちなみにTaihsiang氏とはフィリピンで開催されたPyCon APAC 2019で初めて会い、その後EuroPython、PyCon JPにも参加していたのでPyCon Taiwanで会うのは4回目です。
どっちも普通じゃないなと思います。

Honey, There is a Python in my Android Phone!
---------------------------------------------
* スピーカー: Ing Wei Tang

スピーカーのIng Wei Tang氏はPyCon Malaysia 2019のChairであり、私は今年のマレーシアで初めて会いました。
彼がPyCon Taiwanに参加していることを私は全然知らず、この日の朝にエレベーターでばったり会って、今日発表があることを知って聞きに来ました。

発表の内容は古くなったAndroidをどう再利用するかというところで、Java/KotlinではなくPythonでプログラミングをしようという話です。

.. figure:: /images/tw/james.jpg
   :width: 400

   Ing Wei Tang氏

話は2016年のクリスマスに遡ります。当時Tang氏は自身の蔵書のカタログを作りたいと思っていました。
ISBNから書籍に関するメタデータ(価格、著者、出版日等)を取得するPythonスクリプトを書きたが、バーコードスキャナーは持っていませんでした。

Androidにはバーコードをスキャンする機能があるので、これをPythonから呼べないかと調べてみたそうです。すると以下の2種類の方法が見つかったそうです。

* Android Scripting Environment(ASE)
* `Scripting languages for Android(SL4A) <https://github.com/damonkohler/sl4a>`_

これらを使用すると、 ``self._rpc("scanBarcode")`` のようなコードでAndroid APIとやりとりができるそうです(プライベートメソッド使うんだ...と個人的には思いました)。
このようにしてAndroidでバーコードをスキャンして、蔵書のカタログができたそうです。

次に、QPython3が紹介されました。QPython3はAndroid上で動作するアプリーションで、そのアプリの中で任意のPythonコードを実行できます。
QPython3は以下のリンクでGoogle Playストアからインストールできます。

* `QPython3 - Python3 for Android <https://play.google.com/store/apps/details?id=org.qpython.qpy3&hl=ja>`_

そのアトはQPython3で作成したアプリケーションの例として、GPSを使用した移動経路のロガーや、ジャイロスコープを利用してAndroidの向きに連動してWeb画面上の立方体が回転するデモを紹介していました。
QPython3に付属するandroidhelperを使用すると、Androidのさまざまなセンサーなどの値がとれるようです。

現実のデバイスでプログラミングするとっかかりとしては手頃で面白そうだなと思いました。
参考までに、iOSにも `Pythonista 3 <https://apps.apple.com/jp/app/pythonista-3/id1085978097>`_ という似たようなアプリケーションがあります。
興味のある方はこちらもチェックして見てください。

.. admonition:: 初めてのPyCon登壇

   Tetsuya Hirata(`@JesseTetsuya <https://twitter.com/JesseTetsuya>`_)

   去年、初めてPyCon JPの存在を知り、一般参加者として参加しました。
   それ以来、私も登壇してみたいなと思っていました。
   ある日、台湾人の友達と食事をしていた際に台湾にいきたいなと思っていたところ、ちょうどPyCon TaiwanのCFP(発表の募集)が始まっていたので、応募し採択されて登壇することになりました。

   トークセッションは、3部屋に分かれて行われ、一番大きな部屋(キーノートやオープンニングセッションが行われる部屋)で話すことになりました。以下の画像になります。

   .. figure:: /images/tw/main-hall.jpg
      :width: 400

      メインホール

   これまで国内でもLTやトークをしたことがありませんでした。
   30分のトークは初めてだったため、入念に準備をしていきました。
   この部屋で行われた過去のPyCon Tawainの動画を何度も見ましたが、動画内にはスピーカーの顔とスライドしか写っていなかったので、こんな会場になっているとは思ってもみませんでした。

   発表中に話すスピードが早くなってしまい、30分枠のトークであるにもかかわらず、およそ8分ほど余って話終えてしまいました。
   トークセッションには、発表時間 + 質問時間が設けられています。幸いにも、質問が沢山きました。以下の画像が、質疑に答えている様子です。

   .. figure:: /images/tw/jesse-qanda.jpg
      :width: 400

      質問に答えているところ

   質問は、発表の間、sli.do (https://www.sli.do/)上でうけつけ、司会役の方が読み上げてくれます(sli.doは勉強会やカンファレンスにて、会場からの質問を匿名で集められるサービス)。

   しかし、一部聞き取れず、「I'm sorry that I can not answer this question(ごめんなさい、その質問には答えることができません)」と答えて誤魔化したりしていました。

   そんなこんなで誤魔化していましたが、実は、そのsli.do上の質問内容が後ろのスクリーンに写っていました。

   いずれにせよ、時間が余ってしまったことは、反省点として残りましたが、ある意味伸びしろがあると捉えるようにしました。
   sli.doで上がってきた質問への回答内容を、スライドに盛り込めば、ちょうどいい時間で発表が終わるなと思いました。

   PyCon Taiwanのスタッフの方々に、とても親切にして頂きました。
   スタッフの飲み会に参加させて頂いたり、夜市に連れて行ってもらったり、発表30分前にPC接続確認と軽い練習をやらせて頂いたりしました。
   ここで頂いた恩は、どこかで台湾のPythonコミュニティに返せるといいなと思っています。

   .. figure:: /images/tw/taiwanstaff.jpg
      :width: 400

      PyCon Taiwanスタッフとボランティア

ランチ
------
PyCon TaiwanのランチはPyCon JPと同様のお弁当スタイルです。
複数種類のお弁当が用意されており、好きなお弁当を取っていくスタイルです(結構余っていたようです)。

.. figure:: /images/tw/bento.jpg
   :width: 300

   お弁当

簡単にどんな種類の弁当があるかの説明があるのですが、なんとなく牛か豚か鶏かくらいはわかるのですが、細かい情報がわからずなかなか選びにくかったです。
おそらく3日間とも同じメニュー構成だったと思われますが、私は2、3日目に食べた韓国系の焼き肉弁当がおいしかったです。

PEP 572: The Walrus Operator
----------------------------
* スピーカー: Dustin Ingram
* スライド: https://speakerdeck.com/pycon2019/dustin-ingram-pep-572-the-walrus-operator (US PyConでのスライドですが、内容はほぼ同じです)

Dustin氏はGoogleのDeveloper Advocateであり、Python Package Authority(PyPA)のメンバーでもあります。
氏はPyCon JP 2019でも「Modern Development Environments for Pythonistas」というタイトルで発表をしていましたが、台湾では異なるタイトルでの発表でした。
こちらの内容はUS PyCon 2019でも発表していたようです。

今回は期間が近いということもあり、このようにPyCon JPとPyCon Taiwanの両方で発表している人が結構います。

.. figure:: /images/tw/dustin.jpg
   :width: 400

   Dustin Ingram氏

発表はPEP572の話に入る前に、PythonのGovernance(運営)についての話から始まりました。
言語の最終決定者としてBDFLのGuido van Rossum氏がおり、PEPで言語仕様の提案が行われていることの説明がありました。
自分の一番好きなPEPは `PEP 566 Metadata for Python Sofotware Packages 2.1 <https://www.python.org/dev/peps/pep-0566/>`_ と言ってましたが、自身が作成者のPEPだからだそうです(笑)。
PEPはDraft(草稿)が議論を得てAccept(採択)されるとImplementation(実装)が行われます。
また、すべてのPEPの判断をGuido氏が行うことは大変なため、BDFL Delegatesという仕組みで判断をGuido氏が他の人に委任することができます。

次にPEP 572のセイウチ演算子(``:=``)をいくつかの例を交えて紹介していました。
以下はその一例で、上が既存の書き方で下がセイウチ演算子を使った場合です。

.. code-block:: python
   :caption: 関数の呼び出し回数を減らす

   foo = [f(x), f(x)**2, f(x)**3]

   foo = [y:= f(x), y**2, y**3]

.. code-block:: python
   :caption: ストリームの処理

   chunk = file.reads(8192)
   while chunk:
       process(chunk)
       chunk = file.reads(8192)

   while chunk := file.reads(8192):
       process(chunk)

しかし、この演算子は `=` とは同じように使えない場合がいくつかあり、それらも実例を交えて紹介していました。
この部分は個人的にとても勉強になりました。

.. code-block:: python
   :caption: セイウチ演算子を使用できないパターン

   (z := (y := (x := 0)))
   a[i] := x
   self.rest := []
   (x := 1, 2)  # xには1がセットされる
   total +:= tax

このセイウチ演算子の元となったPEP 572ですがメーリングリスト上で非常に長い議論となりました。
またさまざまなコアの開発者が意見を述べました。

* `Poll: Do you like the PEP 572 Assignment Expressions?のメールのスレッド <https://mail.python.org/archives/list/python-committers@python.org/thread/23IAVIROHJFSNTPWQ7SYO4OS4XLWRAMR/#6LP4HRABH5T5HNULQAU5TLADODXPMYAE>`_

そして2018年7月12日に、Guido氏がPEP 572をAcceptし、そのあとにGuido氏がBDFLをやめるというメールを出しました。
当然ですがこれはPython界隈に衝撃的なニュースとして伝わり、さまざまな人がツイートしたそうです。

* `PEP 572をAcceptしたPull Request <https://github.com/python/peps/pull/735/files>`_
* `Guido氏のメール: Transfer of power <https://mail.python.org/archives/list/python-committers@python.org/message/GQONAGWBBFRHVRUPU7RNBM75MHKGUFJN/>`_

その後Python言語の仕様策定をどのように運用していくかの議論がはじまり、 `PEP 8000 Python Language Governance Proposal Overview <https://www.python.org/dev/peps/pep-8000/>`_ をベースにいくつかの運営方法が提案され、投票で `PEP 8016 The Steering Council Model <https://www.python.org/dev/peps/pep-8016/>`_ がそして。
採用されました2019年1月から2月にかけてSteering Councilメンバーの投票が行われ5名のCouncilメンバーが決定しました。

この5名のメンバーによるキーノートがUS PyConで行われ、その模様は以下の記事でレポートしてあります。

* `第3回　3日目朝のLT紹介，キーノートはPython仕様策定のキーパーソンによるパネル：世界最大のPythonカンファレンス「US PyCon 2019」レポート <https://gihyo.jp/news/report/01/us-pycon2019/0003?page=2>`_

PEP 572の技術的な話だけでなく、その周辺で起こったPythonの運営体制などについても触れた、興味深いトークでした。

おやつタイム
------------
おやつタイムは午前と午後に毎日提供されていました。
甘い物もしょっぱいものもあり、また飲み物は基本的に砂糖入りとデブ活がはかどります...

.. figure:: /images/tw/snacks.jpg
   :width: 300

   大量のおやつ

この時間に書籍の販売コーナーに寄ってみたところ、私の書いた `Pythonによるあたらしいデータ分析の教科書 <https://www.shoeisha.co.jp/book/detail/9784798158341>`_ の中国語版が置いてありました!!
誰かが購入してくれてたらうれしいのですが...
書籍は全体的にディープラーニング系が多いかなという印象でした。

.. figure:: /images/tw/book.jpg
   :width: 400

   私の本が置いてあった!!

また企業ブースもまわってみましたが、京都に本社がある `ハカルス <https://hacarus.com/ja/>`_ さんがブースを出していました。
メンバーのニノさんとはPyCon APACのときに挨拶していたので、ここで再会できました。
CTOの染田さんは2日目に発表予定です。

.. figure:: /images/tw/hacarus.jpg
   :width: 400

   HACARUSブース

ライトニングトーク
------------------
ライトニングトークはしゃべりたいタイトルと連絡先を紙に買いて受付にある箱に入れて、選ばれた人には連絡が来るというスタイルです。
1日目のライトニングトークは申し込んだ人が少なかったのかわかりませんが、5名中4名が日本人(しかもPyCon JPスタッフ)という「お前らちょっと自重しろw」という布陣となりました。
ここで「Do you know PyCon JP?」みたいに、全員で同じフレーズをかぶせていったらウケるのでは?という話を日本人の中でしていました。

それぞれ以下のようなタイトルでMinecraftをPythonから扱う話、PyCon JPで使っているツールの話、PyCon JP 2019の振り返り、PyCon JP 2019の準備をPythonで行った話をLTでしつつ「Do you know PyCon JP?」で少しずつウケていました。

* Minecraft Education and Python - Daisuke Saito
* PyCon JP Introduction of useful tools - Shunsuke Yoshida
* Recap PyCon JP 2019 - Naotaka Yokoyama
* Prepare PyCon JP 2019 with python - Nikkie

.. note::

   以下の4枚の写真は多いので、まとめて1つの写真にしてもいいかなと思います

.. figure:: /images/tw/lt-daisuke.jpg
   :width: 400

   Minecraft Education and Python - Daisuke Saito

.. figure:: /images/tw/lt-yoshida.jpg
   :width: 400

   PyCon JP Introduction of useful tools - Shunsuke Yoshida

.. figure:: /images/tw/lt-naoy.jpg
   :width: 400

   Recap PyCon JP 2019 - Naotaka Yokoyama

.. figure:: /images/tw/lt-nikkie.jpg
   :width: 400

   Prepare PyCon JP 2019 with python - Nikkie

すると、この日最後のLTスピーカーであるKeith Yang氏が、急遽用意した「Do you know PyCOn JP?」のスライドで全部持って行かれました。
彼は過去PyCon Taiwanや各国PyConでも発表経験があり、さすがだなーと思いました。

.. figure:: /images/tw/lt-keith.jpg
   :width: 400

   Keith Yang氏によるDo you know PyCon JP?

.. admonition:: 初めての海外PyConでLT

   PyCon Taiwanは、私にとって初めての海外、初めての海外PyConでした。
   PyCon Taiwanのスタッフをはじめ、色々な方に助けていただき、抽選では運も味方して、カンファレンス1日目にLTができました。
   そのレポートをお送りします。

   2019年に入ってから、私はPyCon JPのコンテンツチームでスタッフ活動をしています。
   コンテンツチームにはPyCon Taiwanに参加する人が多く、海外で知っている人がいるというのは心強かったです。

   開催直前のお知らせメールでは以下のように案内されていました。

   - カンファレンス3日間、毎日の終わりにLTの時間がある
   - LT希望者は、紙片に名前とタイトルを書き、受付近くの壺(jar)に入れて応募する
   - 正午にその日のLTのリストを発表する

   1日目の朝、会場入りした私はLT応募の壺を探します。
   受付周辺が混雑していて見つけられなかったのですが、 `Twitterで疑問を発信 <https://twitter.com/ftnext/status/1174854032164151296>`_ したところ、 `PyCon TWのスタッフの方に回答していただけ <https://twitter.com/PyConTW/status/1174861873759444994?s=20>`_ 、応募することができました。

   お昼過ぎに結果の連絡が来て、LTに確定しました。
   そのあとはトークを聞きつつ、急ぎスライドを作りました。
   行きの飛行機の中でアウトラインは用意していたので、スライドに書き起こしていきます。

   私のLT「 `Prepare PyCon JP 2019 with Python <https://gitpitch.com/ftnext/2019_slides/master?p=pycontw_lt_staff_python>`_ 」では、PythonにもPyCon JPスタッフ活動を手伝ってもらったことを共有しました。
   `PyCon JPのスプリント <https://pyconjp.connpass.com/event/136558/>`_ では、 `応募されたスプリントプロジェクトの一覧 <https://docs.google.com/spreadsheets/d/1SNQsUUar-TD5AHfdDxupgjpdmvBF6Ao_wQ_lf5kJFjo/edit#gid=0>`_ をGoogleスプレッドシートで公開していました。
   最新の応募状況を定期的に取得し、一覧シートを更新する必要があります。
   「こういった繰り返しタスクをPythonにやってもらったよ」という事例を紹介しました。
   本番のシートとは別にデモ用のシートも用意して、実際にシートを更新する様子を見せることもできました。

     .. figure:: /images/tw/thanks-for-pycontw-staff.jpg
      :width: 400

      PyCon Taiwanスタッフの皆さんへのお礼を伝えるスライド

   初めての英語LTだったので、共有したかったことがどれだけ伝わったかは分からないのですが、「初めての海外カンファレンスでLTしています！」「PyCon Taiwanのスタッフの皆さんのおかげで楽しく過ごせています」と伝えたときにいただいた拍手は暖かく、とても嬉しかったです。
   英語で話し、それにリアクションをいただいた5分間は、トークを聞くだけの参加者としては味わえない経験でした。
   次にまたLTをやるとしたら、日本語でやるのと同じくらい会場を沸かせてみたいなと思います。

   英語での発表と聞くと、敷居が高く感じるかもしれません。
   ですが、共有したいことがあるのでしたら、不安を抱えつつもチャレンジしてみることをオススメします。
   「LTをやりたい」という想いがあれば十分です。
   分からないことは質問すれば、きっと色々な方が助けてくれるでしょう。
   質問したいけれども英語がうまく出てこないとき、私はGoogle翻訳アプリを使って筆談していました。
   そして、自分の話に聞き手が反応するという時間は、きっと得がたい経験になります。

   最後に、PyCon Taiwanのスタッフ・参加者の皆さま、素敵なカンファレンスをありがとうございました。


スピーカーディナー
------------------
1日目の夜はスピーカーを招待したディナーがあったので、そちらに参加してきました。
カンファレンス会場から送迎バスで移動して***駅のショッピングモールに来ました。
SUNRISEという名前のビュッフェスタイルのレストランでディナーです。

入り口で名前を確認され、それぞれ指定されたテーブルに着くというスタイルでした。
私の席にはPyCon Taiwanの立ち上げメンバーであるYung-Yu Chen氏や、Shoppyというスポンサーの方などがいました。

.. figure:: /images/tw/speaker-dinner.jpg
   :width: 400

   スピーカーディナーの様子

スタッフ、スピーカー、スポンサー含めて4~50名はいたでしょうか?
さまざまな宗教や食事の制限があったりするので、ビュッフェ形式は理にかなっているなと思いました。
ただ、当然のようにビールがなかったりするので、ひとしきり食事を楽しんでいろんな人と話をしたあとは、台湾のクラフトビールの店に移動です。
この日はDriftwoodというお店で先に何名か日本からの参加メンバー飲んでいて、そこにあとから合流しました。

.. figure:: /images/tw/driftwood.jpg
   :width: 400

   Driftwood

.. todo:: driftwoodで飲んでいる写真

Driftwoodで飲んだあとはホテルに帰るのですが、私と他数名はカンファレンス会場の近くに宿泊しているため、戻る必要があります。
Googleマップで検索してみるとまだ電車が動いているようで、西門から台北駅まで歩いて移動して電車に乗りました。
台北駅はさまざまな路線が入っているため少し迷いましたが、なんとか電車に乗ってホテルの最寄り駅まで戻ることができました。ちなみに写真の通り終電でした。
南港駅からホテルまで距離があるのでタクシーで帰ろうと思いましたが、乗ってみたタクシーでは全然話が通じず、やむを得ず降りてUBERで帰りました。
やっぱり海外だとUBERなどの配車サービスは便利ですね。

.. figure:: /images/tw/last-train.jpg
   :width: 400

   台湾でまさかの終電

こうして、なんとか1日目が終わりました。

カンファレンス2日目
===================

Keynote: Paul Ivanov
--------------------
* Programming Language Tourism

Paul Ivanov(`@ivanov <Programming Language Tourism>`_)氏はJupyterの `Steering Counsil <https://jupyter.org/about>`_ メンバーであり、Bloombergのシニアエンジニアです。

「私たちはどこにいますか?いま私たちはPyCon Taiwanにいます。」と問いかけたあとに「どこからきましたか?」と参加者に問えば、それぞれ異なったスケールで回答があるよといいました。例えばJupyterの人に聞いたら多分「地球から」と答えるだろうと(笑)。
アメリカならカリフォルニア、サンフランシスコと答えたり、ベイエリアと答えたりといった感じです。

* Jupyter の Counsil
* 台北ははじめて
* PythonがStackoverflowでトップになった
* 育っているしHappy
* GitHubのデータでもPythonはだいたい3番目くらい(JS, Java)
* Goodbye, Python 2: なんか面白い詩のようなものがあった
* Scratch

  * MakeCode Arcade→JSに変換できる

自分の発表
----------
* HackMD: https://hackmd.io/@PyConTW/2019/%2F%40pycontw%2FB1i3ro2UB
* Slide: https://gitpitch.com/takanory/slides?p=20190922pycontw#/
* 無事発表終了
* 30分なので結構はしょりぎみに説明した。コードとかは細かく話せない感じ
* 質疑応答は3分間

.. figure:: /images/tw/takanory.jpg
   :width: 400

   筆者の発表の様子

* How to avoid the 3 second response time limit from slack api when using slack bot?

  * BotではRTM APIが推奨されている。Botの場合は手でコマンドを送ってそれに反応しているので、あまり3秒のリミットは気にならない
  * もう一個思い出せない。

ライトニングトーク
------------------
カンファレンス2日目のライトニングトークでもいろいろな発表がありました。いくつか紹介します。

.. figure:: /images/tw/students.jpg
   :width: 400

   高校生たちによる発表

* 高中生做點事

  * 言葉がわからないので意味は全くわかりませんでしたが、元気な高校生4人組の発表でした。あとで調べてみたところソフトウェア関係の部活のようで、小学生にプログラミングを教えたりもしているようです。発表の中では自分たちの活動とLINEBotを紹介していました。

* 個人発起的小小小社群

  * PyCon JPにも参加していたKK氏による発表です。小さいコミュニティを作って継続しようということを参加者に勧めていました。

* 高雄發大財

  * Kaohsiung(高雄).pyの主催者による発表です。高雄は台湾の南にある都市で、将来的にPyCon Taiwanを高雄で開催したいという発表をしていました。また、LTの冒頭に「Do you know Kaohsiung.py」と1日目のLTのネタをかぶせてきました。

* My PyCon diary in 2019

  * 日本から参加したLina KATAYOSE氏(`@selina787b <https://twitter.com/selina787b/>`_)の発表です。今年US、Thailandにも参加している自身の体験を共有して、みんなも海外PyConに行ってみると楽しいよという話をしていました。今年は5回参加しているけど、筆者とNoah氏がさらにたくさん参加しているよと言及されていました。またこの発表の後に「インドに来てね」というように誘われたそうです。

* SprintSeoul

  * 韓国のYounggun氏(`@scari_net <https://twitter.com/scari_net/>`_)による発表です。ソウルでは2カ月ごとに `SprintSeoul <https://www.sprintseoul.org/>`_ という開発イベントを継続的に開催しているそうです。内容もPythonのみに限らず様々な言語で行っているようです。他の地域でもぜひやってみねてと促していました。

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
主催者はWei Lee(TODO: Twitter)氏で、PyCon JP参加時のさまざまな写真をスライドショーで紹介していました。

.. figure:: /images/tw/openspaces.jpg
   :width: 400

   Open Spacesの様子(奥の白いTシャツがWei Lee氏)

Wei Lee氏が他の参加者に私のことを「彼は日本から参加していて、各国のPyConで発表している」といったことを説明していました。
その後田の参加者から「日本と台湾のPyConはどう違うのか?」という質問があったので「開発Sprintのありなしとか、チュートリアルが別の日だったりとかの細かい違いはあるけど、みんなUSのPyConやお互いを参考にしあっているのでそこまでの違いはないと思います。」という説明をしました。

ここのいた人が他国のPyConに興味を持って参加してくれるとうれしいなと思いました。

Keynote: Tracy Osborn
---------------------
* タイトル: The Different Paths We Take As Programmers 
* スライド: https://speakerdeck.com/tracymakes/keynote-the-different-paths-we-take-as-programmers

カンファレンス3日目は夕方にもTracy Osborn氏(`@tracymakes <https://tracymakes>`_)によるキーノートがありました。

.. figure:: /images/tw/tracy.jpg
   :width: 400

   Tracy氏と著作

終了後に持ってきた書籍をプレゼントするというと、参加者が一斉に群がる様が個人的には面白かったです。

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

   James氏、息子さん、Noah氏と

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
