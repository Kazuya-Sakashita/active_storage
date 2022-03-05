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

参考HP
https://qiita.com/hiroki_404_/items/e71991ac88421e5caeec

rails6でのupdate_attributesは非推奨となっているので、updatetとして編集。
記事の newする際の<%= f.text_field :title %>が間違いで:titleではなく:name
が正しい。記事最終段階では修正されている。
