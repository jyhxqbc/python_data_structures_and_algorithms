# Python 算法与数据结构视频教程

## 课程简介
数据结构和算法是每个程序员需要掌握的基础知识之一，也是面试中跨不过的槛。目前关于 Python 算法和数据结构的中文资料比较欠缺，
笔者尝试录制视频教程帮助 Python 初学者掌握常用算法和数据结构，提升开发技能。
本教程是付费教程(文字内容和代码免费)，因为笔者录制的过程中除了购买软件、手写板等硬件之外，业余需要花费很多时间和精力来录制视频、查资料、编写课件和代码，养家糊口不容易，希望大家体谅。

## 链接

[网上阅读《Python 算法与数据结构教程 》](http://ningning.today/python_data_structures_and_algorithms/)

[github 链接](https://github.com/PegasusWang/python_data_structures_and_algorithms)

[readthedoc 电子书下载](http://python-data-structures-and-algorithms.readthedocs.io/zh/latest/)

## 痛点
- 讲 Python 数据结构和算法的资料很少，中文资料更少
- 很多自学 Python 的工程师对基础不够重视，面试也发现很多数据结构和算法不过关，很多人挂在了基础的数据结构和算法上
- 缺少工程应用场景下的讲解，很多讲算法的资料太『教科书化』。本书实现的代码工程上可用
- 网上很多视频教程比较水，收费还很不合理，纯属智商税

## 作者简介
目前就职于[知乎](https://www.zhihu.com/people/pegasus-wang/activities)，从实习期间接触 Python 起一直从事 Python 网站后端开发，有一定 Python 的使用和实践经验。

知乎专栏：
- [《Python 学习之路》](https://zhuanlan.zhihu.com/c_85234576)
- [《玩转vim(视频)》](https://zhuanlan.zhihu.com/vim-video)

电子书：[《Python web 入坑指南》](http://python-web-guide.readthedocs.io/zh/latest/<Paste>)

## 课程内容
包括我们在业务开发和面试中常用的算法和数据结构，希望可以帮助新人快速上手，很多老手写业务代码写多了很多基础知识忘记了，
也可以作为回顾。课程尽量用通俗的方式讲解，结合 python 语言和日常开发实践的经验，让没有太多基础和非科班的同学也能够理解。
对于每个算法和用到的数据结构我们需要知道:

- 原理
- Python 实现方式
- 时间、空间复杂度
- 使用场景，什么时候用

## 目录结构
这里讲解的章节我参考了下边教材中列举的一些书籍，并且自己设计了大纲，争取做到循序渐进，简单实用。因为实现一些高级数据结构的时候会用到
很多底层数据结构，防止跳跃太大导致读者理解困难。

课程的目录结构如下，每一章都有配套的文字讲义(markdown)，示例代码，视频讲解，详细的讲解一般会放在视频里，使用手写板来
进行板书，包括文字、图示、手动模拟算法过程等。

- 课程介绍
- 课程简介之笨方法学算法
- 抽象数据类型 ADT，面向对象编程
- 数组和列表
- 链表，高级链表。双链表，循环双端链表
- 队列，双端队列，循环双端队列
- 栈，栈溢出
- 算法分析，时间复杂度 大O 表示法
- 哈希表，散列冲突
- 字典
- 集合
- 递归
- 查找：线性查找和二分查找
- 基本排序算法
- 高级排序算法: 归并排序、快排
- 树，二叉树
- 堆与堆排序
- 图，dfs 和 bfs
- python 内置常用数据结构和算法的使用。list, dict, set, collections 模块，heapq 模块
- 面试笔试常考算法

## 编程语言
我们这里使用最近很火的Python。Python 入门简单而且是个多面手，在爬虫、web 后端、运维、数据分析、AI 方面领域都有 Python 的身影。
知乎、豆瓣、头条、饿了么、搜狐等公司都有广泛使用 Python。笔者日常工作使用也是 Python，有一定实践经验，
在知乎上维护了一个专栏[《Python 学习之路》](https://zhuanlan.zhihu.com/c_85234576)。

Python 抽象程度比较高， 我们能用更少的代码来实现功能，同时不用像 C/C++ 那样担心内存管理、指针操作等底层问题，
把主要心思放在算法逻辑本身而不是语言细节上，Python 也号称伪代码语言。所有代码示例使用 Python2/3 兼容代码，
不过只在 python3.5 下测试过，推荐用相同版本 Python。

## 受众
想要学习 Python 算法和数据结构的初、中级同学，包括自学的同学和本科低年级学生等。需要掌握 Python
的基本语法和面向对象编程的一些概念，我们这里只使用最基本的 Python 语法，不会再去介绍用到的 Python 语法糖。

# 预备知识
- 掌握 Python 基本语法，有过使用 Python 的经验。知道 class、module、yield 等
- 基本的面向对象编程知识，会定义和使用 Python 中的类 (class)
- 知道 Python 中的魔术方法，比如 `__len__` `__contains__`
- 无需太多数学基础，仅在算法时间复杂度分析的时候会用到一些简单数学知识。对于学习基础算法，逻辑思维可能更重要一些

## 教材
这里我参考过三本书：

[《算法图解》](https://book.douban.com/subject/26979890/): 图解的形式很适合新手，示例使用的是 python

[《Data Structures and Algorithms in Python》]( https://book.douban.com/subject/10607365/): 适合对 Python
和算法比较熟悉的同学，或者是有其他语言编程经验的同学。英文版，缺点是书中错误真的很多，代码有些无法运行

[《算法导论》第三版]( https://book.douban.com/subject/20432061/): 喜欢数学证明和板砖书的同学可以参考，有很多高级主题。使用伪代码


## 讲课形式

绘图演示+手写板+现场编码

我将使用绘图软件+手写板进行类似于纸笔形式的讲解，边讲边开个终端分成两个窗口，一个用 vim
编写代码，另一个窗口用来运行代码，所有代码我将会现场编写(还是很有挑战的)，不会像某些大学教师一样只喜欢念 ppt。
每个视频我会尽量控制时长，讲的内容尽量通俗易懂，摆脱学院派的授课方式。

你可以参考我在知乎发的专栏文章看下：

[那些年，我们一起跪过的算法题[视频]](https://zhuanlan.zhihu.com/p/35175401)

[抱歉，我是开发，你居然让我写单测[视频]](https://zhuanlan.zhihu.com/p/35352024)


## 课程特点

- 每个算法和数据结构都有讲义、视频(包含讲解、图示、手动模拟)、源代码。其中只有视频内容为付费内容
- 讲义循序渐进，结合自己的学习和使用经验讲解。github 上实时更新
- 视频演示更加直观易懂
- 演示代码实现思路，所有代码在视频里均现场编写
- 偏向工程应用和代码实现。代码直接可以用。每个文件都是自包含的，你可以直接运行和调试，这是目前大部分书籍做得不到位的地方
- 良好的工程实践：[编码之前碎碎念(工程实践)](http://python-web-guide.readthedocs.io/zh/latest/codingstyle/codingstyle.html)。
这是很多看了几本书没有太多业界实践经验就敢讲课的培训班老师教不了的。**知识廉价，经验无价**
- 每个实现都会有单测来验证，培养良好的编码和测试习惯，传授工程经验
- 结合 cpython 底层实现讲解（比如list 内存分配策略等），避免一些使用上的坑。并且会用 python 来模拟内置 dict 等的实现
- 每篇讲义后有思考题和延伸阅读链接，帮助大家加深思考和理解

## 资料

- 视频。包含所有讲解视频
- 代码示例。所有代码我会放到 github 上。
- markdown 讲义，包含视频内容的提要等内容
- 延伸阅读。我会附上一些阅读资料方便想深入学习的同学

## 如何获取每章代码

注意每一章目录里都有 py 文件，在电子书里看不到。clone 下代码找到对应目录里的 python 文件即是每章涉及到的代码。


## 如何学习
笔者讲课录制视频的过程也是自己再整理和学习的过程，录制视频之前需要参考很多资料
希望对所讲到的内容，你能够

- 理解所讲的每个数据结构和算法的
    - 原理
    - Python 实现方式
    - 时间、空间复杂度
    - 使用场景，什么时候用
- 自己尝试实现，如果抛开视频自己写起来有困难可以多看几次视频，一定要自己手动实现。很多面试可能会让手写
- 每章讲义后边都会有我设计的几个小问题，最好能够回答上来。同时还有代码练习题，你可以挑战下自己的掌握程度。
- 最好按照顺序循序渐进，每章都会有铺垫和联系

## 课程目标
掌握基本的算法和数据结构原理，能独立使用 Python 语言实现，能在日常开发中灵活选用数据结构。
对于找工作的同学提升面试成功率。


## 工具

推荐使用以下工具进行开发，如果使用编辑器最好装对 应 Python 插件：

- Pycharm
- Sublime
- Atom
- Vscode
- Vim
- Emacs


## 勘误

输出其实也是一种再学习的过程，中途需要查看大量资料、编写讲义、视频录制、代码编写等，难免有疏漏之处。
有出版社找过笔者想让我出书，一来自己对出书兴趣不大，另外感觉书籍相对视频不够直观，有错误也不能及时修改，打算直接把所有
文字内容讲义放到 github 上，供大家免费查阅。

如果你觉得文字内容或者视频内容有错误，欢迎在 github 上提 issue 讨论，我会修正相关内容，防止产生误导。


## 本电子书制作和写作方式
使用 mkdocs 和 markdown 构建，使用  Python-Markdown-Math 完成数学公式

安装依赖：
```sh
pip install mkdocs    # 制作电子书, http://markdown-docs-zh.readthedocs.io/zh_CN/latest/
# https://stackoverflow.com/questions/27882261/mkdocs-and-mathjax/31874157
pip install https://github.com/mitya57/python-markdown-math/archive/master.zip

# 或者直接
pip install -r requirements.txt

# 如果你 fork 了本项目，可以定期拉取主仓库的代码来获取更新，目前还在不断更新相关章节
```

编写并查看：
```sh
mkdocs serve     # 修改自动更新，浏览器打开 http://localhost:8000 访问
# 数学公式参考 https://www.zybuluo.com/codeep/note/163962
mkdocs gh-deploy    # 部署到自己的 github pages
```

您的打赏就是我写作的最大动力，呵呵哒!
<center>
![微信打赏](http://7ktuty.com1.z0.glb.clouddn.com/weixin_dashang.png)
</center>
