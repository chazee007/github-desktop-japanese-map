Add Existing Repository 画面ガイド（Screen Guide）
このページでは GitHub Desktop の「Add Existing Repository」画面 について、
画面構造・入力欄の意味・操作の流れを日本語で整理しています。

🖼 スクリーンショット（全体）
【スクリーンショット挿入枠】
![alt text](<Add Local Repository-up-4.png>)

📌 1. この画面の目的
すでにローカルに存在する Git リポジトリを GitHub Desktop に登録する

他のツールで作成した Git リポジトリを取り込む

クローン済みのプロジェクトを GitHub Desktop で管理できるようにする

後継者が迷いやすいポイント：

「Add Existing」は“ローカルにすでにあるものを登録する”操作

Clone や Create と役割がまったく違う

.git フォルダがないと登録できない

🧩 2. 画面構造（番号つき）
【番号つきスクショ挿入枠】
![alt text](<Add Local Repository-Local Path-3.png>)

● ① Local Path（フォルダ選択）
既存リポジトリのフォルダを指定する欄。

● ② Choose…（フォルダ選択ダイアログ）
ローカルのフォルダを選択する。

● ③ Add Repository ボタン
指定したフォルダを GitHub Desktop に登録する。

🛠 3. 操作手順（Step-by-Step）
GitHub Desktop を開く

File → Add Local Repository を選択

Local Path（フォルダ）を指定

.git フォルダが存在することを確認

Add Repository をクリック

GitHub Desktop に登録され、管理できるようになる

⚠️ 4. よくあるミス・注意点
.git フォルダがないと「これは Git リポジトリではありません」と表示される

間違った階層のフォルダを選ぶと認識されない

Clone と Add Existing を混同しやすい

📎 5. 関連ガイド
- [Clone Screen](clone-screen.md)
- [Create Repository Screen](create-repo-screen.md)


🔙 戻る
[← トップページに戻る](../README.md)
