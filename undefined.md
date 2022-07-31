# C# 多线程与异步

作者：痴者工良

地址：[https://threads.whuanle.cn](https://threads.whuanle.cn)

此系列教程包括了多线程、锁、同步异步、线程池、任务、async/await、并行、并发等知识点，从零基础掌握多线程和异步，带你了解和走进同步和异步的世界。

* 教程中每个小节都有代码示例
* 深入原理，讲解深层知识
* 由易到难，从入门到掌握
* 循序渐进，一步步学习，一步步拓展知识面
* 内容完整、齐全，可以系统式学习
* 大量代码示例和场景实践

* [1. 线程基础](1.thread_basic/README.md)

  * [1.1 Thread 基础](1.thread_basic/1.thread.md)
  * [1.2 多线程模型](1.thread_basic/2.thread_model.md)
  * [1.3 线程池](1.thread_basic/3.pool.md)

* [2. 线程同步](2.thread_sync/README.md)

  * [2.1 原子操作 Interlocked](2.thread_sync/1.interlocked.md)

  * [2.2 Locker 和 Monitor 排他锁](2.thread_sync/2.locker_monitor.md)

  * [2.3 进程互斥锁 Mutex（排他锁） ](2.thread_sync/3.mutex.md)

  * [2.4 非排他锁 Semaphore](2.thread_sync/4.Semaphore_SemaphoreSlim.md)

  * [2.5 自动线程通知 AutoRestEvent](2.thread_sync/5.AutoRestEvent.md)

  * [2.6 手动线程通知 ManualResetEvent](2.thread_sync/6.ManualResetEvent.md)

  * [2.7 线程完成数 CountdownEvent ](2.thread_sync/7.CountDownEvent.md)

  * [2.8 并行协调 Barrier ](2.thread_sync/8.Barrier.md)

  * [2.9 读写锁 ReaderWriterLock](2.thread_sync/9.ReaderWriterLock.md)

  * [2.10 自旋 SpinWait](2.thread_sync/10.SpinWait.md)

* [3. Task](4.task/README.MD)

  * [3.1 任务基础 1](3.task/1.task1.md)

  * [3.2 任务基础 2](3.task/2.task2.md)

  * [3.3 任务基础 3](3.task/3.task3.md)

  * [3.4 ValueTask](3.task/4.value_task.md)

  * [3.5 使用 Task 实现一个任务流](3.task/5.workflow.md)

  * [3.6 async 和 awiat](3.task/6.async_await.md)
