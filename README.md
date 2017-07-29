# About CPython Internals
> 十小时学习 CPython 3.6 内部实现  

Python 的官方实现版本 CPython 是 C 语言实现的，对于想要深入学习 Python 实现过程的人来说（比如说我），缺少时效性强的指导手册。有一本 08 年出版的《Python 源码剖析》，算是影响力最大的一本了，但是也已经比较久远了。而且现在 Python 已经发布到 3.6.2 版本了，与 Python 2.x 在很多地方已经存在相当大的差异。

除此之外，网上还有一份公开课，是 [Python Tutor - Visualize Python, Java, JavaScript, TypeScript, Ruby, C, and C++ code execution](http://www.pythontutor.com/) 的作者 [Philip Guo](http://www.pgbovine.net/) 2014 年所授课程 CSC 253 中的一部分：[CPython internals: A ten-hour codewalk through the Python interpreter source code](http://pgbovine.net/cpython-internals.htm)。本课程以 CPython 2.7.8 为例，共分为九节课，深入浅出地介绍了 CPython 的内部实现机制。根据本课程，前后花了大概十个小时的时间，我试着探索、学习了 CPython 3.6.1 的源码。我将每节课学习、探索的笔记整合起来，制作了这一本《CPython Internals 学习笔记》，开源分享至 [GitHub - rainyear/CPython-Internals-Lecture-Notes: CPython Internals 学习笔记](https://github.com/rainyear/CPython-Internals-Lecture-Notes)。