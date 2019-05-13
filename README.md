# Docker-v2ray-https


#### 此应用主要作为科学上网 请不要做非法的事

#### 请安装docker 和docker-compose 环境

> www.test.com 替换自己域名  
> test@gmail.com 替换自己的邮箱
> www.test.com_location 文件修改为自己域名的前缀 ××××_location (xxxx 代表自己的域名)
> client 为客户端连接文件

```
v2ray
├── client
│   └── client.json
├── config.json
├── docker-compose.yml
├── nginx
│   └── vhost.d
│       ├── default
│       └── www.test.com_location
└── README.md

```

> 执行安装命令
```
docker-compose up -d
```

> 查看应用是否运行
```
docker-compose start
``` 
> 查看日志
```
docker-compose logs -f
```


