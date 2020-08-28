# ハッカソン用のテストプログラム
## 実装機能
## 機能としてAPIを実装
### メモ
* 追加、一覧、詳細、編集、削除など  モデルはmemos scaffoldで作成  
memos_controller.rb
### ユーザー
* 追加、一覧、詳細、編集、削除など モデルはusers scaffoldで作成  
users_controller.rb
### ログイン機能
* ログインのみ　ログインが成功時にトークンを作成して、そのトークンを用いてユーザー判別  
login_controller.rb

## API使い方
https://rails-api-memo-test.herokuapp.com/users  
getリクエスト ユーザー一覧
https://rails-api-memo-test.herokuapp.com/login/lgin
postリクエスト ログイン機能 返り値 トークン値
https://rails-api-memo-test.herokuapp.com/memos  
getリクエスト ヘッダーにAuthorization でトークン値を付随してリクエスト

## カラム、パラメータ
ユーザー  {user:{ email:パラメータ,password: パラメータ}}  
メモ  {memo:{ test: パラメータ}}
