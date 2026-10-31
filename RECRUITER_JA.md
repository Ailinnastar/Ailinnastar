# Ailinna Zhangのプロジェクト紹介

データサイエンス、ソフトウェア開発、ビジネス分析を通じて、データを理解し、意思決定に役立つ形へつなげています。研究からアプリ開発まで、8つのプロジェクトをご紹介します。

## 肺がん再発予測の機械学習研究

公開GEOデータを統合し、7種類のモデリング手法を比較した大学の共同研究です。データセットをまたぐ評価と外部検証に取り組み、年齢・病期・15遺伝子のスコアを入力できるShinyプラットフォームを構築しました。将来の臨床判断支援を見据え、研究結果を操作しながら理解できる形にまとめています。

- コード: https://github.com/Ailinnastar/luad-recurrence-metastasis
- 分析レポート: https://ailinnastar.github.io/luad-recurrence-metastasis/
- 研究プラットフォーム: https://elenna-shine-shiny.shinyapps.io/shiny_recurrence_app/

## TaskPilot: AIコミュニケーションプラットフォーム

ReactとNode.jsを用いたグループ共同作業向けアプリです。リアルタイムチャット、招待制ワークスペース、タスク・期限管理、投票、会議メモを一つにまとめています。OpenAI・Anthropic・Geminiの3つのAIプロバイダーに対応し、APIキーを設定すると会議の要約やタスク抽出を利用できます。パスワード認証、参加権限の確認、WebSocket通信、再起動後のデータ読み出しを自動テストで確認しています。

- アプリ: https://ailinna-taskpilot-demo.onrender.com/
- コード: https://github.com/Ailinnastar/security-enhanced-platform

## Virtual Scroll Access System

Java 17を用いて4人で開発した、SOFT2412/COMP9412の文書共有アプリです。文書の閲覧・アップロード・ダウンロード、お気に入り、プロフィール、管理者機能、操作記録を備えています。私は文書共有機能、管理者向けの機能・統計、操作ログ、スクラムの進行を担当しました。公開版にはDockerによる起動環境と61件のJavaScriptテストを整備しています。

- アプリ: https://ailinna-vsas-demo.onrender.com/
- コード: https://github.com/Ailinnastar/virtual-scroll-access-system

## EC商品照合・価格比較デモ

多言語の商品名を正規化し、候補商品の照合スコアと通貨換算後の価格を比較するPythonプロジェクトです。実際に取り組んだ商品照合の関数と、架空の商品データで試せる再現可能なデモを公開しています。

- コード: https://github.com/Ailinnastar/ecommerce-analytics-demo

## League of Legendsデータ分析

128,064件の元データと22のパッチを対象に、プロの試合におけるチャンピオン選択と勝敗の関係を分析しました。データクリーニング、欠損値の検討、予測モデル、公平性の評価までの流れを、インタラクティブな分析サイトにまとめています。

- コード: https://github.com/Ailinnastar/LeagueOfLegends
- 分析サイト: https://ailinnastar.github.io/LeagueOfLegends/

GitHubプロフィール: https://github.com/Ailinnastar

## MRIにおける脂肪・水分分離

MATLABを用いた画像解析プロジェクトです。複数エコーの信号モデルと複数初期値からの最適化を組み合わせ、脂肪率を表すPDFFとR2*を推定します。合成信号による実験と自動シミュレーションを通じて、推定の安定性を検討しています。

- コード: https://github.com/Ailinnastar/mri-fat-water-separation

## 自律迷路走行ロボット

3系統の赤外線センシングと2つの連続回転サーボを用いたArduino C++の開発プロジェクトです。通路のセンタリング、分岐での旋回、行き止まりからの方向転換、停止処理を組み合わせ、制御ロジックをホスト環境のテストでも確認しています。

- コード: https://github.com/Ailinnastar/autonomous-maze-robot

## タンパク質の細胞内局在予測

アミノ酸配列から特徴量を抽出し、複数の分類器を組み合わせて5種類の細胞内局在を予測する研究コードです。開発時のコードを整理し、入力検証、特徴量抽出、合成データによる予測の自動テストを整備しています。

- コード: https://github.com/Ailinnastar/protein-subcellular-localization
