# ecsite












# DB

## usersテーブル

|Column|Type|Options|
|------|----|-------|
|id|int|null: false|
|name|string|null: false|
|email|string|null: false, unique: true|
|password|string|null: false|
|remember_token|string|null: false|
|created_at|timestamp|null: false|
|updated_at|timestamp|null: false|

## itemテーブル

|Column|Type|Options|
|------|----|-------|
|id|int|null: false|
|name|string|null: false|
|amount|int|null: false|
|created_at|timestamp|null: false|
|updated_at|timestamp|null: false|

## cartテーブル

|Column|Type|Options|
|------|----|-------|
|id|int|null: false|
|user_id|int|null: false|
|item_id|int|null: false|
|quantity|int|null: false|
|created_at|timestamp|null: false|
|updated_at|timestamp|null: false|


