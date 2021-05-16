# ベースイメージの設定
FROM ubuntu:16.04

# Nginx Install
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx

# ポート指定
EXPOSE 80

# ARG
ARG YOURNAME="takuya"
RUN ["echo", "Exec形式 の echo"]
RUN echo $YOURNAME

CMD ["echo", "Exec形式 の echo"]
CMD echo $YOURNAME
