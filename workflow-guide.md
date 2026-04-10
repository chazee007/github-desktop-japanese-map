📘 GitHub Desktop 日本語マップ
完全作業手順書（あなた専用・再現性100%）

🟦 1. GitHub Desktop でリポジトリを作成
- GitHub Desktop を開く
- File → New Repository
- 入力する
- Name：github-desktop-japanese-map
- Local Path：任意
- README を作成：チェック
- Create Repository を押す

🟦 2. VSCode でリポジトリを開く
- GitHub Desktop の右側にある
Open in Visual Studio Code を押す
- VSCode が開く
- 左側にフォルダが表示されていなければ
Open Folder → github-desktop-japanese-map → Select Folder

🟦 3. README.md を編集して保存
- VSCode で README.md を開く
- 内容を編集
- Ctrl + S で保存

🟦 4. GitHub Desktop でコミット & プッシュ
- GitHub Desktop に戻る
- 左側に変更ファイルが表示される
- Summary に入力
Update README.md
- Commit to main
- 右上の Push origin

🟦 5. docs/translation/github-desktop/ を作成
VSCode 左側（Explorer）で：
- github-desktop-japanese-map を右クリック → New Folder
→ docs
- docs を右クリック → New Folder
→ translation
- translation を右クリック → New Folder
→ github-desktop

🟦 6. github-desktop-ja.md を作成
- github-desktop を右クリック → New File
→ github-desktop-ja.md
- テンプレートを貼り付ける
- 保存（Ctrl + S）

🟦 7. fields-guide/ を作成
- github-desktop を右クリック → New Folder
→ fields-guide

🟦 8. fields-guide の3ファイルを作成
- fields-guide を右クリック → New File
→ clone-screen.md
- 同じく
→ create-repo-screen.md
- 同じく
→ add-existing-screen.md

🟦 9. 3つのファイルにテンプレートを貼る
- clone-screen.md
- create-repo-screen.md
- add-existing-screen.md
それぞれにテンプレートを貼り付けて保存。

🟦 10. GitHub Desktop で最終コミット & プッシュ
- GitHub Desktop に戻る
- Summary に
Add fields-guide templates
- Commit to main
- Push origin

🟩 これで “完全に完成”
あなたが今日やった作業は、
この手順書をそのまま辿れば100%再現できる。

← [日本語マップに戻る](../github-desktop/github-desktop-ja.md)