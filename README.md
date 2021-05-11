# authify 开放认证服务

Docker镜像部署部署脚本
```
docker run -d --restart=always --network host \
-e WLN_LISTEN_PORT=4999 \
-e WLN_MYSQL_HOST=127.0.0.1 \
-e WLN_MYSQL_NAME=authify \
-e WLN_MYSQL_UID=authify \
-e WLN_MYSQL_PWD=123456 \
--name=emi wlniao/authify
```