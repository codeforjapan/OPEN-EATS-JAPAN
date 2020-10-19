OPEN EATS JAPAN
-----

## 飲食店情報オープンデータ項目定義書
* 本データ項目定義書は、飲食店情報をオープンデータとして公開する際の標準的なフォーマットを定めたものです
* 日本各地の団体やサービスで収集・保有されている飲食店情報を相互に利用可能にすることを目的としています
* できるだけ標準化された形でのデータ公開が望ましいですが、必ずしも本書通りに作成する必要はなく、必須項目以外は除外したり、所有データに合わせてデータ項目の追加等を行ってもかまいません

### ドキュメント

* 飲食店情報オープンデータ項目定義書
    * 飲食店情報をオープンデータとして公開する際の標準的なフォーマットを定めた仕様書
    * [飲食店情報オープンデータ項目定義書 - Googleスプレットシート](
https://docs.google.com/spreadsheets/d/1fneMd1HGSnWZAaRyK_r2MWKxwujRqC7A/edit#gid=1513166793)


### 飲食店情報オープンデータ項目定義書　ページ一覧
| No  | 名称 | 説明備考 |
|:----|:-----|:--------|
| 1 | 飲食店_店舗 | 店舗の基本情報を記述するためのデータ項目定義。|
| 2 | 飲食店_メニュー | 飲食店で提供されるメニュー情報を記述するためのデータ項目定義。		表形式でデータを作成する場合、店舗に対してメニューは複数紐付くため、テーブルは分けて作成することを想定しているが、紐付けるのが難しい場合は店舗と同じテーブルで「メニュー1」「メニュー2」…という形で作成しても良い。|
| 3 | 標準産業分類コード | 日本標準産業分類（平成25年10月改定）（平成26年4月1日施行）において定義されている分類コード。https://www.soumu.go.jp/main_content/000290732.pdf" "本書では飲食店を分類するために、「大分類 M 宿泊業，飲食サービス業」より「中分類 76 飲食店」及び「中分類 77 持ち帰り・配達飲食サービス業」を抜粋して掲載している。 |
| 4 | （参考）データモデル | 各テーブルのリレーションやカーディナリティ（多重度）を示したER図。|


### 連絡先

* [OPEN EATS JAPANプロジェクトについて](https://www.code4japan.org/activity/open_eats_japan)

#### OPEN EATS JAPANプロジェクト
OPEN EATS JAPANプロジェクトの進め方については、下記にIssueを上げて議論をしていきます。
定義書の決定の仕方や考え方を整理してますので、ご意見をいただければと思います

* [#16「飲食店情報オープンデータ項目定義書」の位置づけと意思決定の明確化](https://github.com/codeforjapan/OPEN-EATS-JAPAN/issues/16)


#### 自治体の方

オープンデータを進めるにあたり支援の必要な自治体ご担当者の方は info@code4japan.org にメールでお問い合わせください。

#### 民間の個人や企業の方
シビックテックに興味をお持ちのエンジニア・デザイナーの方や、飲食店情報の標準化に興味をお持ちの方は、Code for JapanのSlack (https://cfjslackin.herokuapp.com/) にご参加ください。

別な方法として、下記からの招待メール経由でCode for JapanのSlackに参加が出来ます。
* [Code for JapanのSlackの招待](https://join.slack.com/t/cfj/shared_invite/zt-88tbjehh-_ANL8iwMkwAuuBtXqiyPYg)


## 飲食店情報オープンデータ項目定義書の改善提案

### GitHubで行うこと

* 改善提案をIssueで議論
* ドキュメントのバージョン管理
* おすすめの標準タグ（キーワード）セットや推奨テンプレートの定義

OPEN EATS JAPANに関連した議論&ドキュメントのバージョン管理はGitHubで行います。
改善提案はGitHubのIssueを上げてください。  


GitHubに運用面の提案も是非にお願いします。

### 定義書の更新

* 最新の定義書はシート毎にCSVファイルで管理してます
* Issue単位で議論をして、決定したらCSVに対してPull Requestを出して更新をします
* データ定義書はバージョンアップ毎にGoogleスプレッドシートの[飲食店情報オープンデータ項目定義書](https://docs.google.com/spreadsheets/d/1fneMd1HGSnWZAaRyK_r2MWKxwujRqC7A/edit#gid=1513166793)を更新します

### GitHubとSlack

OPEN EATS JAPANについては、Code for Japan Slack の **`#openeatsjapan`** チャンネル（2020年7月24日以前は `#covid19-opendata` チャンネル）でも並行して話をしていきます
Slackでは、全体的な話、相談、情報共有、雑談等で使用します。

GitHubがわからない方「Issueってなに？」「どうやって改善提案を上げるの？」という方は出来る限りサポートをするので、Slackの `#openeatsjapan` チャンネルで質問をしてください

### 協力団体
本プロジェクトでは、すでに飲食店情報やテイクアウト・デリバリー情報の検索サービスを運営している民間企業や、各地のシビックテック団体と協力し、互いの所有するデータやサービスデザインを共有しながら飲食店データの標準フォーマットの検討を進めています。

| 協力団体 | 備考 |
|:--------|:--|
| [うちたべ](https://uchitabe.com/)　| |
| [オープン川崎/Code for Kawasaki](https://www.openkawasaki.org/) | [よこはま かわさき BENTO MAP](https://brownbag.openkawasaki.org/) |
| [KATTE](https://katte.info/)　| |
| [Code for YOKOHAMA](https://code4.yokohama/)　| [YOKOHAMA to Go](https://to-go.yokohama/) |
| [Save the tables](https://savethetables.org/)　| |
| [株式会社トレタ](https://toreta.in/jp/)　| |


### 飲食店情報のオープンデータ一覧

* トレタ - 日本の飲食店オープンデータ
    - https://github.com/toreta/restaurants-opendata-in-japan
* Save the tables - 日本の飲食店オープンデータ
    - https://github.com/Savethetables/Restaurant/
- Code for YOKOHAMA - テイクアウトとデリバリ情報 (YOKOHAMA to GO)
    - https://github.com/Code4Yokohama/yokohama-to-go/blob/master/data/takeoutyokohama.csv
- オープン川崎 - BrownBagプロジェクト
    - https://github.com/openkawasaki/brownbag-django/


