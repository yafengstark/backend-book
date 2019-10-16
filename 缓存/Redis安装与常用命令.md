



[Redis在windows下安装过程](https://www.cnblogs.com/M-LittleBird/p/5902850.html)

- 安装windows服务
- 设置开机自启动



解决

> error) ERR operation not permitted

只需第一行执行

```shell
redis 127.0.0.1:6379> AUTH admin
```



## 启动服务

redis-server redis.windows.conf



## 配置密码

## 配置使用内存

