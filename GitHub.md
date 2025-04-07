# GitHubの使い方ガイド

このリポジトリでは、GitHubの基本的な使い方についてまとめています。GitやGitHubを初めて使う方でも理解しやすいように、手順や用語をわかりやすく解説しています。

## 🔰 GitHubとは？

GitHubは、ソースコードをバージョン管理できる「Git」という仕組みを、インターネット上で使いやすく提供しているサービスです。  
複数人での開発や、コードのバックアップ、公開・共有に最適です。

## 📁 このリポジトリの内容

- GitとGitHubの違い
- GitHubのアカウント作成方法
- リポジトリの作成・クローン・プッシュのやり方
- Gitの基本操作（clone / add / commit / push / pull）
- Visual StudioやVS Codeとの連携
- よく使うコマンド一覧

## ✅ GitHubの基本操作

```bash
# リポジトリをクローン（PCにコピー）
git clone https://github.com/ユーザー名/リポジトリ名.git

# ファイルを変更・追加

# ステージング（変更をGitに伝える）
git add .

# コミット（変更内容を記録）
git commit -m "変更内容のメッセージ"

# GitHubにアップロード（反映）
git push origin main
