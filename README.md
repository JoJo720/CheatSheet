# CS 自救指南

本菜鸟某211非科班，无培训经历，纯自己折腾，计算机外门汉，走了很多弯路。目前在某厂过着996的生活，最近实在是被自己给菜哭了，遂萌生了CS自救计划。迫于业余时间紧张，公司与外网管控严格，无法将公司学习笔记带回家整理，思量一番，决定制定课程表，使用 github 查看学习进度，解决资源隔离问题，于是，本仓库诞生.

**注：**

* **本课程是针对本人实际情况制定的，只能作为参考建议.**
* **本仓库参考网络资源及学习建议，持续完善中…**

## 课程简介

| 课程               | 参考书籍                                                     | 参考课程                                                     | 参考视频                                                     | 产出目标                                                     | 挑战难度 | 说明                                                         |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| 导论               | [《计算机程序的构造和解释》](https://book.douban.com/subject/1148282/) | [Brian Harvey 开设的 SICP 课程](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter)(Berkeley  61A) | B站 [Brian Harvey 开设的 SICP 课程](https://www.bilibili.com/video/av40460492/) | 完成配套的习题                                               | ⭐⭐⭐      | 大多数计算机专业本科教学以程序设计“导论”作为开始。这类课程的最佳版本不仅能满足初学者的需要，还适用于那些在初学编程阶段遗漏了某些有益的概念和程序设计模式的人。 |
| C语言基础          | The Absolute Beginner's Guide to C(或其它C语言参考书)        | 密歇根州立大学[CSE 251 Programming in C](https://www.cse.msu.edu/~cse251/index.html) | B站上有很多不错的C语言教程，自己找                           | 完成课程站点上的所有14个Steps实验+3个Projects                | ⭐⭐⭐      | （1）这门课相当于是CS101，为什么要学C语言？因为C语言是现在主流语言的鼻祖，也是主流系统编程语言，系统架构师必须懂C语言。另外，下门课程[深入理解计算机系统]需要C语言+Linux编程基础。 <br />（2）课程站点上面的PPT可以大致浏览一下，如果已经有足够编程基础的话，书可看可不看，关键是14个实验和3个项目要搞定。 |
| 深入理解计算机系统 | [深入理解计算机系统(CSAPP)](http://product.dangdang.com/24106647.html) | 华盛顿大学[CSE351: The Hardware/Software Interface](http://courses.cs.washington.edu/courses/cse351/) | B站 [Washington CSE351 2017](https://www.bilibili.com/video/BV1Zt411s7Gg) | 完成[CSAPP书籍配套的所有Labs](http://csapp.cs.cmu.edu/3e/labs.html) | ⭐⭐⭐⭐     | 这门课程是系统编程基础，也是后续操作系统/网络/数据库/编译等课程的基础，相关内容是通向系统架构师的基本功。这门课比较贴近企业实战，对动手能力要求很高，课程一大目标是要程序员写出对机器友好的高性能代码。 |
| 数据结构           | Head First Java + 数据结构书自选                             | 伯克利大学[CS61B Data Structures](https://sp19.datastructur.es/) | B站 [UCB CS 61B Data Structures](https://www.bilibili.com/video/BV1EJ411n72e) | 完成CS 61B站点上的所有Labs/Homeworks/Projects。              | ⭐⭐⭐⭐     | 数据结构的重要性毋庸置疑，伯克利的CS课程都是比较偏向实战型工程师的，纯理论的东西相对少。本课的重点是树立抽象编程思维，务必把所有Labs/Homeworks/Projects都搞定。 |
| 数学               | [《计算机科学中的数学》](https://book.douban.com/subject/33396340/) | MIT[6-042j-mathematics-for-computer-science-fall-2010](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/) | B站[[MIT]6.042/ 18.062J Mathematics for Computer Science,Fall 2010](https://www.bilibili.com/video/av668970666/) | 完成[MIT 6.042](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/)所有projects与exams | ⭐⭐⭐⭐⭐    | 从某个角度说，计算机科学是应用数学的一个“发育过度”的分支。尽管许多软件工程师试图——并且在不同程度上成功做到——忽视这一点，我们鼓励你用学习来拥抱数学。如若成功，比起那些没有掌握数学的人，你将获得巨大的竞争优势。 |
| 操作系统           | [操作系统导论(Operating Systems: Three Easy Pieces)](http://product.dangdang.com/27882546.html) | 麻省理工MIT 6.828 [Operating System Engineering](https://pdos.csail.mit.edu/6.828/2018/index.html) | B站 [HMC CS 134 2019 Operating System](https://www.bilibili.com/video/av47977122) | 完成MIT 6.828站点上的所有7个Labs                             | ⭐⭐⭐⭐⭐    | 6.828是MIT的神课，这门课难度不小，含金量也不小。如果能把所有实验都搞定，对操作系统的认识会有质的飞跃。 |
| 计算机网络         | [计算机网络：自顶向下方法](http://product.dangdang.com/25299722.html) | 斯坦福 [CS 144 Introduction to Computer Networking](https://cs144.github.io/) | B站 [斯坦福大学：CS144 计算机网络介绍](https://www.bilibili.com/video/BV137411Z7LR) | 完成CS 144 站点上的所有8个Labs。                             | ⭐⭐⭐⭐     | 计算机网络知识和技能，是互联网应用开发的基础，也是成为系统架构师的基础。这门CS 144和配套书《计算机网络：自顶向下方法》，是目前最佳的学习计算机网络基础的课程和参考书。这也是一门投入产出比比较高的课(学了马上能用)。 |
| 编译原理           | [Crafting Interpreters](https://www.craftinginterpreters.com/contents.html) 或者 [Write an Interpreter in Go](https://www.amazon.com/Writing-Interpreter-Go-Thorsten-Ball/dp/3982016118) | 斯坦福[[CS143](http://web.stanford.edu/class/cs143/)         | B站 [CS143 斯坦福编译原理](https://www.bilibili.com/video/BV1cE411f78c) | 参考[Crafting Interpreters](https://github.com/munificent/craftinginterpreters)，使用Java或者golang语言(或其它你熟悉的语言)，实现Lox小型编程语言。<br />或者，参考[Write an Interpreter in Go](https://interpreterbook.com/)，或[Write A Compiler in Go](https://compilerbook.com/)，使用Java语言实现Monkey小型语言。 | ⭐⭐⭐⭐⭐    | 视频可以不看，但是一定要自己动手实现一个小语言解释器或者编译器。 |
| 数据库系统         | [数据库系统概念](http://product.dangdang.com/22632572.html)  | 卡耐基梅隆CMU [15-445/645 Database Systems](https://15445.courses.cs.cmu.edu/fall2020/) | B站 [卡耐基梅隆大学15-445 数据库系统介绍](https://www.bilibili.com/video/BV1Cp4y1C7dv) | 参考[vanilladb项目](https://github.com/vanilladb/vanillacore)，使用golang语言实现clone版的vanilladb（原项目是Java实现的）。 | ⭐⭐⭐⭐⭐    | 视频/课程/书可以不看，但是一定要自己动手实现一个小型的数据库系统，包括服务器端的存储引擎、SQL解析器、查询引擎和JDBC访问接口。企业开发大部分是基于数据库的应用，如果要成为企业级架构师，必须对数据库底层实现有一定掌握。课程项目要求用golang，对golang语言不熟悉的，自己找资料自学，如果你按照课程计划坚持学到这门课，那么你已经具有足够基础，可以轻松pick up任何一门编程语言。 |
| 分布式系统         | [《数据密集型应用系统设计》](https://book.douban.com/subject/30329536/) | [MIT的6.824](https://pdos.csail.mit.edu/6.824/schedule.html) | [MIT的6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) | 完成[MIT的6.824](https://pdos.csail.mit.edu/6.824/schedule.html)所有Labs | ⭐⭐⭐⭐⭐    | 随着计算机在数量上的增加，计算机同样开始 *分散*。尽管商业公司过去愿意购买越来越大的大型机，现在的典型情况是，甚至很小的应用程序都同时在多台机器上运行。思考这样做的利弊权衡，即是分布式系统的研究所在，也是越来越重要的一项技能。 |

## 学习进度

### 课程：导论

…



## 相关资料

* [自学计算机科学](https://github.com/keithnull/TeachYourselfCS-CN/blob/master/TeachYourselfCS-CN.md)
* [一份硬核计算机科学CS自学计划](https://github.com/spring2go/cs_study_plan)
* [Open Source Society University](https://github.com/ossu/computer-science)
* [408专业课笔记](https://github.com/SSHeRun/CS-Xmind-Note)
* [浙江大学课程攻略共享计划](https://github.com/QSCTech/zju-icicles)
* [清华大学计算机系课程攻略](https://github.com/PKUanonym/REKCARC-TSC-UHT)

* [上海交通大学生存手册](https://github.com/SurviveSJTU/SurviveSJTUManual)

* [小鹤双拼](https://www.flypy.com/pin.html)