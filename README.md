## 基本情報

|key|value|
|----|----|
|Name|HanamaruDell|
|Birth(Age)|1995/04/17|
|Family|既婚・子なし|
|Location|神奈川県|
|Education|地方駅弁の情報系学部|
-------------------------------------------------------------------------------------------------

### 経験技術
**サーバサイド技術**
* Java(Struts,iBatis)：1年
* Java(SpringBoot)：3年

**フロントサイド技術**
* JavaScript：3年
* html/CSS/BootStrap/Tymeleaf：3年

**DBMS**
* Oracle：2年
* SQLSever：1年
* PosgreSQL：1年

**OS**
* Linux(RedHut)：2年
* WindowsSever2016：2年

**ミドルウェア**
* Tomcat：2年
* WebSphere Application Server：2年

**ソース管理**
* SVN：2年
* GitHub/BitBucket：2年

**プロジェクト管理ツール**
* Redmine：3年
* Backlog：3年

### 保有資格
* 基本情報技術者試験
* 応用情報技術者試験
* SAP（AAFA　ERP6.0）

-------------------------------------------------------------------------------------------------

## 職務履歴の基本情報
約5年間製造業会社向けの購買システムの開発(自社パッケージ導入)に従事した。
ウォーターフォール開発で要件定義から設計・実装・テスト・運用保守と一貫したSIをPLとして担当。

## 購買システム(自社PKG)について
多様な購買業務方式に対応しており、SpringBootを用いて構築されたMVCモデルのWebシステム。
機能数はマスタを除いて30機能ほどあり、画面数は1機能8画面ほどの総画面数300程度のシステムの規模。
DBMSは標準仕様はPostgreSQLを使用しているが、Oracle、SQLServerを使用した案件もある。
アプリケーションサーバはTomcat、WebSphere Application Serverに対応。

-------------------------------------------------------------------------------------------------

## 苦労した案件
開発総工数40人月程度の購買システム刷新のプロジェクトにPLとして参画した。

**課題①**
商品改良した購買システムのファースト案件であった。
改良版では新FW(Struts→Spring)に刷新、テーブル構造の見直し、画面構造の改良などを実施しており、ほぼ新商品に近い製品のため、商品に対して開発メンバーの知見が浅い状態だった。

**課題②** 
PMがマネージメント業務中心のタイプのため、PLとして技術的なフォローをしていく必要があった

### 開発した主なカスタマイズ・アドオン機能
* パンチアウト連携といった外部のカタログサイトとcXML送受信連携機能
* 申請金額、発注金額、検収金額を案件の進捗状況に応じて積み上げる予算管理機能
* バーコードリーダを用いて納品番号を読み込ませ、入荷処理を行う機能

### 要件定義フェーズ
* 追加要件に対してPMはKKDによる見積を行っていたが、簡易的なFP法を作成し精緻な見積に修正した
* Azure環境にVMを立てTomcat上にアプリをデプロイすることで、簡易的なデモ環境を構築して、実際にキーマンに触ってもらうことでパッケージの理解度を向上させた

### 基本＆詳細設計フェーズ
* 画面レイアウトの作成、画面遷移処理図の作成、画面・DB編集設計、入力チェック仕様を設計し顧客レビューを実施した。
* IT経験の少ない顧客に対して、モックアップの作成や、Excel/PowerPointで表や図でかみ砕いた説明をすることで認識齟齬を減らした。

### 開発フェーズ
* PLとしてGitのプルリクエストを活用して、メンバーのコードをレビューした。
* SpringBootの開発経験が浅いメンバーも多くいたため、JPAの使い方、スコープ、楽観ロック方法など、製造の注意所を開発手引きにまとめてフォローをして全体効率化を図った。
* 煩雑化していた処理を共通メソッド化することで、全体の負担の軽減、PG品質の向上を図った
* 上記記載のアドオン機能に関しては、業務理解度・パッケージ理解度が高い自身でコーディングを全て担当した。

### テストフェーズ
* Redmineとバージョン管理(Bitbucket)を連携することで、不具合内容と修正コーディング内容の紐づけをすることで同様の事象の不具合の横展開することで、潜在バグを含めて改修することで品質向上を図った。

