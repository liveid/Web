# ChatGPT Web


###  使用 Railway 部署

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/T4hhV-?referralCode=Q7sc9e)


#### Railway 环境变量

| 环境变量名称          | 必填                   | 备注                                                                                               |
| --------------------- | ---------------------- | -------------------------------------------------------------------------------------------------- |
| `PORT`                | 必填                   | 默认 `3002`
| `AUTH_SECRET_KEY`          | 可选                   | 访问权限密钥                                        |
| `MAX_REQUEST_PER_HOUR`          | 可选                   | 每小时最大请求次数，可选，默认无限                                        |
| `TIMEOUT_MS`          | 可选                   | 超时时间，单位毫秒                                                                             |
| `OPENAI_API_KEY`      | `OpenAI API` 二选一    | 使用 `OpenAI API` 所需的 `apiKey` [(获取 apiKey)](https://platform.openai.com/overview)            |
| `OPENAI_ACCESS_TOKEN` | `Web API` 二选一       | 使用 `Web API` 所需的 `accessToken` [(获取 accessToken)](https://chat.openai.com/api/auth/session) |
| `OPENAI_API_BASE_URL`   | 可选，`OpenAI API` 时可用 |  `API`接口地址  |
| `OPENAI_API_MODEL`   | 可选，`OpenAI API` 时可用 |  `API`模型  |
| `API_REVERSE_PROXY`   | 可选，`Web API` 时可用 | `Web API` 反向代理地址 [详情](https://github.com/transitive-bullshit/chatgpt-api#reverse-proxy)    |
| `SOCKS_PROXY_HOST`   | 可选，和 `SOCKS_PROXY_PORT` 一起时生效 | Socks代理    |
| `SOCKS_PROXY_PORT`   | 可选，和 `SOCKS_PROXY_HOST` 一起时生效 | Socks代理端口    |
| `SOCKS_PROXY_USERNAME`   | 可选，和 `SOCKS_PROXY_HOST` 一起时生效 | Socks代理用户名    |
| `SOCKS_PROXY_PASSWORD`   | 可选，和 `SOCKS_PROXY_HOST` 一起时生效 | Socks代理密码    |
| `HTTPS_PROXY`   | 可选 | HTTPS 代理，支持 http，https, socks5    |
| `ALL_PROXY`   | 可选 | 所有代理 代理，支持 http，https, socks5    |

> 注意: `Railway` 修改环境变量会重新 `Deploy`

### 