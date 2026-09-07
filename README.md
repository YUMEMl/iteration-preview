# Iteration

Iterationは、ローカルLLMを使って会話・文章作成・プロジェクト開発を一つの画面で扱うためのアプリです。

> 現在は開発中です。このリポジトリでは紹介のみを公開しており、アプリ本体やソースコードはまだ配布していません。

## できること

- ローカルモデルとの会話
- 文章の作成・整理・翻訳
- 画像や資料を添付したやり取り
- モデル、応答言語、System Prompt、Context Lengthの設定
- プロジェクト内のファイル読取とコード検索
- 差分を確認してからのファイル変更
- Terminalを使ったビルドとテスト
- Git、LSP、MCP、Web情報を使った開発作業
- カスタムAgentや読取専用Agentによる並列調査

## 基本方針

Iterationは新しい基盤モデルではありません。利用者が選んだローカルモデルを、普段の会話から開発作業まで同じ流れで使うためのアプリです。

モデルの追加ダウンロード、ファイル変更、コマンド実行、外部ツールの利用は、それぞれ内容を確認してから行う設計にしています。

## 開発状況

現在はLinux向けのDesktop版とCLI版を開発・検証しています。不具合の修正や操作性の改善を進めている段階です。

Windows／macOS対応、配布方法、対応モデル、ライセンスなどの詳細は、公開準備ができた段階で案内します。

---

Iteration is a local-first assistant for conversation, writing, and project development.

It is currently under development. This repository is an introduction only; application downloads and source code are not publicly available yet.

Developed by [YUME](https://github.com/YUMEMl).
