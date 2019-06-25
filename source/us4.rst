==============================
 US PyCon 2019レポート: 第4回
==============================

.. contents:: 目次
   :local:

レポートの最終回は、カンファレンス3日目で私が発表したポスターセッションやPSFによるコミュニティのレポート、開発スプリントなどの様子をお伝えします。

ポスターセッション
==================
カンファレンス3日目の午後(10:00から13:00)はポスターセッションとJob Fairのみが開催され、Talkなどはありません。
今回私がPyCon 2019に参加した理由は、このポスターセッションに採択されたためです。
ワンチャンスあるかなとは思っていましたが、まさか本当に採択されるとは思っていなかったので、連絡が来たときには非常に驚きました(Talkも出していましたが、こちらは不採用でした)。

ポスターセッションになじみのない方もいると思うので簡単に説明すると、広い会場にボードが用意してあり、発表者はそこにポスターを掲示します。
参加者は複数あるポスターを練り歩いて掲示されている内容を見たり、ディスカッションをします。
通常のTalk発表と異なり、ディスカッションが中心となることが特徴だと思います。

.. figure:: /images/us/poster1.jpg
   :width: 400

   朝一でポスター掲示をしたところ

PyCon 2019のポスターセッションでは全部で30の発表がありました。
私は23番ブースで「Python Boot Camp: Introduction of efforts to spread Python all over Japan」というタイトルで、一般社団法人PyCon JPの活動である `Python Boot Camp <https://www.pycon.jp/support/bootcamp.html>`_ についての成果や工夫などについて発表しました。

.. figure:: /images/us/poster2.jpg
   :width: 300

   ポスターセッションのリスト

ポスターの準備
--------------
実際の発表の前に、ポスターの準備について説明します。
ポスターのサイズは横4フィート(約1.2メートル)x縦3フィート(約0.9メートル)との連絡がありました。
これは日本でポスターを作る場合にはA0くらいで大丈夫そうです。

私はポスター発表などしたことがないし、まずはどんな内容のポスターにするかのアイデア出しをしないといけません。
Google Docsに「こういうネタがよさそうかな」と私がざっと書いたものをベースに、以下のメンバーとオンラインでディスカッションしてアイデア出しをしました。

* 寺田 学(`@terapyon <https://twitter.com/terapyon>`_): Python Boot Camp講師、US現地での発表も手伝ってもらった
* 片寄 里菜(`@selina787b <https://twitter.com/selina787b/>`__): Python Boot Camp現地スタッフ、US現地での発表も手伝ってもらった
* 筒井 隆次(`@ryu22e <https://twitter.com/ryu22e>`_): Python Boot Campコアスタッフ
* 小林 智博(`@kobatomo3H <https://twitter.com/kobatomo3H>`_): Python Boot Campコアスタッフ
* 清水川 貴之(`@shimizukawa <https://twitter.com/shiizukawa>`_): Python Boot Camp講師

.. figure:: /images/us/poster-idea.png
   :width: 400

   ポスターのアイデア出し議事録

次にポスターをまずは日本語でざっくり作ります。
ポスターの原稿作成にはMacのKeynoteを使用しました。
ネットで調べた情報ですが、スライドのサイズを3370pts×2383ptsという巨大なものにします。そしてフォントサイズはタイトルが80pt、セクションタイトルが44pt、通常のテキストは26ptなどとしました。
そしてざっくり作成したKeynoteからPDFを生成し、Dropboxで共有して関係者にレビューしてもらいました。

* 参考: `A0ポスター用のKeynoteの設定 <http://jfujimo.to/memo/PosterPresentation/>`_

.. figure:: /images/us/poster-dropbox.png
   :width: 400

   Dropboxでのレビュー

ひととおりネタがまとまったら次は英文の作成です。
これは日本語と英語を書いたGoogle Docsを作成し、ドキュメントにコメントをもらう形で英文を修正していきました。
この段階ですでにポスター作成のスケジュールがギリギリになってきており、社内の英語ができるメンバーに協力を仰いだところ、 `James <https://twitter.com/jamesvandyne>`_ がたくさん添削やよりよい英文の提案をしてくれました。本当に助かりました。

.. figure:: /images/us/poster-text.png
   :width: 400

   ポスターのテキストの添削

英文ができあがったところで、英語バージョンのポスターを作成します。
これはKeynoteでもう1スライド作って埋めていくだけなので、ある意味単純作業です。
英語バージョンのポスターができたらいよいよ印刷です。
ポスターの印刷は筒井さんに教えてもらった `グラフィック <https://www.graphic.jp/>`_ を使用しました。
こちらの業者は、ポスター印刷時にInDesign上でデータが問題ないかのチェックができるツールを提供しており、印刷イメージが確認できてとても便利でした。
Adobe CCに登録して初めてInDesignをインストールし、Keynoteファイルを取り込んで見よう見まねでなんとか入稿用のデータを作成しました。
PyCon出発時に手元にポスターがないとだめなので、かなりの個人炎上案件でした。
最終的に、4月23日(火)の夜中1時に無事入稿し、ゴールデンウィーク初日の4月27日(土)に無事ポスターが届きました(出発は5月1日)。

.. figure:: /images/us/poster3.jpg
   :width: 300

   ポスターが間に合った!

この3角形のパッケージは潰れにくそうなので、そのままこの段ボールで飛行機の手荷物であずけました。
クリーブランドの空港で、バッキバキになったポスターが出てくるんじゃないかとドキドキしていましたが、荷物のレーン上に無事なポスターを見つけて非常にホッとしました。

.. figure:: /images/us/poster4.jpg
   :width: 300

   ポスターが無事アメリカに到着した!!

ポスターセッション当日
----------------------
さて、話をPyConに戻してポスターセッション当日です。
10時となってポスターセッションが開始になりました。
といっても明確ななにかがあるわけではありません。

初めての海外でのポスターセッションでの発表は私一人では非常に心細かったのですが、アイデア出しなどにも参加してた寺田さん、Selinaさんが手伝ってくれたのでとても助かりました。
揃いのPython Boot Camp Tシャツがあることも、チームっぽい感じがしてとてもよかったと思っています。
ぽつぽつとポスターを見ていく人が現れ、いろいろな方にPython Boot Campについて説明したり、質問に答えたりしました。

.. figure:: /images/us/poster5.jpg
   :width: 400

   参加者に説明しているところ(奥が筆者)

.. figure:: /images/us/poster7.jpg
   :width: 400

   参加者とディスカッションする筆者

.. figure:: /images/us/poster6.jpg
   :width: 400

   ポスターに興味を持って撮影する参加者

よく質問された内容は以下のようなものでした。

* 日本では何カ所くらいで開催したのか?

  * 32回開催して、29の都道府県で開催済みです。47都道府県を制覇しようとしています
* どんな内容でどのくらいの時間で実施しているの?

  * 4時間でPythonの入門からWebスクレイピングの体験までをサポートしています
* 運営資金はどうしているの?

  * 年に一回PyCon JPイベントを開催しているので、そこのスポンサー収入を一部残して資金として使用しています
* 何人くらいが参加しているの?

  * 1回について20人前後が参加しています。のべ人数だと800人以上がこのイベントに関わってきました

ポスター発表をしていると、本当にさまざまな国からPyConに参加している人が来てくれて、とても面白かったです。
特にアフリカやアジアなどから参加している、(おそらく)まだそれほどPythonが自国で広まっていない人は、この活動に深く興味を持っているようでした。
もしかしたら数年後にどこかの国で同じような活動が立ち上がるかも知れません。
韓国からの参加者は「 https://pycamp.pycon.jp/ のテキストを韓国語に翻訳したい」と言っていました。

他にも、過去にPyCon JPなどで会った方との再会や、はじめて出会う人がいたこともとてもよかったです。以下のような人たちと出会うことができました。

* 彼女が日本人で、日本語を少ししゃべれる方
* 娘が日本で空手を習っているという方
* スペインからの参加者で、PyCon JP 2018のキーノートのManuel Kaufmann(`@reydelhumo <https://twitter.com/reydelhumo>`_)と友達の方
* 日本人の方で、現在はアメリカの金融系の会社に勤めている方(毎年Job Fairで参加しているそうです)
* Pyshon Software FoundationのChair PersonのNaomi Ceder(`@NaomiCeder <https://twitter.com/NaomiCeder>`_)氏
* MailmanのCore Developerで筑波在住のStephen Turnbull(`@yasegumi <https://twitter.com/yasegumi>`_)氏。3年前くらいはPyCon JPにも来てくれていました。

また、PyCon night Tokyo/Osakaで2016年に発表してくれた、DisneyのPaul Hildebrandt (`@paulhildebrandt <https://twitter.com/paulhildebrandt>`_)氏とも再会できました。
このときはGoogleの `@ymotongpoo <https://twitter./com/ymotongpoo>`_ (彼はスポンサーとしてPyConに参加していました)も、一緒にPython Boot Campなどについての説明を手伝ってくれました。ありがとう。

* 参考: `PyCon JP Blog: PyCon night Tokyo/Osaka 2016.06 を開催しました <https://pyconjp.blogspot.com/2016/06/pycon-night-tokyoosaka-201606.html>`_  

.. figure:: /images/us/poster8.jpg
   :width: 400

   Paul Hildebrandt氏(右がymotongpoo)

そして、私のポスターセッションに、なんとPython作者のGuido van Rossum氏も来てくれました!!!
Guido氏はポスターを興味を持って見てくれて、筆者は「日本各地で開催していること、このイベントをきっかけに日本各地でコミュニティが立ち上がった」ということを説明しました。

.. figure:: /images/us/poster9.jpg
   :width: 400

   ポスターを眺めるGuido氏と筆者

Guido氏が「へー、いろんなコミュニティがあるんだねー」と言いながらポスター右下のコミュニティの地図を見たときに「UDONPy!!?ブワッハハハハハ!!!」とめちゃくちゃウケていました。
Guido氏は麺類が好きらしく、うどんも好きだそうです。
私は「 `UDONPy <https://udonpy.connpass.com/>`_ は香川県のPythonコミュニティで、Python Boot Campがきっかけで誕生したものですよ」と紹介しました。
Guido氏はスマートフォンでUDONPyのロゴを撮影していました。UDONPyの世界デビューも間近です。

.. figure:: /images/us/python-community-map.png
   :width: 400

   Python Boot Campがきっかけで生まれたコミュニティの地図

そして、ひととおり会話が終わったところでGuido氏から「一緒に写真撮る?」という申し出がありました。
これは筆者にとって、とてもうれしい提案でした。

今回USでのPyConに初参加することで、Guido氏を目にすることはあるだろうと思っていましたし、実際に会場内やPyLadiesオークションなどで何度か見かけました。
そしてGuido氏は当然有名人なので、いろんな人に声をかけられて2ショットでの写真撮影に快く応じていました。
ただ、私自身は「Guido氏はそこまで快く思っていないかも知れないし、声をかけてツーショットを撮るのはなにか違うな」と思っていました。そのため、自分から「写真を一緒に撮ってもらえますか?」のように声をかけることはしないと決めていました(遠くから盗撮や、PyLadiesオークションでは撮影しましたw)。

そう決めていた私に対して、Guido氏から「写真撮る?」と言われたとき、私は平静を装って「はい、ぜひ!」と言いましたが、心の中では超大きなガッツポーズをしていました。
さまざまな参加者だけでなく、Guido氏とも交流してこの写真が撮れたことで「PyConのポスターセッションでおれはやったな。完全にやってやったな。」と自らを褒め称えました。
   
.. figure:: /images/us/poster10.jpg
   :width: 400

   Guido氏とPython Boot Campチーム

なお、ポスターのデータは以下のURLで公開しています。
Python Boot Campの概要、目的、背景、工夫そして成果がまとまっています。
ぜひ見てみてください。

* https://www.dropbox.com/s/cgve0tcipoeqsge/pycon-poster-pythonbootcamp.pdf


Python Software Foundation Community Report and Community Service Awards
========================================================================
* ビデオ: https://www.youtube.com/watch?v=P4IfFLAX9hY

ここではEwa Jodlowska氏により、PSF(Python Software Foundation)の報告と、Community Service Awardsの表彰が行われました。

Python関連の様々なコミュニティが世界中にあり、いろいろな機会が提供されているという説明がありました。
そして https://python.org/psf/annual-report/2019/ に年次事業報告書が公開されているという説明がありました。
PSFはさまざまなコミュニティをサポートしているということ、また、PSFもサポートをお願いしてるという説明がありました。PSFをサポートするには以下の方法があります。

* https://pycon.us/pbf から寄付する方法
* PyCharmのライセンスを購入すると、その一部がPSFに寄付されること
  
次にPSFチームの紹介がありました。現在PSFチームとしては8名のメンバーがフルタイムで活動しているようです。最近PSFに入った人もいれば、20年間活動している方もいらっしゃるそうです。

.. figure:: /images/us/psf-team.jpg
   :width: 400

   PSFチーム

   
最後に `PSF Community Service Awards <https://www.python.org/community/awards/psf-awards/>`_ の表彰が行われました。
複数のコミュニティのオーガナイザーや、PyPIの移行作業を行った人、複数年PyConのプログラムメンバーを務めた方などが表彰されていました。

いろいろな人に支えられて、PSFを中心としたPythonコミュニティが拡がっていることを感じました。表彰されたのは以下の方々です。

* Mario Corchero: PyCon ES、PyLondinium、2018年のPyCon Charlas(スペイン語)トラックの主催者
* Chukwudi Nwachukwu: ナイジェリアのPythonコミュニティの拡大
* Alex Gaynor: 2015-22016のPSF Director。PyPIの移行などを行う
* Mariatta Wijaya: CPythonのコントリビューター。PyCascadesのCo-Chair
* Maricela Sánchez Miranda: 2019のPyCon Chalas ChairやPyCon Day Mexico、Django Girls Pueblaの主催
* John Roa: PyCon Colombiaの創始者であり主催者
* Stefan Behnel: Cythonとlxmlのメンテナー
* Eric Ma: 複数年のFinancial AidのCo-ChairやPyConプログラム委員会のメンバー

Final Remarks and Conference Close
==================================
* ビデオ: https://www.youtube.com/watch?v=ADutU_sFXXA

カンファレンスの最後はクロージングです。
Closing Dinnerの案内や次の日から行われる開発Spritの説明などが行われました。

そして、ここで昨夜行われたPyLadiesオークションの収益金について報告がありました。
毎年寄付金額が増えており、今年はなんと41,000ドルでした。すごい金額です!!

.. figure:: /images/us/auction-result.jpg
   :width: 400

   寄付金額は41,000ドル!(約450万円)

また、各地域のPyConの情報をまとめた https://pycon.org/ をリリースしたので、各地域PyConの主催者は情報を更新してほしいという案内がありました。
筆者も `リポジトリ <https://github.com/python-organizers/conferences>`_ のコミット権をもらったので、更新する予定です。

今回のPyConには約3,200名が参加したそうです。
参加者に対して、自分の近くのPythonコミュニティに参加したり、開催をサポートしたり、主催してほしいというコメントがありました。

次に2020, 2021のPyConのChairである、Emily Morehouse-Valcarcel(`@emilyemorehouse <https://twitter.com/emilyemorehouse>`_)氏が紹介されました。
開催地はピッツバーグで、以下の日程で開催されます。

* 2020年4月15日~23日
* 2021年5月12日~20日

最後に「Thanks」と大きく書かれたスライドを表示し、PyConを作ってきた人たちを会場全体で拍手で讃えました。
呼ばれた人は立ち上がって参加者からの感謝の拍手を受けます。
最初は各スタッフ、次いで、当日ボランティアなどが紹介されました。
筆者も「ポスタースピーカー」と言われたときに立ち上がって、拍手を受けてこのコミュニティの一員になったような気がしました。
そして最後に会場の全員に対して感謝を述べて「2020年にピッツバーグで会いましょう」と締めくくってカンファレンスは終了しました。

.. figure:: /images/us/pittsburgh.jpg
   :width: 400

   PyCon 2020、2021の開催地はピッツバーグ

Dinner Party
============
カンファレンス最終日の夜はDinner Partyがあります。
会場は `Great Lakes Science Center <http://greatscience.com/>`_ という科学館です。

.. figure:: /images/us/greatscience.jpg
   :width: 400

   Great Lakes Science Center

科学館の見学とかもできるので楽しみだったんですが、少し仮眠するつもりがパーティー終了1時間前くらいに目が覚めてしまい(起きれてよかった)、料理をひととおり食べて缶ビールを2缶飲むのがせいいっぱいでした。

.. figure:: /images/us/party.jpg
   :width: 400

   パーティーはすでに宴たけなわ

パーティー終了後は当然飲み足りなかったので、 `Noble Beast Beer <https://www.noblebeastbeer.com/>`_ に飲みに行きました。
クリーブランドのブルワリーは、どこもデカい建物の中にバーと醸造所が併設してあり、できたてが飲めてとてもよいなと思いました。
この店は、熟成用と思われる大きな樽があることが特徴的でした。

.. figure:: /images/us/noblebeast.jpg
   :width: 400

   Noble Beastのバカでかい樽

開発Sprint
==========
カンファレンスの次の日からは開発Sprintです。
開発Sprintは集まってチームごとに開発を進めるイベントで、US PyConでは5月6日から9日までの4日間開催されます。
コアな開発者が一堂に会するため、ここでさまざまな開発が一気に進みます。

さまざまな部屋でいろいろなチームが開発などをしており、毎日ボードに「どこで何をやっているか」が案内されていました。

.. figure:: /images/us/sprint-board.jpg
   :width: 200

   Sprintの案内ボード

筆者は1日しかSprintには参加しませんでしたが、自分の作業を進めたり、Packaging Summit(Pythonのパッケージングについてのミーティング)に参加してみたりしました。
このSummitは、内容が難しいことと私の英語力の問題もあり、全然ついていけませんでした。
Packaging Summitで議論された内容に興味のある方は、以下のツイートを参照してください。

* `ernest w. durbin iii on Twitter: "Topics for the @ThePyPA Packaging Summit at #PyCon2019 Sprints… " <https://twitter.com/EWDurbin/status/1125414881363148800>`_

次の日に移動するメンバーも多いので、Sprint 1日目の夜に日本メンバー全員でディナーに行きました。
ちょっといいお店でステーキが食べたい!!ということで、ホテルで紹介してもらった
`Blue Point Grille: Fine Dining Seafood <http://www.bluepointgrille.com/>`_ に行きました(かなりいいお店はドレスコード的に無理でした)。

.. figure:: /images/us/blue-point.jpg
   :width: 400

   Blue Point Grilleの店内
  
.. figure:: /images/us/steak.jpg
   :width: 400

   ステーキおいしかったけどイモが多い...
  
.. admonition:: コラム: 初めてのSprint

   * Masaki Kagesawa (影澤 正輝: `@Masakikage <https://twitter.com/Masakikage>`_)

   僕は今までOpen Sourceに貢献したことがなく、今回が初めての貢献でした。
   最初はFlaskのSprintに参加しようと思いましたが、"Good First Issue" タグが付いたIssueがほとんどなかったため、初心者歓迎で多くの人が使ってる **pip** チームのSprintに参加しました。
   私のメンターは自分と同い年で、インドの大学に通ってる学生であり、なんとpipのコアメンテナーです。世界中のみんなに使われてるpipのコアメンテナーが21歳ということにびっくりしました。

   初日はコードのリファクタリングをしてPull Requestを作成しました。
   次の日にmergeされていると思っていましたが、コミットメッセージがガイドと合っていないという指摘を受けました。git rebase後もう一度Pull Requestを更新し、mergeしてもらいました。

   * `Outdated cleanup by MKagesawa · Pull Request #6462 · pypa/pip <https://github.com/pypa/pip/pull/6462>`_

   その後「今後もpipに貢献をしたいならPull Requestをテストして欲しい」とメンターから言われました。言われてみれば、pipは80個以上のPull Requestがオープン状態でした。貢献者はたくさんいてコードを書いてくれるけど、メンテナーは人数少ないからなかなかPull Requestをテストしてマージする時間がないとのことです。

   自分でもコードを書くよりも、テストをしてmergeに貢献する方がインパクトあるなと思いました。今後は週末など時間があるときにオープンソース活動を継続していきたいと思います。

   .. figure:: /images/us/packaging-summit.jpg
      :width: 400

      Sprint中パッケージチームはミニカンファレンスを実施した

   .. figure:: /images/us/sprints.jpg
      :width: 400

      Sprint会場の様子
         
まとめ
======
以上でクリーブランドで開催されたPyCon 2019のレポートは終了です。
非常に刺激的であり、規模などに圧倒されつつも、楽しくビールがおいしい7日間でした。
日本からたくさんのメンバーが参加したこともあり、私が参加していないイベントの情報交換やこのレポートでもコラムを執筆してもらったりと、より幅広くPyConを知ることがでとてもよかったです。

.. figure:: /images/us/team-japan.jpg 
   :width: 400

   日本からの参加メンバーで集合写真

また、日本のPython mini Hack-a-thonで友達になったJasonが、いろいろな人とつなげたり、PyConの楽しみ方を教えてくれたのはとてもありがたかったです。
本当にありがとう。

.. figure:: /images/us/jason-family.jpg 
   :width: 400

   Jasonファミリー、ゆきちゃんとけいちゃん(約2ヶ月)

しかし、せっかくいろいろな人と知り合っても、一回だけだとすぐに忘れてしまいます。
来年もUS PyConに参加して、より深くグローバルなPythonコミュニティとの関係を築いていきたいなと強く思いました。
ピッツバーグにはどんなクラフトビールがあるのかなぁ?

.. figure:: /images/us/bridge.jpg 
   :width: 400

   クリーブランドのMain Avenue Bridge
