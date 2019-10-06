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
