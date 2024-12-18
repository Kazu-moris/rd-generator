# rd-generator

要求定義文書（RD：Requirements Definition）から要件定義文書（RD：Requirements Document）を生成するためのツールです。生成AIによる支援を受けられます。

## 概要

本ツールは、要求定義文書の内容を解析し、以下の機能を提供します：

- 要求定義文書から要件定義文書のドラフトを自動生成
- 要件の抽出と構造化
- トレーサビリティの確保
- 要件の優先順位付け支援

左が入力画面で右が出力画面になる。
要件定義文書のサンプルをDocsに格納する
要件定義から、プロダクトバックログ、WBS、チーム編成、スケジュールを考えるのでそれを前提とした要件定義を作成する。

## 主な機能

1. 要求定義文書の取り込み
   - Word/Excel/PDFなどの一般的なフォーマットに対応
   - テキストベースの入力にも対応

2. 要件の自動抽出
   - 自然言語処理による要件の特定
   - 要件間の関連性の分析

3. 要件定義文書の生成
   - 標準テンプレートに基づいた文書生成
   - カスタマイズ可能な出力フォーマット
   - デフォルトの出力フォーマットはMarkdown

## 技術スタック

- フロントエンド
  - Next.js 14 (App Router)
  - TypeScript
  - Tailwind CSS
  - shadcn/ui

- バックエンド
  - Next.js API Routes
  - OpenAI API (GPT-4)

- データベース
  - Prisma
  - PostgreSQL

## インストール

1. リポジトリのクローン

## 使用方法

[使用方法の詳細を記載予定]

## ライセンス

[ライセンス情報を記載予定]