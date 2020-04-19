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
| Work | https://line.me/R/ti/p/%40pcm4959u |
| Slide | https://www.slideshare.net/yuyaosujo |

---

## 概要

エンジニアとして2年の実務経験があります。
はじめの1年は開発 (C#) とWEBディレクターとして金融機関向けのクロスプラットフォームアプリ開発に携わりました。

その後、Kaggle での経験を買って頂き現職の Stockmark 株式会社に入社。
1年間、機械学習エンジニアとして BERT などの言語モデルの基礎技術検証や B向けサービスの機械学習バッチの開発を担当しています。

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

- PyTorch

    - 実務使用経験 1年
    - kaggle での使用

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

---
## 強み

- ビジネス要件に沿って機械学習の評価指標の検討・定義し、その精度向上までできる

- 機械学習モデルの学習 ~ プロダクション適用までできる

    - Django を用いた予測API の実装ができる
    - MySQL で DB からデータを取得、pandas や言語モデルで加工・特徴量抽出、機械学習モデルの学習、予測結果の DB 格納ができる

- Flask を用いた簡単な社内用解析ツールの作成など、機械学習技術を活用できる

- Kaggle 仕込みの高速な PDCA 回す力

---
## 職務経歴

### 2019.4 ~ : [Stockmark 株式会社](https://stockmark.co.jp/)

職務: 機械学習エンジニア

#### [2019.10~] [パワーポイントにスライド一枚単位でラベル付けをする機械学習バッチ作成](https://stockmark.co.jp/news/2020/01/20/3267/)

  - 使用技術
    - PyTorch, Tf-idf, BERT, fastText, AWS (RDS, Lambda, Batch), Xml

  - 内容
    - パワーポイントから xml ベースのテキストを抽出し DB 保存
    - DB からスライドに紐づくテキストを抽出、特徴量作成、学習、AWS S3 に学習モデルの upload
    - S3 から学習モデルの DL, 予測対象スライドのテキストを DB から抽出、バッチ内で予測し予測結果を DB に格納

#### 類似スライドレコメンドエンジンの作成

  - 使用技術
    - ResNet50

#### [2019.7~8] [B向けニュースアプリケーションのユーザーレコメンド機能開発](https://www.slideshare.net/yuyaosujo/mlpp-4-amp-mlloft-6)

  - 使用技術
    - Django, fastText, K-means クラスタリング

  - 内容
    - 読んだ記事ベースでのユーザーベクトル作成
    - 検索キーワードと cos類似度を計算しユーザーランキング作成
    - Django Web API から Rails のサーバーにランキング結果を渡す

#### [2019.7] スクレイピング記事の有料無料判定バッチ作成

  - 使用技術 : Docker, Flask, EC2, LinerRegression


#### [2019.5~6] 企業名抽出関連

  - 使用技術
    - BERT, Google 翻訳 API, fastText

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
    - 金2(うち優勝1回)
    - 銀1(solo)
    - 銅2(solo)

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

・ C 向けで多くのユーザーを抱えるプロダクトに携わって、ユーザーに直接価値を届けたい

