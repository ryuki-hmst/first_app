# Book-Summaries DB設計
## usersテーブル
|Column|Type|Options|
|------|----|-------|
|nickname|string|null: false|
|email|string|null: false,unique: true|
|password|string|null: false|
### Association
-
-

## postsテーブル
|Column|Type|Options|
|------|----|-------|
|title|string|null: false|
|author|string|null: false|
|rate|float||