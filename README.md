# v2ray compose client

## 启动
配合服务端一键启动 [v2Ray-docker-compose-diy](https://github.com/ebitgeek/v2Ray-docker-compose-diy)

修改 uuid 和 服务器地址 和端口号, 必须与服务端匹配

```shell
docker-compose up -d
```

目前开有本地服务
* 本地 socks proxy server 端口: *21080*
* 本地 http proxy server 端口: *28080*
* 本地 shadowsocks server 端口: *8388*

本地 shadowsocks server 的密码可再 client.conf.jsonc中修改  
默认连接信息
```
ss://YWVzLTI1Ni1nY206RWI5I3hGTTFYWGloYmtEUA==@127.0.0.1:8388/?#v2ray
```
