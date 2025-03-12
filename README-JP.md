# GitHub Copilotワークショップを活用したマルチエージェントアプリケーション開発

このリポジトリは、GitHub Copilotを使用したマルチエージェントアプリケーション開発のためのワークショップを提供します。

## 説明

このワークショップでは、マルチエージェントシステムの基本概念と、GitHub Copilotを使用して効率的に構築する方法を学びます。

## ワークショップシナリオ

### 1. アプリケーション概要の分析

このアプリケーションに不慣れな場合でも、GitHub Copilotがこのアプリケーションのワークスペースを説明できます。GitHub Copilot Chatを使用して、このプロジェクトの概要を確認しましょう。

- ヒント: **スラッシュコマンド**、**チャット変数**、**チャット参加者**を使用する。
  - [GitHub Copilot Chatチートシート](https://docs.github.com/en/copilot/using-github-copilot/copilot-chat/github-copilot-chat-cheat-sheet)

### 2. このアプリケーションが使用するツールと製品の分析

デプロイ先のAzureに不慣れな場合、このアプリケーションが使用するツールと製品を調査します。そして、Copilot Editsを使用してその結果のドキュメントを作成します。

- ヒント: **GitHub Copilot Edits**を使用する
  - [GitHub Copilot Edits](https://code.visualstudio.com/docs/copilot/copilot-edits#_use-edit-mode)

### 3. 特定の項目の探索

`app`フォルダなどの特定の項目に興味がある場合は、そのような特定の項目を**Working Set**にドラッグ＆ドロップして、Copilot ChatやEditsを試してみましょう。

- ヒント: **Working Set**を使用する
  - [Working Set](https://code.visualstudio.com/blogs/2024/11/12/introducing-copilot-edits#_stay-in-control)

### 4. アプリケーションのフローチャートの作成

このアプリケーションにまだ不慣れな場合、コンポーネントのワークフローとそれらの相互作用を理解したいかもしれません。GitHub Copilot Agentモードを使用して、このアプリケーションのフロントエンドとバックエンド部分の全体的なフローチャートを分析し、ファイルに出力します。

- ヒント: **GitHub Copilot Agentモード**を使用する
  - [GitHub Copilot Agentモードのドキュメント](https://code.visualstudio.com/docs/copilot/copilot-edits#_use-agent-mode-preview)

### 5. 様々な図の作成

GitHub Copilotでアプリケーションを分析できることがわかりました。また、GitHub Copilot Agentモードで図を作成できます。
次に、システムのさまざまな側面を視覚化し、アプリケーションの相互作用と静的アーキテクチャの理解を深めるために、他の図を作成してみましょう。

- ヒント: **Mermaid表記**を使用する
  - [Mermaidガイド](https://mermaid.js.org/intro/getting-started.html)

### 6. Azureへのデプロイ方法の発見

アプリケーションのアーキテクチャと機能を理解しました。そして、Azureへのデプロイ方法に興味があります。GitHub Copilotを使用して、このアプリケーションをAzureにデプロイする方法を発見してみましょう。

### 7. Azureへのデプロイ

デプロイに必要な知識とツールを手に入れました。アプリケーションをAzureにデプロイする時が来ました。

### 8. Azureの体験

アプリケーションをAzureに正常にデプロイしたら、プラットフォームを探索し、その様々な機能を活用してアプリケーションを強化する時間を取りましょう。監視、スケーリングオプション、サーバーレス機能の統合などを検討して、Azureの機能を最大限に活用しましょう。また、Azureのセキュリティ機能とベストプラクティスに慣れて、アプリケーションが堅牢で安全であることを確認しましょう。

### 9. GitHub Copilotを使用したアプリケーションのカスタマイズ

GitHubとAzureの基本を理解したところで、GitHub Copilotを使ってアプリケーションをどのようにカスタマイズするかを検討しましょう。

## 必要条件

* Azure サブスクリプション
* [Azure CLI (az)](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Azure Developer CLI (azd)](https://aka.ms/azure-dev/install)
* [Git](https://git-scm.com/downloads)
* [GitHub アカウント](https://github.com/)

オプション:
* [Docker](https://docs.docker.com/get-docker/) インストール済み
* [Java 17](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-17)
* [Maven 3.8.x](https://maven.apache.org/download.cgi)
* [Node.js](https://nodejs.org/en/download/)

Windows ユーザー向け:
* [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install) - Windows上でLinux GUIアプリケーションを実行するため。
または
* [Powershell 7+ (pwsh)](https://github.com/powershell/powershell) - スクリプトの実行やシステム構成の管理のため。
  * **重要**: PowerShellコマンドから`pwsh.exe`を実行できることを確認してください。これが失敗する場合は、PowerShellのアップグレードが必要かもしれません。

## 使用方法

## インストール

## 参考文献

## ライセンス

[MITライセンス](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/f3ac65a05ed8c8ea70b653875ccac0c6dbc10ba1/LICENSE)のもとで公開

## 著者

- github: <https://github.com/shinyay>
- twitter: <https://twitter.com/yanashin18618>
- mastodon: <https://mastodon.social/@yanashin>
