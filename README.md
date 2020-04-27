# dockerfile
复制内容到Dockerfile文件，
docker build -t php-fpm71:71 .

```
docker 使用简单实例：
docker run -d -p 9001:9000 -v /home/wwwroot/aaa:/home/wwwroot/aaa -v /home/wwwroot/aaa/api/web:/home/wwwroot/aaa/api/web php-fpm71:71
进入docker容器：
docker exec -it containerID /bin/bash
```
