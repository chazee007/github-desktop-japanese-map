# 📘 GitHub Desktop 日本語マップ  
GitHub Desktop の画面構造・用語・入力フィールドを体系的に整理した日本語マップです。  
このリポジトリは、**GitHub Desktop を業務で使う人が迷わないための辞書**として機能します。

---

## 🎯 このリポジトリの目的

- GitHub Desktop の UI を **日本語で体系化**する  
- 画面ごとの **入力フィールドの意味・使い方**を整理する  
- 新規メンバーや後継者が **迷わず使える業務資産**を作る  
- あなた自身が **将来見返しても理解できる知識体系**を残す  
- GitHub Desktop のアップデートに合わせて **継続的に更新できる構造**を作る

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

## 🧭 このリポジトリの使い方

### 1. **GitHub Desktop の画面を確認したいとき**
`github-desktop-ja.md` を開く  
→ 全体の UI マップを確認できる

### 2. **特定の画面の入力項目を知りたいとき**
`fields-guide/` の各ファイルを見る  
→ Clone / Create / Add existing の意味がすぐ分かる

### 3. **新しい画面を追加したいとき**
1. `assets/screenshots/` に画像を追加  
2. `fields-guide/` に Markdown を追加  
3. README にリンクを追加（任意）

---

## 🛠️ 運用ルール（後継者向け）

- **原則として Markdown で記述する**  
  → GitHub 上で読みやすく、差分管理がしやすい

- **画像は assets/screenshots に保存する**  
  → 画像の散乱を防ぐ

- **画面ごとのファイル名は英語で統一**  
  → GitHub Desktop の UI と対応させるため

- **更新時は必ずコミットメッセージに内容を書く**  
  例：  
  `Add: clone-screen field descriptions`  
  `Update: Japanese map for v3.4 UI`

---

## 🔄 今後の拡張予定

- GitHub Desktop のバージョンごとの差分管理  
- よくあるエラーと対処法  
- GitHub Desktop → VS Code の連携ガイド  
- GitHub Flow / Pull Request の日本語マップ  
- 家族・後継者向けの「GitHub 入門書」化

---

## 👤 作成者メモ（あなた自身のための欄）

- このリポジトリは **業務資産**として長期運用する  
- GitHub Desktop の UI を体系化し、  
  **誰が見ても理解できる知識体系**を作ることが目的  
- 画面キャプチャは随時追加してよい  
- Markdown は VS Code で編集すると効率が良い

---

# ✅ README.md 完成  
この内容をそのまま **README.md に貼り付けてコミット**すれば、  
あなたのリポジトリは「資産」としての形が整う。
