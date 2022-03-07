# 職務経歴書

## 基本情報

| key | value |
| :---: | :---: |
| Name | kaerururu |
| Kaggle | https://www.kaggle.com/kaerunantoka | 
| Blog | https://kaeru-nantoka.hatenablog.com |
| GitHub | https://github.com/osuossu8 |
| Qiita | https://qiita.com/kaeru_nantoka |
| Twitter | https://twitter.com/kaeru_nantoka |
| Slide | https://www.slideshare.net/yuyaosujo |

---

## 概要

エンジニアとして4年弱の実務経験があります。
はじめの1年は開発 (C#) とWEBディレクターとして金融機関向けのクロスプラットフォームアプリ開発に携わりました。

その後 Kaggle で実績を積み、前職の Stockmark 株式会社に入社。
1年と数ヶ月、機械学習エンジニアとして BERT などの言語モデルの基礎技術検証や 法人向けサービスの機械学習バッチの開発を担当しました。

そして、toC 向けのサービスに携わりたい想いから現職の DMM.com に入社。
現在までの 1年半、機械学習エンジニアとして担当サービスの検索改善タスクに携わりました。施策の提案から実装、運用まで取り組んでいます。

---
## スキル

- 実務で使用したことのあるもののみ載せています。

### プログラミング言語

- Python

- Linux

    - Centos7, ubuntu1804 

- SQL

    - MySQL, Amazon RDS
    - DynamoDB

### フレームワーク

- Apache Spark

    - PySpark, Scala Spark

- PyTorch

    - 実務使用経験 1年
    - Kaggle での使用

- Django
    
    - 実務経験は 1ヶ月半程度
    - 個人開発あり

- Flask

### ツール

- AWS

    - Lambda
    - EC2
    - Batch
    - RDS
    - S3
    - DynamoDB

- Docker

- GitHub

- Sequel Pro

- Slack

- Trello

- esa

- Confluence

- tekton

---
## 強み

- 巨大なユーザー数を抱える WEB 企業にて、大容量データを扱った経験
  - テキストデータ、トランザクションデータ

- Apache Spark を用いた分散処理の実装・運用経験

- 実務課題の洗い出し、仮説の構築、施策の提案、機械学習・統計的処理を用いたアルゴリズムの構築・運用の経験

- Kaggle 仕込みの高速な PDCA 回す力

- 日本語 NLP の実務利用経験
  - 類似資料検索エンジンの作成

---
## 職務経歴

### 2020.8 ~ : 合同会社 DMM.com

職務: 機械学習エンジニア
勤続期間: 1年半~

[2021.2~2022.2] 検索改善施策

  - 内容
    - 公開情報でないので詳しくは書けないですが、ユーザーごとに合った検索改善を実施しています。
    - 施策の提案, POC, バッチ実装, 施策リリースまで携わっています。

[2020.8~2021.2] [ML を用いたリスト改善](https://inside.dmm.com/entry/2021/12/30/search_machinelearning)

  - ツール
    - Spark (scala), AWS (SQS, Lambda, S3), Pandas

  - 内容
    - POC からバッチ実装, 効果検証までやりました。

---

### 2019.4 ~ : [Stockmark 株式会社](https://stockmark.co.jp/)

職務: 機械学習エンジニア
勤続期間: 1年 

#### [2019.10~] [パワーポイントにスライド一枚単位でラベル付けをする機械学習バッチ作成](https://stockmark.co.jp/news/2020/01/20/3267/)

  - 使用ツール
    - PyTorch, AWS (RDS, Lambda, Batch), Xml

  - 使用手法
    - Tf-idf, fastText, BERT

  - 内容
    - パワーポイントから xml ベースのテキストを抽出し DB 保存
    - DB からスライドに紐づくテキストを抽出、特徴量作成、学習、AWS S3 に学習モデルの upload
    - S3 から学習モデルの DL, 予測対象スライドのテキストを DB から抽出、バッチ内で予測し予測結果を DB に格納

#### 類似スライドレコメンドエンジンの作成

  - 使用ツール
    - PyTroch

  - 使用手法
    - ResNet50

#### [2019.7~8] [法人向けニュースアプリケーションのユーザーレコメンド機能開発](https://www.slideshare.net/yuyaosujo/mlpp-4-amp-mlloft-6)

  - 使用ツール
    - Django 

  - 使用手法  
    - fastText, K-means クラスタリング

  - 内容
    - 読んだ記事ベースでのユーザーベクトル作成
    - 検索キーワードと cos類似度を計算しユーザーランキング作成
    - Django Web API から Rails のサーバーにランキング結果を渡す

#### [2019.7] スクレイピング記事の有料無料判定バッチ作成

  - 使用技術 : Docker, Flask, EC2
  
  - 使用手法 : LinearRegression


#### [2019.5~6] 企業名抽出関連

  - 使用手法
    - fastText, BERT, Google 翻訳 API

  - 内容
    - ニュース記事から企業名を抽出し、社内の企業名リストを更新するアルゴリズムの開発

    - 企業名の表記揺れ辞書の作成


#### [2019.4~5] 基礎技術検証

  - 内容
    - BERT を用いたニュース記事の fact/opinion 分類
    - fastText + ELMo モデルの精度 71% --> 90% の精度向上

---
### 2018.4 ~ 2019.3 : 受託開発会社 

職務 : エンジニア --> Web ディレクター

- C# を用いた金融機関向けのクロスプラットフォームアプリケーションの開発および関係会社や社内デザイナーのディレクション業務

---
### 2017.4 ~ 2018.3 : 金融機関

職務 : 営業

---
## 社外活動

- Kaggle 2018.8 ~
  
  - Kaggle Master
    - 金3(うち優勝1回)
    - 銀6
    - 銅3

  - 扱ったことのあるデータ
    - 画像, 音声, テキスト, テーブル

- [機械学習を応用した自主開発プロダクト（LINE-BOT）公開](https://line.me/R/ti/p/%40pcm4959u)
 
  - 使用技術

    -  Keras, Flask, LINE-API, Heroku
  
  - 友達登録数 51名 

---
 ## 登壇歴

 
 - 2019/09/20 MLPP #4 & ML@Loft #6 
    
    - [社内で XX に詳しい人を知りたい](https://www.slideshare.net/yuyaosujo/mlpp-4-amp-mlloft-6)

---
## この先やってみたいこと

・ これまで培った技術や経験を活かし、新しい価値を産み出したい

