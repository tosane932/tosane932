![tosane932 profile banner](profile-banner.png)

[Qiita](https://qiita.com/tosane932) ・ [Zenn](https://zenn.dev/tosane932) ・ [DEV Community](https://dev.to/tosane932)

# 🛠️ 現場経験を、使われるWebアプリケーションへ

IT業界での実務経験はありませんが、大型・中型トラックドライバーとして働きながら、2026年5月12日からPython / Flaskを中心にWebアプリケーション開発を学んでいます。AIも開発支援として活用しています。

物流・飲食・販売の現場経験と、Webデザインで学んだ視線誘導・配色・情報設計を生かし、**利用者が迷わないUI、業務改善、ヒューマンエラー防止**につながる仕組みを考えています。実装して終わりではなく、第三者が実際に触れられる状態まで公開し、テストと実機確認を重ねることを大切にしています。

## 🚀 Tosane Works

**[Tosane Works](https://github.com/tosane932/tosane-works)** は、代表作品を分野別にまとめたポートフォリオリポジトリです。

- **[🥐 Bakery Hub — Store](https://github.com/tosane932/tosane-works/tree/main/store/bakery-hub)**: 売上分析から材料発注・店舗メモ・タスクまで扱う、ベーカリー向け業務支援Webアプリ（[Live Demo](https://bakery-salesdata.onrender.com/)）
- **[🕊 Puoppo — Information](https://github.com/tosane932/tosane-works/tree/main/information/puoppo)**: 公式RSSの記事を収集し、Gemini APIで要約・分析する情報収集Webアプリ（[Live Demo](https://puoppo.onrender.com/)）
- **[🚛 Driver Personality Test — Logistics](https://github.com/tosane932/tosane-works/tree/main/logistics/driver-personality-test)**: 物流現場の状況判断をもとに、安全運転の傾向を可視化する全50問の診断アプリ（[Live Demo](https://tosane932.github.io/tosane-works/logistics/driver-personality-test/)）

作品のスクリーンショット、技術構成、機能、設計判断は、Tosane Works内の各作品READMEへ集約しています。

## 🧰 Tech

- **Backend / Database**: Python, Flask, SQLAlchemy, Alembic, PostgreSQL, SQLite
- **Test / Delivery**: pytest, GitHub Actions, Docker, Gunicorn, Render
- **Frontend / API / Auth**: JavaScript, HTML, CSS, Gemini API, Flask-Login, Flask-WTF, Google OAuth
- **Other**: Ruby on Rails 8, Git / GitHub

## 🎯 Development Philosophy

> **老若男女、誰が見ても使いやすいアプリ**

- 曖昧な文言を避け、現在の状態と次の操作を画面へ表示する
- 色だけに頼らず、アイコンと具体的な言葉を組み合わせる
- ヒューマンエラーを注意力だけに任せず、UI・入力検証・権限分離で防ぐ
- pytestとCIを段階的に拡充し、DB migrationやセキュリティを含めて回帰確認する
- AIには作業範囲・禁止事項・停止条件を伝え、叩き台や調査に活用する。差分・影響範囲・テスト結果は人間が確認し、提案を無批判に採用しない
- 忙しい現場でも迷わず使えるかを実機で確かめ、実際に触れられる成果物として公開する

## 🚚 Background

- **大型・中型トラックドライバー（現役）**: 7年以上の物流経験を、安全確認・危険予知・誤操作防止の設計へ反映
- **百貨店催事**: 広島風お好み焼きの調理・実演販売、材料発注、売上管理、スタッフ採用・管理を経験
- **自動販売機補充**: 売上データをもとに、巡回ルート・積載量・商品構成・販促施策を設計
- **Webデザイン**: 視線誘導、配色、情報の優先順位をUI改善へ活用

業務を外から想像するのではなく、現場で迷ったこと、待ったこと、間違えやすかったことを、アプリの仕様へ落とし込むのが私の開発の出発点です。

## 📜 Qualifications

- ウェブデザイン技能士 3級
- 色彩検定 3級
- 情報処理技能検定（表計算）1級
- 日本語ワープロ検定 準1級
- MOS Excel 2007

## 💻 Development Environment

13年前のLenovo G580をSSD 256GB・メモリ16GBへ増強し、Lubuntu 24.04 LTSで開発しています。制約がある環境でも、原因を切り分けて代替案を試し、公開できるところまで進めています。

## ✍️ Writing

開発中に起きたエラー、原因、修正結果、再発防止策を、事実と推測を分けて記録しています。

- [Qiita：開発記録・エラー解決・検証結果](https://qiita.com/tosane932)
- [Zenn](https://zenn.dev/tosane932)
- [DEV Community：英語での技術記事](https://dev.to/tosane932)

## 📅 Development History

<details>
<summary><strong>主な開発履歴を見る</strong></summary>

<br>

- **2026/05/12** — Pythonを中心としたWebアプリケーション開発の学習を開始
- **2026/05/23** — GitHubでソースコード管理を始め、Python / Flaskによる初期作品を公開
- **2026/06/02** — Ruby on Rails 8のWebアプリをRenderへ公開し、クラウド環境の制約と代替策を検証
- **2026/06/24〜07/04** — Bakery Hubのデータ保存をPostgreSQLへ移行し、Docker化・Render公開まで実施
- **2026/07/06** — Driver Personality Testを開発し、全50問・5段階配点・出題順のランダム化を実装
- **2026/07/11** — pytestとGitHub Actionsを導入し、継続的な回帰確認を開始
- **2026/07/17** — PuoppoへGoogle OAuthとFlask-Loginを導入
- **2026/08/02** — Codexによるリポジトリ全体の静的レビューを行い、保存型XSSを修正
- **2026/08/19〜08/24** — Bakery HubへDataset基盤とGuest権限分離を段階的に導入
- **2026/09/07** — 期限・利用制限・データ分離を備えたGuest Demoを一般公開
- **2026/09/13〜09/26** — 材料発注・店舗メモ・タスクを追加し、スマートフォンの長押し・並び替えUXまで改善
- **2026/09/28** — 代表3作品をTosane Worksへ統合し、分野別に見られるポートフォリオへ再構成

詳しい変更履歴と設計判断は、[Tosane Works](https://github.com/tosane932/tosane-works)および[Qiita](https://qiita.com/tosane932)で公開しています。

</details>
