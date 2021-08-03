# docker-learning-test
学习DockerFile和DockerCompose的应用

## 文件说明
* app.py

    一个用python写的网页应用，基于redis记录页面访问次数。
* requirements.txt

    记录部署这个网页应用所需要的组件，如redis。

* Dockerfile
    
    负责管理组件，构建镜像。

* docker-compose.yml
    
    负责配置下载好的镜像，生成容器。
    
    如设定网页部署端口为5000。


## 使用说明
启动docker
```
cd /docker-learning-test
docker-compose up -d
```
访问页面

http://localhost:5000
