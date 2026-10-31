# Ailinna Zhangのプロジェクト紹介

データサイエンス、ソフトウェア開発、ビジネス分析に関する制作・研究内容をまとめています。各リポジトリに概要、実行方法、検証内容、制約を記載しています。

## 肺がん再発予測の機械学習研究

公開GEOデータの統合、複数モデルの比較、データセットをまたぐ検証、外部検証を扱った大学の研究プロジェクトです。将来の臨床判断支援を検討するShinyプラットフォームも公開しています。臨床利用が検証された医療製品ではありません。共同制作物の帰属は元資料に従います。

- コード: https://github.com/Ailinnastar/luad-recurrence-metastasis
- 分析レポート: https://ailinnastar.github.io/luad-recurrence-metastasis/

## TaskPilot: AIコミュニケーションプラットフォーム

ReactとNode.jsを用いたグループ共同作業向けアプリです。認証、リアルタイムチャット、招待制ワークスペース、タスク、投票、会議メモ、外部LLMを利用した要約機能を備えています。パスワードのハッシュ化とワークスペースへのアクセス確認を実装しています。エンドツーエンド暗号化を実装した製品ではありません。

- コード: https://github.com/Ailinnastar/security-enhanced-platform

## Virtual Scroll Access System（SOFT2412のチームプロジェクト）

Java 17による文書共有アプリです。アカウント管理、アップロード・ダウンロード、お気に入り、管理者機能、操作記録を備えています。A2-T13-88の共同制作物であり、単独開発ではありません。公開用コピーでは授業資料、非公開の議事録、既存の利用者データを除き、Docker起動方法と無料デモ用のデプロイ設定を追加しています。

- コード: https://github.com/Ailinnastar/virtual-scroll-access-system

## EC商品照合・価格比較デモ

元の商品照合コードから、商品コレクションの解析と候補スコアリングの関数を抽出しています。別途、商品名の正規化、要確認フラグ、通貨換算後の価格比較を架空データで確認できるデモを用意しています。元の業務用Excelや顧客向け資料は含みません。

- コード: https://github.com/Ailinnastar/ecommerce-analytics-demo

## League of Legendsデータ分析

データクリーニング、欠損値分析、予測、モデルの公平性を扱う分析サイトです。

- コード: https://github.com/Ailinnastar/LeagueOfLegends
- 分析サイト: https://ailinnastar.github.io/LeagueOfLegends/

GitHubプロフィール: https://github.com/Ailinnastar

## MRIにおける脂肪・水分分離

MATLABを用いて、複数エコーの信号モデル、脂肪・水分の曖昧性、複数初期値からの最適化、PDFF・R2*推定を扱う大学の画像解析プロジェクトです。公開内容はソースコードと合成信号の実験で、被験者スキャンやDICOMデータは含みません。

- コード: https://github.com/Ailinnastar/mri-fat-water-separation

## 自律迷路走行ロボット

赤外線センサーと連続回転サーボを用いたArduino C++の開発途中版です。元の作業履歴から復元したコードであり、最終提出版とは確認できていません。分岐処理と停止動作をホスト環境で確認するテストを付けています。実機での走行時間や最終版の機能を保証するものではありません。

- コード: https://github.com/Ailinnastar/autonomous-maze-robot

KPMG、Oliver Wymanを含む勤務先・顧客の機密情報は、この公開プロジェクト集に含めていません。

## タンパク質の細胞内局在予測

アミノ酸配列由来の特徴量と複数の分類器を組み合わせるバイオインフォマティクスの研究コードです。2025年の開発履歴から復元した版を公開し、入力検証、特徴量抽出、合成データでの予測を確認するテストを追加しています。元のデータセットや最終提出版は含まず、履歴書に記載した当時の精度を再現したという意味ではありません。前処理と交差検証に関する制約はREADMEに明記しています。

- コード: https://github.com/Ailinnastar/protein-subcellular-localization
