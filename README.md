《Java 7 Concurrency Cookbook（Java 7 并发编程指南）》   作者： Javier Fernández González

“并发编程网”的翻译：http://ifeve.com/java-7-concurrency-cookbook/

译者：郑玉婷，许巧辉 校对：方腾飞，欧振聪  

本项目是《 Java 7 Concurrency Cookbook 》的笔记。

# [第一章: 线程管理](docs/chapter1.md)

1.1 介绍 

1.2 线程的创建和运行 

1.3 获取和设置线程信息 

1.4 线程的中断 

1.5 操作线程的中断机制 

1.6 线程的睡眠和恢复 

1.7 等待线程的终结 

1.8 守护线程的创建和运行 

1.9 处理线程的不受控制异常 

1.10 使用本地线程变量

1.11 线程组

1.12 处理线程组内的不受控制异常

1.13 用线程工厂创建线程

# [第二章：基本线程同步](docs/chapter2.md)

2.1 介绍 

2.2 同步方法 

2.3 在同步的类里安排独立属性

2.4 在同步代码中使用条件

2.5 使用Lock来同步代码块

2.6 使用读/写锁来同步数据访问

2.7 修改Lock的公平性

2.8 在Lock中使用多条件

# [第三章: 线程同步工具](docs/chapter3.md)

3.1 介绍

3.2 控制并发访问一个资源

3.3 控制并发访问多个资源

3.4 等待多个并发事件完成

3.5 在一个相同点同步任务

3.6 运行并发阶段性任务

3.7 控制并发阶段性任务的改变

3.8 在并发任务间交换数据

# [第四章: 线程执行者](docs/chapter4.md)

4.1 介绍 

4.2 创建一个线程执行者 

4.3 创建一个大小固定的线程执行者 

4.4 执行者执行返回结果的任务 

4.5 运行多个任务并处理第一个结果 

4.6 运行多个任务并处理所有的结果

4.7 在延迟后执行者运行任务

4.8 执行者定期的执行任务

4.9 执行者取消任务 

4.10 执行者控制一个结束任务 

4.11 执行者分离运行任务和处理结果 

4.12 执行者控制被拒绝的任务

# [第五章: Fork/Join 框架](docs/chapter5.md)

5.1 介绍 

5.2 创建 Fork/Join 池 

5.3 加入任务的结果 

5.4 异步运行任务 

5.5 任务中抛出异常

5.6 取消任务