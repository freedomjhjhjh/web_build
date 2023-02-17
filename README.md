![logo](https://shreade.cn/image/logo.png)
## 搭建
——————————————————————————————————
*  拉取代码
```shell
git clone https://github.com/freedomjhjhjh/web_build.git
cd web_build
```
*  修改ip地址，替换本机ip
    -  app/config.json, 替换redis.default.addr 和 webrtc.candidates.nat1to1
    -  nginx/www/js/config.js, 替换WSS_URL变量值
      
*  服务启动
```shell
docker-compose up -d
```
*  正常启动直接访问
```shell
https://ip地址/demo
```

## 联系方式

<img src="https://shreade.cn/image/weixin200.jpg" alt="avatar" />

[https://shreade.cn](https://shreade.cn)

提供低延迟、高质量的音视频通信服务，专注于视频会议的私有化部署。
