# 問題の作り方

## 前提
このリポジトリをフォークし、フォーク先をローカルにクローンする。
作業はそのローカルリポジトリ上で行う。

`prob00`を完了している前提で話を進める。

## 方法
状況を見て`prob##`のように連番付きのディレクトリを作成する。

その中に`README.md`という名前のテキストファイルを作成し、そこに問題文を記述する。

また、サンプルプログラムやデータなどもディレクトリの中に入れておく。

これらの変更内容をoriginへpushする
```
git add .
git commit -m "prob##追加"
git pull nit master
git push origin master
```

Github上でPull Requestを投げる。

NIT-Anan-ProconのOwnerいずれかが内容を確認し、リクエストの許可をまつ。

許可されれば、変更がnitに取り込まれる。
