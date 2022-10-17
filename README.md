记录netty不错的架构设计

用以今后开发项目参考

## DiscardServer
请求是如何按照顺序进行处理的？
实现只处理单独请求的handler和全局共享handler（实现限流等全局控制逻辑）

http://seeallhearall.blogspot.com/2012/06/netty-tutorial-part-15-on-channel.html#:~:text=Shared%20and%20Exclusive%20Channel%20Handlers