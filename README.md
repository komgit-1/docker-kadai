# Docker Webアプリ開発環境（Go + MySQL）
本リポジトリは、GoとMySQLを用いたWebアプリの開発環境です。
Docker Composeを使い、コマンド1つで開発環境を起動できます。

## 起動手順

1. リポジトリをクローンします。

2. .env.exampleをコピーして.envを作成し、データベースのパスワードを設定します。

3. 以下のコマンドを実行し、開発環境を起動します。
   
   docker compose up --build -d

4. ブラウザで http://localhost:8080 にアクセスし、画面が表示されれば起動完了です。