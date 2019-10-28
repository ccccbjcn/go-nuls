FROM golang:1.7.4-alpine

#COPY ./NULS-Wallet /app/NULS-Wallet
RUN apk update \
        && apk upgrade \
        && apk add --no-cache bash \
        bash-doc \
        bash-completion \
        && rm -rf /var/cache/apk/* \
        && /bin/bash
#RUN chmod +x /app/NULS-Wallet

ENV PORT 8080
EXPOSE 8080

#ENTRYPOINT /app/NULS-Wallet
