お問い合わせフォーム

環境構築

Dockerビルド

１　git clone リンク

２　docker-compose up -d -build

※MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせて　docker-compose.ymlファイルを編集してください


laravel環境構築

１　docker-compose　exec php bash

２　composer install

３　evn.exampleファイルから.evnを作成し、環境変数を変更

４　php artisan key:generate

５　php artisan migrate

６　php artisan db:seed


使用技術

・php 8.0
・Laravel 10.0
・MySQL 8.0



URL

・開発環境： http://localhost/

・phpMyAdmin: http://localhost:8080/




