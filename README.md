![](./img/header.png)

<h1 align="center">YACW</h1>
<h2 align="center">Yet, Another ChatGPT WebAPP</h2>

<p align="center"><a href="https://yacw.laoliu.icu">测试站点</a></p>

是的，又一个 ChatGPT 网页客户端。

前端由 Vue + Element-Plus 构建，后端由 Go + Gin 构建，前后端分离部署。

### 免费 & 开源

我们提供源代码，您可以将其部署在任何地方──服务器、电脑，甚至是您的手机上。

### 注重隐私

我们不会收集任何敏感信息，并采取了多种措施确保所有数据的安全性。

### 用户体验优先

我们希望可以为您带来最佳的 ChatGPT 使用体验。

## 自部署

### 使用 Docker Compose 与 Traefik  *我们是这么部署的

```bash
# 您需要自行配置 Traefik，并适当修改 docker-compose-traefik.yml
docker compose up -f docker-compose-traefik.yml -d
```

### 使用 Docker Compose 和反向代理程序

```bash
docker compose up -d
# 您需要自行配置反向代理程序
```

## 反馈

如果您在使用中有任何问题，请在 GitHub Issue 中提出。
