# ベースイメージの設定
FROM ubuntu:16.04

# Nginx Install
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx

# ポート指定
EXPOSE 80

# ユーザ追加
RUN ["adduser", "takuya"]

RUN ["whoami"]

# ユーザを指定してコマンド実行
USER takuya
RUN ["whoami"]
