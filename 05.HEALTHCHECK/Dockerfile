# ベースイメージの設定
FROM ubuntu

# Nginx Install
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install nginx

# ポート指定
EXPOSE 80

# Nginx 実行
CMD ["nginx", "-g", "daemon off;"]
