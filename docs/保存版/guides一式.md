# GitHub Desktop 操作ガイド 一式（保存版）

このPDFは、GitHub Desktop の基本操作5つを  
「推奨の読み順」で1冊にまとめた保存版です。

<div style="page-break-after: always;"></div>

## 1. 新規リポジトリ作成  
GitHub Desktop を使い始める最初のステップです。  
ここを理解すると後の操作がスムーズになります。

## 📷 画面スクショ  
<img src="create-repo-screen-up-1.png" width="600">

<div style="page-break-after: always;"></div>

## 入力欄ガイド

### 1. **Name（リポジトリ名）**
- **意味**：プロジェクトの名前  
- **入力内容**：半角英数字（スペース不可）  
- **推奨形式**：`project-name`（ハイフン区切り）  
- **例**：  
  - photo-organizer  
  - plant-database  
  - family-asset-system  

### 2. **Description（説明）**
- **意味**：プロジェクトの説明文  
- **入力内容**：日本語でOK  
- **例**：  
  - 植物写真を自動分類するツール  
  - 家族資産管理システムのドキュメント  
  - GitHub Desktop の日本語マップ  

### 3. **Local Path（保存先フォルダ）**
- **意味**：PC上の保存場所  
- **操作**：「Choose…」を押してフォルダを選ぶ  
- **推奨**：  
  - C:/Users/charjee/Documents/GitHub/  
  - D:/Projects/  
- **注意**：  
  - OneDrive 内は避ける  
  - 日本語フォルダ名は避ける  

### 4. **Initialize this repository with a README**
- **意味**：README.md を自動生成  
- **推奨**：チェックを入れる（必須）  
- **理由**：  
  - GitHub 上で見やすい  
  - 後継者が理解しやすい  
  - 最初のコミットが作られる  

### 5. **Git Ignore / License（任意）**
- Git Ignore：不要（後で追加可能）  
- License：不要（個人利用なら空でOK）  

## ▶ 最後に押すボタン

### **Create Repository**
- **意味**：リポジトリを作成  
- **押すタイミング**：  
  - Name  
  - Local Path  
  - README  
  が設定できたら押す  

## 作成後にやること（あなたの作業フロー）
1. GitHub Desktop 右上の **Open in VS Code** を押す  
2. VS Code で以下を開く：  
   - README.md  
   - 日本語マップ  
   - ガイド  
3. GitHub Desktop に戻って Commit → Push  

## 注意点（あなた専用メモ）
- OneDrive に保存しない  
- フォルダ名は英語に統一  
- README は必ず作る  
- 後継者が見ても理解できる構造にする  
- プロジェクトごとにフォルダを分ける  

## 追加スクショ枠
- Name 入力欄のスクショ  
- Local Path のスクショ  
- README チェック欄のスクショ  

<div style="page-break-after: always;"></div>

## 2. リポジトリのクローン（clone-guide）

この操作で止まる人が一番多いポイントです。  
ここを越えれば次に進めます。

GitHub 上の既存リポジトリを  
あなたのPCにコピー（クローン）する手順をまとめたガイド。

## 📷 画面スクショ  
<img src="Clone Repository-up-1.png" width="600">

## 入力欄ガイド

### 1. **URL（Repository URL）**
- **意味**：クローンしたい GitHub リポジトリのURL  
- **入力内容**：GitHub の「Code」ボタンからコピー  
- **例**：  
  - https://github.com/charjee/photo-organizer.git  
  - https://github.com/charjee/github-desktop-japanese-manual.git  

### 2. **Local Path（保存先フォルダ）**
- **意味**：PC上の保存場所  
- **操作**：「Choose…」で選択  
- **推奨**：  
  - C:/Users/charjee/Documents/GitHub/  
  - D:/Projects/  
- **注意**：  
  - OneDrive 内は避ける  
  - 日本語フォルダ名は避ける  

### 3. **Clone ボタン**
- **意味**：クローン開始  
- **押すタイミング**：  
  - URL  
  - Local Path  
  が設定できたら押す  

## クローン後にやること（あなたの作業フロー）
1. GitHub Desktop が自動で読み込む  
2. 右上の **Open in VS Code** を押す  
3. VS Code で README や資料を確認  
4. 編集したら Commit → Push  

## 注意点（あなた専用メモ）
- URL は必ず `.git` で終わる  
- 保存先は OneDrive を避ける  
- フォルダ名は英語に統一  
- クローン後は VS Code を横に置くと楽  

## 追加スクショ枠
- URL 入力欄  
- Local Path  
- Clone ボタン  

<div style="page-break-after: always;"></div>

## 3. コミットの基本操作（commit-guide）

commit と push の違いが分からないと  
「保存したのに反映されない」状態になります。

## 📷 画面スクショ  
<img src="commit-guide -copy.png" width="550">
<div style="page-break-after: always;"></div>

## コミットとは？
- 変更を記録する操作  
- GitHub に送る前の “下書き保存”  
- コミットしないと Push できない  
- 後継者が変更内容を追跡できる  

## コミットの流れ（基本操作）

1. 変更されたファイルを確認  
2. Summary（必須）を入力  
3. Description（任意）  
4. **Commit to main** を押す  

## コミット後にやること（Push）
1. 左上に **Push origin** が表示される  
2. Push origin をクリック  
3. GitHub に変更が送信される  

## 注意点（あなた専用メモ）
- Summary は必ず書く  
- 1コミット＝1目的  
- コミット → Push の順番  
- オフライン時はコミットだけして後でPush  

## 追加スクショ枠
- Summary 入力欄  
- Commit to main  
- Push origin  

<div style="page-break-after: always;"></div>

## 4. Push 操作（push-guide）

commit だけでは GitHub に反映されません。  
Push が必要です。

## 📷 画面スクショ  
<img src="push-guide.md-pushu_orgin.png" width="600">

## Push の基本
- PCでコミットした変更を GitHub に送る操作  
- コミット後に自動で Push ボタンが出る  

## Push の流れ
1. コミット後、左上に **Push origin** が表示  
2. Push origin をクリック  
3. 数秒で完了  
4. 完了後は **Fetch origin** に戻る  

## Push が必要なタイミング
- コミットしたあと  
- 新しいファイルを追加したあと  
- README を更新したあと  
- ガイドを追加したあと  
- 翻訳ファイルを編集したあと  

## 注意点（あなた専用メモ）
- Push しないと GitHub 上に反映されない  
- Push し忘れると後継者が最新を見れない  
- オフライン時は後でまとめてOK  
- Push は何回しても安全  

## 追加スクショ枠
- Push origin  
- Fetch origin  

<div style="page-break-after: always;"></div>

## 5. ブランチ操作（branch-guide）

ブランチは「作業用の別ライン」。  
main を壊さずに作業したいときに使う。

## 📷 画面スクショ  
<img src="Current Branch-Tab.png" width="600">

## ブランチとは？
- main を壊さずに作業するための別ライン  
- 大きな変更やテストに使う  
- 完成したら main にマージ  

## ブランチの基本操作

### 1. 新しいブランチを作る
1. Current Branch  
2. New Branch  
3. 名前を入力  
4. Create Branch  

### 2. ブランチを切り替える
1. Current Branch  
2. 一覧から選ぶ  

### 3. main に戻る
1. Current Branch  
2. main を選ぶ  

## ブランチを使うタイミング
- 大きな変更を試すとき  
- 本番に影響を出したくないとき  
- 他の人と同時に作業するとき  
- 新しい機能を試すとき  

## 注意点（あなた専用メモ）
- ブランチは main から作る  
- main に戻らず作業すると混乱  
- ブランチ名は英語で短く  

## 追加スクショ枠
- Current Branch  
- New Branch  
- ブランチ一覧  

<div style="page-break-after: always;"></div>

# 📘 完了  
以上が **GitHub Desktop 操作ガイド 一式（保存版）** の完全整形版です。

🔙 戻る  

# 🔙 戻る（GitHub Desktop 日本語マップへ）
https://github.com/charjee/github-desktop-japanese-map/tree/main/docs/translation/github-desktop
