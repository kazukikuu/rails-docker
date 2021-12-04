# README
作成されたファイルをコンテナ内に取り込むため build を実行
$ docker-compose build

コンテナの起動
$ docker-compose up -d

データベースの作成
$ docker-compose run web bundle exec rails db:create

アクセス
localhost:3000

コンテナの停止
$ docker-compose down
