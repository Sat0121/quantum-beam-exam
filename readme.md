# 量子ビーム工学 試験解説サイト

このリポジトリは、量子ビーム工学の試験問題とその詳細な解説を提供するウェブサイトのソースコードを含んでいます。

## 概要

- 試験日: 2021年2月3日
- 対象分野: 量子ビーム工学
- 収録問題:
  - 問題2: BCC構造の回折に関する解析
  - 問題3: 結晶のサイズ効果に関する解析

## プロジェクト構造

```
quantum-beam-exam/
├── assets/
│   └── css/
│       └── styles.css
├── problems/
│   ├── problem2/
│   │   ├── index.html
│   │   ├── detailed.html
│   │   └── solutions.html
│   └── problem3/
│       ├── index.html
│       ├── detailed.html
│       └── solutions.html
├── index.html
└── README.md
```

## セットアップ手順

1. リポジトリのクローン:
   ```bash
   git clone https://github.com/yourusername/quantum-beam-exam.git
   cd quantum-beam-exam
   ```

2. ローカルでの確認:
   - ローカルのウェブサーバーでサイトを確認する場合:
     ```bash
     python -m http.server 8000
     ```
   - ブラウザで `http://localhost:8000` にアクセス

## デプロイ

このプロジェクトはGitHub Pagesを使用して自動デプロイされます。

1. GitHub Pagesの設定:
   - リポジトリの Settings > Pages で、ソースを `gh-pages` ブランチに設定
   - GitHub Actionsによって自動的にデプロイされます

2. デプロイの確認:
   - `https://yourusername.github.io/quantum-beam-exam/` でサイトを確認

## コントリビューション

1. このリポジトリをフォーク
2. 新しいブランチを作成 (`git checkout -b feature/improvement`)
3. 変更をコミット (`git commit -am 'Add new content'`)
4. ブランチをプッシュ (`git push origin feature/improvement`)
5. Pull Requestを作成

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。