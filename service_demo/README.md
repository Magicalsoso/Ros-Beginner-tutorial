# service_demo

Service通信示例，用C++实现service通信。

## 功能介绍

假设Service的提供方/服务器端提供名为`greetings`的服务，其srv的请求是姓名和年龄，反馈为一个字符串，向请求方问好。

本例需要自定义srv文件，见[srv/Greeting.srv](./srv/Greeting.srv)。

代码见`src/`下的[client.cpp](./src/client.cpp)和[server.cpp](./src/server.cpp)。



## 运行方法

启动服务器端

```sh
rosrun service_demo server
```

启动客户端

```sh
rosrun service_demo client
```


