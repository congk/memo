# 搭建 Shadowsocks 服务

## 安装

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
source .bashrc
nvm install 16
npm i -g shadowsocks
```

## 配置

修改 `vi ~/.nvm/versions/node/v16.20.2/lib/node_modules/shadowsocks/config.json`

```json
Server: 0.0.0.0
Password: xxxxx
```

## 启动

```sh
nohup ssserver &
```
