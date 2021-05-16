# ベースイメージの設定
FROM ubuntu:16.04

# Nginx Install
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx

# ポート指定
EXPOSE 80

# デフォルトシェルの指定
SHELL ["/bin/bash", "-c"]

# RUN
RUN echo hello
