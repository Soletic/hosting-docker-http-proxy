# Docker image used for http proxy

Based on the [open source docker image jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy).

We built this image to override the nginx parameter client_max_body_size and improve compatibility if owncloud is behind the proxy.

