###　githubの環境構築について
- アカウントの追加
- cloneする
    - ```git clone https://github.com/hogehoge ```
    - リポジトリの中身が表示されたらOK
- 初期化する
    - ```git init ```
    - ターミナル上にbranch名が表示されればOK(e.g. main)
- remoteの設定
    - ```git remote add origin https://github.com/hogehoge ```
    - errorが表示されなければOK
### issuueの作成
- 題名に問題点
- 解決案の書き込み
- 以下、issueo00Nが作成されたとする
### git のコマンド
- branchを移動
    - ``` git checkout -b issue00N ```
    - ターミナル上のブランチ名が変更されたらOK(e.g. (issue00N))
- 実際にコード書く
- 変更点を記録する
    - ``` git add . ```
    - vsコード上の記入したバーが表示されなくなったらOK
- コミットする
    - ``` git commit -m "ここを変更しました。など、、、" ```
    - errorが表示されなかったらOK
- remoteに反映
    - 初回の場合
        - ``` git push -u origin issue00N ``` 
    - 2回目以降の場合
        - ``` git push ```
- remoteの変更を取り込む
    - ```git fetch & git marge```
    - 自分のファイルの中身が変更されていたらOK
### Pull requestsについて
- コメントにissue番号をつける
- 番号の付け方は ``` - #00N``` 
- 自分が書いたコードにレビューをもらう
- 良さそうだったらLGTMとコメント & approve
- みんなからapproveがもらえたらmerge




    








