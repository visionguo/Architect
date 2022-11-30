# 数据结构
# 算法
# 操作系统
# 网络
# 数据库
# 大数据


https://github.com/xingshaocheng/architect-awesome

数据结构

队列
java队列 - queue
Queue：一个队列就是一个先入先出（FIFO）的数据结构
Queue接口与List、Set同一级别，继承了Collection接口，LinkedList实现了Deque接口

非阻塞队列：ConcurrentLinkedQueue(无界线程安全)，采用CAS机制(compareAndSwapObject原子操作)
阻塞队列：ArrayBlockingQueue(有界)、LinkedBlockingQueue(无界)、DelayQueue、PriorityBlockingQueue，采用锁机制；使用ReentrantLock锁

集合
Set
HashSet


链表、数组
List分为3类：ArrayList、LinkedList和Vector
1、是按顺序查找
2、允许存储项为空
3、允许多个存储项的值相等

字典、关联数组

栈
1、Stack是线程安全的
2、内部使用数组保存数据，不够时翻倍

树
二叉树
每个节点最多有两个叶子节点
二叉树由节点和边组成，节点分为根节点、父节点和子节点

完全二叉树
平衡二叉树
二叉查找树(BST)
