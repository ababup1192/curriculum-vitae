# 職務経歴書

## 基本情報

|key | value |
|:--|:-------|
|Name | 渡部未来 (Mirai Watanabe)|
|Github| [ababup1192](https://github.com/ababup1192) |
|Qiita| [ababup1192](https://qiita.com/ababup1192) 
|Twitter| @ababupdownba|

## 経歴概要

- 大学では、指導教員の開発するAOJに触れてから、Web教育サービス、教育そのものに興味を持ち、Scalaを用いたWeb開発を学び積極的にAOJ改善に努めている。
- 指導教員から授業のコマを頂き、Git・GitHubを用いたPR形式での問題を解かせRuby・Sinatra、React等を用いてWeb開発のイロハを学生に教える。(教えることを通して自身が知識を使うだけでなく、相手に上手く伝達する術、教育の考え方を学ぶため。)
- Scala、Haskell、Elmなどの関数型・オブジェクト指向についての考え方を、Twitterやブログ等を通して発信し、より広い範囲で教えることに努めてきた。
- 今後は、関数型・オブジェクト指向問わず優れた技術の先駆者として業界を牽引していきたいと思っている。

## スキル・強み

### 言語

|名前|年数|備考|
|:--|:--|:--|
|C| 5年|
|Java| 5年|Android開発で使用|
|Ruby| 5年|講義で学生に指導|
|Scala|6年|Web開発で使用|
|Haskell|６年|
|TypeScript| 2年|
|Elm| 9ヶ月|研究開発で使用|

### OS

|名前|年数|備考|
|:---|:--|:--|
|Mac|6年||
|Linux|6年|CentOS, Ubuntu|
|Unix|10年|Solaris|

### 開発ツール・環境

|名前|年数|
|Vim|6年|
|IntelliJ|4年|
|Git・GitHub|5年|
|Docker|2年|
|Nginx|5年|

### フレームワーク・ライブラリ・ミドルウェア

|名前|年数|備考|
|:---|:--|:--|
|PlayFramework|5年|AOJ、Web開発等で使用|
|Spring Framework|2年|AOJバックエンドリプレースに使用|
|Sinatra|5年|講義で学生に指導|
|Akka|3年|AOJサブモジュールで使用|
|MySQL|5年|
|PostgreSQL|1年|
|MongoDB|2年|


## やってみたいこと

- Elmをサービスに導入していきたい
- 高負荷を考慮したスケール可能なサービス・マイクロサービス
- 多くの職種の人を交えたDDD
- これまで一人で作業することが多かったので、デザイナー・営業・経営様々な人の刺激を受けて知識を吸収したい
- 独自サービスやOSSの発信
- 新技術に対する書籍の執筆

## 職務経歴

何年に何してたかわからないのでメモ(あとで消す)

### D
- 2017 4年(超過なう)
- 2016 3年
- 2015 2年
- 2014 1年
###M
- 2013 2年
- 2012 1年
### B
- 2011 5年(超過)
- 2010 4年
- 2009 3年
- 2008 2年
- 2007 1年

### 2014年4月~: 会津大学院博士後期課程

#### 言語ネットワーク

複数の同じ意味を持つ言語を同期し続け、それぞれのエディタを備えたシステムを提供することで、テキスト・ビジュアル・音声など複数の種類の利点を享受できる。教育・ソフトウェア開発・芸術、幅広い分野で利用されることを想定している(例: デジタル・アナログ時計の言語ネットワーク、XML・JSON・YAML・ツリービューの言語ネットワーク、PlantUML・UMLビジュアルエディタの言語ネットワーク)

- 概念の定義、アーキテクチャの設計、言語ネットワークの構築
- Zipperアルゴリズムやインクリメンタルパーサを推奨することで計算量を減らすことに努めた
- プラットフォームや言語の選定にこだわった - 使用想定の幅が広い為 ブラウザで動かしたかった 生産効率を求めてパーサコンビネータやコレクション、GUIアーキテクチャが備わっているElmを選択した
- Elm, SVG, HTML, CSS

#### Aizu Online Judgeのバックエンドアーキテクチャのリプレース

Aizu Online Judge(AOJ)のバックエンドのレガシーコードをリプレース。

- アーキテクト・技術提案・指導
- レガシーコード調査 - JSPを用いて開発されており、機能とデザインが分離が難しい状況であったため、REST APIによる機能の分離を提案
- ソースコード管理の徹底 - バージョン管理が行われていなかった、開発者のみがデプロイ可能となっていため、Git・GitBucketを用いた運用フローを徹底した
- 属人化の排除 - Dockerコンテナを用いて運用手法を単純化して、属人化を排除に努めた、SSL対応の自動化など
- 教育・レガシーコード改善の提案 - GitHubフローまでの教育資料の用意、Spring Frameworkでの開発の流儀を
- Java, Spring Framework, Docker, Git, GitBucket


