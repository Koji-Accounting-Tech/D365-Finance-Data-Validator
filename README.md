# D365 Finance Data Validator (Python/Pandas)

## 概要
Dynamics 365 Finance & Operations へのデータ移行を効率化するための検証ツールです。
会計コンサルタントの視点で、インポート前に発生しやすいデータの不備を自動検知します。

## 主な機能
- 貸借一致チェック（Debit/Credit balance check）
- 必須項目（勘定科目コード等）の欠損値チェック
- 二重入力の防止ロジック
- 列名の空白（スペース）自動クレンジング

## 開発の背景
Microsoftの面接フィードバックに基づき、技術課題を克服するために自力で構築しました。
