## あなたに何を解決してほしいのか?
候補者にプロダクト/サービス/開発チームのどんな技術的な課題、問題を解決してほしいのか (Tobe)
* **開発チームのクロス体制** // 特に解決したい問題
  * これはどういうこと?
    * 開発メンバーが2人以上いないということ
  * なぜ問題なのか
    * 不測の事態で長期離脱できない
* サービスの品質チェック
  * これはどういうこと?
    * コードのレビュー体制が無い
  * なぜ問題なのか
    * バグに繋がったり、改修のスピードが出ない
    * 品質が検証できてない
    * 今は実行結果(UI)しか見れないけど、もっと内部の動きにフォーカスしたい
    * ↑だと可用性とか拡張性まで気を配れていない
* 技術ドリブンのサービス改善
  * これはどういうこと?
    * 新しい技術を使ってみてよいものとかを取り入れて、機能とかパフォーマンスとか改善につなげたい
    * ex. AIの導入（自然言語処理）
      * 受講履歴から最適なスケジュール設定、テスト配信などを行う
  * なぜ問題なのか
    * 開発チームとしてのアピール
    * ただ言われて作るチームではない
      * たとえば、redis を入れると、dbの負荷を抑えられる
      * より安定したユーザー体験を提供できる
    * 技術進化の恩恵をユーザーに提供できてない (開発の効率も含む)
* セールスチームからの要望を技術で解決して欲しい
  * これはどういうこと?
    * 問題解決の道筋を描く
  * なぜ問題なのか?
    * 現状のリソース(開発体制1名)でしか対応できていない
    * 今後、問題が増えてくるし、新しい開発にも取り組んでいけていない
* サーバスペックの定期監視
  * これはどういうこと?
    * インフラは監視含めて外注しているので、それを自身でも定期監視
  * なぜ問題なのか
    * 問題が起きてから対応になってしまう
    * 予兆を把握できていない

## 現在はどういうプロダクト/サービスを、どういう技術を使って開発しているのか? (Asis)
* 具体的なプロダクトやサービスの内容
  * SE、ITエンジニア向け eラーニング [独習ゼミ](https://www.seplus.jp/dokushuzemi/doku_zemi/)
    * 独習ゼミは翔泳社の書籍や動画で学び、確認テストをWebで受講するシンプルなeラーニングです
  * SE、ITエンジニア向け定額制研修 [SEカレッジ](https://www.seplus.jp/dokushuzemi/secollege/)
    * 月額1社25000円～で社員は受講し放題となる定額制研修です。SE、ITエンジニア向けに動画を含め年間600コースを公開。AI、クラウドなど最新テーマからビジネスマナーまで幅広く対応、体系的にスキルアップできます
  * sales person向け営業支援ツール
    * 開発中
* 具体的な技術
  * 開発言語:PHP ver.5.4~7.0
  * Framework:Laravel 3.x~5.4
  * database:MySQL 5.6 / AWS RDS
  * ServerOS:CentOS 6 / AWS S3
  * Frontend:Bootstrap 3 / jQuery / Riot.js / Pjax
  * 開発管理:Git/GitHub
  * issue管理:Redmine/GitHub Projects
  * コミュニケーション:Slack

## あなたにどのように解決して欲しいのか?
Tobeで挙がった問題・課題に対して、一緒にどのように取り組んでほしいのか
* 開発言語問わず、インフラ構築やWebアプリケーションの開発でも言われたことをやるのではなく、技術が好きで探求出来る方に、
    * 自分で面白がって作ることが好き
* 遅くても少しずつ1年かけて↓のことができるようになって欲しい
  * セールスチームからの要望解決
  * 技術ドリブンのサービス改善
  * 大幅リニューアルというよりドキュメント整備など含め、1歩ずつ改善を積み重ねられる
* それに向けて、候補者の開発経験をもとにして、何から取り組むのかを決める
  * 例えば、環境を作って、実際にLaravelを使った開発をやってみるところからスタート
  * 例えば、実際のアプリケーション開発のテストを書く、ドキュメントを書く、機能を改修する、というプロセスを経る

## 誰と解決するのか?
現在の開発チームはどのようなチームなのか (with who)
* 新しい技術が好き
  * AI使いたい! IoT興味がある!
  * RasberryPi で工作したい
* 長く使われる技術も使いたい
  * Vimとか秀丸とか
* 有給消化率がKPIになっている
* 開発経験年数が長い、気さくな(おじさん30代)チーム
* 開発チームのメンバーは3人
  * 研修系サービスを主にやっている、ラン部のおじさん1人とタッグでやる
  * コメディカル人材メディアやアプリは気さくなおじさん2人で開発
* 自社プロダクト/サービスで儲けたい
