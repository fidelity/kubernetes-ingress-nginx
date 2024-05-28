FROM squidfunk/mkdocs-material:9.4.5

COPY action.sh /action.sh

RUN apk add --no-cache bash \
  && chmod +x /action.sh \
  && apk update && apk add curl=7.79.1-r2

ENTRYPOINT ["/action.sh"]
