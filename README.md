# 日々の学び  
  
# 2023/09/21  
開発工程の資料を読み終わった  
週間業務開発システムの要件定義書の最初だけ作成  
作業計画の型を作った  
作業計画の型に週間業務報告の内容を書いた  
自分の効率の良い覚え方や勉強の仕方に対してしっかりと向き合う
  
  仕事  
他人PG読解が終わらなかった。悔しい  
指摘内容を修正する場合は指摘内容に対しての修正だけをするべきで他の部分はいじらない  
日本語を理解し、うまく使わないと伝わらない人たちが多いしうまく使うことをもとめられることが多い
渡すと代入するは違う  
引数は入力側で戻り値は出力側  
引数を材料、入力（例えば大根）。関数、メソッドを処理（大根をおろす）、戻り値を結果、出力（大根おろし）と覚えると覚えやすかった。

# 2023/09/19
エクリプスのインストール  
エクリプスの使い方を少し理解、操作  
LINUXの概要を学んだ  
3種類ある（ディストリビューション）  
（課金）RHEL  
Ubuntu  
centOS  
開発工程についての資料を半分読んだ


# 2023/09/１６  
エクセルの実装課題4時間17分かかった  


# 2023/09/11  
仕事  
XAMPPの設定  
アプリの機能確認  
  
プライベート  
エクセルの勉強  
時間の計算問題  
SUMIF関数  
指定され検索条件に一致するセルの値を合計する  
SUMIF(範囲、検索条件、合計範囲)  
COUNTIF関数  
指定された範囲に含まれるセルのうち、検索条件に一致するセルの個数を返す  
COUNTIF(範囲、検索条件)  


# 2023/09/07  
仕事  
テスト観点の作成  
テストケースの作成  
納期は要件定義等で決めたことが守られていればOK  
リセットボタンの修正  
片道をクリックしたときに倍になっていってしまうことを修正  
プライベート  
NOW関数  
現在の日付と時刻を返す  
=NOW()  
TODAY関数  
現在の日付を返す  
=TODAY()  
YEAR関数  
日付に対応する年を返す戻り値は1900~9999の範囲の整数  
=YEAR（日付）
DATE関数  
指定された値に対応する日付を返す  
=DATE(年、月、日)  
TIME関数  
指定された値に対応する時刻を返す  
=TIME(時、分、秒)  



# 2023/09/06  
仕事  
アロー関数を積極的に使うようにした  
リセットボタンを作り、リセットの処理を書いた  
inputタグへinnerTextでかえしていたのをvalueで変更  
小数点の対応、Math.floorを使った  

プライベート  
エクセルの勉強  
MIN関数の勉強  
ショートカットキーエクセル  
絶対参照(F4)
COUNT関数  
=COUNT(範囲)  
範囲内で数値データが入力されているセルの個数を返す  
COUNTA関数  
=COUNTA(範囲)  
範囲内でデータが入力されているセルの個数(数字も文字も含む)を調べることができる  
INT関数  
=INT(数値)  
数値を超えない最大の整数を返す  
正の数では小数以下切り捨てと同じ
RANK関数  
=RANK(数値、範囲、順序)  
範囲内で数値が何番目に位置するかを返す  
数値　範囲内での順位（位置）を調べる数値を指定する  
範囲　調べる範囲を指定する  
順序　上位の基準を指定する  
0か省力すると数値が大きい方が上位  
１を指定すると小さい方が上位  
PHONETIC関数  
=PHONETIC(範囲)  
ふりがなの文字列を取り出す  
MOD関数  
数値を除数で割ったときの余りを返す  
=MOD(数値、除数)  
数値は分子、除数は分母  
シリアル値（1900年1/1を１と基準にしている）


# 2023/09/05
8月にITの会社に就職  
これから毎日学んだこと、取り組んだことなどを記入していく  
仕事  
Google　MAPs APIで現在地を取得し、取得した現在地にマーカーを配置  
配置した場所を中心に距離を入力することで、現在地を中心点に円を描くようにした  
プライベート  
エクセルの勉強  
IF関数の勉強  
＝IF条件式,真値、偽値
ROUND関数  ROUNDUP  ROUNDDOWN  
絶対値$F$5のように$は２回入力する



# 2023/07/18  
  
## javaの勉強  
エラーが発生。バージョン違いでうまくいかない？  
  
## オリジナルアプリのフレンド機能  
カリキュラムで流れを学んだ  
フレンド追加のために取り入れるもの  
TOPページに対戦を募集しているリンクを追加  
TOPページに対戦を募集するリンクを追加  
オリジナルアプリのREADME更新
### 対戦募集投稿ページの内容
対戦募集はフレンドのみか、誰でも見れるか、選べるようにする  
募集するゲームタイトル欄  
一言挨拶(募集画面に出る)  
募集開始ボタンを作る()
### 対戦募集詳細ページの内容  
対戦募集投稿ページの内容を見せる  
対戦を申し込むボタンを作る  
募集した本人は募集削除もできるようにする  
### 個人の詳細ページに追加するもの  
他ユーザー、フレンド申請するボタン  
ユーザー、フレンド申請を受け付けないように設定できる  

# 2023/07/15  
  
## オリジナルアプリのフレンド機能  
カリキュラムにてフレンド機能の仕組みを学んだ
class_nameというオプションで１つのモデルを便宜的に２つの別のモデルとして参照できるようにできる  
sourceは参照元のモデルを指すオプションのこと

## javaの勉強  
### アノテーション  
注釈という意味、クラスやメソッドに特別な意味を持たせるための機能  
  
### @controller  
そのクラスがコントローラーであることをSpringに伝えるためのアノテーション  
Springでは、クラス定義の直前に@Controllerと記述することで、クラスがコントローラーとして扱われるようになる。  
  
### @GetMapping  
ブラウザで入力されたURLと、実行されるメソッドを紐づけるためのアノテーション。 
railsのルーティングと同じ機能  
メソッドの前に、@GetMapping("/hello")というアノテーションをつけることで、  
URLにアプリのルートパス/helloと入力された場合、そのメソッドが実行されるようになる。  
  
### @ResponseBody  
ブラウザからリクエストに対して、直接HTMLを返す際に利用するアノテーション  
  
  変数を呼び出す時が少し特殊であると思った。  
  




# 2023/07/12
## javaの勉強
変数  
演算子  
配列とリスト  
条件分岐  
繰り返し処理  
就活対応のためオリジナルアプリはできなかった。フレンド機能の追加をしていく
  
# 2023/07/10  
## progateにてjavaを学習開始  
System.out.printLn("hello");  
出力の時はこのように記載する。  
  
## solidityについて調べた  
どうやらベースはjavascriptやCが近いようだった。  
よってjavascriptの理解は深めていく必要があると思った。

## paizaでスキルチェック勉強
Dランク  
D226:伸びる身長  正解  

# 2023/07/05
paizaでスキルチェック勉強
Dランク  
D233:3人の経験値  正解  
Cランク  
C115:渋滞の距離  不正解  
システムがよくわからない。何が違うのかわからなかった。


# 2023/07/04
paizaでスキルチェック勉強
Dランク
D214:身長差 不正解  ルールがよくわからなかったがわかったら正解。  
D170:校庭マラソン  正解  　
D189:何周年の確認  正解  
D120:鉛筆の数  正解  
D038:試合の回数  正解  
自己紹介 Ruby編  正解  
Cランク  
C099:折り紙の貼り合わせ  不正解  わからなかった
