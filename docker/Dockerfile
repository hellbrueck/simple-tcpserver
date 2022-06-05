FROM alpine:latest

RUN apk add --no-cache ncat

EXPOSE 11211

CMD ["ncat", "-v", "-e", "/bin/cat", "-k", "-l", "11211"]
