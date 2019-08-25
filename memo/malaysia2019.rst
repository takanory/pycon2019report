=========================
 PyCon Malaysia レポート
=========================

概要
====
* https://pycon.my/

準備
====
* Younggunからメール届く
* Conferecne Kit持って行って(写真)
  * https://wiki.python.org/psf/PSF%20Conference%20Kit
* まぁやります
* 韓国→(イクバル)→日本→マレーシア→日本

Day 1
=====
* 受付してPSF Conference Kitの設置
* NoahがPSFブース担当らしい

Kyenote
-------
* AIとかの現在を紹介
* 機械学習はデータから学ぶ
* データは現在の石油
* 機械学習の基本的なアルゴリズムについて解説(SVM, KNN等
  * 結構詳細に解説している
* SVMは推薦システムに使われているよ
* 遺伝的アルゴリズム
* ベイジアン
  * スパムフィルター
* Neural Networkds
  * ANN
  * バックプロパゲーション
  * Deap Learning(ANNは深層学習のベースだよ)

自分の発表
----------

ランチ
------
* ランチおいしい
* ランチで隣に座った人が日本語少しできる人だった。
* 最近大阪と東京に旅行してきたらしい。
* すき家ばっかり行っていたらしい。(牛丼は食べられないので、魚のメニューを食べていたらしい)
* スポンサーブースまわった。AirAsiaなんだろうと思ったらWebとかアプリとか内省しているらしい

Designing and Building Serverless Machine Learning-powerd Applications with Python
----------------------------------------------------------------------------------
* Joshua Arvin Lat("Arvs")
* 内容
  * Concept
  * Design
  * Implementation
  * Management
* AWSつかって文字列認識
* そのあと翻訳

Supercharge Django for modern web development
---------------------------------------------
* Renyi Khor
* フォントが小さい...

Django and GraphQL
------------------
* Manuel Riel
* RESTの課題
  * ゆるい標準化
  * 関係のモデル化が難しい
  * Over/Under Fetching(全フィールドとってきちゃう
* GraphQLだとqueryなげかたら必要な情報が1回で返ってくるよ
* Core Concepts: 文法の紹介
  * Type, Query, Mutation, Arguments, Nesting
  * Subscription
    * Realtime Updates
  * Fragments
    * Vue.jsとDjangoを使った実装例
* Auth
  * Login, Permissions

Ready to say goodbye python 2.7
-------------------------------
* Noah Chen
* 2.7が2020でサポート切れるよって話は早々に終わり
* PSFの宣伝
* PyCon US, EuroPythonの紹介
* PyConAPACのWebサイトはまだないよ(笑
* Asiaにいろんなコミュニティあるよって話
* PEPの話からPython 2.7の話に戻ってきたww
  * PEP 372
  * PEP 404
  * PEP 20
* Python 4っていつくらい?みたいに聞いたらCarolが「not sure」ってその場で答えるのぜいたくだなw

Studi.MY: A case study of a Python outreach program
---------------------------------------------------
* Ai Sin Chan
* https://studi.my/
* Developerではないらしい
* XOXSOの人

Scaling AirAsia 3.0
-------------------
* Tevanraj Elengoe
* RubyConf MY 18のOrganizer
* AirAsiaはTravel technology company
* airlineと違ってホテル、ショッピングとかもある
* SuperApp
* Expediaとかと比べても規模でかいのか、すげー
* site  
  * 30k request/sec
  * 2k-4k containers per day for APIs
* AASET(AirAsia Software Engineering and Technology
  * 100++people
  * エンジニア、QA、DevOps
  * バンガロール、KL、シンガポール
* .NetからPythonに移行したらしい
  * オープンソースにしたかったらしい
* google app engine使っているのか
  * Kong: API Gateway(https://konghq.com/kong)
* Kubernetesに載せ替えようとしている
* SOAPからRestAPIにした
  * SOAPの手前にRESTを作って変換
* Multi-cloud company
  * AWS, GCP, Azure, Alibaba Cloud

Lightning Talks
---------------
* 時間で切っちゃえばいいのに
* CodeCollab
  * シンガポールの先生
  * https://codecollab.io/
* Rizky
  * PSF Fellowになったらしい
  * PRO GAMERらしい
  * なんかIOT
* Noah
  * https://pyconapac.org/
  * めっちゃ作りかけのWebサイトww
  * Noahが時間内にLT終わった!!!
* 入らなかったやつは明日に回すシステムらしい

Closing
-------
* さくっと

Dinner
------
* 豪華なホテルのビュッフェ
* やはりビールはなし
* そのあとNoahとビールへ

Day 2
=====

Keynote
-------
* タイトル: Practical Python and Jupyter for Data Science and Beyond
* スライド: https://speakerdeck.com/willingc/practical-python-and-jupyter-for-data-science-and-more
* Carol Willing
* Who am I
  * Jupyter, nteractを作っている
* Practical Data Science
  * 現実世界でのデータサイエンス
* Python Ecosystem
* Python
  * Growth, Governance, Python 3.8, Farewell to Python 2
  * Growth: いろんな分野で使われているよ。web、科学、devops, data science, system, test, educationなど
    * Guido: In reality, programming languages are how programmer..
  * Governance: Post-BDFL
    * PEP 8016
    * Steering Councilができました
    * Python 3.8がリリースされたら次のCouncilになる?
    * PEP 13
  * Python 3.8
    * Python 3.8のbetaを試してね
    * ライブラリとか作ってたらTravis CIでテストしてみて
    * 重要な変更
      * 位置のみ引数
      * セイウチ演算子
      * f-stringの=
      * PEP 587: Python initialization Configuration
      * PEP 574: pickle
  * Farewell Python 2.8
    * pythonclock.org, python3statement.org
    * InstagramもPython 3に移行したよ
* 2014年頃IPython Notebookを教えていた
  * 現在github上に500万以上のnotebookがある
* Knowledge
  * Prepare
    * Try it in the browser(mybinder.org)
  * Install Python: OS, conda, python.org
  * Install Libs: conda, pip
    * venvの作り方, condaでの手順
    * JupyterLab
    * nteract: ReactJS fontend
    * VSCode, PyCharmはnotebookをサポートしているのでおすすめ
  * Exploration
    * Tutorialをやろう: Pandas, Matplotlib
    * Jupyter NotebookのOnline bookあるよ
    * Community
      * User groups, Meetups, PyLadies, Capentries
  * Prototypings
  * Production
    * Papermill, Scrapbook, Bookstore, Commuter
* Community
  * guidoのお言葉
* Join the PSF
