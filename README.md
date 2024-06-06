VSCのターミナルで操作

1.　自分のPCに取り込む
  git clone codeからコピーしたURL

2.　サブブランチを作成する
　おそらく最初はmainブランチにいる。
　以下のコードでブランチを確認できる
  git branch

  アスタリスクが付いているのが、今いるブランチ
  
  以下のコードでサブブランチを作成
  git branch 任意のブランチ名

3. サブブランチに移動
   git checkout 異動するブランチ名

4. ソースを修正

5. 修正したソースをステージングエリアに登録

  git add .

6. コミット
   git commit -m "任意のメッセージ, ~を修正"

7. プルリクエスト
   git push origin master

   もしできない場合
   git push codeからコピーしたURL

8. GitHubで create pull requestに進む

VSC
9. サブブランチを削除
   git checkout master

   git branch -D 削除するブランチ名

10. GitHubの内容を自分のPCのメインブランチに反映
    git pull

11. 自分のPCで削除したサブブランチがGitHubに残っていれば削除
