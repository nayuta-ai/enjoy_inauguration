# Development Procedure
## First
任意のディレクトリで以下のコードを実行
```
git clone https://github.com/nayuta-ai/enjoy_inauguration.git
cd enjoy_inauguration
git branch <任意のブランチ名>
git switch <任意のブランチ名>
```

## 変更内容をリモートリポジトリに反映させる
local環境で以下のコードを実行
```
git add .
git commit -m "修正内容"
```
リモートの変更を取得
```
git checkout main
git pull origin main
git checkout <任意のブランチ名>
git merge main
git push origin HEAD
```
Github内でプルリクエスト\\
緑の判定が出たらマージ
## リモート内容をローカルに反映
```
git checkout main
git pull orign main
git branch --delete <任意のブランチ名>
```
