FROM alpine

RUN apk add -U iperf3 && \
    rm -rf /var/cache/apk/*

ENTRYPOINT ["iperf"]
