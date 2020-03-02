# debug nginx

[Envoy won’t connect to my HTTP/1.0 service](https://istio.io/docs/ops/common-problems/network-issues/#envoy-won-t-connect-to-my-http-1-0-service), so I added belows.

- `proxy_http_version 1.1`
- hostname: `my-nginx`
