---
marp: true
paginate: true
theme: sayyyyyy-theme
---

Marpで発表スライドを作ろう

---
自己紹介

せー
- フェンリル株式会社
- バックエンドメインのWebエンジニア
- 23卒

---

スライド何で作成していますか？

---
Marpとは

Markdownドキュメントを記述することでスライドに変換できるツール

---

このスライドもMarpで作成しています

---

作り方(今回はVSCodeの拡張機能を利用します)

---

1. VSCodeの拡張機能を入れる

これです↓
![marpの拡張機能画面](./images/vscode_extension_marp.png)

---

2. 先頭に以下の記述をする
```
---
marp: true
---
```

---

おわり！

---

プレビュー表示するとスライド形式で表示されます

---

その他にも

---

テーマの変更
```
---
marp: true
theme: 
---
```

---

ページ番号の追加
```
---
marp: true
paginate: true
---
```

---

自分でカスタマイズする

```
style: |
  section {
    background-color: gray;
    font-size: 40px;
  }
```

cssファイルとしても定義できます

---

`cmd + shift + p`でコマンドパレットを開いて`Marp: Export Slide Deck`を選択すると別ファイルとしてエクスポートできます

---

所感
- 軽い資料を作成するときはすごく便利
- gitで管理できる
- 凝った資料を作るのは大変
