# 目录

### 第一部分  NETTY的概念和结构
#### 前言
#### 第一章   Netty—异步和事件驱动
##### 1.1 Java网络编程
##### 1.2 Netty的核心组件
##### 1.3 Netty的核心组件
##### 1.4 小结
#### 第二章   你的一个Netty程序
##### 2.1 创建开发环境
##### 2.2 Netty服务器/客户端概览
##### 2.3 开发Echo服务器
##### 2.4 开发Echo客户端
##### 2.5 编译和运行Echo服务器和客户端
##### 2.6 小结
#### 第三章   Netty的组件和设计
##### 3.1 Channel，EventLoop和ChannelFuture
##### 3.2 ChannelHandler和ChannelPipeline
##### 3.3 Bootstrapping
##### 3.4 小结
#### 第四章   传输
##### 4.1 案例学习：传输方式迁移
##### 4.2 传输API
##### 4.3 提供的传输方式 
##### 4.4 传输使用案例
##### 4.5 小结
#### 第五章   ByteBuf
##### 5.1 ByteBuf API
##### 5.2 ByteBuf类—Netty的数据容器
##### 5.3 字节级操作
##### 5.4 ByteBufHolder接口
##### 5.5 ByteBuf分配
##### 5.6 引用计数
##### 5.7 小结
#### 第六章   ChannelHandler和ChannelPipeline
##### 6.1 ChannelHandler家族
##### 6.2 ChannelPipeline接口
##### 6.3 ChannelHandlerContext接口
##### 6.4 异常处理
##### 6.5 小结
#### 第七章   EventLoop和线程模型
##### 7.1 线程模型概览
##### 7.2 EventLoop接口
##### 7.3 任务调度
##### 7.4 实现细节
##### 7.5 小结
#### 第八章   启动辅助
##### 8.1 Bootstrap类
##### 8.2 Bootstrapping客户端和无连接协议
##### 8.3 Bootstrapping服务器
##### 8.4 在一个Channel中Bootstrapping客户端
##### 8.5 在bootstrap中增加多个ChannelHandler
##### 8.6 使用Netty的ChanelOptions和attributes
##### 8.7 Bootstrapping DatagramChannels
##### 8.8 关闭
##### 8.9 小结
#### 第九章   单元测试
##### 9.1 EmbededChannel概览
##### 9.2 测试ChannelHandlers和EmbededChannel
##### 9.3 测试异常处理
##### 9.4 小结


### 第二部分 编解码
#### 前言
#### 第十章       Netty的编解码（codec）框架
##### 10.1 什么是编解码？
##### 10.2 解码器
##### 10.3 编码器
##### 10.4 编解码抽象类
##### 10.5 小结
#### 第十一章   Netty提供的ChannelHandlers和codec
##### 11.1 用SSL/TLS保障Netty应用的安全
##### 11.2 创建Netty HTTP/HTTPS应用
##### 11.3 空闲连接和超时
##### 11.4 基于分隔符和长度的协议
##### 11.5 写大量数据
##### 11.6 序列化数据
##### 11.7 小结

### 第三部分 网络协议
#### 第十二章  WebSocket
##### 12.1 WebSocket简介
##### 12.2 WebSocket例程
##### 12.3 增加对WebSocket支持
##### 12.4 测试这个应用
##### 12.5 小结
#### 第十三章  用UDP广播事件
##### 13.1 UDP基础
##### 13.2 UDP广播
##### 13.3 UDP例程
##### 13.4 消息POJO: LogEvent
##### 13.5 写广播器
##### 13.6 写监控器
##### 13.7 运行LogEventBroadcaster和LogEventMonitor
##### 13.8 小结

### 第四部分  案例学习
#### 第十四章  第一部分
##### 14.1 Droplr-创建移动服务
##### 14.2 Firebase-一个实时的数据同步服务
##### 14.3 Urban Airship-创建移动服务
##### 14.4 小结
#### 第十五章  第二部分
##### 15.1 Facebook中的Netty：Nifty和Swift
##### 15.2 Twitter中的Netty：Finagle
##### 15.3 小结

### 附录-Maven入门
##### A.1 什么是Maven
##### A.2 POM示例
##### A.3 Maven命令行
##### A.4 小结
