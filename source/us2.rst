==============================
 US PyCon 2019レポート: 第2回
==============================

.. contents:: 目次
   :local:

カンファレンス2日目の様子をお伝えします。
この日はとにかくキーノートの内容が私には衝撃的でした。

その他にPSF(Python Software Foundation)のExcetive DirecotrであるEwa Jodlowskaさんへのインタビューや、PyLadiesオークションの模様についてレポートします。


Keynote: Shadeed "Sha" Wallace-Stepter
======================================
.. figure:: /images/us/sha.jpg
   :width: 500

   Shadeed "Sha" Wallace-Stepter氏

この日は2つのキーノートが連続しているものでした(そして、そこには大きな意味がありました)。
トークはShaさんの生い立ちの話から始まるのですが、それはとても重苦しい内容でした。
氏はサンフランシスコで5人兄弟の真ん中で生まれ、中学生の時には銃を運んでいたそうです。

この段階ですでに私は「えっ、PyConのキーノートで、このあとどういう話になるの!?」と困惑していました。その後も重たい話は続きます。

おばさんが近くに住んでおり、ドラッグのディーラーをしているということ、3歳上の兄はギャングに所属していてドラッグの売人をしていたこと、その兄が捕まって刑務所に入っていったこと。そして14歳ですべてが変わったそうです。
それは、兄が銃で撃たれて殺されたということです。
兄はSha氏の肩にもたれて、氏はその最後の吐息を聞いたそうです(兄はまだ17歳のはずです)。

そして、自身も18歳のときに犯した罪により27年間の実刑判決を受け、服役することとなります。
氏は2009年にSan Quentin刑務所に移送されましたが、そこは教育プログラムを受けることができる刑務所でした。
そこでオーディオとビデオについて学び、起業家精神が目覚めたそうです。

その後2011年から(服役中に)San Quentinテレビでコンテンツ制作者として仕事を始めたり、Podcastを行ったりしたそうです。
2016年には `TEDxSan Quentin <https://www.ted.com/tedx/events/13459>`_ というTEDxイベントを刑務所内で開催し、自らもスピーカーとして発表したそうです。

そして2017年に刑務所内でのプログラミングに関する教育プログラムでJessicaと出会い、Pythonを学んだそうです。
最初は「Python = Jessica」というイメージだったとのこと。
Jessicaは服役囚にPythonを教え、そのチュートリアルを録画しましたが、受刑者はWebにアクセスする手段を持っていません。
するとTim O'Reilly(オライリーメディアの創立者)がタブレットを刑務所に提供し、氏はオンラインコースにアクセスできるようになりました。

そして氏は19年の刑期を終え、2018年8月17日に37歳で出所しました。

最初はいったいどういう内容になるのかと思っていたキーノートでしたが、Shaさんの過酷な生い立ちから一転、San Quention刑務所に入って更生し、Pythonと出会うという素晴らしい内容でした。
そしてこのトークを受けて、Pythonを教えた側のJessica氏のキーノートへと続きます。

Keynote: Jessica Mackeller
==========================
.. figure:: /images/us/jessica.jpg
   :width: 500

   Jessica Mackeller氏

* San Wuentinでの1年前の写真
* Goalは監獄に入る人を減らすことと、再度はいる人を減らす
* 技術者は仕事とスキルとお金を持っている
* 個人として

  * お金やものの支援
  * トレーニングと社会復帰、刑務所の中でも外でも
  * Political 
* Prison Programs

  * Prison University Project
* コンピューターとか携帯の使い方を教える
* As technologists: 技術者として

  * Teck-focused job training ant re-entry

    * Last Mile: changing lives through tech
    * https://thelastmile.org/
  * Bootcamps
  * Tech support for local reform organizations

    * pro bono
* As employers

  * Hire poeple with records
  * 逮捕されたことがあると就職率が低い→黒人の方がさらに低い

    * Background checks
    * Entry-level roles
    * Active outreach

* Pilotの中でサポートするスペシャリストがいるの。すごい

  * Last MileプログラムでHTML, CSS, JavaScriptをまなんだ
  * その後Boot Campに参加

* Taking Action

  * Vote in and get our family and fire
  * Ask our employers and schools how they
  * By PyCon 2020, help someone who got out f prison recently get a job

* gofundmeで募金の呼びかけ

  * https://www.gofundme.com/antwan-williams
  * あっという間にお金が集まったらしい

.. figure:: /images/us/sha-jessica.jpg
   :width: 500

   2人のキーノートスピーカー

このトーク、 `Jessicaさんのツイート <https://twitter.com/jessicamckellar/status/1127639822640660482>`_ によると非常に残念なことに録画に失敗していたそうです。
現在再録画にむけて動いているそうで、ビデオが作成されることを私も心待ちにしています。
また、トークの概要について上記のツイートへの返答の形でJessicaさんが書いてくれているので、そちらも読んでみてください。

.. admonition:: コラム: PSF Executive Directorへのインタビュー

   * 山下 加奈恵(KANAN: `@Addition_quince <https://twitter.com/Addition_quince>`_)

   カンファレンス2日目のキーノート後に、 `PSF(Python Software Foundation) <https://www.python.org/psf/>`_ のEwa Jodlowskaさんにインタビューしてきました。
   EwaさんはPSFが初めてフルタイムで雇用した職員であり、現在はExexutive Directorとして活躍しています。
   そんなEwaさんにPSFのことやコミュニティ活動について、Python EDの寺田さんを含む4名でお話を聞いてきました。

   Ewaさんとは、もちろん初めてお会いするので、インタビュー直前は妙に緊張しましたが、笑顔で迎えてくれて一瞬で和やかな雰囲気になりました。
   短い時間でしたが、たくさんのお話を聞くことができました。

   .. figure:: /images/us/ewa1.jpg
      :width: 500

      Ewaさんへのインタビューの様子

   PSFの主な活動内容や、 `BDFL <https://ja.wikipedia.org/wiki/%E5%84%AA%E3%81%97%E3%81%84%E7%B5%82%E8%BA%AB%E3%81%AE%E7%8B%AC%E8%A3%81%E8%80%85>`_ からGuido氏が引退したことによる影響などの話も挙がりましたが、中でもコミュニティ活動の話がとても盛り上がりました。
   日本での活動として、 `Python Boot Camp <https://www.pycon.jp/support/bootcamp.html>`_ (日本中で開催している初心者向けPythonチュートリアル)や `PyLadies Caravan <https://pyladiestokyo.github.io/caravan/>`_ (日本全国の女性Pythonistaとコミュニケーションするイベント)といった、地域に限定しない全国に向けた活動を行っていることを紹介しました。
   PyLadies Caravanの活動内容については私から説明しましたが、Ewaさんが興味を持って聞いてくれたのが印象的でした。

   現在US PyConの参加者に占める女性の割合は35%程度とのことですが、数年前まではそれほど多くはなかったそうです。
   色々な試行を時間を掛けて行って、少しずつ女性の参加しやすい環境を醸成してきたとのことです。
   私自身USのPyConは初参加でしたが、女性の参加者が多いことと多様性を受け入れる雰囲気を感じていました。
   やはりそれは様々な人の努力で少しずつ作り上げてきたものなのだと思いました。
   そして、きっと日本のPyCon JPやさまざまなコミュニティでも同じように少しずつ変えられるとよいなと感じました。

   Ewaさんには、まだこれからも目指すべきコミュニティのあり方に向かって推進したいというパワフルさがいっぱいで、日本のコミュニティがより元気になるために、何をやりたいかを考えたくなる良い機会となりました。
   私自身も、これからのPyLadies Caravanなどの活動で、PyConで感じたことを還元できたらと思います。

   .. figure:: /images/us/ewa2.jpg
      :width: 500

      インタビューを終えて(右端がKANANさん)

PyLadies Auction
================
この日の夜は、韓国から参加しているYounggunから「楽しいから参加すべき」と強く言われた `PyLadies Auction <https://us.pycon.org/2019/events/auction/>`_ に参加しました。
このイベントはすでに8回目らしく、毎年PyConで開催されているようです。

このオークションはチャリティイベントであり、商品を落札することによってPyLadiesコミュニティをサポートする寄付金を支払うというものです。
単なるチャリティイベントというだけでなく、普通に入札している様子を見ているだけでもとても楽しいイベントでした。
参加者は5ドルを支払って開場に入りますが、ホテルのおいしい夕食がついてくるのですでにそれだけで5ドル分は元をとったという感じでした(ビール等は別会計です)。

.. figure:: /images/us/auction1.jpg
   :width: 500

   おいしいオークションのディナー

オークションの商品は企業スポンサーやFellowのみなさんが提供した物で、PyCon 2019のロゴをあしらったタペストリーや、Pythonロゴギター、Pythonイヤリングなどさまざまです。
スタッフ(PyLadiesメンバー)が商品を持って会場内を練り歩き、参加者が入札していきます。
私の横にいた寺田さんなどは入札しようとしていましたが、すぐに結構いい金額になるため、早々にあきらめていました(笑)。
   
.. figure:: /images/us/auction2.jpg
   :width: 500

   Pythonロゴのステンドグラス

次の商品はGuido氏の肖像画のジグソーパズルですが、途中で本人が受け取って開場を練り歩きました。面白いサプライズですし、Guido氏自身もこのイベントを楽しんでいるんだなと思いました。
ちなみにこのジグソーパズルは3,000ドルで落札されました。おどろきです。
   
.. figure:: /images/us/auction3.jpg
   :width: 500

   自分のジグソーパズルを持って歩くGuido van Rossum氏

最後の商品は先ほどのジグソーパズルの元となった肖像画です。
これが写真の通りとても大きいです。落札した人はいったいどこに飾るんでしょうか...
また、参加者の一人が「とてもいい額だね」と言ってウケてました。
この肖像画が席にいるGuido氏の後ろに来たときはシャッターチャンスとばかりに、多くの参加者が写真を撮りに行ってました(私もその一人です)。
そして、この肖像画は9,001ドルで落札されました。約100万円です。すごい(語彙力)。
   
.. figure:: /images/us/auction4.jpg
   :width: 500

   Guido van Rossum肖像画(デカい!!)
   
.. figure:: /images/us/auction5.jpg
   :width: 500

   本人と肖像画

ものすごい金額が飛び交って、日本人は全然ついていけないPyLadies Auctionでした。
なお、アメリカでは寄付の文化が根付いていることと、寄付をすると税制の優遇があることも後押しになっているのかなと思います。
自分がサポートしたいコミュニティに寄付することによって、税制的にも優遇されるのであれば、PyLadiesなどPython関連に寄付することはとてもよいことだなと思いました。
また、慈善事業というだけでなく、単体としても楽しいイベントとなっているのはさすがだなと感じました。

まとめ
======
