FROM alpine:3.18

RUN apk -U --no-cache add \
  python3

RUN pip3 install --upgrade pip && \
    pip3 install --no-cache-dir \
    tornado \
    aiohttp_jinja2==1.5.1 \
    jinja2==3.0.3 \
    mako
