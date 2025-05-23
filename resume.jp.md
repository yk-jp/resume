### コハツ　ユウスケ - ソフトウェアエンジニア

[Portfolio](https://yk-jp.github.io/portfolio/) | [GitHub](https://github.com/yk-jp) | [LinkedIn](https://www.linkedin.com/in/yusukekohatsu/)

## 職務要約

明治大学を卒業後、日立システムズにてシステムエンジニアとして勤務。顧客管理システムのバックエンド(Java、MySQL)開発とテスト設計を担当。その後カナダへ渡航し、フルタイムでの就労資格を得るまでの間、インターンやボランティアとしてグローバルな環境でエンジニアの経験(Next.js、TypeScript、Express.js、MySQL)を積む。個人では OSS の開発イベントである Hacktoberfest へ参加し、技術スキル(Python、TypeScript、 React.js)の向上。

その後、Sippy Software にバックエンドエンジニアとして入社。SIP 音声通話システム(Python、GO、MySQL)のセッション確立のデータや接続状況の更新管理、コール履歴を DB から取得する機能の最適化(Python、PHP、PostgreSQL)など担当。CEO、リードエンジニア直属で開発をしていたため、日々の時間とタスクの進め方に気をつけることを心がける。

日本へ帰国後、株式会社 ICHIGO にて、オーダーマネジメントシステム(Ruby、Shopify、AWS、ypeScript)の開発に従事。カスタマーポータルやサブスクサービス(Next.js、TypeScript)など、英語が話せる強みを活かしてフルスタック開発に従事。また、他のチームやパートナー企業と連携をとりながら日々のサポート支援、インシデント対応など、迅速な対応経験をする。

## スキルと経験

<strong>高トラフィックを管理するバックエンド開発:</strong> Sippy Software では、1 年で 90 億分の通信トラフィックを処理するバックエンドシステムを Go と Python を用いて担当した。Python から Go のマイグレーション途中であったため、マイグレーションに加えリグレッションが起こらないよう対応できた。開発エンジニアが 3 人構成のチームでありながら、ユーザビリティーのため、Python での XML-API の開発や Vue と PHP で実装されたコール管理システムにて、膨大なデータを処理する実装に従事し貢献した。

<strong>ビジネスインパクトのある仕事経験:</strong> 株式会社 ICHIGO では、海外にお菓子の箱をサブスクとして提供している。多彩な配送方法やサポート対応可の国のルールなど、多種多様な外部サービスを使用して複雑なシステムでロジスティクスが設計されているため、ファイナンシャルダメージとならないよう様々なビジネスシナリオや障害対応など正確に対応してきた。マーケティングチームやバイヤーなど、必要な機能の追加やキャンペーンのためのサポート対応など非エンジニアとのコミュニケーションが滞らないように英語と日本語を駆使して対応している。

<strong>グローバルで働く経験:</strong> キャリアの半分は海外での就労、また現在の株式会社 ICHIGO では 8 割が外国籍のため主言語を英語として仕事に従事してきた。非同期コミュニケーションが多かったため、時差や仕事範囲を明確にした上でタスクに遅れが生じないよう要点の洗い出しや、短時間のミーティングを設けるなど、コミュニケーションロスを減らす工夫をした。

<strong>パブリッククラウドの知識と経験:</strong> これまで AWS をメインに使用してきた。主に CloudWatch や S3、パラメータストア、ECS を活用して開発やデバッグ等に携わる。個人ではスキル向上のために AWS 認定ソリューションアーキテクトを取得した。

## 職務経歴

<div style="display: flex; justify-content: space-between; align-items: baseline; width: 100%;">
  <span style="font-size:1.2em; font-weight:bold;">株式会社ICHIGO | ソフトウェアエンジニア</span>
  <span >2024/10 - 現在 | Tokyo、Japan</span>
</div>

- 2 週間のスパンで新たな発送方法の立ち上げが必要となり、開発メンバーの中心として、AWS S3 と配送サービス API を使用して 2 週間以内に新しい駄菓子 Box 配達機能を実現
- 外部サービス（Shopify、Amazon）から OMS への価格データの同期バグがあり、Ruby、Sidekiq、Shopify、外部 API を活用し、rate limit、API throttling を考慮した上で修正
- Ruby を用いたバッチ一括処理の実装で、外部 API を利用した配送用ラベル印刷の効率化を実現
- Sentry からのアラートをチェックし、報告すべきエラーについてチーム内に共有。
- 1 週間の短い期日で税関ルール変更に伴う緊急対応のための新規リストページを、期限内に TypeScript、Next.js、AWS S3 を用いて開発
- 複雑な配送ロジックから、クリティカルなバグを出さずにコードをリファクタリングし、不必要なコードを削除と関連テストコードの修正に貢献
- メイン業務に加え、他チームからのサポート依頼チケットも英語と日本語で日々対応

<div style="display: flex; justify-content: space-between; align-items: baseline; width: 100%;">
  <span style="font-size:1.2em; font-weight:bold;">Sippy Software, Inc | バックエンドエンジニア</span>
  <span >2022/12 - 2024/08 | Burnaby, Canada</span>
</div>

- 数百万の通話記録のレコード取得時間が長い問題に対し、SQL クエリを最適化したことで通話明細リストの生成速度を 3 倍向上
- 顧客要望に迅速対応するため、電話番号変換用のカスタムシェルスクリプトを提供し、1 週間で報酬$300 の単発案件を完了
- Python と PostgreSQL を用いて新しい請求書テーブル機能を開発・導入
- IP 電話のセッション確立の通話やり取りをデバッグし、プロトコル基準に反したメッセージ情報の修正を Go と Python を用いて対応
- Python から Go へのマイグレーションを、リグレッションが起こらないようウクライナチームのテスターとコミュニケーションを密にとり機能の反映
- Python、Go、PHP、XML-RPC を活用し、分散コンポーネントの保守性・疎結合性を重視した設計・実装を主導
- Python と pytest で堅牢な XML-API を開発し、100%のテストカバレッジを維持
- 新しく入ったフロント、バックエンドエンジニアに対して環境構築やペアプログラミングを通してチーム全体の生産性向上に貢献

<div style="display: flex; justify-content: space-between; align-items: baseline; width: 100%;">
  <span style="font-size:1.2em; font-weight:bold;">Myadcenter | フルスタックエンジニアインターン</span>
  <span >2022/01 - 2022/06 | Remote, Toronto, Canada</span>
</div>

- 堅牢なバリデーション付きの電話番号購入フォームを MaterialUI、JavaScript、Next.js、Twilio API を用いて、開発
- 請求データ取得処理の効率化と課題解決を Node.js、JavaScript、Express.js、MySQL を用いて対応
- データ検索・フィルタリング手法のコードが再利用可能ではなかったため、 Node.js、JavaScript、Next.js、MySQL を活用しリファクタリング対応

<div style="display: flex; justify-content: space-between; align-items: baseline; width: 100%;">
  <span style="font-size:1.2em; font-weight:bold;">日立システムズ | システムエンジニア</span>
  <span>2020/04 - 2021/09 | Tokyo, Japan</span>
</div>

- Java でユーザー管理システム向けの堅牢な REST API を開発し、JUnit で 100%のテストカバレッジを達成
- ユーザー管理システム用の再利用可能なテーブルコンポーネントを HTML、CSS、TypeScript で作成
- Java 、MySQL と手動テストにより、建設原価管理システムの全潜在バグを出荷前に検出し、100%のテストカバレッジを実現
- ユーザーテストを徹底し、JIRA でバグを他のチームに報告
- MySQL と JIRA を用いて、建設原価管理システムのテストケース設計と検証を通じて全機能バグを解消

## OSS コントリビューション

**fpdf2 [PR](https://github.com/py-pdf/fpdf2/pull/543)**

- HTML から PDF を作成する Python Library
- 新しい HTML のタグサポートと、メインクラスの Deprecation の削除。リグレッションを考慮して対応

**novu [PR](https://github.com/novuhq/novu/pull/1412)**

- Slack や Email、Push など多数のチャンネルを管理する通知プラットフォーム
- Cypress、React.js を使用してコンポーネントテストを追加し、カバレッジの向上に貢献

## 学歴

**Cornerstone International Community College of Canada:** Web and Mobile App Development 2022/01 - 2023/12 <br>
**明治大学（東京）:** 総合数理部 ネットワークデザイン学科 2016/04 – 2020/03

## 資格

**AWS 認定ソリューションアーキテクト – アソシエイト** 2024/03 - 2027/03<br>
**IELTS General Training O.A. 8.0** 2023/08 - 2025/08<br>
**Hacktoberfest 2022 OSS コントリビューション** 2022/10
