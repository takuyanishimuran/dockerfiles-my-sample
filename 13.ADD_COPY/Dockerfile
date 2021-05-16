# ベースイメージの設定
FROM ubuntu:16.04

# ADD でローカルファイル追加
ADD test.txt /docker_dir/

# ADD でリモートファイル追加
ADD http://www.wings.msn.to/index.php /docker_dir/web/

# COPY でファイル追加
COPY test.txt /docker_dir/texts/

# RUN
RUN echo hello
