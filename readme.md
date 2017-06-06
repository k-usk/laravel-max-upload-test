# Heroku x Laravelで `upload_max_filesize` を変更するサンプル

* Laravelであることは特に関係がない
* `public`以下に、 `.user.ini` ファイルを設置しその中でPHPの設定を記述

記述内容

```
upload_max_filesize = 6M
```

（Heroku環境は削除済み)

## 環境

* Heroku
* Laravel 5.4
* PHP 7.1.3
