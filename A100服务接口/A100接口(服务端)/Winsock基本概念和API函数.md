## Winsock基本概念和API函数

### 一 定址

​	要通用于过winsock建立通信，必须了解如何利用指定的协议工作站定址。winsock 2 引入了几个新的，与协议无关的函数，他们可和任何一个地址家族一起使用；但是大多数情况，各协议家族都有自己的地址解析机制，要么通过一个函数，要么作为一个投给getsockopt的选项。

​	因为目前网络编程中用的最多最普遍的也许就是TCP/IP协议了，所以这里主要介绍此协议下的winsock编程。

* 1 、IP

   网际协议 是一种用于互联网的网络协议，已经广为人知，它可广泛用于大多数计算机操作系统上，也可用于大多数局域网LAN和广域网，从他的设计看来，IP是一个无连接的协议，不能保障数据床底万无一失。两个比他高级的协议（TCP/UDP）用于依赖IP协议的数据通信。

* 2、TCP

  ​





