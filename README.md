# eloquent-app-practice

## 概要

COACHTECH 教材 Tutorial 9-4「Eloquent ORM ハンズオン演習」で作成した成果物です。
Eloquent ORMを使って、ブログ投稿を管理するシステムを作成しました。
投稿の一覧表示・新規作成・編集・削除ができます。

## 使用技術

- PHP 8.x
- Laravel 10.x
- Eloquent ORM
- MySQL
- Laravel Sail
- Docker

## 学んだこと

- Eloquent ORMを使って、投稿データの取得・作成・更新・削除を行う方法を学びました。
- ControllerにCRUD処理を実装し、ルーティングと結びつける流れを学びました。
- Bladeを使って画面を作成し、フォームからデータを送信する流れを学びました。
- フォームから送信された値は、`$request->input('title')` のように `input()` メソッドを使って取得でき、入力値を取得していることがコード上でも明確になると学びました。

## 動作確認

Laravel Sailを起動し、ブラウザで以下のURLにアクセスします。

http://localhost/posts

以下の操作ができることを確認します。

- 投稿一覧の表示
- 新規投稿の作成
- 投稿の編集
- 投稿の削除
