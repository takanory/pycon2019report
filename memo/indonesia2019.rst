======================
 PyCon Indonesia 2019
======================


Opening
=======

Opening Speech
--------------
* Dr. Trianggoro Wiradian

PyCon Organuzer
---------------
* DoniがChairperson
* メンバーの紹介
* Telegramに入ってる人いる?→Farahがなんか有名っぽい??
* SuraとBaya→SuraがSharkでBayaがワニ
* PyCon Indonesiaの歴史。2017が最初だよ。2018はジャカルタ
* スポンサー紹介。Patronの紹介(突然のインドネシア語
* 全体のイベント紹介
* ハッシュタグは #pyconid2019

alterraのスポンサートーク
-------------------------
* インドネシア語なのでわからない...

Keynote1
========
* 発表はインドネシア語だけどスライドは英語

2nd Keynote
===========
* How Python Changed My Life
* ABout me
  * Coding since 2000
  * Python since 2010
  * @femmerling
  * Gojekの開発者
  * LEGOとか組み立てるのが好き
  * Python-IDには2013から参加
  * Python-ID JogjaのCo-Founder
  * 結婚して子どもが3人(拍手
* 暗黒時代
  * 1999でGeocitiesでHTMLページを書いたのが最初
  * VB6の本を読んでいた
  * 2002年に大学に入ってCの勉強を始めた
  * 学習のためのリソースが限られていた
* C言語の後
  * VB6でヴィジュアルプログラミングを始めた
  * Java知った→JavaとJSP
  * 初めてのWebプログラミング
  * 次にPHPを知った
* 楽しんだけど
  * PHPは最初のインタプリター言語
  * 動的型付け
  * JSP、.Netに比べてPCで軽く動く
  * Webにリファレンスがある
  * 大学で使っている人が多かった→質問できる
  * 軽いホスティングサーバーで動作する
* But
  * じぶんにインスパイアしない
  * IRCはとってもharsh
  * コーディング哲学がない
* しかし
  * PHPで卒業した
  * PHPで仕事した
* 明るい時代
  * Pythonを見つけた
* 物語
  * PHPとZENDで作っていた
  * app engineを見つけた
  * Pythonと出会った
* Pythonnは
  * とてもシンプル
  * 簡単に学べた
  * 行数が少なく作れる
  * さまざまなプログラミングのコンセプトを学んだ
  * テスト、セキュリティなどを学ぶモチベーションとなった
* 終わりじゃない
  * IRCのコミュニティはとてもあたたかい
  * 豊富な標準ライブラリ
  * チュートリアルがある
  * BDFLはとてもクールでinspiring
* Can I make it simpler?
* なにがかわったか?
  * Career jump
  * hackathonでprizeもらったり、大きいstartupを立ち上げたり
* I discovered the Zen of Python
* コーディングの外でPythonはなにを考えさせたか
  *
* Zen of Python
  * import this
* 勉強を続けてる
  * iOS, Androidの開発
  * 他の言語→lambdaは嫌い
  * DevOpsについてもっと学んでいる
  * スタートアップのたちあげかたについて学んでいる
* Guidoの言葉を引用
* コミュニティへの貢献
  * Python IDに参加
  * Slackとか
  * PyPIにアップロード、募金
* Keynote2人をあつめて質疑応答するの面白いな

Lunch
=====
* Josefとかと食べた。Josefは台湾でのLTがはじめてだったらしい
* 今回は発表者じゃなくて参加者

rest in peace REST, The rise of GrpahQL
=======================================
* speaker: Abhishek Mishra
* PyCon Indiaの人っぽい
* はじめてのPyCon Indonesia
* Abhishek
* REST
  * ステートナシのアーキテクチャースタイル
  * リソースをURIで取得
  * JSONを取得
  * GET/POST/PUT/DELETE
* RESTはリソースを返すので
  * 複数のエンドポイントがある
* BFF: Backend for Frontends
* RESTのよくないところ
  * Over/Under-fetching
  * エンドポイントがたくさん
  * Queryの複雑化(N+1)
  * 型がない
* 解決策
  * json:api, OData, FALCOR?, GraphQL
* サンドイッチの注文を例にRESTとGraphQLの違い(わかりやすい
  * RESTだと全部入りがきて不要な食材を抜く。GraphQLは注文時にほしい食材を言う
* GraphQL
  * Single request, endpoint
  * Specification
  * More contron over data
  * Relational queries
  * 強い型
* Schemaが一番大事だよ
* デモでGraphQLで問い合わせて返すところを見せた with Graphene
* GraphQLの経験が15年以上必要w

自分の発表
==========
* スライド: https://gitpitch.com/takanory/slides?p=20191123pyconid#/
* そこそこウケかな。ビール飲みたいのところは「インドネシアの人は飲まないの知ってるので、あなたはお茶を飲んで私はビールを飲みます」みたいなこと言ったらウケてた。
* Slack(80%)、JIRA(90%)を知らない人が多かった。こういうものだよって他の例を挙げたけど伝わったのかは不明
* 質疑応答
  * 誰が実行できるかの権限設定とかあるの?(聞き取れなくてIskandarが日本語でフォローしてくれた
    * Slackbotとしてはないので、例えばgadminコマンドだと私のGoogleアカウントの権限でなんでもできちゃう。それだと危険なので、gadminコマンドでは「SlackのAdminか」をプログラムでチェックしている
  * サーバーはどこで動かすのか?ローカルでもよいのか?    
    * Incoming WebhookもSlackbotも開発時に自分のPC上で開発して動かすことが可能。PyCon JPではWebサーバーを持っているのでそこでbotも動かしている。サーバーがない場合はEC2とかHerokuとかで動かすことになると思う。
  * ピザを注文するときに、ピザ→サイズは何?→サイズ→トッピングは?みたいなBotを作ることはできるか?
    * Slackbotのやりとりは状態を持っていないので、基本的には `$pizza サイズ 種類 住所` みたいなコマンドを作るしかない。Slack自体はボタンを表示して複数のやり取りをするような機能はあるので、その機能を使うと良さそう。Slack社が提供するライブラリだと対応しているかも?

Getting Fast Feedback While Coding Python
=========================================
* Hans Sebastian
* 7年アメリカで働いて最近3年はインドネシアで働いている
* QAエンジニア?
* バックエンドってなにがある?みたいにして、いろんな人から聞いてまとめていくスタイル
* 実際にテストコードを書いていく感じ

Lightning Talks
===============
* Visualizing High-Dimensional Data
  * PCAで2時苦にする→でもいまいち
  * t-SNE: 遅いらしい
  * UMAP
  * Fashion MNISTでやってみる→UMAPよさそう?
  * 名前とニュースの分類はそこまでうまくいかない
* BPS Surabayaからデータを抜き出す
  * 場所ごとの人口?
  * Foliumで可視化
* How easy programming to kids: Dima
  * Blocks Programmingがなぜいいのか?
  * AsomeBotってのがあるらしい
  * http://asomeit.com/product/
  * Demoでうまく表示できない。操作している画面をカメラで撮って写すという荒技ww
* Python is all You need for Speech Recognition
  * librosa, Kera, TensorFlow, PyTorch
  * https://librosa.github.io/librosa/
  * インドネシア語のデータセットもあるよとのこと
* pandas
  * pandasの基本的な機能の紹介
  * 他の可視化ライブラリと連携できるよ
  * いろんなファイル形式を読み書きできるよ
* 5 minutes style transfer
  * input image + style image = generated image
  * transfer learning: VGG
  * 時間切れで途中で終わった
* Smart Ecosystem with Mozilla IoT: Rizky
  * Alexaとかあるけど音声盗んでるよね的な
  * iot.mozilla.org
* Python dan Hardware
* Call and Responceみたいなの気になる

Closing
=======
* Doni
* 500+
* 2年前は学生が80%だったけど、60%になった
* Male 80%
* 85 Speakers Submission
* 2020の場所はBandungが人気らしい
* bit.ly/pyconid2019→インドネシア語だったから読めないww
* なんかdoniに渡してた

Party
=====
* おしゃれな場所
* ゴルフ場のレストランだけど、外なので気持ちいい
* 2種類のスープの鍋
* バンド演奏していたら女性オーガナイザーが一緒に歌っていた。PyConの伝統?
* 日本で働きたい学生とかもいた。
* アニメの話をふられても、最近アニメとか見てないんですよね...ごめんね
