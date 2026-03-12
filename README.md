# Javaレガシー移行向け GitHub Copilot 日本語テンプレート集

## 概要
このリポジトリは、Java 6 / 8 世代のレガシーシステムを Java 21 へ安全に移行するための、
GitHub Copilot 向け日本語テンプレート集です。

以下を含みます。
- リポジトリ全体のカスタムインストラクション
- 役割別 custom agents
- agent skills
- 調査、依存関係監査、試験検証のチェックリスト
- 日本語の運用テンプレート

## 想定用途
- レガシーJavaシステムの現状調査
- Java 21 への段階移行計画
- OSS / 依存ライブラリの互換性監査
- 安全な移行実装と試験
- GitHub Copilot を活用した協業品質の安定化

## ディレクトリ構成
- `.github/copilot-instructions.md`
- `.github/agents/`
- `.github/instructions/`
- `.copilot/skills/`

## 使い方
1. このリポジトリを対象案件の Git リポジトリへ取り込みます
2. `.github/copilot-instructions.md` を案件向けに調整します
3. `.github/agents/` の各 agent を用途に応じて選択します
4. `.copilot/skills/` のチェックリストとテンプレートを使って調査・検証を進めます

## 注意
- 社内情報や顧客情報は含めないでください
- 実案件へ適用する際は、対象システムの事情に応じて調整してください
