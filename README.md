# Remote Desktop Monitor Client

Language: [中文](README_zh.md) / [English](README.md)

Remote Desktop Monitor Client

First, start the server.Then, input the ip and port in [client](https://github.com/lingxiaoguang/remote-monitor-client)
and now you can monitor and operate the desktop of server.

![](./remote-monitor.gif)
![1](case1.png)
![2](case2.png)

# 安装 和 运行

有两种方式，一种为网页，一种为electron应用，推荐网页的方式

#### 网页的方式:

```
yarn global add remote-monitor-client-web

remote-monitor-client-web 
```
#### electron应用的方式

首先下载项目，然后
```
npm run build
```
之后安装对应的安装包即可（目前只支持mac）


# 原理

[Node.js实现远程桌面监控](https://juejin.im/post/5d18d4c36fb9a07ecb0bbe7b)

