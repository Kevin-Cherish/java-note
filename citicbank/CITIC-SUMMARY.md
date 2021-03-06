# citicbank 学习知识点
- [八种基本数据类型的大小,以及他们的封装类](study/1.md)
- [Switch可以用的参数种类](study/2.md)
- [Object有哪些公用方法?](study/3.md)
- [HTTP缓存](study/4.md)
- [Java的四种引用,强弱软虚,用到的场景.](study/5.md)
- [Hashcode的作用以及原理,Hash的算法:开放地址法和链地址法的对比.Hash扩容及加载因子的介绍.rehash过程等.](study/6.md)
- [ArrayList,LinkedList,Vector的区别.](study/7.md)    
- [String,StringBuffer与StringBuilder的区别](study/8.md)
- [Map,Set,List,Queue,Stack的特点与用法](study/9.md)
- [HashMap和HashTable的区别.要深层理解,不只是线程安全,还有Hash算法的区别](study/10.md)
- [HashMap和ConcurrentHashMap的区别,HashMap的底层源码.](study/11.md)
- [TreeMap,HashMap,LindedHashMap的区别.](study/12.md)
- [Collection包结构,与Collections的区别.](study/13.md)
- [try catch finally,try里有return,finally还执行么?](study/14.md)
- [Excption与Error包结构.非检查异常你遇到过哪些情况,检查异常你遇到过哪些情况.](study/15.md)
- [Java面向对象的三个特征与含义.以及面向对象的五个原则](study/16.md)
- [Override和Overload的含义去区别.](study/17.md)
- [Interface与abstract类的区别,应用场景.](study/18.md)

19. Static class 与non static class的区别.
20. java多态的实现原理.
21. 实现多线程的两种方法:Thread与Runable.以及wait,join,notify等的使用.
22. 线程同步的方法:sychronized,lock,reentrantLock,Condition等.
23. 锁的等级:方法锁,对象锁,类锁.

24. 写出生产者消费者模式.用阻塞队列和不用的情况.
25. ThreadLocal的设计理念与作用.
26. ThreadPool用法与优势.
27. Concurrent包里的其他东西:ArrayBlockingQueue,CountDownLatch等等.

- [wait()和sleep()的区别.](study/28.md)
- [foreach与正常for循环效率对比.](study/29.md)

30. Java IO.
31. 反射的作用于原理.
32. 泛型常用特点.
33. XML与JSON的对比.
34. Java与C\++对比.
35. 设计模式的六大原则.总开闭原则.
36. 常用设计模式的DEMO和介绍:单例,工厂,适配器,责任链,观察者等等.
37. Servlet非常重要,要完整的说出声明周期.
这个我推荐大家多百度看大牛博客文档,比看书快.
JVM
1. 内存模型以及分区,需要详细到每个区放什么.
2. 堆里面的分区:Eden,survival from to,老年代,各自的特点.
3. 对象创建方法,对象的内存分配,对象的访问定位.
4. GC的两种判定方法:引用计数与引用链.
5. GC的三种收集方法:标记清除,标记整理,复制算法的原理与特点,分别用在什么地方,如果让你优化收集方法,有什么思路?
6. GC收集器有哪些?
7. Minor GC与Full GC分别在什么时候发生?
8. ClassLoader介绍.
9. 类加载的五个过程:加载,验证,准备,解析,初始化.
10. 双亲委派模型:Bootstrap ClassLoader,Extension ClassLoader,ApplicationClassLoader.
11. 分配:静态分配与动态分配.
操作系统
1. 进程和线程的区别.
2. 死锁的各种知识点,要非常熟悉.
3. 内存管理方式:段存储,页存储,段页存储.
4. 进程的几种状态.
5. 进程几种通信方式.
6. 什么是虚拟内存以及实现.
7. 虚拟地址,逻辑地址,线性地址,物理地址的区别.
8. 线程与进程的同步方式.
TCP/IP
1. OSI与TCP/IP各层的结构与功能,都有哪些协议.
2. TCP与UDP的区别.
3. TCP报文结构.
4. TCP的三次握手与四次挥手过程,各个状态名称与含义,TIMEWAIT的作用以及为甚么出现TIMEWAIT以及握手交换的信息.
5. TCP拥塞控制.
6. TCP滑动窗口与连续ARQ协议.
7. Http的报文结构.
8. Http的状态码含义.
9. Http request的几种类型.
10. HTTP缓存.
11. Http怎么处理长连接.
12. Cookie与Session的作用于原理.禁用Cookie怎么用session,处理大并发量怎么设计Session比较好.
13. 输入一个网页访问,整个过程是怎么样的:从DNS,HTTP,TCP,OSPF,IP,ARP等方面回答.
14. Ping的整个过程.Traceroute的整个过程,从TTL方面回答.
15. Socket通信.
16. IP地址分类.
17. 路由器与交换机区别.
数据结构与算法
1. 链表与数组.
2. 队列和栈,出栈与入栈.
3. 链表的删除,插入,反向.
4. 字符串操作.
5. Hash表的hash函数,冲突解决方法有哪些.
6. 各种排序:冒泡,选择,插入,希尔,归并,快排,堆排,桶排,基数的原理,平均时间复杂度,最坏时间复杂度,空间复杂度,是否稳定.
7. 快排的partition函数与归并的Merge函数.
8. 对冒泡与快排的改进.
9. 二分查找,以及其应用.
10. 二叉树,B+树,AVL树,红黑树,哈夫曼树(可以选择掌握,比较难).
11. 二叉树的前中后续遍历:递归与非递归写法,层序遍历算法.非递归写法和深度广度优先遍历很重要.
12. 数组矩阵的各种花式打印.
13. KMP算法.
14. 排列组合问题.
15. 动态规划,贪心算法,分治算法.(比较难,算法基础扎实的同学可以选择掌握)
16. 大数据处理,怎么设计,TOP-K问题怎么解决.