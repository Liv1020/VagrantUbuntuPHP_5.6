#Ubuntu的php开发环境5.6

1. 注意每次启动vagrant up之后，需要vagrant ssh进入box然后执行：
```shell
sudo su -
service nginx restart
```
因为文件映射的时候，nginx和php-fpm已经启动了。