# 🟦 GitHub Desktop：新しいリポジトリ作成ガイド（New Repository）

GitHub Desktop で新しいリポジトリを作成するときの  
「どこに何を書くか」「どう入力するか」をまとめたガイド。

後継者が見ても理解できるように、  
入力例・注意点・スクショ枠を含めて構成している。

---

## 📷 画面スクショ
※ ここにあなたが撮ったスクショを貼る  
（GitHub Desktop → File → New Repository の画面）

---

![alt text](create-repo-screen-up.png)

![alt text](create-repo-screen-name.png)


## 📝 入力欄ガイド

### 1. **Name（リポジトリ名）**
- **意味**：プロジェクトの名前  
- **入力内容**：半角英数字（スペース不可）  
- **推奨形式**：`project-name`（ハイフン区切り）  
- **例**：  
  - `photo-organizer`  
  - `plant-database`  
  - `family-asset-system`

---

### 2. **Description（説明）**
- **意味**：プロジェクトの説明文  
- **入力内容**：日本語でOK  
- **例**：  
  - `植物写真を自動分類するツール`  
  - `家族資産管理システムのドキュメント`  
  - `GitHub Desktop の日本語マップ`

---

### 3. **Local Path（保存先フォルダ）**
- **意味**：PC 上の保存場所  
- **操作**：`Choose...` を押してフォルダを選ぶ  
- **推奨**：  
  - `C:/Users/charjee/Documents/GitHub/`  
  - `D:/Projects/`  
- **注意**：  
  - OneDrive 内は避ける（あなたの方針）  
  - 日本語フォルダ名は避けるとトラブルが少ない

---

### 4. **Initialize this repository with a README**
- **意味**：README.md を自動生成する  
- **推奨**：✔（チェックを入れる）  
- **理由**：  
  - GitHub 上で見やすくなる  
  - 後継者が理解しやすい  
  - 最初のコミットが作られる

---

### 5. **Git Ignore / License（任意）**
- **Git Ignore**：不要（後で追加可能）  
- **License**：不要（個人利用なら空でOK）

---

## 🟦 最後に押すボタン

### **Create Repository**
- **意味**：リポジトリを作成  
- **押すタイミング**：  
  - Name  
  - Local Path  
  - README  
  が設定できたら押す

---

## 🟦 作成後にやること（あなたの作業フロー）

1. GitHub Desktop 右上の **Open in VS Code** を押す  
2. VS Code で  
   - README.md  
   - 日本語マップ  
   - ガイド  
   を横に開く  
3. GitHub Desktop に戻って Commit → Push

---

## 🟦 注意点（あなた専用のメモ）

- OneDrive に保存しない（あなたの方針）  
- フォルダ名は英語に統一  
- README は必ず作る  
- 後継者が見ても理解できる構造にする  

---

## 📷 追加スクショ枠（必要に応じて）

### Name 入力欄のスクショ
（ここに貼る）

### Local Path のスクショ
（ここに貼る）

### README チェック欄のスクショ
（ここに貼る）

---

以上が **新しいリポジトリ作成画面の完全ガイド**。