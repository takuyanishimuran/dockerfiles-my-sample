# ベースイメージの設定
FROM ubuntu:16.04

# Nginx Install
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx

# ポート指定
EXPOSE 80

# ユーザ追加
LABEL maintainer "takuya nishimura<takuya.nishimura@mail>"
LABEL title="WebAPI"
LABEL version="1.0"
LABEL description="for Label check"
