## P0490:双端队列

总时间限制: 1000ms

内存限制: 65535kB

描述

定义一个双端队列，进队操作与普通队列一样，从队尾进入。出队操作既可以从队头，也可以从队尾。编程实现这个数据结构。

输入

第一行输入一个整数t，代表测试数据的组数。  每组数据的第一行输入一个整数n，表示操作的次数。  接着输入n行，每行对应一个操作，首先输入一个整数type。  当type=1，进队操作，接着输入一个整数x，表示进入队列的元素。  当type=2，出队操作，接着输入一个整数c，c=0代表从队头出队，c=1代表从队尾出队。  n <= 1000

输出

对于每组测试数据，输出执行完所有的操作后队列中剩余的元素,元素之间用空格隔开，按队头到队尾的顺序输出，占一行。如果队列中已经没有任何的元素，输出NULL。

样例输入

```
2
5
1 2
1 3
1 4
2 0
2 1
6
1 1
1 2
1 3
2 0
2 1
2 0
```

样例输出

```
3
NULL
```

