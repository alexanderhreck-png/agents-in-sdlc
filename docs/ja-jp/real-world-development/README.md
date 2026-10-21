---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更の計画、コードの作成、動作のテスト、プルリクエストのレビュー、エージェントを使った作業管理を、反復しながら進めます。

## シナリオ

あなたは、開発者をテーマにしたボードゲームのクラウドファンディングを提供する架空の会社、Tailspin Toys の新しい開発者です。チームのバックログは GitHub issue として登録済みなので、すぐに作業を始められます。フィルタリングやページネーションなどの機能開発に加え、アクセシビリティやコーディング規約などの品質改善も含まれています。

## 環境を選ぶ

GitHub Copilot は、どこで作業していても利用できます。自分の開発スタイルに合った環境を選んでください。各ワークショップには個別のセットアップがあり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、便利なスラッシュ コマンドを利用します。

### [GitHub Copilot アプリ][app]

エージェント セッションを並行して実行し、セッション モードを切り替え、Canvas で共同作業を行い、デスクトップ アプリで GitHub issue とプルリクエストを管理します。

### [GitHub Copilot クラウド エージェント][cloud]

GitHub issue を非同期エージェントに割り当てて作業を案内し、進捗を監視して、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを利用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
