# GitHub Desktopで止まる人のための完全手順
― commitとpushが分からなくても迷わない操作マップ ―

GitHubは難しくない。  
止まる場所が決まっているだけ。

この資料は、その“詰まる地点”を先回りして潰した記録です。

---

## 🎯 このリポジトリの目的

このリポジトリは、  
GitHub Desktop の操作で「止まる人」をなくすために作られています。

- GitHub Desktop の UI を **日本語で体系化**する  
- 画面ごとの **入力フィールドの意味・使い方**を整理する  
- 新規メンバーや後継者が **迷わず使える業務資産**を作る  
- あなた自身が **将来見返しても理解できる知識体系**を残す  
- GitHub Desktop のアップデートに合わせて **継続的に更新できる構造**を作る  

※ 本資料は「どうやるか」ではなく  
**「どこで止まるか」を基準に構成されています**

---

## 👤 この資料が向いている人

- GitHubを触ろうとして止まったことがある  
- commitとpushの違いが分からない  
- 操作ミスが怖くて進めない  
- 一度やめてしまったが再挑戦したい  
- 後継者やチームメンバーに引き継ぎたい  

---

## ⚠️ よくあるミス（ここで止まる）

- commitせずに閉じる → 変更が消える  
- pushしていない → GitHubに反映されない  
- どのリポジトリか分からなくなる  
- ブランチを切らずに作業して混乱する  

---

## 📁 フォルダ構造


```
github-desktop-japanese-map/
├── README.md
├── docs/
│   ├── translation/
│   │   └── github-desktop/
│   │       ├── github-desktop-ja.md
│   │       └── fields-guide/
│   │           ├── clone-screen.md
│   │           ├── create-repo-screen.md
│   │           └── add-existing-screen.md
└── assets/
    └── screenshots/
```

### 各フォルダの役割

- **docs/translation/github-desktop/**  
  GitHub Desktop の UI 日本語マップ（全体）

- **docs/translation/github-desktop/fields-guide/**  
  画面ごとの入力フィールド辞書  
  - Clone  
  - Create new repository  
  - Add existing repository  

- **assets/screenshots/**  
  画面キャプチャを保存する場所  
  → Markdown と組み合わせて視覚的に理解しやすくする

---


---

## 🧭 このリポジトリの使い方

### 1. GitHub Desktop の全体を理解したい
→ `github-desktop-ja.md` を開く  
（UIの全体構造を把握）

---

### 2. 特定の画面の意味を知りたい
→ `fields-guide/` を確認  
（Clone / Create / Add existing）

---

### 3. 新しい画面を追加したい
1. `assets/screenshots/` に画像追加  
2. `fields-guide/` にMarkdown追加  
3. READMEにリンク追加（任意）

---

## 🛠️ 運用ルール（後継者向け）

- Markdownで記述（差分管理しやすい）  
- 画像は assets/screenshots に保存  
- ファイル名は英語で統一（UIと一致）  
- コミットメッセージは必ず記録  

例：  
`Add: clone-screen field descriptions`  
`Update: Japanese map for v3.4 UI`

---

## 🔄 今後の拡張予定

- GitHub Desktop のバージョン差分  
- よくあるエラーと対処法  
- GitHub Desktop → VS Code 連携  
- GitHub Flow / Pull Request 解説  
- 後継者向け「GitHub入門書」化  

---

## ✅ 作業終了前チェック（5秒）

☑ commitしたか？  
☑ pushしたか？  
☑ GitHub上で確認したか？  

---

## 👤 作成者メモ

このリポジトリは単なる解説ではなく、  
**「詰まらないための構造」そのものを記録した業務資産**です。

後継者が迷わず作業できることを最優先とし、  
継続的に更新していきます。