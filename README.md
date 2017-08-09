本仓库是MiniSite页面部署的相关文件

部署步骤：

- 克隆本仓库到本地文件夹
- 进入本仓库作为工作目录
- 执行脚本 sudo docker-compose up

其他说明：
- php-fpm:5.6.31镜像的构建 https://hub.docker.com/r/mrhuangyuhui/nginx-php-fpm/ 是从镜像 https://hub.docker.com/r/richarvey/nginx-php-fpm/ 修改Dockerfile的php-fpm版本而来
- php-fpm容器的详细使用说明参考 https://hub.docker.com/r/richarvey/nginx-php-fpm/
