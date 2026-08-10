> **[Qiitaで開発記録・エラー解決記事を公開しています](https://qiita.com/tosane932)**

# 🛠️ 現場経験を、使われるWebアプリケーションへ

物流・飲食・販売の現場経験と、Webデザインで培った視線誘導・配色・情報設計の知識を組み合わせ、**利用者が迷わず操作でき、実際の業務改善につながるWebアプリケーション**の開発に取り組んでいます。

IT業界での実務経験はありませんが、2026年5月より、本業の大型・中型トラックドライバーを続けながら、PythonおよびRuby on Railsを用いたWebアプリケーション開発を独学で開始しました。

学習開始から約3か月・累計167時間の段階で、以下の開発・運用を経験しています。

- Python / Flaskを用いたWebアプリケーション開発
- PostgreSQL / SQLAlchemy / Alembicによるデータベース設計・変更管理
- Docker / Docker Composeによる開発環境構築
- pytest / GitHub Actionsによる自動テストとCI
- pytestを3件から51件へ拡充し、入力値検証・DB整合性・rollback・履歴保持・ダッシュボード集計まで回帰テスト化
- `(product_id, date)`のDB一意制約追加と、隔離PostgreSQL環境でのupgrade / downgrade検証
- Gunicorn / Renderによる本番公開
- Gemini APIを利用したAI機能の実装
- Google OAuth / Flask-Loginによる認証機能の実装
- JavaScriptによるブラウザ完結型Webアプリケーション開発
- VS Code版Codexを用いた、事実と推測を分けたリポジトリ全体の静的レビュー
- Codexへ変更範囲・禁止事項・停止条件を段階ごとに指定し、小さな単位で修正・検証する運用
- 開発過程・失敗・設計判断のQiitaおよびGitHubへの継続的な記録

Webデザインでは、見た目を整えることだけでなく、**見る人の視線の流れ、情報の優先順位、ボタン配置、操作手順の分かりやすさ**を意識しています。

さらに、全国の百貨店催事で広島風お好み焼きの調理・実演販売、売上管理、材料発注、スタッフ管理を経験したことで、利用者がどこで迷い、どの言葉なら行動へ移りやすいかを、実際の販売現場から学びました。

現在は、次のコンセプトをアプリ開発の判断基準にしています。

> **老若男女、誰が見ても使いやすいアプリ**

- 曖昧な文言を避ける
- 現在の登録状態を画面に表示する
- 操作の種類ごとに色を統一する
- 色だけでなくアイコンと具体的な文言を併用する
- 次に行う操作へ迷わず移動できる導線を作る
- ヒューマンエラーを個人の注意力だけに頼らず、仕組みで防ぐ

物流や飲食など、時間に追われる現場でも直感的に使える画面設計と、利用者が「これ、どうしたらいいですか？」と困る前に迷いの原因を取り除くシステム設計を目指しています。

開発環境には、13年前に購入し、現在も使い続けているLenovo G580を使用しています。処理速度と費用対効果を考え、自らSSD 256GBへの換装、メモリ16GBへの増設、OSの変更・検証を重ね、現在はLubuntu 24.04 LTS上で開発しています。

限られた機材やクラウド環境の制約を理由に止まるのではなく、原因を切り分け、代替案を検討し、**第三者が実際に触れられる「動く成果物」まで届けること**を重視しています。

---

## 📂 資格・現場経験

### 🎨 デザイン・情報処理関連資格

- **ウェブデザイン技能士 3級**
  - Web制作の基礎知識を、画面の視線誘導・情報設計・操作性の改善に活用
- **色彩検定 3級**
  - 配色、視認性、情報の強弱を意識したUI設計に活用
- **情報処理技能検定（表計算）1級**
  - 業務データの整理・集計・分析に関する基礎力
- **日本語ワープロ検定 準1級**
  - README、技術記事、操作説明などの文書作成に活用
- **MOS Excel 2007**
  - 表計算・データ管理・業務集計の基礎を習得

### 🚚 主な現場経験

- **百貨店・催事場での調理・実演販売**
  - 全国の百貨店催事にて、広島風お好み焼きの調理・実演販売、材料発注、売上管理、販売スタッフの採用・管理を経験
  - 自ら商品を作り、セールストークを考え、接客し、お客様へ販売する一連の商売を経験
  - 元お好み焼き職人として、調理・接客・在庫・売上・人員を同時に管理する現場運営に従事
  - お客様がどこで迷うか、どの言葉なら伝わるかという販売現場の感覚を、UIの文言・配色・画面導線へ活用

[「保存」と「更新」は違う。元お好み焼き職人が店長目線でFlaskアプリの迷うUIを潰した話](https://qiita.com/tosane932/items/245152c844261e615641)

- **自動販売機補充オペレーター**
  - 3年間、過去の売上データから巡回ルート、積載量、商品構成、販促施策を逆算して設計
  - 限られた時間と車両容量の中で、効率的な運用を組み立てる業務を経験

- **大型・中型トラックドライバー（現役）**
  - 大型免許を保有し、7年7か月にわたり物流業務に従事
  - 厳しい時間制限と安全基準の中で、運行判断、確認作業、ヒューマンエラー防止を実践
  - 「危険が起きてから対応するのではなく、起きる可能性を予測して先に潰す」という危険予知を、アプリ開発にも応用

---

## 📅 開発の歩みとアウトプット履歴

既存コードをそのまま無批判に取り込むのではなく、現場での課題感に基づいて仕様を考え、AIの提案も目的・影響範囲・検証結果を確認しながら採用しています。

また、動作するコードを作るだけでなく、利用者がどのように受け取るか、誤操作や勘違いが起きないかまで検証し、定期的なコード・UI・READMEのリファクタリングを自身の「技術資産」として記録しています。

<details>
<summary><strong>📖 開発履歴を表示する</strong></summary>

<br>

| 日付 | マイルストーン・実装内容 | 累計学習 | 関連Qiita記事 |
| :--- | :--- | :--- | :--- |
| **2026/05/12** | Pythonを中心とした本格的なシステム開発学習を開始。自動化プログラムとWebアプリケーションの設計・実装に着手 | - | - |
| **2026/05/23** | GitHubによるソースコード管理環境を構築し、Python / Flaskを用いた初期3システムを公開。構想段階で実現性を検証し、車載ローカルサーバー案からWebアプリケーション開発へ方針転換 | 12日 / 56h | [車載ローカルサーバー構想を損切りし...](https://qiita.com/tosane932/items/37c9d2c482a6611d2f25) |
| **2026/06/02** | Ruby on Rails 8を用いたWebアプリケーションをRenderへ本番公開。無料クラウド環境のメモリ・ファイルシステム制約を調査し、ローカルプリコンパイルと永続ディスクによる代替案を検証 | 22日 / 81h | [Render無料枠の制限を回避したRails 8のデプロイ検証](https://qiita.com/tosane932/items/58e00fc7353ef76b4a62) |
| **2026/06/03** | Pythonで事前に外部データを取得・整形し、JSONファイルとして静的サイトへ供給する「データ出荷型」構成を実装。画面表示時の通信待ちを抑える設計を検証 | 23日 / 86h | [Python学習開始24日目の記録...](https://qiita.com/tosane932/items/a227899ee58d68020c21) |
| **2026/06/18** | 過去のREADME・学習記録・技術記事を全面的に見直し。感情中心の記述から、現象・原因・判断・結果を区別した事実ベースの技術ドキュメントへ再構成 | 38日 / 93h | [過去の学習記録を『リファクタリング』する...](https://qiita.com/tosane932/items/3d05208f519db621efef) |
| **2026/06/24** | `sales_data_app`のデータ保存先をSQLiteからPostgreSQLへ移行 | 44日 / 98h | - |
| **2026/06/28** | `sales_data_app`のコード全体を再点検し、重複処理・不要コード・例外処理不足など9件の問題を発見・修正 | 48日 / 100h | [学習100時間のトラックドライバーが...](https://qiita.com/tosane932/items/ac18b633c8c87b9807bb) |
| **2026/06/30** | `sales_data_app`をDocker化し、FlaskとPostgreSQLをまとめて起動できる再現可能な開発環境を構築 | 50日 / 104h | - |
| **2026/07/02** | Docker上のFlaskコンテナとPostgreSQLコンテナを連携し、名前解決・ボリューム・ローカルとの差異を検証 | 52日 / 108h | [FlaskとPostgreSQLのマルチコンテナ環境における...](https://qiita.com/tosane932/items/e19ed4a2ffe27f53faf0) |
| **2026/07/04** | `sales_data_app`をRenderへ本番デプロイ。環境変数・DB接続・起動処理の差異を切り分けて修正 | 54日 / 113h | [【実録】学習113時間のトラックドライバーが...](https://qiita.com/tosane932/items/31bdab8ee2ab8bae2c50) |
| **2026/07/06** | 全50問の運転性格診断アプリを開発。Fisher-Yates法と5段階傾斜配点を実装 | 56日 / 120h | [なぜ『運転性格診断クイズ』なのに...](https://qiita.com/tosane932/items/220d0f7d36bd79b2aa81) |
| **2026/07/09** | 運転性格診断アプリへrippleアニメーションと多重操作防止処理を追加 | 59日 / 122h | [🚽トイレの点滅ランプと"isProcessing"フラグが同じだった件](https://qiita.com/tosane932/items/33734f1e963fcb370318) |
| **2026/07/11** | Dockerfileをマルチステージビルド化し、イメージサイズを実測 | 61日 / 125h | [マルチステージビルドで積み替えても、3MBしか減らなかった話](https://qiita.com/tosane932/items/c1609f17cddf842f1e7c) |
| **2026/07/11** | pytestとGitHub Actionsを導入し、GitHubへのPush時に自動テストを実行するCI環境を構築 | 61日 / 125h | [トラックドライバーが「点検ゲート」を作ってみたら、テストの落とし穴にハマった話](https://qiita.com/tosane932/items/b9b6576c1fda3d3a76d2) |
| **2026/07/16** | `is_active`による論理削除、過去売上履歴保持、Alembic、Gemini APIのボタン実行化、Gunicorn本番起動を実装 | 66日 / 135h | [売上履歴を壊さず商品を販売終了にしたい――Flaskで論理削除とGemini API節約を実装した記録](https://qiita.com/tosane932/items/4825452f4bb73fd90ba8) |
| **2026/07/17** | `puoppo_app`へGoogle OAuthとFlask-Loginを導入 | 67日 / 138h | - |
| **2026/07/18** | CSSを`static/style.css`へ分離し、ページ別スコープを設定 | 68日 / 143h | [「保存」と「更新」は違う。元お好み焼き職人が店長目線でFlaskアプリの迷うUIを潰した話](https://qiita.com/tosane932/items/245152c844261e615641) |
| **2026/07/18** | 店長目線で文言・配色・未来年表示・登録状態・画面導線を改善 | 68日 / 143h | [「保存」と「更新」は違う。元お好み焼き職人が店長目線でFlaskアプリの迷うUIを潰した話](https://qiita.com/tosane932/items/245152c844261e615641) |
| **2026/07/19** | `sales_data_app`のリポジトリ全体を5時間総点検し、不要コード・画像資料・README・ignore設定などを整理 | 69日 / 148h | [🚛 動いているFlaskアプリを5時間総点検――コード・README・Docker・Gitを「現在の仕様」に揃える方法](https://qiita.com/tosane932/items/02de476fad8f0c1261e0) |
| **2026/08/02** | VS Code版Codexで`静的レビュー`を実施。18件の改善候補を抽出し、最初に動的ランキングの保存型XSSを修正 | 83日 / 152h | [🔨47秒でXSS修正！？VS Code版Codexを「他部署から来たベテラン点検員」として使ってみた](https://qiita.com/tosane932/items/95f998ff98c4ac2ec5d9) |
| **2026/08/06** | 欠落していた初期マイグレーションを修復し、空DB構築と既存DB複製環境の両経路を検証 | 87日 / 155h | [Flask-Migrate導入後の空DBで「テーブルが存在しない」と失敗した原因と、初期マイグレーションを修復した記録](https://qiita.com/tosane932/items/13c2ca0e17716594aa1e) |
| **2026/08/10** | pytest強化を第2段階まで実施。3件→9件→51件へ拡充し、売上POST・商品POST・DB一意制約・rollback・履歴保持・dashboard APIを回帰テスト化。AI返答表示も`innerHTML`から`innerText`へ変更 | 91日 / 167h | [Qiitaで最新の開発記録を公開](https://qiita.com/tosane932) |

</details>

---

## ⚡ 開発実績・リポジトリ一覧

### 1. [🍞sales_data_app](https://github.com/tosane932/sales_data_app)

【Python / Flask / PostgreSQL / Docker / Gemini API】

- **オンラインデモ**: [ベーカリー売上管理システムをブラウザで体験する](https://bakery-salesdata.onrender.com/)
- **概要**: 商品マスタ、日次売上入力、売上分析、AIによる経営アドバイスを一元化した、ベーカリー向けWebアプリケーション
- **コンセプト**: 元お好み焼き職人としての店舗運営経験とWebデザインの知識を生かし、老若男女が迷わず使える売上管理システムを設計

### 主な設計・実装

- SQLiteからPostgreSQLへの移行
- SQLAlchemyによるデータ管理
- `is_active`を用いた論理削除と過去データの保持
- Flask-Migrate / AlembicによるDBマイグレーション
- Docker / Docker Composeによる環境構築
- Gunicorn / Renderによる本番公開
- pytest / GitHub Actionsによる自動テスト
- Gemini APIの429・503を区別したエラーハンドリング
- VS Code版Codexによる静的レビュー
- 保存型XSS対策
- UI文言・配色・導線の改善

<details>
<summary><strong>🔧 sales_data_app の詳細な実装・検証内容を表示する</strong></summary>

<br>

- 欠落していた初期テーブル作成履歴を調査し、`products`と`daily_sales`を作成する基礎revisionを追加
- 既存の`is_active`追加revisionを基礎revisionへ接続し、空DBからheadまで到達できる履歴へ修復
- `DailySales(product_id, date)`へ一意制約を追加し、同一商品・同一日の重複をDB側でも拒否
- 通常環境とは異なるComposeプロジェクト名を使用し、コンテナ・ネットワーク・PostgreSQLボリュームを分離
- 空DBから`flask db upgrade`、Gunicorn起動、HTTP 200を確認
- 既存DBを読み取り専用で`pg_dump`し、分離した複製DBへ復元してupgrade経路を検証
- 一意制約追加migrationを隔離PostgreSQL環境でupgrade / downgrade / 再upgradeし、既存データが変化しないことを確認
- pytestを51件まで拡充
- 売上POSTの日付・数量・配列長・商品IDをDB変更前に全件検証
- 不正な売上リクエストをHTTP 400で拒否
- 売上対象商品の存在・対象年月・販売状態を検証
- 商品POSTの配列長・商品ID・対象年月・重複ID・価格・年月を事前検証
- 不正入力時にProduct / DailySalesが変更されないことを確認
- 売上POST・商品POSTの`commit()`失敗時に`rollback()`
- 論理削除後もProduct IDと過去DailySalesを保持
- 既存Product ID再送信時に同じ行を再有効化する挙動をテスト化
- `/api/dashboard-data`で年月別集計・ランキング・グラフ値・inactive商品の過去履歴・全期間集計を検証
- 動的ランキング表示の`innerHTML`を廃止し、DOM APIと`textContent`へ変更
- AI返答表示の`innerHTML`を`innerText`へ変更
- XSS回帰テストでHTML風文字列が要素として解釈されないことを確認
- HTML内のCSSを`static/style.css`へ分離
- ページ専用クラスによるCSSの影響範囲制御
- スマートフォン向けレスポンシブデザイン
- `.gitignore`・`.dockerignore`による機密情報・ローカルデータ・開発資料の除外
- ローカル環境とRender公開環境の別DBで、商品登録・売上入力・ランキング・グラフ表示を実機確認

</details>

### ユーザー視点によるUI改善

- 不要な未来年の選択肢を削除
- 「保存する」を「本日の売上個数を更新する」へ変更
- 商品ごとに「本日の登録済み個数」を表示
- 入力欄へデータベースの現在値を初期表示
- 商品ごとの余白と区切り線を追加
- トップ・日次入力・売上分析間の画面導線を改善
- 商品登録・日次入力・売上分析・AI・戻る操作の配色を統一
- 色だけでなく、アイコンと具体的な文言を併用

### 公開記事

- [「🚛学習100時間のトラックドライバーが、自分のFlaskコードの積載ミスを9つ発見して全部直した話📦」](https://qiita.com/tosane932/items/ac18b633c8c87b9807bb)
- [「マルチステージビルドで積み替えても、3MBしか減らなかった話」](https://qiita.com/tosane932/items/c1609f17cddf842f1e7c)
- [「トラックドライバーが『点検ゲート』を作ってみたら、テストの落とし穴にハマった話」](https://qiita.com/tosane932/items/b9b6576c1fda3d3a76d2)
- [「🔨47秒でXSS修正！？VS Code版Codexを『他部署から来たベテラン点検員』として使ってみた」](https://qiita.com/tosane932/items/95f998ff98c4ac2ec5d9)
- [Flask-Migrate導入後の空DBで「テーブルが存在しない」と失敗した原因と、初期マイグレーションを修復した記録](https://qiita.com/tosane932/items/13c2ca0e17716594aa1e)
- [最新のpytest強化・Codex運用・XSS対策記事はQiitaプロフィールから確認できます](https://qiita.com/tosane932)

---

### 2. [🕊puoppo_app](https://github.com/tosane932/puoppo_app)

【Python / Flask / SQLite3 / Gemini API / Google OAuth / Docker】

- **オンラインデモ**: [Puoppoをブラウザで体験する](https://puoppo.onrender.com/)
- **概要**: 公式RSSから関連記事を収集し、Gemini APIで要約・分析するWebアプリケーション
- **設計判断**: Webサイトからの直接取得が安定しなかったため、公式RSSを利用する安全で継続可能な取得方式へ変更
- **認証**: Google OAuth / Flask-Login
- **今後の課題**: ユーザー別履歴分離、所有者確認、未ログイン時のアクセス制御
- **公開記事**: [「無理に近道するより整備された道を行け」物流の教訓からスクレイピングを捨て、公式RSS×Geminiで割り切ったAIアプリを作った話](https://qiita.com/tosane932/items/92bcf28cd91d645596bd)

---

### 3. [🚛driver-personality-test](https://github.com/tosane932/driver-personality-test)

【JavaScript / HTML / CSS / sql.js】

- **オンラインデモ**: [運転性格診断テストをブラウザで体験する](https://tosane932.github.io/driver-personality-test/)
- **概要**: 7年7か月のドライバー経験をもとに、物流現場で起こり得る判断場面を全50問の診断形式へ落とし込んだブラウザ完結型Webアプリケーション
- **特徴**: 5段階の傾斜配点、Fisher-Yatesランダム化、LocalStorage履歴保存、多重操作防止
- **公開記事**:
  - [「❓️なぜ『運転性格診断クイズ』なのに、これだけ時間をかけたのか」](https://qiita.com/tosane932/items/220d0f7d36bd79b2aa81)
  - [「🚽トイレの点滅ランプと"isProcessing"フラグが同じだった件」](https://qiita.com/tosane932/items/33734f1e963fcb370318)

---

<details>
<summary><strong>📦 その他のリポジトリを表示する</strong></summary>

<br>

### 4. [python-practice](https://github.com/tosane932/python-practice)

【Python / Excel】

- **概要**: 大手ニュースサイトを対象とした、データ抽出および蓄積の技術検証プログラム
- **設計判断**: Webサイトからの直接取得が安定しなかったため、公式RSSフィードを利用する取得方式へ変更
- **実装内容**: Excelへの自動保存・追記、重複データの監視・排除
- **公開記事**: [「車載ローカルサーバー構想を損切りし、Webアプリケーション開発へ舵を切った判断理由」](https://qiita.com/tosane932/items/37c9d2c482a6611d2f25)

### 5. [rails_practice](https://github.com/tosane932/rails_practice)

【Ruby / Rails 8 / SQLite3 / Render】

- **概要**: Rails 8とクラウド環境の制約対応を検証したWebアプリケーション
- **実装内容**:
  - Render無料枠のメモリ不足に対してローカルプリコンパイルを導入
  - SQLite3のデータ消失対策として`storage/`を永続ディスクへ接続
- **公開記事**: [「Render無料枠の制限（512MB RAM・Read-only）を回避したRails 8のデプロイ検証」](https://qiita.com/tosane932/items/58e00fc7353ef76b4a62)

### 6. [hiroshima-logistics-hub](https://github.com/tosane932/hiroshima-logistics-hub)

【Python / JSON / GitHub Pages】

- **概要**: 物流運行管理に必要な外部環境データを、メインサイトへ負荷をかけずに供給する「データ出荷型」Webポータル
- **設計判断**: Pythonで事前にデータを取得し、`data.json`として静的サイトへ供給
- **公開記事**: [「Python学習開始24日目の記録：物流現場でWebエンジニアを目指す86時間の歩み」](https://qiita.com/tosane932/items/a227899ee58d68020c21)

</details>

---

## 🛠️ 開発環境・技術スタック

<details>
<summary><strong>💻 使用環境・技術スタックを表示する</strong></summary>

<br>

### 開発環境

- **PC**: Lenovo G580（約13年間継続使用）
- **ハードウェア改善**: SSD 256GB換装 / メモリ16GB増設
- **OS**: Lubuntu 24.04 LTS
- **Editor**: Visual Studio Code / OpenAI Codex IDE拡張機能
- **Version Control**: Git / GitHub

### Backend

- Python 3.12
- Flask
- Ruby 3.3
- Ruby on Rails 8
- SQLAlchemy
- Flask-Migrate
- Alembic
- Gunicorn
- Flask-Login
- Authlib

### Frontend

- HTML5
- CSS
- JavaScript
- Jinja2
- Fetch API
- Chart.js

### Database

- PostgreSQL
- SQLite3
- sql.js

### Authentication

- Google OAuth 2.0
- Flask-Login
- Authlib

### Infrastructure / Testing

- Docker
- Docker Compose
- Render
- GitHub Pages
- GitHub Actions
- pytest

### AI / External Data

- Google Gemini API
- Google GenAI SDK
- OpenAI Codex（VS Code IDE拡張機能）
- RSSフィード

### UI / UX

- レスポンシブデザイン
- 視線誘導
- 操作別の配色統一
- 現在状態の可視化
- 曖昧な文言の見直し
- 画面導線の設計
- 色だけに依存しない情報伝達
- ヒューマンエラー防止を意識したUI

### 継続学習・技術記録

- Duolingoを利用した英語学習
- 英語の技術ドキュメントおよびエラーメッセージの読解力を継続的に強化
- 開発中に起きた失敗・原因・修正・再発防止策をQiitaへ記録
- READMEを定期的に見直し、現在の実装内容と一致させる運用
- [過去の学習記録を「リファクタリング」する：感情的な記述を事実ベースの技術報告へ再編した理由](https://qiita.com/tosane932/items/3d05208f519db621efef)

</details>

---

## 🚀 将来のビジョンとロードマップ

私の強みは、直面したエラーを現象・環境・依存関係・データ構造に分けて切り分け、制約に対する代替案を検討し、実際に動作するところまで検証する**「事実ベースの問題解決力」**です。

さらに、Webデザインで身につけた視線誘導・配色・情報設計の知識と、物流・飲食・販売の現場経験を組み合わせ、以下を重視しています。

- 利用者が最初に見る情報を明確にする
- 操作順序に沿ってボタンや入力欄を配置する
- 現在登録されている状態を画面上に表示する
- 内部処理とボタン文言を一致させる
- 忙しい現場でも判断に迷いにくい画面を作る
- 操作の意味ごとに色・アイコン・文言を統一する
- 色だけに依存せず、誰にでも伝わる情報設計を行う
- ヒューマンエラーを個人の注意力だけに頼らず、仕組みで防ぐ
- 技術を導入すること自体ではなく、現場の負担を減らすことを目的にする
- 第三者が実際に触れられる状態で公開し、改善を継続する

物流・飲食・販売・保育などで働く人の声を課題発見の起点とし、実際に触れられるWebアプリケーションとして公開しながら改善を続けます。

### 【目標：2026年末までのロードマップ】

2026年末までに「現場で即戦力となるポートフォリオの完成」をマイルストーンとして設定し、以下の3つを軸に実績を積み重ねています。

1. **技術の深掘り**  
   Docker・データベース・CI/CD・クラウド・認証など、アプリケーションの裏側まで理解し、堅牢なシステムを設計・構築できる力を身につける。

2. **実績の証明**  
   開発過程やエラー解決、UI改善の判断理由を、事実ベースの技術記事（Qiita）およびソースコード（GitHub）として継続的に公開する。

3. **現場課題からのプロダクト開発**  
   自身や家族、実際の現場で働く人の声をもとに課題を抽出し、物流・飲食・販売・保育など幅広い分野で役立つWebアプリケーションを企画・開発・公開する。

将来的には、これまでの運行管理・店舗マネジメント・実演販売で培った現場感覚とシステム開発を組み合わせ、実際の業務改善につながるWebサービスを継続的に生み出せるWebエンジニアを目指しています。