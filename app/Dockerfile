# 1. Go 1.22 のイメージを使用
FROM golang:1.22

# 2. 作業ディレクトリを指定
WORKDIR /app

# 3. ホストのファイルをコンテナにコピー（← これが抜けていました！）
COPY . .

# 4. 依存関係（モジュール）をダウンロード
RUN go mod download

# 5. コンテナ起動時にプログラムを実行
CMD ["go", "run", "main.go"]