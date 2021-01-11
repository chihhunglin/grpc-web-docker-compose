# Kubernetes

## Web
### 怎麼使用?

1. `docker run -v ${PWD}:/app -w /app node:14.3.0-alpine npm install`: 安裝`web-cleint`的相依
2. `docker run -v ${PWD}:/app -w /app node:14.3.0-alpine npm run build`: 編譯`web-client`的`client.js`

## Reference

2020-ithelp-contest

- 被選召的 Gopher 們，從零開始探索 Golang, Istio, K8s 數碼微服務世界, https://github.com/superj80820/2020-ithelp-contest
