==========
 PyCon SG
==========

オープニング
============
* スポンサー紹介
* スピーカー一覧も紹介された

キーノート
==========
* AIについて知っているか最初に質問
* AI in Singapore
* R or Python?
  * Google trendでPythonは盛り上がって言ってる
  * MLでPythonを使う人が増えている
  * 昔のデータだけど1B行のデータを処理する話
* AI is here already!
  * よくあるAI/ML/DLの図
  * AI in mu daily life
    * OK Google... -> 誰かのスマートフォンが反応してた(ウケる
    * Google map, No spam, Cashlessでlunch, 映画鑑賞(Netflix等
* AI is not Magic
  * liner regressionとかニューロン、deep learningについて簡単に説明
  * エラーが最小になるようにする
  * DLでの顔認識。顔画像からベクター作って、それが同じかをチェックする
  * なんかいろんな言語がまざった分を出した→わけわからん
  * 音声認識は20msとかに区切ってそれぞれのベクトルを作る
  * 単語のありなしのベクターを作る話
* AI and Jobs
  * AIはJobじゃなくてTaskを置き換える
* AI Singapore
  * https://www.aisingapore.org/
  * 100のプロジェクト
  * 産業とAI Singaporeをつなげるってのをやっているっぽい
  * AI Singaporeでは人を募集しているっぽい?
  * いろんな教育プログラムを用意しているっぽい→無料らしい
  * なんか女性だけのAIのカンファレンスがあったっぽい
  * AIエンジニアを求めていて、データサイエンティストを求めていない→unit test、dockerとかを理解していてほしい
  * AI for Students(AI4S)(v2) 100,000人を5年で、コースは半年
  * AIは私たちをより人間らしくする!

Grequests
=========
* requests + gevents
* Python 2.7使っていたら2020で終了
* requess -> grequests

  * grequests は non-blocking
* go-httpbinを使ってテスト用サーバーをたてる
* 実際に動作させながら、並列で実行されているところを見せる
* grequests使っていてもpython 2.7だと遅い

  * 2.7だと送信がシリアルになる

