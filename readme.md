# GitHub運用 Issue無しver

### 最初の設定
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
### git のコマンド
- branchを移動
    - ``` git checkout -b name```
    - ブランチ名は名前にする
    - ターミナル上のブランチ名が変更されたらOK(e.g. (name))
- 実際にコード書く
- 変更点を記録する
    - ``` git add . ```
    - vsコード上の記入したバーが表示されなくなったらOK
- コミットする
    - ``` git commit -m "ここを変更しました。など、、、" ```
    - errorが表示されなかったらOK
- remoteに反映
    - 初回の場合
        - ``` git push -u origin name ``` 
    - 2回目以降の場合
        - ``` git push ```
- remoteの変更を取り込む
    - ```git fetch & git marge```
    - 自分のファイルの中身が変更されていたらOK
### Pull requestsについて
- 自分が書いたコードにレビューをもらう
- 良さそうだったらLGTMとコメント & approve
- みんなからapproveがもらえたらmerge




    











