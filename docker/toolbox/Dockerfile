FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip && \
    pip install awscli && apk --purge -v del py-pip
EXPOSE 7777 
CMD tail -f /dev/null
