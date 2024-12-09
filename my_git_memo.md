## .gitフォルダを削除する
rm -fr .git

## 一部だけクローン
$ mkdir sparseSample

$ cd sparseSample

$ git init

$ git config core.sparsecheckout true

$ git remote add origin [URL]

$ echo "pg_test2.py" > git info sparse-checkout

## 使用中のブランチを確認
git branch

## mainブランチと比較
git diff main

