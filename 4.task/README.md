# 4. Task



ASP.NET Core 依赖注入生命周期跟异步容易错的地方

异常处理

任务可以方便地传播异常，这和线程是截然不同的。因此，如果任务中的代码抛出一个未处理异常（换言之，如果任务出错），那么调用Wait()或者访问Task<TResult>的Result属性时，该异常就会被重新抛出：

使用静态事件TaskScheduler.UnobservedTaskException可以在全局范围订阅未观测的异常。处理这个事件并将错误记录在日志中，是一个有效的处理异常的方式。



在计算密集型中也可以使用 Task 异步，虽然不会带来性能上的好处，



ValueTask 也合并到这里

```
ThreadPoolTaskScheduler
```

```
TaskScheduler
```
