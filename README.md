# gh-detail
Githubのユーザー情報を取得するプロジェクトです。

## 使い方
1. `gh-detail`をクローンします。
2.  githubのPersonal Access Tokenを作成します。
3. .envファイルを作成し、以下の内容を記述します。
```
GITHUB_TOKEN=github_pat_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```
4. ターミナルで以下のコマンドを実行します。
```
npm install
npm run build
npm start
```