FROM debian:buster-slim

RUN apt-get update && apt-get install -y nginx && rm -rf /var/lib/apt/lists/*

CMD nginx -g 'daemon off;'

EXPOSE 80
