# 三次握手过程详解

这次的示例是为了理解系统函数调用的执行过程对应的握手时的状态变化. 

包括

1. `listen()`函数中`backlog`参数的含义.

2. `accept()`函数调用前后, 服务端与客户端程序的socket状态.