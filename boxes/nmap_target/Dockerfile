FROM alpine

RUN apk add --update --no-cache openssh

ENTRYPOINT [ "/entrypoint.sh" ]
COPY entrypoint.sh /
