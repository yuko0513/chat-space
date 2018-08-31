# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
## membersテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|

## membersテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|

### Association
- belongs_to :group
- belongs_to :user
<<<<<<< HEAD


=======
>>>>>>> origin/chat-space-ブランチ
## messageテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|
<<<<<<< HEAD
|text|t.string :text|null: false|
|images| t.string :name|t.binary :data|null: false|
=======
>>>>>>> origin/chat-space-ブランチ

### Association
- belongs_to :group
- belongs_to :user

<<<<<<< HEAD
## usersテーブル
=======
##passwordテーブル
>>>>>>> origin/chat-space-ブランチ

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
<<<<<<< HEAD
|telephonenumber|integer|null: false, foreign_key: true|
|adress|t.string :|null: false, foreign_key: true|
|password|t.string :passworld|null: false|
=======
>>>>>>> origin/chat-space-ブランチ

### Association
- belongs_to :user


##groupテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|
<<<<<<< HEAD
|group_name|t.string :name|null: false, foreign_key: true|
=======
>>>>>>> origin/chat-space-ブランチ


### Association
- belongs_ many :group
- belongs_many :users
