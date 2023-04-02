# mymuduo

## 项目描述

参考muduo网络库源码，使用C++11重写muduo网络库中的TcpServer核心代码

## 开发环境

- 云服务器ECS（2核 2G 1M宽带）
- Linux version 3.10.0（CentOS 7.9 64位）
- gcc version 4.8.5
- cmake version 2.8.12.2

## 编译

```shell
# 项目编译执行即可 头文件生成至目录/usr/include/mymuduo/，.so库文件生成至目录/usr/lib/
sudo ./autobuild.sh

# 测试用例进入example/文件夹，make即可生成服务器测试用例
cd ./example
make
./testserver
```

