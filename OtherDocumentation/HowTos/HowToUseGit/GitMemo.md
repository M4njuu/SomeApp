# Gitの使い方メモ（基本編）

## 環境構築

1. https://gitforwindows.org/ から、Gitをダウンロードする  
   ![alt text](images/GitMemoImages/GitHomePage.png)

2. git --version でインストールされたかを確認する  
   ![alt text](images/GitMemoImages/GitVersionCheck.png)  

3. https://github.com/ から、GitHubのアカウントを作成する  
   ![alt text](images/GitMemoImages/GitHubHomePage.png)

4. 以下のコマンドで、Gitのユーザ名とメールアドレスを設定する。  

   ```:ユーザ名の設定コマンド
   git config --global user.name "ユーザー名は任意"
   ```

   ```:メールアドレスの設定コマンド
   git config --global user.email "メールアドレス"
   ```

   ```:日本語ファイル名がエスケープされないようにする
   git config --global core.quotepath false
   ```

   ※すでに登録されているかどうかを確認するコマンドはこちら

   ```:ユーザ名の確認コマンド
   git config --global user.name
   ```

   ```:メールアドレスの確認コマンド
   git config --global user.email
   ```

5. sshキーを作成する(何のためになのかは今のところ不明)

   ```sshキーの作成
   ssh-keygen
   ```

## Gitの基本操作  

ローカルリポジトリの作成＆GitHubへのアップロードまで行う

1. リモートリポジトリを作成する  
   https://github.com/ へアクセスする
   ![alt text](images/GitMemoImages/GitHubMyPage.png)

2. Newを押す
   ![alt text](images/GitMemoImages/New.png)

3. ...or create a repository on the command line の部分をコピペする
   ![alt text](images/GitMemoImages/commands.png)

4. コピペしたものを流す
   ![alt text](images/GitMemoImages/beforeCommands.png)

5. 流した後は以下の通り
   ![alt text](images/GitMemoImages/afterCommands.png)

6. ![alt text](images/GitMemoImages/image.png)