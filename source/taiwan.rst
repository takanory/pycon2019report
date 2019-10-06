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

オープニング
============
PyCon Taiwan 2019のChairであるTaihsiang Ho氏(`@tai271828 <https://twitter.com/tai271828>`_)によるオープニングでPyCon Taiwan 2019が始まりました。
説明は中国語でしたがスライドが英語だったので、なんとなくなにについて話しているかはわかりました。

.. figure:: /images/tw/opening.jpg
   :width: 400

   オープニング

ちなみにThaisiang氏とはフィリピンで開催されたPyCon APAC 2019で初めて会い、その後EuroPython、PyCon JPにも参加していたのでPyCon Taiwanで会うのは4回目です。
どっちも普通じゃないなと思います。

Honey, There is a Python in my Android Phone!
=============================================
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

ランチ
======
PyCon TaiwanのランチはPyCon JPと同様のお弁当スタイルです。
複数種類のお弁当が用意されており、好きなお弁当を取っていくスタイルです(結構余っていたようです)。

.. figure:: /images/tw/bento.jpg
   :width: 300

   お弁当

簡単にどんな種類の弁当があるかの説明があるのですが、なんとなく牛か豚か鶏かくらいはわかるのですが、細かい情報がわからずなかなか選びにくかったです。
おそらく3日間とも同じメニュー構成だったと思われますが、私は2、3日目に食べた韓国系の焼き肉弁当がおいしかったです。

PEP 572: The Walrus Operator
============================
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
