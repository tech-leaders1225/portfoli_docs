# ポートフォリオをローカルで環境構築する



# 手順

1. ローカルにエディタをインストール（今回はvscode使用）
2. ローカルにruby環境を構築
3. ローカルにrails環境を構築
4. gitが使えるようにする
5. `git clone`
6. `rails db:setup`
7. `rails s` これでサーバーが起動したらOK！



## 1. ローカルにエディタをインストール

- VScodeのインストールURL：https://code.visualstudio.com/

## 2.3.ローカルにruby、rails環境を構築

- 参考資料：https://qiita.com/mylevel/items/8e0d91f625e1daa8720b



## 4.gitが使えるようにする

- 参考資料：https://techacademy.jp/magazine/5304

## 5.`gitclone`

- https://github.com/tech-leaders1225/attendance_app  このリポジトリを自分のリポジトリにforkする
- forkしたリポジトリを`git clone`する
- portfolioというブランチをローカルにcheckoutする

## 6.rails db:setup

- 続いてアプリのセッティング
- `bundle install`
- `rails db:setup`

## 7.`rails s`

- `rails s`これで、pumaが起動する



