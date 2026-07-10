# Visual Studio Code インストールガイド

## はじめに

このガイドでは、Windows 11にVisual Studio Code（VS Code）をインストールし、正常に起動できる状態になるまでを説明します。

---

## VS Codeとは

Visual Studio Code（以下、VS Code）は、Microsoftが提供する無料のコードエディターです。

MulmoClaudeの開発やMarkdown編集にも利用します。

---

## インストール手順

### 1. VS Code公式サイトを開く

ブラウザーで次のページを開きます。

<https://code.visualstudio.com/>

![Visual Studio Code公式サイト](images/vscode-install-ja/vscode-home.png)

### 2. VS Code をダウンロード

「Download for Windows」をクリックします。

![VS Codeダウンロード](images/vscode-install-ja/vscode-download.png)

### 3. インストーラーを実行

ダウンロードしたインストーラーを起動します。

![VS Codeセットアップ開始](images/vscode-install-ja/vscode-installer.png)

基本的には、すべて既定（Next）のままで問題ありません。そのまま「Next」をクリックして進めてください。

### 4. インストールを開始

「Install」をクリックしてインストールを開始します。

![VS Codeインストール開始](images/vscode-install-ja/vscode-install.png)

### 5. インストール完了

インストールが完了したら「Finish」をクリックします。

VS Code が起動すればインストールは完了です。

![VS Codeインストール完了](images/vscode-install-ja/vscode-install-finish.png)

## この章の確認

PowerShell を開き、次のコマンドを実行します。

VS Code が正しくインストールされ、PATH が設定されていれば、バージョン番号が表示されます。

```powershell
code --version
```

バージョン番号が表示されれば成功です。

例

```text
1.106.0
```