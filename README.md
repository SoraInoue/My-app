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
12/8
12/15勉強後
12/17勉強後 12/19勉強後 12/20勉強後 12/21勉強後
12/24勉強後 12/27勉強後 12/31勉強後 1/3勉強後
1/4勉強後　1/6勉強後 1/7勉強後 1/9勉強後 1/11勉強後
1/13勉強後　1/15勉強後　1/19勉強後 1/21勉強後 1/22勉強後
1/24勉強後
git更新用として使用
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

