📘 GitHub Desktop 日本語操作マニュアル（保存版）
第1章　このマニュアルについて
本書は GitHub Desktop の操作を
日本語で体系的に理解できるようにまとめた操作マニュアル です。

目的：

GitHub Desktop の画面構造を理解する

後継者・家族が迷わず操作できるようにする

公開しても恥ずかしくない品質の資料を残す

長期保存できる資産として管理する

第2章　GitHub Desktop の基本構造
GitHub Desktop の画面は以下の 3 つで構成される。

2-1. Current Repository（現在のリポジトリ）
現在開いているリポジトリの情報

ブランチ切り替え

Fetch / Pull / Push

2-2. Changes（変更点）
変更されたファイル一覧

コミットメッセージ入力欄

コミット前の確認

2-3. History（履歴）
過去のコミット履歴

差分の確認

第3章　新規リポジトリの作成
File → New Repository

以下を入力

Name

Description

Initialize with README（チェック）

Create Repository

右上の Publish repository で GitHub に公開

第4章　既存リポジトリのクローン
File → Clone Repository

GitHub 上のリポジトリを選択

保存先フォルダを指定

Clone

第5章　VSCode での編集
GitHub Desktop → Open in Visual Studio Code

README.md や docs/*.md を編集

保存（Ctrl+S）

第6章　コミットとプッシュ
GitHub Desktop に戻る

左側に変更ファイルが表示される

Summary に変更内容を記述

Commit to main

Push origin

第7章　画面別ガイド
画面ごとの詳細な説明は以下のファイルに分割して管理する。

コード
fields-guide/
├─ clone-screen.md
├─ create-repo-screen.md
└─ add-existing-screen.md
各ファイルには以下を記載：

画面の意味

ボタンの説明

入力欄の役割

操作の流れ

注意点

第8章　よくある操作と注意点
8-1. Pull を忘れない
他の端末で更新がある場合、Pull しないとコンフリクトが発生する。

8-2. コミットメッセージは短く要点だけ
例：

“README 更新”

“docs: 画面別ガイド追加”

8-3. README は Web トップページとして整備
GitHub Pages のトップページとしても機能する。

8-4. PDF 版は docs/保存版 にまとめる
後継者が参照しやすいように PDF 版も保存する。

第9章　スクリーンショット挿入枠（後で追加）
PDF 化の際にスクショを挿入するための枠。

コード
【スクリーンショット挿入枠】
（ここに画像を貼る）
必要に応じて複数追加可能。

第10章　制作過程ログ
制作過程の詳細は以下に保存：

コード
制作過程（詳細時系列ログ）/制作過程.md
🎉 