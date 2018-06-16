# Quick Biographer(β)

## はじめに
忙しい人の為のシンプルなtumblr向け1ページバイオグラフィー作成テンプレートです。  
用意された項目を埋めるだけで簡単にDJ自己紹介サイトが作れます。  
各種ソーシャルサービスへのリンクのほか、SoundCloud、Mixcloudの埋め込みプレイヤーも難しい操作なしで利用可能です。  
簡素でシンプルな作りなので、知識のある方は更にカスタマイズ可能。


## コンセプト

* 忙しい人の為のtumblr向け1ページバイオグラフィー作成テンプレート


## ターゲット

* アマチュアDJ・VJなど。
* 上記の内、バイオグラフィーページ作成に時間をかけられない・かけたくない人
* 上記の内、HTML/CSSの知識があまりない・全くない人

## 注意点

* **シンプル・スピードを求めて極めて簡素な作りです。装飾には向きません。**
* **Tumblrのブログとしての機能は完全にオミットしています。記事の投稿は表示されません。**
* **上記の理由の為、既にtumblrで記事を書いている方は新しいブログを作られることをおすすめします。**


## マニュアル

### 1.tumblrの登録・新規ブログの作成。
こちらは割愛します。以下URLを取得したところから。

### 2.テーマの適用
**外観を編集＞テーマの編集＞HTMLを編集。**   
index.htmlの中身を全てコピーし、元々書かれているHTMLに上書きします。  
以降基本的にここはいじらずに運用が可能です。

保存ボタンを押した後、左矢印で前の画面へ。

### 3.設定方法
順番は前後しますが、まず左画面最下部詳細設定より  
**「デフォルトのモバイルテーマを使用」** のチェックを外します。  
（以下ボタンを青→灰色へ変更することを全てこう呼称します）  
これをやらないとスマホ等で表示した時に情報が正しく表示されません。


### 各設定項目について

#### 外観オプション


|項目名          |説明          |
|:--------------|:------------|
| タイトル       |自身の名義。このページのタイトルと一番大きな見出しになります。| 
| 説明          |自己紹介文を書きます。HTMLによる装飾に対応しています。  | 

#### テーマオプション

|項目名          |説明          |
|:--------------|:------------|
| Photo1,2       |写真をアップロードします。デフォルトでは2枚までアーティスト写真等をアップロードできます。<br>大きな画面(横幅401px以上)では1辺400px、小さな画面(横幅400px以下)では350pxの正方形で表示されるので、それよりも大きなサイズの正方形大が推奨です。1辺が倍の800px確保できているのが推奨。| 
| Dark Color    | ページ内、暗い部分の背景色。<br>文字色は白・リンク色が青系の色になっているので、それが見えるような色が良いと思います。  | 
| Muliple Photos | 2枚目の写真をアップする場合はチェックを入れる。<br>ここにチェックを入れないと二枚目が表示されません。| 
| Mail Address<br>Blog<br>Twitter<br>SoundCloud<br>Mixcloud<br>Instagram<br>YouTube  |それぞれのサービスアイコンを表示するかどうか。<br>この後の項目にアドレス・IDを入力してもここにチェックが入ってないと表示されないので注意。| 
|Soundcloud Embed<br>Mixcloud Embed| それぞれ埋め込みプレーヤーを表示するかどうか。 | 
|Credit       | クレジット・所属などを記入します。    | 
| mailto<br>Blog URL<br>[hoge]username<br>（[hoge]には各種サービス名)       |各コンテンツのUsername(メールはメールアドレス)を入力。<br>メールアドレス公開に対するスパム対策はご自身でお願い致します。| 
| Heading       | 出演情報やリリース情報などにつけるタイトル・見出し    | 
| info1-3       | デフォルトでは3つまで、出演情報など    | 
| info1-3 URL       | 上記に対応する詳細URL等。#を指定しておくことでリンクを無効にできます（見た目は現状変わりません）    | 
|Notes For Information|出演情報項目に対する備考。|
|SoundCloud ID|埋め込みプレイヤー用。ユーザーネームではなく、固有のID(数字)が必要であることに注意。<br>[What is My SoundCloud User ID](https://helgesverre.com/soundcloud/)等のサービスでの取得が簡単です。|
|Google Analytics ID|トラッキングを有効にするためにはここにトラッキングIDを入れる。|


### 4.ページの追加について

記事を書いてブログのようには利用できませんが、固定ページを作ってそのリンクをヘッダー部に表示できます。
(モバイル向けサイズの場合は3本線メニューボタンをクリックすると項目が出る)

過去の出演履歴や、イベント出演時の機材構成データなどを書いておくと便利かもしれません。

また、「リダイレクト」を選ぶことで外部サイトへのリンクも貼ることが可能です。

こちらの機能を使う場合には、「このページへのリンクを表示」へのチェックを忘れずに。


### 参考 
[デモページ1](https://qb-demo1.tumblr.com)  
[デモページ2](https://qb-demo2.tumblr.com)

### 確認している不具合・仕様
18/6/15 
* プレビューにて、スライドショーで表示される画像が一枚多い（文字列が表示されている）  
→tumblrのプレビュー機能が干渉していると思われる、実際のURLでは正常に表示される。

* 初期値にてチェックボックスの表示と実際が対応していない(オフにしているSNSアイコンが表示されている、など)  
→一度チェックを入れて外したりすると適切な表示になる（tumblr側の何らかの仕様か？）

18/6/16
*  ~~リンクが機能しない不具合~~  
→解決済み


---

ご連絡は TwitterID [@yuriz0](https://twitter.com/yuriz0) まで。  
(HTML/CSS/JSのカスタマイズに関しては非サポート)
