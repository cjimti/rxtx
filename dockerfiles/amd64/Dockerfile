FROM alpine:3.9
RUN apk --no-cache add ca-certificates
COPY rxtx /
WORKDIR /
ENTRYPOINT ["/rxtx"]