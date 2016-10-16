docker-curl
===========

[![](https://images.microbadger.com/badges/image/solidnerd/curl.svg)](http://microbadger.com/images/solidnerd/curl "Get your own image badge on microbadger.com")

curl in a container. This supports http2 as well.

## Current Version: [7.50.2](https://github.com/SolidNerd/docker-curl/blob/master/Dockerfile)


## Quickstart
With Docker Compose is a Quickstart very easy. Run the following command:

```
docker run --rm -it solidnerd/curl:7.50.2 -s --http2 -I https://nghttp2.org
```

## Help
Which commands can i use. Run this to get the information:

```
docker run --rm -it solidnerd/curl:7.50.2 --help
```


## Inspiration

This image is inspired by the great article from [nathan leclaire](https://nathanleclaire.com/blog/2016/08/11/curl-with-http2-support---a-minimal-alpine-based-docker-image/).
