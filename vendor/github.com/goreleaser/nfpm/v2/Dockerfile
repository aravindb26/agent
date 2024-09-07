FROM alpine:3.20.3
COPY nfpm_*.apk /tmp/
RUN apk add --allow-untrusted /tmp/nfpm_*.apk
ENTRYPOINT ["/usr/bin/nfpm"]
