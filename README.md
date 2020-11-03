![logo](https://shreade.cn/image/logo.png)
## Web端搭建

```shell
git clone https://github.com/freedomjhjhjh/web_build.git
cd web_build
cp app/config.json.example app/config.json
#
#config.json说明
#  ListenIp: 服务监听的IP
#  ListenPort: 服务监听的端口
#  MinPort、MaxPort: UDP端口范围
#  License: 序列号
#  NatIps: 外网IP
#

cp nginx/www/js/config.js.example nginx/www/js/config.js

#修改WSS url地址

docker-compose up

#访问https://ip
```

## 联系方式

<img src="https://shreade.cn/image/weixin-qrcode.jpg" alt="avatar" style="zoom:50%;" />
