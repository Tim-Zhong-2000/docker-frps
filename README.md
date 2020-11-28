# frps 一键部署
## 环境要求
docker
docker-compose

## 部署说明
1. 根据需求编辑`config/frps.ini`配置文件。配置可以参考官方给的配置样例`config/frps_full.ini`，这个文件在运行时不会被加载。
2. 启动服务
```docker-compose up -d```
3. 部署完成