# Hello Lazycat（极简 demo）

用来跑通「懒猫应用部署流水线」的最小应用：一个静态页面 + nginx 镜像 + 懒猫 LPK 清单。

## 结构

```
index.html                     静态页面
Dockerfile                     nginx:alpine，拷贝 index.html
lzc-icon.png                   512x512 应用图标
deploy/lazycat/lzc-manifest.yml 懒猫应用清单（包名 / 路由 / 服务）
```

## 部署信息

| 项 | 值 |
| --- | --- |
| 项目名 | Hello Lazycat |
| 应用包名 | cloud.lazycat.app.hello-lazycat |
| 版本 | 1.0.0 |
| 子域名 | hello-lazycat |
| 容器端口 | 80 |

上线后访问：`https://hello-lazycat.<微服名>.heiyu.space`
