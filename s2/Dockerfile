# STEP:1  Ubuntu (ベースイメージ)
FROM ubuntu:latest

# STEP:2  Nginx のインストール
RUN apt-get update && apt-get install -y -q nginx

# STEP:3  ファイルコピー
COPY index.html /usr/share/nginx/html/

# STEP:4  Nginx の起動
CMD ["nginx", "-g", "damon off;"]
