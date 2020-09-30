# README

＊Ancestryについて
カテゴリーツリーの作成時に使用

＊active_hashについて
画像の複数投稿で使用

*編集機能実装について

9/15
9/16
9/18 9/19
9/21
9/27 9/30
Ancestryのedit部分について
= f.collection_select :genre_id, Genre.roots, :id, :name, {prompt: "選択して下さい", selected: @item.genre&.root_id},{ class: 'sell-collection_select__input', id: 'genre-select', required: "required"}
Genre.rootsで呼び出し元を定義
selected: @item.genre&.root_idで呼び出すidを選択しておく
9/22
hamlとjsでの変数（数字）はカスタムデータを介してのやり取りでも可能
9/24

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

