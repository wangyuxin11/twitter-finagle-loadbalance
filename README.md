# twitter-finagle-loadbalance
finagle简单使用

在看awseome-scala的时候，正好看到了twitter的finagle。自己公司里貌似也有那种关注load balance等的解决方案，不过不是很容易理解。考虑到自己之前几个月都在弄电子技术了，重新弄点网络相关的把。

这次的任务是做了一个thrift+finagle的远程服务调用例子。其实不是很难，如果不是连续碰到finagle的坑的话。

finagle是twitter开源出来的一个分布式系统解决方案，毕竟是大公司出来的东西，更新频率特别是文档很低，很多文档基本都是几年前，好在有代码……

http://blog.gssxgss.me/try-finagle-1/
