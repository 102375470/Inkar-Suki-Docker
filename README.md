
# Inkar-Suki-Docker

This is a docker compose deploy support for the Inkar-Suki project.

## 部署

```bash

git clone https://github.com/102375470/Inkar-Suki-Docker.git
cd Inkar-Suki-Docker


1. 修改配置文件 `./config/config.yml`
2. 运行以下命令启动容器：
   NAPCAT_UID=$(id -u) NAPCAT_GID=$(id -g) docker-compose up -d
3. 访问 [http://localhost:6099](http://localhost:6099)
    - 默认密码：`napcat`
4. 扫码登录后：
    - 进入"网络配置"
    - 新建websocket客户端
    - URL输入：`ws://inkar-suki:2333/onebot/v11/ws`
    - 点击"启用,保存"
```
## 友情链接

- [Inkar-Suki](https://github.com/HornCopper/Inkar-Suki.git) - 集成多种功能的群聊机器人 by @HornCopper；
