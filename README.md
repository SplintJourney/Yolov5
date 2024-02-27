# Yolov5
執筆中

結果も表示したい

**システム概要**

20人の学生の顔から学籍番号を自動で識別するシステム

一人の学生の顔の画像：100枚

用意した画像：2000枚


**完成状態**

<img width="160" alt="image" src="https://github.com/sss-blisp/Yolov5/assets/139861013/66cd675c-8c7c-430f-b759-43e59a2da2b6">




**背景**

・授業の出席パスワードは、本学のポータルサイトにて手動で入力する必要がある。

・本学の学生を対象にした学内アンケートによると、回答者150人のうち、80%が学生が毎回出席登録のために、ポータルサイトにログインすることは面倒であると回答した。

・そのため、画像による物体検出技術を活用し、AIによる顔認証システムを開発を目指す。




**構成図**

 <img width="942" alt="image" src="https://github.com/SplintJourney/AWS/assets/139861013/366fb3a7-c263-4b31-bc58-b785dfcb5d41">



**使ったサービス、言語**

YOLOv5

Python3.8

実行環境　Google Colaboratory

VOTT

Roboflow

**開発期間**

３ヶ月


**開発時期と人数**

大学2年の冬から3年の夏までの約６ヶ月

プロメンに所属するメンバー3人


**担当箇所**

データのアノテーション

モデルの作成


**工夫点**

yolov5で提供されているデータセットを使用した転移学習


**課題**

・テストデータでの精度は　%だった

・簡易的にyolov5の推測ラベルをスプレッドシートに出力できたが、実環境での駆動はできなかった

・これは、時間的制約やポータルサイトでの認証が必要であったためである。
