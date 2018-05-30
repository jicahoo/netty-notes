# netty-notes
As title.

# Netty的基本思想
* 内核是基于事件模型的异步并发框架. 你去看io.netty.util.concurrent包，就是基本的netty模型，EventExcutor, Promise, Future, GenericFutureListener
* 网络IO只是一种非常适合异步的应用. 在netty中，有一个单独的模块，netty-transport.
