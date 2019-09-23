## Laravelの学習メモ

### 階層について

#### app/Http/**Controllers**/

・Controllerクラスが入る

#### database

・接続するDBのファイル作成する。例）touch database.sqllite

#### database/migrations

・DBのバージョン管理する　
※　デフォルトを削除する

#### public

・CSS/JS/IMGの静的リソースを管理する

#### **resources**/view

・ビュー（画面テンプレート）を置く

####  **routes**

・どの URL にアクセスした時にどの処理を実行するかの設定

#### .env

・DBの接続情報を格納するファイル

#### conf

・全体の設定ファイル

・conf/app.phpで日本語設定にする

```php
'timezone' => 'Asia/Tokyo',
'locale' => 'ja',

```









