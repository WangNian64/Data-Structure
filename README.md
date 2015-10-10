d# Data-Structure
##代码内容
《数据结构与算法分析》上的代码实现,
按照该书的章节顺序，主要实现书上给出的例子。 

##已经实现：
###第三章
	- 链表
	- 栈
	- 队列
###第四章
	- 排序二叉树
	- 平衡二叉树
	- 伸展树（自底向上）
	- 伸展树（自顶往下）
###第五章
	- 哈希表（分离链接法）
	- 哈希表（开放定址法）
###第六章
	- 二叉堆
	- 左式堆
	- 二项队列
###第七章
	- 插入排序
	- 希尔排序
	- 堆排序
	- 归并排序
	- 快速排序
###第八章
	-不相交集
###第九章
	-邻接表(Versioni 1,2)
	-拓扑排序(Versioni 1,2)
	-单源最短路径算法
	-最大网络流
	-最小生成树
	-深度优先搜索
	-双连通性
	-欧拉回路
###第十章
	-分治算法：最近点问题
	-动态规划：斐波那契数列，递归关系，矩阵乘法顺序，最优搜索二叉树
	-随机化算法：跳表
	-回溯法：收费公路重建，三连棋游戏（带AI）
###第十二章
	-红黑树：自顶向下插入，自顶向下删除
	-AA树
	-Treap树
	-Kd树
	-配对堆
##文件内容
其中链表，栈，队列只给出了.h与.cpp文件  
其他所有实现均给出了.h .cpp文件以及测试的test.cpp代码  
编程平台是Vitual Studio 2010，使用c语言编写（其中有少部分使用std::cout输出）。


##我的博客
在我的博客中写下了这些数据结构的介绍，以及实现过程中遇到的问题，欢迎大家来我的博客：  
http://blog.csdn.net/yw8355507

##完成！
耗时两个月，每天晚上5个小时。终于把《数据结构与算法分析》一书中，几乎所有的数据结构，以及它所提及的算法全部实现！（除了少数特别简单的未实现）  
 
感慨万千，亲手实现数据结构与算法的过程，让我学习到了太多太多的东西:   
**1.** **递归：**    
以前编码的过程中，对于递归与非递归的转化是非常的不熟练的。现在无论怎么切换，头脑中都会有一个分层的模型可以模拟出整个的处理过程，并且现在可以非常熟练的使用递归来化简编码。

**2.** **时间空间分析：**   
现在，我已经可以非常轻松的来评估一个算法的时间复杂度，空间复杂度。对于递归过程也能确定是否需要使用动态规划来处理。对于整个程序的运行时间已经可以轻松估计了。

**3.** **数据结构与算法选择：**   
不夸张的说，现在看见网上的算法练习题，或者是公司的笔试题，第一遍就能立刻找到解法，然后可以进一步的通过选择合理的数据结构与算法，来尝试降低算法的复杂度。特别是对于hash表，优先队列，排序等等问题，似乎已经没有多少难度。
  
**4.** **攻克难题的信心：**   
在实现这本书上的算法时，有许多算法书上基本就是顺带一提，或者一个很难的算法随意讲一讲。我总是尝试通过各种方法来把这个算法实现。      
1. 首先是博客，书上讲的不清楚，别人的博客里总有讲的清楚的吧，最典型的例子就是伸展树的学习。书上大致一提，然后通过别人的博客，彻底学明白了，然后实现了出来。   
2. 其次是自行尝试优化：图论中，寻找欧拉回路，要达到算法复杂度O(E+V)，最初在网上博客中寻找，别人的博客中，要不是达不到这个复杂度，要不就是说的和书上一样含糊，而且没有实现的代码。一不做二不休，先写出可以用的再来优化，结果写完第一遍之后，就明白了该如何优化，书上即使不给我指导，我自己也能找出来，最后一共修改了3次代码，最后达到了书上所说的复杂度。

**4.** **调试的能力与耐心：**   
说实话，二叉树这种带有指针的东西，特别是有父亲节点的时候，是最不好调试的。而且，在编码过程中，我犯过的错误不仅仅是逻辑错误，还有许多编码的错误，比如==写成=，这些细节都是编译器发现不了的，逐行阅读代码，也是自己没法注意到的。调试的过程，自己一步步加断点，打印，一步步缩小范围。找到出错的函数后，跟着代码一步步实现，最终都找出了bug。没有放弃一个代码，全部都完成了debug。

##下一步计划:
现在书单中还有《现代操作系统》，《深入理解计算机系统》，《APUE》，《Effective C++》《STL源码解析》等等书没有读完，最近事情也比较多，打算先看看操作系统，其他的书挑出重点来仔细读读，不再像数据结构这本书这样特别细的读了。再就是算法实习生这边，打算有时间再读读Python与机器学习的一些算法，CSS与HTML入个门，做一做小demo，让自己对前端的东西也能上手写一写。