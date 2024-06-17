***
## About
**Init with 841ed4e9@<https://github.com/zizifn/edgetunnel>**

**edgetunnel is a VLESS protocol implementation using WebSocket, which is deployed on network edge.**

***
## Deploy
[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/N2o16384/edgetunnel)

***
**Once deployed, they are important**
## ENVS
  - UUID

  The access token for vless auth, EMPTY means using code default
  - PROXYIP

    The cdn(Name/IP) works as a proxy, EMPTY means proxy is host self

## Vless Headers
  - cdn

    Define a proxy. If EMPTY, use PROXYIP(ENV) proxyIP(code) in sequence

## API
  - <https://edgetunnel-xxxx.pages.dev/info>

    Client info
  - <https://edgetunnel-xxx.pages.dev/uuid>

    Gen a UUID
  - <https://edgetunnel-xxx.pages.dev/server>

    Show known cdn and serverless host list

***
**More detailed guide please refer to <https://github.com/3Kmfi6HP/EDtunnel>**


