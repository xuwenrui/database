### 安装Redis
官方网站：http://redis.io/

官方下载：http://redis.io/download 可以根据需要下载不同版本

windows版：https://github.com/MSOpenTech/redis（需编译）

整理版本：http://pan.baidu.com/s/1ge4H08F

更多版本：https://github.com/MSOpenTech/redis/releases

### 启动Redis
redis-server.exe redis.conf

![启动Redis][1]

这个窗口要保持开启  关闭时redis服务会自动关闭

### 测试使用

![测试使用][2]

另外开启一个命令行窗口 进入redis目录下 （注意修改自己的ip）

redis-cli.exe -h 192.168.10.61 -p 6379


  [1]: http://static.oschina.net/uploads/space/2014/0228/182527_GKSy_140593.jpg
  [2]: http://static.oschina.net/uploads/space/2014/0228/183030_0eTx_140593.png
