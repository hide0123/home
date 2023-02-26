---
title: "Docsyで新規投稿する方法"
date: 2023-02-20T21:34:12+09:00
draft: false
---

# 前提条件

- [Hugo](https://gohugo.io/)がインストールされていること
- `npm ci`を実行して依存パッケージがインストールされていること

# 手順

1. `hugo new blog/ファイル名.md`を実行する
2. `content/ja/blog/ファイル名.md`のtitleを書き換える
3. 最終行に記事内容をMarkdown形式で書き込む
4. `hugo server -D`を実行し，対象のページにアクセスして表示を確認する
5. 問題がなければ，draftをfalseにした後コミットしてプッシュする