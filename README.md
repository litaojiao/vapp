$ git clone https://github.com/virtualopensystems/vapp.git

编译：
$ cd vapp
$ make

vhost-user参考后端如下启动：
$ ./vhost -s ./vhost.sock

参考客户端如下启动：
$ ./vhost -q ./vhost.sock
