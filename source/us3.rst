==============================
 US PyCon 2019レポート: 第3回
==============================

レポートの第3回は、カンファレンス3日目前半の様子をお伝えします。
朝のライトニングトーク、Python Steering Councilによるkeynoteです。
Councilは今後のPython言語仕様を策定する委員会です。
コラムではランニングイベントのFun Runと就職イベントのJob Fairについてレポートします。

.. contents:: 目次
   :local:

ライトニングトーク
==================
* ビデオ: https://www.youtube.com/watch?v=bnxxoTx9Sko

3日目は朝8:40からライトニングトークです。朝早いですね...
いくつかの発表をピックアップして紹介します。

* Code Our Dreams
  
  高校生にもコンピューターサイエンスやプログラミング的な知識はこれから重要になるが、先生がいなかったり、学校が貧乏なためにPCの数が足りなかったりとかで、そういうことを学ぶ機会に恵まれない学生がたくさんいるそうです。
  そこで発表者は `Code Our Dreams <https://www.codeyourdreams.org/>`_ (注: 今はCode Your Dreamsと名前が変わったようです)という非営利の団体を立ち上げ、シカゴの学生にプログラミングを教える活動をしているそうです。
  この活動に共感する企業に、スポンサーをしてほしいという要望を伝えていました。
  スピーカーは大学生ですが、地域の課題を解決するために団体を立ち上げて活動しPyConで発表するという、すごい人がいるもんだなーと感じました。

.. figure:: /images/us/codeourdreams.jpg
   :width: 400

   Code Our Dreamsについての発表

* learn to program with minecraft

  PythonからMinecraftにつなげられるシステムはありますが、現状は片方向(Python→Minecraft)しかやりとりができません。
  それをWebSocketを使用して双方向でやりとりできる仕組みを開発中とのことです。
  現在はコンセプト段階とのことです。

* PySlackers

  Pythonユーザーが集まっているSlack上のオープンコミュニティの紹介です。
  https://pyslackers.com/ から参加できます。
  現在21,352人のメンバーがおり、79のチャンネルがあるそうです。
  無料版のSlackは参照できるメッセージ数に上限があり、現在は一週間くらいで過去のメッセージが見れなくなるそうです。

* conda-forge

  Anacoda用のパッケージをwheelに変換するライブラリの紹介です。
  `conda-press <https://github.com/regro/conda-press>`_ を使うと変換できるそうです。

* Regional Python Conferences!

  各地域、各国のPython関連のカンファレンスを紹介するLTです。
  1イベント30秒くらいでテンポ良くつないでいきます。
  PyCon Africa(今年初めて開催される、アフリカ全域のPyCon)や、PyCon JPの紹介もありました。

  スライドはあっても発表する人がいないときに、その前のイベントの人が「このイベントのことはよく知らないけどー」とか言いながら、適当に説明するのが個人的には面白かったです。
    
.. figure:: /images/us/pycon-africa.jpg
   :width: 400

   PyCon Africaはガーナで8月に開催

.. figure:: /images/us/pycon-jp.jpg
   :width: 400

   寺田さん(`@terapyon <https://twitter.com/terapyon>`_)によるPyCon JPの紹介

.. admonition:: コラム: 5k Fun Run/Walk

   * Lina Katayose(`@selina787b <https://twitter.com/selina787b>`_)

   カンファンレンス3日目の朝にはFun Runというイベントがありました。
   
   `5k Fun Run/Walk <https://us.pycon.org/2019/5k/>`_ はタイトルの通り、5kmを楽しく走るイベントです。
   いつかやってみたいと思っており、今年初めて参加できました。

   参加者は朝6時にカンファレンス会場近くの集合場所に集まり、スクールバスでEdgewater Parkに移動し、この公園内でレースをします。
   Fun Run開始時はとても寒く、気温は11℃くらいでした。
   朝早く起きて「寒い中、どうしてこんなチャレンジをしているのか」と自問自答しながらも、レース会場に向かっていました。
   十分な防寒対策などはなく、私はレギンスとPyLadies Tシャツのみ。
   レース開始までガクガク震えながら待っていました。

   レース参加者は事前に受付で参加チケットを渡して、レースTシャツとゼッケンを渡されているようでした。しかし、私の英語理解不足で、Tシャツとゼッケンを交換できておらず、当日スクールバスの中で交換をしました。
   スクールバスはアメリカ映画で見た黄色いもので、初めて乗りました。

   .. figure:: /images/us/schoolbus.jpg
      :width: 300

      黄色スクールバス

   バスの中では、隣に座った方とお話しました。いろいろ話しているうちにレース会場に到着し、簡単な準備運動をしてレースの開始を待ちます。レース会場は簡易的なものかと思いきや、設備もしっかりとしていて驚きました。

   .. figure:: /images/us/selina.jpg
      :width: 200

      PyLadies Tシャツ

   そして、レースが始まりました。はじめのうちは先頭集団に何とかついていきましたが、途中から急激なペースダウン。筋トレはしていたものの走る練習をしていなかったため、全くダメでした。それでも「せっかく来たのだから走り切ろう」という気持ちが働き、走り切りました。それにしても疲れた！けど、走り切った！

   結果、私の記録は34分34秒。女性の部で5位(9人中)、全体では48位(62人中)でした。
   5kmレース自体も初めてだったので、自分なりには良いかなと思っています。次回は23分を目指したいです！

   レースの結果は以下のページから参照できます。

   * `PyCon 5k Fun Runの結果 <https://www.hermescleveland.com/roadracing/results/2019/PYCON.htm>`_
    
キーノート: Python Steering Council
===================================
* ビデオ: https://www.youtube.com/watch?v=8dDp-UHBJ_A

ライトニングトークに続けてPython Steering Councilによるキーノートがありました。
Python Steering CouncilとはPythonの言語仕様を策定する委員会の名前です。

今まで、Pythonの言語仕様の策定は、Guido氏が `BDFL <https://ja.wikipedia.org/wiki/%E5%84%AA%E3%81%97%E3%81%84%E7%B5%82%E8%BA%AB%E3%81%AE%E7%8B%AC%E8%A3%81%E8%80%85>`_ として最終決定を行ってきていました。
しかし、Guido氏が2018年7月12日にBDFLからの引退を表明したため、今後の仕様策定をどう決めていくかという議論があり、 `PEP 13 -- Python Language Governance <https://www.python.org/dev/peps/pep-0013/>`_ でPython Steering Councilという5名の組織で決定していくこととなりました。
その後、 `PEP 8100 -- January 2019 steering council election <https://www.python.org/dev/peps/pep-8100/>`_ で投票が行われ、Councilのメンバーが決定しました。

* 参考: 引退を表明したメール `[python-committers] Transfer of power <https://mail.python.org/pipermail/python-committers/2018-July/005664.html>`_

このキーノートでは、2日目のレポートのインタビューにも出ていた、PSF(Python Software Foundation) Executive DirectorのEwa Jodlowska氏が司会進行し、それに対してCouncilメンバーが質問に回答する形で進行しました。

.. figure:: /images/us/council.jpg
   :width: 400

   Python Steering Council

* Ewa: まずは自己紹介をお願いします。

  * Berry Warsaw: LinkedInで働いていて、Python Foundationチームにも在籍しています。1994年にGuidoと出会って、それからPythonとGuidoが好きです。最初のPython workshopは20名の参加者だったけど、25年でものすごい参加者となってびっくりしている。
  * Brett Cannon: MicrosoftのVSCodeのPython拡張の開発マネージャーをしています。大学でPythonと出会いPython devメーリングリストでさまざまなやりとりをしたりPRを送ったりしていた。
  * Carol Willing: 2016にフィリピンのキーノートでPythonが人々のプログラミング言語であるという話をしました。2012年にPythonのプログラミングをはじめ、Jupyter Notebookはとても便利なツールだと感じた。そしてこのコミュニティの一員になりたいと思った。
  * Guido van Rossum: 私はプログラマーでした。好きなプログラミング言語がなかったのでPythonを作りました。Pythonはオープンソースと残りはコミュニティです(拍手)。BDFLとして30年間PEPでの仕様の採択をしてきました。

    論争を呼んだPEP(注: `PEP 572 <https://www.python.org/dev/peps/pep-0572/>`_)を採択した次の日の朝、私はもうBDFLをやりたくないと思いました。そこで20分かけてコア開発者に対して自分たちで今後は進めてほしいというメールを送りました。コア開発者は委員を立ち上げるという方向に消えました。それは正しいやり方でとても安心しました。

    みなさんは子どもを大学生まで育てたことはありますか?直接関わることはほとんどなくなりますが、気にかけることをやめることはありません。私はそのような感覚を今Pythonに対して感じています(拍手)。それが、私が自分でSteering Councilに立候補して、イマココにいる理由です。
  * Nick Coghlan: ハードウェアとC++から、Pythonを使うようになった。Pythonを使うようになったのは、シグナルプロセッシングとunit testがあること、waveモジュールがあることやSWIGを使ってC++のモジュールをラップして使えるからです。Pythonを使ってハードウェアと通信するシステムを作成した。Pythonを使うことによって現実世界の面倒な部分を無視して、開発できるようになった。

* Ewa: ガバナンス(組織運営)がBDFLからSteering Councilに変わって、Pythonはどのように変化し続けると思いますか?

  * Guido: BDFLだったころ、PEP(Pythonの拡張提案)に対して最終的にyes/noやA/Bを選ぶことは責任があり、かなりストレスが大きかった。そのストレスがCouncilの5人に分散されるようになる。
    Python言語の組織運営については `PEP 13 <https://www.python.org/dev/peps/pep-0013/>`_ に記載した規定に則って運営することになります。
    もっと重要な決定は、決定のためにコア開発者や外部の協力者に決定を委任することです。
    まだ数ヶ月しか経っていませんが、このやり方はうまくいくと思います。
    今後のCouncilはできるだけ決定を委任していこうと思います。
    
* Ewa: Pythonとデータサイエンスは継続して成長しています。CarolはJupyterのSteering Councilメンバーでもありますが、科学系のPythonコミュニティの強さについて教えてください。

  * Carol: 新しいアイデアをコミュニティの全エリアから聞くことが大事です。Web、組み込み、教育、科学、データ分析などそれぞれ異なる要望があります。Steering Councilにさまざまなバックグランドのメンバーがいることにより、よりより選択をできると思います。

* Ewa: Brett、たくさんのインフラ関係の作業を管理してきました。Mariattaが作成した `PEP 581 <https://www.python.org/dev/peps/pep-0581/>`_ でバグチケットを bugs.python.org からGitHubに移動する予定ですが、現在はどのような状況でしか?

  * Brett: まず最初にPEP 581について議論し、私たちはそれを受諾しました。そして実際の移行作業を `PEP 588 <https://www.python.org/dev/peps/pep-0588/>`_ にまとめています。language summitでもこの件について議論しフィードバックをもらいました。大きな問題はないので進めていく予定です。

* Ewa: Packagingワークグループはmozillaから支援を受けた。次のアクションは?

  * Nick: パッケージ関連ではPython Packaging Authority(PyPA)とPackaging workgroupがあります。これはPSFとコア開発者の関係と似ています。PyPIの利用者の使い勝手は向上してきたが、パッケージ作成者にとっては異なるプラットフォーム、異なるPythonバージョン用のパッケージを作成するなど複雑になっています。そこをよりよくしたいです。
  * 開発Sprintでパッケージについて議論するので、そこでもアイデアが出てくるでしょう。

* Ewa: 新しいガバナンスモデルでは `PEP 1 <https://www.python.org/dev/peps/pep-0001/>`_ (注: PEPのガイドライン)を変更しますか?

  * Brett: PEPはRFCなどのアイデアからきています。現在のプロセスは必要十分だと思います。PEPは意思決定するためのプロセスで、BDFL delegateという決定を他のエキスパートに委譲する仕組みがあります。Pythonコミュニティは大きくなったので、次の世代のリーダーは言語についての重要な決定をする機会があります。リーダーにはコミュニティとPython言語を健全な状態で、次の25年を活気にあふれたものにしてほしいです。そのためにも積極的に権限を委譲していこうと思います。
    
* Ewa: Python言語の実装か言語そのものだと、どこを見ていこうと思っていますか?

  * Guido: 私たちはPythonの実装を見ています。私たちはPython言語とその実装をどのように進めていくかについて議論しています。

* ここで会場に対して「Python 2を使っている人」と質問して挙手を求めました。「思ったよりは少ない」とのコメントでした。
* Ewa: Python2のサポートが2020年1月1日で終了します。あと8ヶ月ですが、何かプランはありますか?

  * Guido: パーティー?(拍手)
  * Nick: 数年前のPyCon AustraliaでPython 3についてのよい発表があった。その中で商用ベンダーはPython 2を2020以降もサポートするオプションを紹介していた。
  * Carol: 科学者はPython 3を長い間使用しています。過去のPyConでInstagramが2から3に移行した素晴らしいキーノートがあったでの、参考になります。

* 参考: `Pycon2017 instagram keynote <https://www.slideshare.net/LisaGuo4/pycon2017-instagram-keynote>`_    

* Ewa: コア開発者のDiversity(多様性)を継続、ひろげるのためになにか考えはありますか?

  * Carol: 2017年にMariattaが最初の女性コア開発者となりました。楽しかったら開発Sprintにも参加してください。
  * Barry: Paul Everettについて触れておきたいです。彼はコミュニティでいろんな人をメンターした。

* Ewa: ここで、sli.doを使って会場からの質問を受け付けました。
* 一番好きなPEPはなに?

  * Barry: `PEP 401 -- BDFL Retirement <https://www.python.org/dev/peps/pep-0401/>`_ (エイプリルフールのジョークPEPです)
  * Brett: `PEP 3100 -- Miscellaneous Python 3.0 Plans <https://www.python.org/dev/peps/pep-3100/>`_ (Python 3.0計画)
  * Crarol: `PEP 581 -- Using GitHub Issues for CPython <https://www.python.org/dev/peps/pep-0581/>`_ (CPythonのバグをGitHubで管理する)
  * Guido: `PEP 484 -- Type Hints <https://www.python.org/dev/peps/pep-0484/>`_ (型ヒント)
  * Nick: `PEP 343 -- The "with" Statement <https://www.python.org/dev/peps/pep-0343/>`_ (with文)

* Ewa: Pythonのコア開発者になるための最初のステップはなんですか?

  * Brett: `Python Developer's Guidee <https://devguide.python.org/>`_ を見てください。そこに開発をはじめるためのアイデアなどのドキュメントがまとまっています。

* Ewa: コア開発者が燃え尽きたという話をよく聞きます。Councilにはそれを改善する計画はありますか?コミュニティになにかできることはありますか?

  * Brett: PEP-581でコア開発者はより作業がやりやすくなると思います。また昨年のキーノートでこのことについて話しました。私たちが下した決定に対してソーシャルメディアなどの反応をよく見ています。建設的なフィードバックは歓迎ですし、否定的なフィードバックも排除すると言うことはありません。オンライン上でのやりとりがちょうどよいものであることは、燃え尽きることを防ぐ助けにとてもなります(拍手)。
  * 参考: `PyCon 2018のBrettによるキーノート <https://youtu.be/tzFWz5fiVKU?t=2969>`_
  * Nick: 私たちはPSFとともに積極的に活動していきます。みなさんがPSFやコア開発者をサポートする具体的な方法があります。現在ファンドレイザー(資金調達)が進行中です。

* Ewa: 最後によい補足をありがとうございます。  https://pycon.us/psf からファンドレイザーのページにアクセスできます。それではみなさん参加してくれてありがとうございます。残りのPyConを楽しんでください(拍手)。
  
.. figure:: /images/us/council2.jpg
   :width: 400

   Councilメンバー

.. admonition:: コラム: Job Fair

   * Masaki Kagesawa (影澤 正輝: `@Masakikage <https://twitter.com/Masakikage>`_)

   僕にとってPyConでの最大の収穫はJob Fairでした。普通アメリカ(筆者中: 影澤さんはニューヨーク大学の大学生)で大学生が行くJob Fairは各企業にリクルーターが1〜2人来て、人気企業は話すだけで30分待ちになるのが普通です。

   PyConの参加者の多くは仕事探しをしているわけではないためJob Fairは混んでなく、各ブースでエンジニアとリクルーターの両方からしっかりと話を聞けました。

   アメリカでの就職はオンラインでアプリケーション(日本のエントリーシートの様なもの)を提出するだけでは、なかなかインタビュー(面談)すらしてもらえません。
   よっぽど優れていなければ、人事に数秒目を通して落とされます。
   PyConでは人事の方としっかり話して名刺をゲットしたので、オンラインではなく直接メールして応募する予定です。
   15社くらい連絡先を入手したので就活にはものすごく役にたちました。

   .. figure:: /images/us/jobfair1.jpg
      :width: 300

      Job Fair参加企業のリスト


   .. figure:: /images/us/jobfair2.jpg
      :width: 400

      Job Fairブースの様子

   .. figure:: /images/us/jobfair3.jpg
      :width: 400

      Kenshoブース

   .. figure:: /images/us/jobfair4.jpg
      :width: 400

      Citadelブース

まとめ
======
第3回のレポートは以上です。
Guido氏がBDFLを引退してからはじめてのPyConということもあり、Python Steering Councilについてのキーノートは興味深いものでした。
そして、今後もPythonは継続的に健全に発展しそうな雰囲気が感じられ安心しました。

次回レポート(最終回)では3日目後半として私が発表したポスターセッション、PSFのコミュニティレポート、クロージングや開発Sprintなどについてお伝えします。
