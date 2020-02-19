# 職務経歴書

## 個人データ

  * 氏名：山際 康貴
  * ID: `tamanobi`
  * URL: none

## 職務経歴

### ピクシブ株式会社（2016/04〜)

  * pixivのメンテナンスチームに配属
  * 1年間pixivの開発に携わり、さまざまな開発を行う
    * pixiv ID変更
    * フォーマットの異なる画像投稿可能
    * 内製のメール配信システムの構築
    * メール配信システム(SaaS)の運用管理
  * 2018年1月、内製で開発・運用していた広告システムのチームの立ち上げメンバーの1名になる
  * 社内広告システムの開発（チームリーダー）
    * 開発体制の改善
    * プロジェクト管理
    * 不要なシステムのクローズ
    * システムが持つ課題整理
    * 広告商材の管理システムの多言語化対応
    * ログ活用のためのデータウェアハウスの構築

### ソフトウェア開発

#### 社内広告システムの開発・運用

  * 管理サーバーをRuby on Rails（オンプレ）、配信サーバーをGo（GCP）で開発
    * 派生開発と運用が主
  * [広告レポートの自動システム](https://inside.pixiv.blog/2020/01/09/180000)
    * Pythonコードのモジュール化や、レビューを担当
  * 広告効果改善施策
    * pixivの決済基盤システムに機能追加
      * 提案から実装まで
    * 広告ログの分析
      * Python, Pandas, scikit-learn, Rなどを用いたCTR予測モデリング
      * [広告セグメント情報(カテゴリカルデータ)に対するロジスティック回帰分析の適用](https://qiita.com/tamanobi/items/32c67ed0ad1f73040ef7)
    * ログ活用のためのデータウェアハウスの構築
      * Python, SQL
      * GoogleのDataflowとBigQueryを利用したサマリーテーブルの設計
      * アーキテクチャ設計、テーブル設計、実装、プロジェクト管理を担当

### マネージメント

  * 自分含め4人のチームで開発
    * メンバーへの1on1
    * 開発プロセスの見直し
      * チーム間コミュニケーションの整理（ファサードパターン）
      * 開発優先度決定の場を用意
    * ペアプログラミングの導入
    * イシュー粒度のコントロール
    * 障害時の対応フローを定める
    * OKRの決定
    * 障害発生や、割り込み、リリース件数の計測

## 業務外活動

### 受託

  * 画像からのカジノチップ検出
    * OpenCV, Apache MXNet, Amazon SageMakerを使ったPoC
    * 要件定義から実装まで一通り
    * 3Dモデルから写真を生成し、自動アノテーションを行い、SSDで物体検出し、mAPは98%まで上げた
  * とあるアプリ広告のアドバイス
    * 見るべき指標の提案
    * 広告効果改善策の提案
    * 情報提供（PMPや、viewable rateなどの潮流）

### 発表

  * [【生配信】類似画像検索システムを作る【サポーターズCoLab勉強会】](https://supporterzcolab.com/event/853/)
  * [【サポーターズCoLab勉強会】画像と機械学習](https://supporterzcolab.com/event/389/)
  * [【サポーターズCoLab勉強会】ブロックチェーン: NEMを学ぶ](https://supporterzcolab.com/event/381/)
  * [【サポーターズCoLab勉強会】Seleniumを使ったブラウザテスト(E2Eテスト)の導入事例](https://supporterzcolab.com/event/106/)
  * [【勉強会】ツールとしての機械学習](https://supporterzcolab.com/event/103/)
  * [大規模WebサイトのURL刷新の方針と実装](https://speakerdeck.com/tamanobi/da-gui-mo-uebusaitofalseurlshua-xin-falsefang-zhen-toshi-zhuang)
    * PHP Conference2017
  * [【勉強会レポート】GoとDockerで学ぶAPIハンズオンレポート](https://techplay.jp/column/790)
    * 講師

## 著作

  * WEB+DB PRESS Vol.95
    * PHP大規模開発入門【第16回】PHPの静的解析
  * Software Design 2017年10月号 
    * 第6章：Git活用の実例 [1] クラウド=GitHubとオンプレ=GitLabを使い分けるピクシブ
  * [Kubernetesがどういうとき役立つのかわからない人のための本（GCP風味）](https://booth.pm/ja/items/1572988)
    * 同人

## プログラミングスキル

  * Go
    * 広告配信サーバー開発
    * [【勉強会レポート】GoとDockerで学ぶAPIハンズオンレポート](https://techplay.jp/column/790)
  * PHP
    * pixivの開発と広告商材の管理システムで主に利用
    * 内部実装の見直し、リファクタリングなど
    * 個人プロダクトでLaravelを使用
  * Python
    * 広告システムやカジノ案件の受託で使用
    * 機械学習(scikit-learn, Keras), OpenCV
    * [ディープニューラルネットワークと近似最近傍探索で類似画像検索する](https://qiita.com/tamanobi/items/514fc11d69264c1e0ed9)
    * [類似画像検索の資料](https://drive.google.com/drive/u/0/folders/1ImpvHc0HwDQidrYtelQtupCPGVsi_HBF)
    * [画像と機械学習の資料](https://drive.google.com/drive/u/0/folders/1Elh-3X-nsQVFXzZ8QmZopqJsmtROsTp-)
  * Ruby
    * そこまで得意ではない
    * [E2Eテストの導入とその困難](https://drive.google.com/drive/u/0/folders/1Elh-3X-nsQVFXzZ8QmZopqJsmtROsTp-)
    * [【サポーターズCoLab勉強会】Seleniumを使ったブラウザテスト(E2Eテスト)の導入事例](https://supporterzcolab.com/event/106/)
    * [LINE BOT: pixivコミックをおすすめしてくれる司書チャットボットを試作しました - pixiv inside [archive]](https://devpixiv.hatenablog.com/entry/2016/12/04/150000)
  * JavaScript
    * pixivの開発と、広告配信システム、広告商材の管理システムで使用
    * pixivの開発では、Vue.jsとReact
    * 個人プロダクトで、Reactを使用
  * Scala
    * pixivの決済基盤システムを触るときに学び、使用

## 受賞

  * 2018年12月 [ブロックチェーン(Ontology)ハッカソン3位](https://medium.com/ontologynetwork/ontology-holds-tokyo-hakcathon-with-microsoft-7f8bf559d461)
  * 2012年9月 [第2回リサーチフェスタ2012 金賞](https://www.tut.ac.jp/news/120905-1920.html)
  * 2010年12月 有機ELを用いた近未来型電子名刺 [ビジネスグランプリ in 新潟（NB-1グランプリ） 優秀賞](http://www.nagaoka-ct.ac.jp/ec/2010/news2010_10.shtml)
