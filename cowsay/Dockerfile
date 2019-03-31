#FROM命令は使用するベースイメージを設定
FROM debian

RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT [ "/entrypoint.sh" ]