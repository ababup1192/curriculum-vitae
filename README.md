# 職務経歴書

## 基本情報

|key | value |
|:--|:-------|
|Name | 富山未来 (Mirai Tomiyama)|
|Github| [ababup1192](https://github.com/ababup1192) |
|Qiita| [ababup1192](https://qiita.com/ababup1192) |
|Scrapbox| [ababup1192](https://scrapbox.io/ababup1192/) |
|Twitter| [@ababupdownba](https://twitter.com/ababupdownba)|

## 経歴概要

- 大学では、Web教育サービス、教育そのものに興味を持ち、Scalaを用いたWeb開発を学び積極的にAOJ改善に努めている。
- 大学講義ではGit・GitHubを用いたPR形式での問題を解かせRuby・Sinatra、React等を用いてWeb開発のイロハを学生に教える。(教えることを通して自身が知識を使うだけでなく、相手に上手く伝達する術、教育の考え方を学ぶため。)
- Scala、Haskell、Elmなどの関数型・オブジェクト指向についての考え方を、Twitterやブログ等を通して発信し、より広い範囲で教えることに努めてきた。
- 今後はさらに小規模開発では学べない事柄を学び、職場でも指導ができる立場となり、先駆者としてのキャリアを積んでいきたい。

## スキル・強み

### 言語

|名前|年数|備考|
|:--|:--|:--|
|C| 5年|
|Java| 5年|Android開発で使用|
|Ruby| 5年|講義で学生に指導|
|Scala|8年|Web開発で使用|
|Haskell|６年|
|TypeScript| 5年|
|Elm| 3年|研究開発で使用|
|Go| 2ヶ月|研究開発で使用|


### OS

|名前|年数|備考|
|:---|:--|:--|
|Mac|6年||
|Linux|6年|CentOS, Ubuntu|
|Unix|10年|Solaris|

### 開発ツール・環境

|名前|年数|
|:--|:--|
|Vim|6年|
|IntelliJ|6年|
|Git・GitHub|6年|
|Docker|3年|
|Nginx|5年|
|AWS|3年|
|GCP|2ヶ月|
|アジャイル・スクラム|3年|

### フレームワーク・ライブラリ・ミドルウェア

|名前|年数|備考|
|:---|:--|:--|
|PlayFramework|6年|AOJ、Web開発等で使用|
|Spring Framework|2年|AOJバックエンドリプレースに使用|
|Sinatra|5年|講義で学生に指導|
|Akka|3年|AOJサブモジュールで使用|
|MySQL|6年|
|PostgreSQL|1年|
|MongoDB|2年|



## やってみたいこと

- これまで一人で作業することが多かったので、デザイナー・営業・経営様々な人の刺激を受けて知識を吸収したい
- 社内教育文化の発展に貢献したい
- 高負荷を考慮したスケール可能なサービス・マイクロサービスを学びたい
- 多くの職種の人を交えたDDDを実践していきたい
- Elmをサービスに導入していきたい
- 独自サービスやOSSの発信
- 新技術に対する書籍の執筆

## 職務経歴

### 2022年5月~: 株式会社HotSpring

[旅行サービス こころから](https://www.cocolocala.jp/)開発


### 2018年3月~2022年4月: [株式会社ビズリーチ(Visional)](https://www.bizreach.co.jp/)

#### HRMOS
採用管理システムの開発

#### HRMOS 新卒エディション
HRMOSの新卒エディションプロジェクト立ち上げ・開発

### 2014年4月~2018年2月: 会津大学院博士後期課程

#### 言語ネットワーク

複数の同じ意味を持つ言語を同期し続け、それぞれのエディタを備えたシステムを提供することで、テキスト・ビジュアル・音声など複数の種類の利点を享受できる。教育・ソフトウェア開発・芸術、幅広い分野で利用されることを想定している(例: デジタル・アナログ時計の言語ネットワーク、XML・JSON・YAML・ツリービューの言語ネットワーク、PlantUML・UMLビジュアルエディタの言語ネットワーク)

- 概念の定義、アーキテクチャの設計、言語ネットワークの構築
- Zipperアルゴリズムやインクリメンタルパーサを推奨することで計算量を減らすことに努めた
- プラットフォームや言語の選定にこだわった - 使用想定の幅が広い為 ブラウザで動かしたかった 生産効率を求めてパーサコンビネータやコレクション、GUIアーキテクチャが備わっているElmを選択した
- Elm, SVG, HTML, CSS, (旧システム: Scala.js)

#### Scalaクイズアプリ

Scalaの学習に特化したクイズアプリケーションの開発

- 設計、開発
- クイズ自動生成アルゴリズムの作成 - 公式ドキュメントやライブラリ情報をクローリングし、そこからクイズを自動生成しDBに格納するアルゴリズムを考案、開発した
- クイズ配信サーバの開発 - DBに格納されたクイズをAndroidクライアントに配信するためのサーバをPlayでREST APIを用いて配信
- Androidクライアント開発 - Scaloidを用いたScalaによるアプリケーション開発、マテリアルデザインを採用
- Scala, Scaloid, scala-scraper, Play, AWS, Docker

#### Aizu Online Judgeのバックエンドアーキテクチャのリプレース

Aizu Online Judge(AOJ)のバックエンドのレガシーコードをリプレース。

- アーキテクト・技術提案・指導・リーダー(5人体制)
- レガシーコード調査 - JSPを用いて開発されており、機能とデザインが分離が難しい状況であったため、REST APIによる機能の分離を提案
- ソースコード管理の徹底 - バージョン管理が行われていなかった、開発者のみがデプロイ可能となっていため、Git・GitBucketを用いた運用フローを徹底した
- 属人化の排除 - Dockerコンテナを用いて運用手法を単純化して、属人化を排除に努めた、SSL対応の自動化など
- 教育・レガシーコード改善の提案 - GitHubフロー・Spring Frameworkでの開発の流儀を資料にまとめ提供することで教育を徹底した
- Java, Spring Framework, Docker, Git, GitBucket

#### 医療電子カルテ データベースドライバ開発
電子カルテシステムにおけるRDB・NoSQL２つの機能を持ち合わせたデータベースドライバの開発。

- 設計・開発
- 複数人(5人規模)開発フローの提案 - Git・GitHubを利用した複数人の開発体制を厳守して、競合や開発の手が止まってしまうような問題を解決
- Scalaでの経験を用いてJava8でも関数型プログラミングを利用して、RDBとNoSQLが扱いやすい統一したインターフェースの開発

### 2012年4月~: 会津大学院博士前期過程

#### 家族見守りサービス

お子様やお年寄りの方の位置情報を把握し、簡易ランチャーにより有害なサイトへのアクセス等を制限し見守るAndroidアプリケーションの開発。

- 設計、開発、サーバ管理、運用・保守
- 位置情報の精度の改善 - 当時はGPSの位置情報取得の精度が良くなかった為、独自のアルゴリズムを組むことで対処をおこなった
- Scala, Java, Android, PlayFramwork

#### AOJサブモジュール開発

問題毎のBBSやカテゴリー、タグ機能の開発。

- 設計、開発、サーバ管理、運用・保守
- 最先端技術の選定 - 手続き型言語やオブジェクト指向言語単体では、思うように保守性・拡張性に優れたコードが書けず、当時では最先端だった関数型の特徴を取り入れたScalaやPlayFrameworkを積極的に採用して開発をした
- Scala, Play, Git

### 2007年4~: 会津大学コンピュータ理工学部

#### 研修医学習補助サービス

研修医の方が学ぶべき膨大な資料をカテゴライズし、検索可能にしたWebサービスの開発。

- プロジェクトマネージャ(8人体制)、要求仕様書、スケジュール管理、開発
- プロジェクトマネージャとして - チームメンバーが円滑にタスクをこなせるように管理し、期間内に無事納品
- 要求仕様を元にPHPとMySQLを利用し、資料や動画のサムネイルを生成し学習資料の一覧が閲覧しやすいページャを生成


## 執筆歴

- Architecture for Language Networks Systems
  - 言語ネットワークのアーキテクチャについての論文([WWWJ2018 Special Issue](http://www.springer.com/computer/database+management+%26+information+retrieval/journal/11280 ジャーナル)に投稿、結果待ち

- [Architecture for Hybrid Language Systems](http://ieeexplore.ieee.org/document/7876328/)
  -  言語ネットワークの前身、テキスト言語とビジュアル言語 2つの言語の同期のみのシステムだった

- [Modeling Tools for Social Coding](https://link.springer.com/chapter/10.1007/978-3-319-22689-7_31)
  - 言語ネットワークの前身、汎用的なシステムではなくモデリングツールとして開発をしていた

- [Scala.jsを全力でオススメする](https://qiita.com/ababup1192/items/7896d26d29fdb06d7243)
  - Scalaの豊富な機能がフロントエンドで使えることをまとめた
- [関数型言語Elmでテスト駆動開発(第1~4章)](https://qiita.com/ababup1192/items/d6ca1af6efcbac8d550f)
  - 関数型プログラミングがテスト駆動開発に向いていること、学習中のElmの表現力を知りたくて連載 t-wadaさんにもTwitterで取り上げていただいた
- [関数型ReactでビジュアルFizzBuzz](https://qiita.com/ababup1192/items/bf6d25845a4556a9e0ca)
  - Elmに移る前に、TypeScript+Reactの限界を確かめるために、Redux風のものをRx技術と組み合わせて簡易ライブラリを作成し、まとめた

### 登壇歴

- [Elm Tokyo Meetup 飛び入りLT](https://elm-tokyo.connpass.com/event/62355/)
  - 言語ネットワークについてのLT

## 自己PR

- オブジェクト指向と関数型を利用した保守性・拡張性を意識したコードを書くことができます
- 新しい物事を積極的に調査、取り組み、利点や使い方を伝えることが得意です
- 小さい案件でプロジェクトリーダを行う機会が多かったため、上流から下流、お客様との調整など、一通りこなせます
- 学生に物事を教える機会が多かったため、技術・状況・手順を細かく砕いて伝えることができます
- サーバやアプリケーションのトラブルの対応に慣れています
- インプットを一人で溜め込まず、定期的にTwitter、ブログ等で発信を心がけています
- OSは、Unix/Linux系が多かったため、ターミナルを使用してコマンドを実行することに慣れています
