# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

# Ruby version
- Ruby 2.3.1
- Rails 5.2.1

# Database initialization
- MySQL

# How to run
以下のコマンドを実行してください。

```
git clone https://github.com/yoshitokamizato/beer_on_rails.git
```

ディレクトリに移動

```
cd beer_on_rails
```

データベースを作成

```
bundle exec rake db:create
```

# Check Remote branch
リモートのブランチ一覧を確認するには以下のコマンドを入力

```
git branch -a
```

リモートのブランチが確認できない場合

```
git fetch
```

ローカルでリモートブランチと同じブランチを作成しチェックアウトする

```
git checkout -b local_branch origin/remote_branch
```
