---
title: Fuzzing 学习资源汇总
date: 2019-03-08 21:17:19
tags:
- Fuzzing
- 学习资料
categories:
- 学习资料
- Fuzzing
---

**本文主要是向大家推荐一系列，用于fuzzing和Exploit开发初始阶段学习的资源合集，其中将包括相关的书籍，课程 – 免费或收费的，视频，工具，教程，以及一些供大家练习使用的靶机应用。**

# **fuzzing书籍：**

> [《模糊测试-强制性安全漏洞发掘》](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119)作者： Michael Sutton, Adam Greene, Pedram Amini。
>
> [《软件安全测试Fuzzing和zhi’laing质量保证](https://www.amazon.com/Fuzzing-Software-Security-Assurance-Information/dp/1596932147)[》](https://www.amazon.com/Fuzzing-Software-Security-Assurance-Information/dp/1596932147)作者：Ari Takanen, Charles Miller, and Jared D Demott。
>
> [《开源Fuzzing工具》](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950)作者： Gadi Evron and Noam Rathaus。
>
> [《Python灰帽子》](https://www.amazon.com/Gray-Hat-Python-Programming-Engineers/dp/1593271921)作者：Justin Seitz。

**注意：**以下书籍中的相关章节专注于Fuzzing。

> [《Shellcoder手册：发现和利用安全漏洞》（第15章节）](https://www.amazon.com/Shellcoders-Handbook-Discovering-Exploiting-Security/dp/047008023X)作者：Chris Anley, Dave Aitel, David Litchfield等。
>
> [《iOS黑客手册 – 第1章》](https://www.amazon.com/iOS-Hackers-Handbook-Charlie-Miller/dp/1118204123)作者：Charles Miller, Dino DaiZovi, Dion Blazakis, Ralf-Philip Weinmann, Stefan Esser。
>
> [《IDA Pro – IDA Pro Book：全球最受欢迎的反编译器非官方指南》](https://www.amazon.com/IDA-Pro-Book-2nd-ebook/dp/B005EI84TM)

# fuzzing课程/培训视频：

## **免费**

> [纽约大学Poly（查看更多视频）](https://vimeo.com/5236104) – 由Dan Guido免费提供。
>
> [Samclass.info（检查项目部分和第17章）](https://samsclass.info/127/127_F15.shtml) – 由Sam提供。
>
> [现代二进制开发（RPISEC） – 第15章](https://github.com/RPISEC/MBE) – 由RPISEC提供。
>
> [攻击性计算机安全 – 第6周](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) – 由W. Owen Redwood和Xiuwen Liu教授提供。

## **付费**

> [Offensive Security, ](https://www.offensive-security.com/information-security-training/)[CTP和高级Windows开发（AWE）](https://www.offensive-security.com/information-security-training/)
>
> [针对渗透测试的SANS 660/760高级Exploit开发](https://www.sans.org/course/advanced-exploit-development-penetration-testers)
>
> [Exodus Intelligence – 漏洞开发大师班](https://blog.exodusintel.com/2016/05/18/exodus-intelligence-2016-training-course/)

# 视频：

视频主要谈论fuzzing技术，工具以及最佳实践。

##  纽约大学Poly课程视频

> [Fuzzing 101 (Part 1)](https://vimeo.com/5236104) - Mike Zusman。
>
> [Fuzzing 101 (Part 2)](https://vimeo.com/5237484) - Mike Zusman。
>
> [Fuzzing 101 (2009)](https://vimeo.com/7574602) - Mike Zusman。
>
> [Fuzzing – Coursera软件安全课程](https://www.coursera.org/learn/software-security/lecture/VgyOn/fuzzing) – 由马里兰大学提供

## **会议讲座和教程**

> [Youtube上各种有关fuzzing的探讨](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD)[和演示文稿播放列表](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD) – 这些视频中有很多不错的内容
>
> [浏览器bug狩猎 – 最后一个人的回忆录](https://vimeo.com/109380793) – Atte Kettunen
>
> [将基于代码覆盖率的灰盒Fuzzing视为马尔科夫链](https://www.comp.nus.edu.sg/~mboehme/paper/CCS16.pdf)
>
> [DerbyCon 2016：Fuzzing基础知识……或如何破解软件](http://www.securitytube.net/video/16939)

# 教程和博客

文章和博客解释了fuzzing的方法，技术和最佳实践。

> [有效的文件格式Fuzzing](http://j00ru.vexillium.org/slides/2016/blackhat.pdf) – Mateusz“j00ru”Jurczyk @Black Hat 2016欧洲，伦敦
>
> [过去一年的Windows内核字体fuzzing第一部分成果 ](https://googleprojectzero.blogspot.in/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html)- 谷歌的Project Zero的一篇惊人的文章，描述了如何进行fuzzing和创建fuzzers。
>
> [过去一年的Windows内核字体fuzzing第二部分技术 ](https://googleprojectzero.blogspot.in/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html)- 谷歌的Project Zero的一篇惊人的文章，描述了fuzzing和创建fuzzers需要什么。
>
> [fuzzing项目中有趣的bug和资源](https://blog.fuzzing-project.org/) – 来自fuzzing-project.org。
>
> [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) – @BrandonPrry。
>
> [用AFL和libFuzzer轻松介绍C++代码fuzzing ](http://jefftrull.github.io/c++/clang/llvm/fuzzing/sanitizer/2015/11/27/fuzzing-with-sanitizers.html)- Jeff Trull。
>
> [15分钟fuzzing介绍 ](https://www.mwrinfosecurity.com/our-thinking/15-minute-guide-to-fuzzing/)- MWR安全。

注意：fuzzing.info已经为我们整合了许多优秀的资源，我不会重复他们的工作。我将会添加一些他们错过的论文。[Fuzzing Papers](https://fuzzing.info/papers/) - fuzzing.info

> [Fuzzing Blog](https://fuzzing.info/resources/) - fuzzing.info
>
> [Fuzzing中出现崩溃的根本原因分析](https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - Corelan团队。[Root cause analysis of integer flow](https://www.corelan.be/index.php/2013/07/02/root-cause-analysis-integer-overflows/) -Corelan团队。
>
> [Creating custom peach fuzzer publishers](http://blog.opensecurityresearch.com/2014/01/creating-custom-peach-fuzzer-publishers.html) - Open Security Research。
>
> [在](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/)[Fuzzing](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/)[大型开源项目之前需要考虑的七件事](https://www.linuxfoundation.org/blog/7-things-to-consider-before-fuzzing-a-large-open-source-project/) – Emily Ratliff。

> 

---

# 工具

1. 以时间和针对的系统的表格（待整理）
2. 采用到的技术与时间的表格（待整理）

有助于fuzzing应用的工具

## Cloud Fuzzers

在云环境中帮助fuzzing测试的Fuzzers。

### [Cloudfuzzer](https://github.com/ouspg/cloudfuzzer)

> 云fuzzing框架，可以轻松在云环境中运行自动化模糊测试。

---

## **文件系统 Fuzzers**

可帮助fuzzing文件格式的Fuzzers，如PDF，MP3，SWF等

### [MiniFuzz – Wayback Machine](https://web.archive.org/web/20140512203517/http://download.microsoft.com/download/D/6/E/D6EDC908-A1D7-4790-AB0B-66A8B35CD931/MiniFuzzSetup.msi)

> Microsoft提供的基本文件格式模糊测试工具。（Microsoft网站上不再提供）。

###  [AFL Fuzzer（仅适用于Linux）](http://lcamtuf.coredump.cx/afl/)

> Afl-fuzz是一种基于面向安全的模糊测试工具，它采用了一种新型的方式（编译时检测和遗传算法），来自动发掘干净的、有趣的测试案例，即在目标二进制中触发新的内部状态。这基本上改善了模糊代码的功能覆盖。该工具生成的简洁的合成语料库也可以用来传播其它更多的劳动型或资源密集型测试方案。与其他仪器化的模糊工具相比，afl-fuzz是以实用性而被设计的：它具有适度的性能开销，采用了多种高效的模糊战略，和努力最小化的技巧，基本上不需要配置，并且能够无缝处理复杂的、真实世界案例，以及常见的图像分析或文件压缩等。
>
>  **相关教程：**
>
> 1. [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) – @BrandonPrry。
> 2. [使用afl的persistent模式给capstone做模糊测试](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html) – @toasted_flakes。
>
> 3. [RAM磁盘以及从AFL Fuzzing中保存你的SSD](http://cipherdyne.org/blog/2014/12/ram-disks-and-saving-your-ssd-from-afl-fuzzing.html)
>
> 4. [使用American Fuzzy Lop狩猎Bug](https://josephg.com/blog/bug-hunting-with-american-fuzzy-lop/)
>
> 5. [American Fuzzy Lop在真实案例中的高级使用](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)
>
> 6. [使用afl-fuzz隔离Python](https://tomforb.es/segfaulting-python-with-afl-fuzz)
>
> 7. [Fuzzing Perl： American Fuzzy Lops的故事](http://www.geeknik.net/71nvhf1fp)
>
> 8. [使用AFL-Fuzz Fuzzing，一个练习示例（AFL vs Binutils）](https://www.evilsocket.net/2015/04/30/fuzzing-with-afl-fuzz-a-practical-example-afl-vs-binutils/)
>
> 9. [Fuzzing的重要性？](https://mgba.io/2016/09/13/fuzzing-emulators/)
>
> 10. [Heartbleed是如何被找到的](https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html)
>
> 11. [使用American Fuzzy lop Fuzzing文件系统](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)
>
> 12. [使用AFL Fuzzing Perl/XS模块](https://medium.com/@dgryski/fuzzing-perl-xs-modules-with-afl-4bfc2335dd90)
>
> 13. [AFL研讨会Fuzzing – 真正的漏洞带来的一系列挑战](https://github.com/ThalesIgnite/afl-training)
> 14. [AFL内部实现细节小记](http://rk700.github.io/2017/12/28/afl-internals/)
> 15. [afl-fuzz技术白皮书](https://blog.csdn.net/gengzhikui1992/article/details/50844857)
> 16. [如何使用AFL进行一次完整的fuzz过程](https://blog.csdn.net/abcdyzhang/article/details/53487683)
> 17. [AFL(American Fuzzy Lop)实现细节与文件变异](https://paper.seebug.org/496/)
> 18. [fuzz实战之libfuzzer](https://www.secpulse.com/archives/71898.html)

###  [Win AFL](https://github.com/ivanfratric/winafl)

>  Linux下的智能模糊测试神器afl-fuzz的Windows版本

###  [Shellphish Fuzzer](https://github.com/shellphish/fuzzer)

> AFL的Python接口，允许注入测试用例和其他功能。

###  [Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/)

> 一款智能模糊测试工具, 广泛用于发现软件中的漏洞和缺陷,它有两种主要模式,基于生长的模糊测试和基于变异的模糊测试。
>
>  **相关教程：**
>
>   1. [开始使用Peach](http://community.peachfuzzer.com/v2/PeachQuickstart.html)
>  2. [Peach Fuzzing第一部分](http://www.flinkd.org/fuzzing-with-peach-part-1/) – corelan团队Jason Kratzer
>  3. [Peach Fuzzing第二部分 ](http://www.flinkd.org/fuzzing-with-peach-part-2-fixups-2/)- corelan团队Jason Kratzer
>  4. [自动生成Peach pit文件/fuzzers ](http://doc.netzob.org/en/latest/tutorials/peach.html)- FrédéricGuihéry，Georges Bossert
>  5. **peach使用介绍：**[1、peach语法介绍](<https://www.kanxue.com/chm.htm?id=12592&pid=node1001008>)、[2、peach语法实战](<https://www.kanxue.com/chm.htm?id=12593&pid=node1001008>)、[3、Peach 实战之 gif 文件格式](<https://www.kanxue.com/chm.htm?id=12594&pid=node1001008>)、[4、Peach Pit 模版调试技巧](<https://www.kanxue.com/chm.htm?id=12595&pid=node1001008>)

###  [MozPeach](https://github.com/MozillaSecurity/peach)

> 由Mozilla Security提供的peach 2.7。

###  [rmadair ](http://rmadair.github.io/fuzzer/)

> 基于文件突变的fuzz测试工具，使用PyDBG来监测感兴趣的信号。

###  [honggfuzz-2015(google)](https://github.com/google/honggfuzz)

> 一个易于使用的fuzzer以及有趣的分析选项。支持基于代码覆盖的feedback-driven fuzzing。同时支持GNU/Linux，FreeBSD，Mac OSX和Android系统。
>
> **相关资料：**
>
> 1. [riusksk分析](https://bbs.pediy.com/thread-247954.htm)
> 2. 

###  [zzuf-2007](https://github.com/samhocevar/zzuf)

> zzuf是一个透明的应用程序输入模糊器。其目的是通过破坏用户提供的数据来查找应用程序中的错误（这些数据通常来自Internet上不受信任的来源）。它的工作原理是拦截文件和网络操作，并改变程序输入中的随机位。zzuf的行为是确定性的，可以更容易地重现错误。其主要使用领域是：
>
> - **质量保证**：使用zzuf测试现有软件，或将其集成到您自己软件的测试套件中
> - **安全性**：通常，分段错误或内存损坏问题意味着潜在的安全漏洞，zzuf有助于暴露其中一些漏洞
> - **代码覆盖率分析**：使用zzuf最大化代码覆盖率
>
> zzuf的主要目标是媒体播放器，图像浏览器和Web浏览器，因为它们处理的数据本质上是不安全的，但它也成功地用于查找系统实用程序（如objdump）中的错误。
>
> **相关资料：**
>
> 1. [使用手册](http://caca.zoy.org/wiki/zzuf)

###  [radamsa-2012](https://gitlab.com/akihe/radamsa)

> 它通常用于测试程序如何能够承受格式错误和潜在的恶意输入。它的工作原理是读取有效数据的样本文件，并从中生成有意义的不同输出。radamsa的主要卖点是它已经在程序中找到了大量的错误，这些错误实际上很重要，它易于编写脚本，并且易于启动和运行。
>
> **相关资料：**
>
> 1. [相应PPT](http://www.cs.tut.fi/tapahtumat/testaus12/kalvot/Wieser_20120606radamsa-coverage.pdf)

###  [binspector](https://github.com/binspector/binspector)

> 二进制格式分析和模糊测试工具

### [grammarinator](https://github.com/renatahodovan/grammarinator)

> 基于ANTLR v4语法的文件格式模糊测试工具（ANTLR项目中已有多种语法可用）。
### [PerfFuzz-2018](<https://github.com/carolemieux/perffuzz>)

> 当程序被提供具有病理行为的输入时，软件中的性能问题可能意外地出现。但是我们怎样才能首先找到这些输入？PerfFuzz可以自动生成这样的输入：给定一个程序和至少一个种子输入，PerfFuzz自动生成输入，在没有任何领域知识的情况下，跨程序位置运行病理行为。PerfFuzz使用多维性能反馈，独立地最大化所有程序位置的执行计数。这使PerfFuzz能够找到各种输入，在程序中运行不同的热点。
>
>  **相关资料：**
>
> 1. [论文(ISSTA’18)](<http://www.carolemieux.com/perffuzz-issta2018.pdf>)

### [FairFuzz-2018](<https://github.com/Ljiee/fairfuzz>)

> AFL扩展，通过定位稀有分支来增加代码覆盖率。FairFuzz在具有高度嵌套结构的程序（数据包分析器，xmllint，使用laf-inte编译的程序等）上具有特殊优势。
>
>  **相关资料：**
>
> 1. [论文ASE ’18](<http://www.carolemieux.com/fairfuzz-ase18.pdf>)

### [Vuzzer-2017](https://github.com/vusec/vuzzer)

> 该工具提出了一种应用程序感知的进化模糊测试策略，它不需要任何有关应用程序或输入格式的先验知识。为了最大化覆盖范围并探索更深入的路径，该工具利用基于静态和动态分析的控制和数据流特征来推断应用程序的基本属性。与应用程序无关的方法相比，这可以更快地生成有趣的输入。我们在VUzzer中实现我们的模糊测试策略并在三个不同的数据集上进行评估：DARPA Grand Challenge二进制文件（CGC），一组实际应用程序（二进制输入解析器）和最近发布的LAVA数据集。
>
>  **相关资料：**
>
> 1. [论文NDSS ’17](<http://www.cs.vu.nl//~giuffrida/papers/vuzzer-ndss-2017.pdf>)
> 2. [工具所用污点分析数据存储结构：EWAHBoolArray](https：//github.com/lemire/EWAHBoolArray)
> 3. [APLPIN](https://github.com/mothran/aflpin)
> 4. [DECREE](https://github.com/CyberGrandChallenge/cgc-releasedocumentation/blob/master/walk-throughs/pin-for-decree.md)
> 5. [AFLFAST](https://github.com/mboehme/aflfast)

### [sanitizers-2016（google）](https://github.com/Google/sanitizers)

> Google项目，包括AddressSanitizer(检测可寻地址问题), MemorySanitizer(检测未初始化内存的使用), ThreadSanitizer（检测数据争用和死锁问题）, LeakSanitizer（检测内存泄露问题）。
>
> 

### [CERT Basic Fuzzing Framework (BFF) For Linux-2014](https://github.com/CERTCC/certfuzz)

> CERT Basic Fuzzing Framework（BFF）是一种软件测试工具，可以在Linux，Mac OS X和Windows上运行的应用程序中发现缺陷。BFF对消耗文件输入的软件执行突变模糊测试。它们会自动收集导致软件以独特方式崩溃的测试用例，以及调试与崩溃相关的信息。BFF的目标是最大限度地减少软件供应商和安全研究人员有效发现和分析通过模糊测试发现的安全漏洞所需的工作量。基于zzuf框架实现

### [CERT Failure Observation Engine (FOE)For windows-2014](https://vuls.cert.org/confluence/display/tools/Home)

> The cert Failure Observation Engine (FOE) 是一个软件测试工具，它被用于在Windows平台上运行的应用程序中发现漏洞。FOE在消耗文件输入的软件上执行突变模糊测试。（突变性模糊测试是采取形式良好的输入数据并以各种方式破坏它的行为，寻找导致崩溃的情况。）FOE自动收集导致了软件以独特方式使测试用例崩溃，以及利用崩溃来调试信息。FOE的目标是最大限度地减少软件供应商和安全研究人员有效发现和分析通过模糊测试发现的安全漏洞所需的工作量。
>
> **相关资料：**
>
> 1. [使用FOE Fuzzing](https://samsclass.info/127/proj/p16-fuzz.htm) – Samclass.info

### [KEMUfuzzer-2010](<https://github.com/jrmuizel/kemufuzzer>)

> KEmuFuzzer是一个基于仿真或直接本地执行测试系统虚拟机的工具。 目前KEmuFuzzer支持：BHOCS，QEMU，VMware和virtualbox。
>
> **相关资料：**
>
> 1. [相关PPT](https://pdfs.semanticscholar.org/e48e/fb9187655ab1393f497f9330e8340b09e643.pdf) 

### [Pathgrind-2013](<https://github.com/jrmuizel/kemufuzzer>)

> Pathgrind使用基于路径的动态分析来fuzz linux / unix二进制。 它是基于valgrind被写在python内的。
>
> **相关资料：**
>
> 1. [相关PPT](https://pdfs.semanticscholar.org/e48e/fb9187655ab1393f497f9330e8340b09e643.pdf) 

### [QuickFuzz-2017](https://github.com/CIFASIS/QuickFuzz)

> QuickFuzz是一个用Haskell编写的工具，用于测试第三方软件上常见文件格式的意外输入，利用现成的，众所周知的模糊器。与其他世代模糊器不同，QuickFuzz不需要为相关文件格式编写规范，因为它依赖于Haskell代码库中可用的现有文件格式处理库。QuickFuzz是开源的（GPL3），它可以使用其他错误检测工具，如[zzuf](http://caca.zoy.org/wiki/zzuf)，[radamsa](https://github.com/aoh/radamsa)，[honggfuzz](http://google.github.io/honggfuzz/)和[valgrind](http://valgrind.org/)。
>
> **相关资料：**
>
> 1. [主页介绍](http://quickfuzz.cifasis-conicet.gov.ar/) 
> 2. [论文:《QuickFuzz testing for fun and profit》](https://dl.acm.org/citation.cfm?id=3163968)
> 3. [另外一篇相同名称论文：《QuickFuzz: An Automatic Random
>   Fuzzer for Common File Formats》](https://people.seas.harvard.edu/~pbuiras/publications/QFHaskell2016.pdf)

### [SymFuzz-2015](https://github.com/maurer/symfuzz)

> 提出了一个算法的设计，以最大化数量的bug为黑盒子突变性的模糊给定一个程序和种子的输入。主要的直观性的是利用给定程序 - 种子对的执行轨迹上的白盒符号进行分析，来检测输入的BIT位置之间的依赖性，然后使用这种依赖关系来为该程序种子对计算概率上最佳的突变比率。
>
> **相关资料：**
>
> 1. [论文：《Program-Adaptive Mutational Fuzzing》](https://ieeexplore.ieee.org/document/7163057?arnumber=7163057) 

### [Choronzon-2015](https://github.com/CENSUS/choronzon)

>Choronzon是一个进化型的模糊工具。它试图模仿进化过程，以保持产生更好的结果。 为了实现这一点，它具有评估系统的能力，用以分类哪些模糊文件是有趣的，哪些应该被丢弃。
>此外，Choronzon是一个基于知识的模糊器。 它使用用户定义的信息来读取和写入目标文件格式的文件。要熟悉Choronzon的术语，您应该考虑每个文件由染色体表示。用户应该描述所考虑的文件格式的基本结构， 优选文件格式的高级概述，而不是描述它的每个细节和方面。那些用户定义的基本结构中的每一个都被认为是基因， 每个染色体包含一个基因树，并且它能够从中构建相应的文件。
>
>**相关资料：**
>
>1. [演讲视频](https://www.youtube.com/watch?v=WafsYOCl8hQ) 
>
>2. [演讲PPT》](https://census-labs.com/media/choronzon-zeronights-2015.pdf)
>
>   

### [Hodor-2016](https://github.com/nccgroup/Hodor)

> 它可以配置为使用已知良好的输入和分隔符来fuzz特定的位置。在一个完全愚蠢的模糊器和一些更聪明的东西之间，与实现一个合适的智能模糊器相比，它的努力要少得多。



---

## **机器学习 Fuzzers**

### [Neural Fuzzer-2016](https://github.com/CIFASIS/neural-fuzzer)

> Neural-Fuzzer是一款实验性模糊器，旨在使用最先进的机器学习来学习一组初始文件。它分两个阶段进行：**培训**和**生成**。
>
> - 在训练模式中：它使用[长短期记忆（LSTM）](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)来学习字节序列的结构。
> - 在生成模式下：它将自动生成损坏或意外的文件，它将尝试使给定的程序崩溃。
>
> Neural-Fuzzer是开源的（GPL3），由[keras](http://keras.io/)驱动，类似于[rnn-char](https://github.com/karpathy/char-rnn)和序列预测中的其他技术。



### [Pulsar-2015-协议](https://github.com/hgascon/pulsar)

> Pulsar是一种具有自动协议学习和仿真功能的网络模糊器。该工具允许通过机器学习技术建模协议，例如聚类和隐马尔可夫模型。这些模型可用于模拟Pulsar与真实客户端或服务器之间的通信，这要归功于语义正确的消息，这些消息与一系列模糊测试原语相结合，允许在其协议状态的更深层状态下测试未知协议的实现是否存在错误机。
>
> **相关资料：**
>
> 1. [论文：《PULSAR: Stateful Black-Box Fuzzing of
>    Proprietary Network Protocols》](https://ieeexplore.ieee.org/document/7163057?arnumber=7163057) 

### [RamFuzz-2017](https://github.com/dekimir/RamFuzz)

> RamFuzz是单元测试中各个方法参数的模糊器。单元测试可以使用RamFuzz为被测方法生成随机参数值。记录这些值，并且可以重播日志以重复完全相同的测试方案。但随机参数值不仅限于基本类型：RamFuzz还可以从用户代码中自动生成任何类的随机对象。这允许用户模糊接受类参数的方法。例如，如果一个方法采用a `int`，a `struct S`和a `class C`作为参数，RamFuzz可以随机生成它们！测试作者不必担心创建`S`和`C`对象的技术性; RamFuzz会自动完成。
>
> 为此，RamFuzz包含一个代码生成器，它读取C ++源代码并从中生成一些测试代码。此测试代码通过随机选择的构造函数创建类实例，然后继续使用随机生成的参数调用实例方法的随机序列。结果是一个随机类对象，可以将该类作为参数提供给任何方法。
>
> 当然，这会产生表面上非常有用的表面测试 - 大多数方法不会采用完全随机的参数，而是以某种方式约束它们。目的是可以从许多RamFuzz测试运行的日志中自动推断出这些约束。由于测试是随机的，因此每次运行都是一种不同的方案，可以增加测试代码的覆盖范围。如果随机性质良好，则长时间反复运行测试将涵盖各种可能的参数值，可能包括一些完全有效的测试。然后可以使用这些日志来训练AI以识别哪些参数值有效。或者，可以使用模糊测试策略来引导参数值生成向有效测试的演变。
>
> RamFuzz提供了一些Python工具，可以轻松地在其生成的日志上训练AI - 请参阅[`ai`](https://github.com/dekimir/RamFuzz/blob/master/ai)目录和[概述文件](https://github.com/dekimir/RamFuzz/blob/master/sci/ramfuzz.md)。例如，可以训练神经网络以基于其RamFuzz日志准确地预测测试运行的结果。这是可能的，因为RamFuzz设法提供足够多的测试运行，以便识别成功和不成功的内容。
>
> 但请注意，RamFuzz不会自动生成方法调用结果的测试断言。将创建其他项目以自动完成，但RamFuzz将通过方便地处理参数模糊测试和日志记录来实现。
>
> RamFuzz是在Apache 2.0许可下提供的。它目前仅支持输入C ++（请参阅下面的“已知限制”），它需要C ++ 11支持来编译其输出代码和运行时
>
> [论文：《RamFuzz: A Framework for C++ Test Generation via Deep Learning》](https://github.com/dekimir/RamFuzz/blob/master/sci/ramfuzz.md#ramfuzz-a-framework-for-c-test-generation-via-deep-learning) 

------

## **Kernel Fuzzers**

### [TriforceAFL-2016](https://github.com/nccgroup/TriforceAFL)

> AFL / QEMU 模糊器具有全系统的仿真。这是AFL的修补版本，支持使用QEMU的全系统模糊测试。它所包含的QEMU已经更新，允许在运行x86_64的系统仿真器时进行分支机构跟踪。它也添加了额外的指令来启动AFL的forkserver，进行模糊设置，并标记测试用例的启动和停止。
>
> **相关资料：**
>
> 1. [project](https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2016/june/project-triforce-run-afl-on-everything/)

### [KernelFuzzer-2016](https://github.com/mwrlabs/KernelFuzzer)

> 跨平台内核Fuzzer框架
>
> **相关资料：**
>
> 1. [主页文档介绍](https://labs.mwrinfosecurity.com/publications/platform-agnostic-kernel-fuzzing/)
> 2. [视频文档讲解](https://www.youtube.com/watch?v=M8ThCIfVXow)



### [syzkaller-2017(google)](https://github.com/google/syzkaller)

> syzkaller是一个无监督的覆盖引导内核模糊器。目前还在持续更新，readme上列出了其它相关的文档资料。
>
> **相关资料：**
>
> 1. [基于syzkaller的研究工作](https://github.com/google/syzkaller/blob/master/docs/research.md)
> 2. 来自HardenedLinux项目：
>    - [使用syzkaller和qemu的内核质量保证](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syzkaller_general.md)（关于如何使用qemu设置syzkaller的教程）
>    - [Syzkaller崩溃DEMO](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syzkaller_crash_demo.md)（关于如何使用新的系统调用扩展syzkaller的教程）
>    - [使用syzkaller的内核调试工具](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syz_debug.md)（由syz-manager和gdb创建的调试qemu VM）
>    - [一些syzkaller内部的解释](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_qa/fuzz_testing/syz_analysis.md)
>    - [模糊ceph文件系统的一个例子](https://github.com/hardenedlinux/Debian-GNU-Linux-Profiles/tree/master/docs/harbian_qa/fuzz_testing/syz_for_ceph)
> 3. [使用syzkaller进行覆盖引导内核模糊测试](https://lwn.net/Articles/677764/)（作者David Drysdale）
> 4. [ubsan，kasan，syzkaller und co](http://www.strlen.de/talks/debug-w-syzkaller.pdf)（[视频](https://www.youtube.com/watch?v=Acp0A9X1254)）（作者：Florian Westphal）
> 5. [调试syzkaller发现的内核崩溃](http://vegardno.blogspot.de/2016/08/sync-debug.html)（作者：Quentin Casasnovas）
> 6. [Linux管道工2016年谈话幻灯片](https://docs.google.com/presentation/d/1iAuTvzt_xvDzS2misXwlYko_VDvpvCmDevMOq2rXIcA/edit?usp=sharing)
> 7. [syzkaller：下一代内核fuzzer](https://www.slideshare.net/DmitryVyukov/syzkaller-the-next-gen-kernel-fuzzer)（操作基础，如何运行syzkaller以及如何将其扩展到模糊新驱动程序的教程）
> 8. [syzbot和一千个内核bug的故事](https://events.linuxfoundation.org/wp-content/uploads/2017/11/Syzbot-and-the-Tale-of-Thousand-Kernel-Bugs-Dmitry-Vyukov-Google.pdf) [ [视频](https://www.youtube.com/watch?v=qrBVXxZDVQY) ]



## **浏览器 Fuzzers**

###  [Nightmare-2017](https://github.com/segmentio/nightmare)

> Nightmare是Segment的高级浏览器自动化库。 目标是探索一些模仿用户操作的简单方法（如goto，type和click），使用对每个脚本块感觉同步的API，而不是深层嵌套的回调。它最初设计用于在没有API的站点之间自动执行任务，但最常用于UI测试和网络爬虫。
>
> github 上start数量16992多。

### [IFuzzer-2016](https://github.com/vspandan/IFuzzer)

> 该论文主要是针对脚本引擎的fuzz，只是文中使用了js engine作为目标。核心思想就是：收集大量的测试代码，使用antlr4编写好的语法解析器解析出`非终结符片段`，把输入解析成AST后，在AST上进行变异。变异的方式主要是利用收集的“片段”去替换解析树中相同非终结符，由于采用了遗传算法，通过对每个个体的评估，筛选优秀的个体进行“杂交”产生新的个体进入下一轮fuzz，“杂交”的方法是交换两个个体中相同的非终结符节点，产生两棵新的输。
>
>  **相关资料：**
>
> 1. [论文-ESORICS 2016](https://link.springer.com/chapter/10.1007/978-3-319-45744-4_29)
> 2. [论文笔记](http://muhe.live/2018/06/09/%E8%AE%BA%E6%96%87%E9%98%85%E8%AF%BB-IFuzzer-An-Evolutionary-Interpreter-Fuzzer-using-Genetic-Programming/)-@muhe

### [Wadi-fuzzer](https://github.com/sensepost/wadi)

> Wadi是基于web浏览器语法的模糊器。 这个语法用于描述浏览器应该如何处理Web内容，Wadi转向并使用语法来打破浏览器。
> Wadi是一个Fuzzing模块，用于NodeFuzz fuzzing Harness并利用AddressSanitizer（ASan）在Linux和Mac OSX上进行测试。
>
> **相关资料：**
>
> 1. [官方文档介绍](https://sensepost.com/blog/2015/wadi-fuzzer/)
>

### [NodeFuzz-2012](https://github.com/attekett/NodeFuzz)

> NodeFuzz是用于Web浏览器和类似浏览器的应用程序的模糊控制器。NodeFuzz背后有两个主要思想。首先是创建一种简单快速的模糊不同浏览器的方法。第二个是使用新的测试用例生成器和客户端仪器轻松扩展一个线束，而无需对内核进行修改。
>
> **相关资料：**
>
> 1. [介绍](https://code.google.com/archive/p/ouspg/wikis/NodeFuzz.wiki)

### [Grinder-2011](https://github.com/attekett/NodeFuzz)

> Grinder是一个自动化Web浏览器模糊测试和大量崩溃管理的系统。Grinder节点提供了一种fuzz浏览器的自动方式，并生成有用的崩溃信息（例如带有符号信息的调用堆栈以及可用于在稍后阶段生成可重现的测试用例的日志信息）。Grinder Server提供了一个整理崩溃的中心位置，并通过Web界面允许多个用户登录和管理所有Grinder节点生成的所有崩溃。
>
> **相关资料：**
>
> 1. [介绍](https://code.google.com/archive/p/ouspg/wikis/NodeFuzz.wiki)

### [Kitty-2016](https://github.com/Cisco-sas/kitty)

> Kitty是一个用python编写的开源模块化和可扩展的模糊测试框架，受OpenRCE的[Sulley](https://github.com/OpenRCE/sulley) 和Michael Eddington（以及现在的Deja Vu Security的）[Peach Fuzzer的](http://community.peachfuzzer.com/)启发。(**还在更新**)
>
> 当我们开始编写Kitty时，我们的目标是帮助我们模糊不寻常的目标 - 意味着通过非TCP / IP通信通道的专有和深奥的协议 - 无需每次都从头开始编写所有内容。一个通用的抽象框架，包括我们可以想到的每个模糊过程的共同功能，并允许用户轻松扩展并使用它来测试他们的特定目标。
>
> [Katnip](https://github.com/cisco-sas/katnip)是[Kitty](https://github.com/cisco-sas/kitty)的实现和扩展的存储库。虽然Kitty定义了基类和语法，但它不包含任何特定的实现。因此，例如，为了通过TCP发送有效负载，您需要创建一些扩展`ServerTarget` 并能够通过TCP发送数据的类，依此类推。Katnip包含这样的课程。目前，Katnip包含以下各种实现：
>
> - 服务器和客户端的控制器
> - 显示器
> - 目标
> - 积木
> - 模板
>
> **相关资料：**
>
> 1. [Kitty介绍](https://kitty.readthedocs.io/en/latest/)
> 2. [Katnip介绍](https://katnip.readthedocs.io/en/latest/)

------

## **ActiveX Fuzzers**

### [dranzer](https://github.com/CERTCC/dranzer)(2012)

>Dranzer是一个工具，使用户能够检查模糊测试ActiveX控件的有效技术。拥有第二个版本[dranzer2.0](https://sourceforge.net/projects/enhanceddranzer/files/dranzer/)

---

## **Library Fuzeers**

### [libFuzzer](http://llvm.org/docs/LibFuzzer.html)

> C/C++编写的目标进程内覆盖引导渐进式fuzzing引擎。基于LibFuzzer实现的两个fuzzer：clang-format-fuzzer和clang-fuzzer。Clang格式大多是一个词法分析器，所以给它随机字节格式是会完美运行的，但也伴随着超过20个错误。然而Clang不仅仅是一个词法分析器，给它随机字节时几乎没有划伤其表面，所以除了测试随机字节，我们还在令牌感知模式中模糊了Clang。两种模式中都发现了错误; 其中一些以前被AFL检测到，另一些则不是：我们使用AddressSanitizer运行这个模糊器，结果发现一些错误在没有它的情况下不容易被发现。
>
>
> **相关资料：**
>
> 1. [libFuzzer教程](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
> 2. [LLVM主页官方文档介绍](http://llvm.org/docs/LibFuzzer.html)
> 3. [libFuzzer研讨会：“C/C++项目的现代fuzzing](https://github.com/Dor1s/libfuzzer-workshop)
> 4. [clang-format-fuzzer](http://llvm.org/viewvc/llvm-project/cfe/trunk/tools/clang-format/)
> 5. [clang-fuzzer](http://llvm.org/viewvc/llvm-project/cfe/trunk/tools/clang-fuzzer/)



---

## **网络协议Fuzzers**

可帮助fuzzing使用基于网络协议（如HTTP, SSH, SMTP等）的应用程序Fuzzers。

###  [Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/)

>  一款智能模糊测试工具, 广泛用于发现软件中的漏洞和缺陷,它有两种主要模式,基于生长的模糊测试和基于变异的模糊测试。

###  [Sulley](https://github.com/OpenRCE/sulley)

> Sulley是一个积极开发的模糊引擎和模糊测试框架，由多个可扩展组件组成。Sulley（IMHO）超过了此前公布的大所属模糊技术、商业和公共领域的能力。框架的目标是不仅是可以简化数据表示，而且也可以简化数据传输和仪表。Sulley是以 Monsters Inc.的生物来命名的，因为，他是模糊的。写在python内的。

### [Sulley_l2](<http://ernw.de/download/sulley_l2.tar.bz2>)

> 有些人可能记得2008年发布的sulley_l2，它是sulley模糊框架的修改版本，增强了第2层发送功能和一堆（L2）模糊脚本。

###  [boofuzz](https://github.com/jtpereyda/boofuzz)

> Sulley框架的分支和继承。





###  [backfuzz-2012](https://github.com/localh0t/backfuzz)

> 一个用python写成的有着不同协议（FTP，HTTP，IMAP等）的模糊工具,

###  [Spike](http://www.immunitysec.com/downloads/SPIKE2.9.tgz)

> 一个fuzzer开发框架。
>
> ### **相关资料：**
>
> 1. [使用Spike Fuzzing查找溢出](https://null-byte.wonderhowto.com/how-to/hack-like-pro-build-your-own-exploits-part-3-fuzzing-with-spike-find-overflows-0162789/)
>
> 2. [使用Spike Fuzzing](https://samsclass.info/127/proj/p18-spike.htm) – samclass.info

###  Metasploit框架

> 通过辅助模块包含一些fuzzing功能的框架。

### [Nightmare](https://github.com/joxeankoret/nightmare)

> 带有Web管理的分布式模糊测试套件，支持使用网络协议进行模糊测试。

### [Dizzy-2018](https://github.com/ernw/dizzy)

> dizzy是一个模糊的框架，用python编写，能够通过大量输出选项进行状态完全和无状态模糊测试。1.可以发送到L2以及上层（TCP / UDP / SCTP）。2.能够处理奇长度分组字段（无需匹配字节边界，因此即使单个标志或7位长字。3.也可以表示和模糊）。4.非常容易的协议定义语法。5.能够做多包状态的完全模糊，能够使用接收到的目标数据作为响应

----

## **分布式 Fuzzers**

### [FuzzFlow-2016](https://github.com/talos-vulndev/FuzzFlow)

> Fuzzflow是来自cisco talos的一个分布式的模糊管理框架，它提供虚拟机管理，模糊作业配、可插拔变异引擎、前/后变形脚本、崩溃收集和可插拔崩溃分析。FuzzFlow是一种基于concolic执行的自动化测试生成工具。FuzzFlow利用动态二进制检测来修改x86 ELF二进制文件，以便为污点分析启用数据流跟踪。通过分析附近约束的数据流路径并通过转换二进制来进行符号执行来解决新输入，从而生成新测试。
>
> ### **相关资料：**
>
> 1. [主页](https://www.talosintelligence.com/moflow)



### [fuzzinator-2018](https://github.com/renatahodovan/fuzzinator)

> *Fuzzinator*是一个模糊测试框架，可帮助您自动执行模糊会话期间通常需要的任务：
>
> - 运行您最喜欢的测试生成器并将测试用例提供给被测系统，
> - 抓住并保存独特的问题，
> - 减少失败的测试用例，
> - 简化bug跟踪器中问题的报告（例如，Bugzilla或GitHub），
> - 如果需要，定期更新SUT
> - 安排多个SUT和发电机，而不会使工作站过载。
>
> ### **相关资料：**
>
> 1. [PPT](https://www.slideshare.net/hodovanrenata/fuzzinator-in-bug-we-trust)
> 2. [教程](https://github.com/renatahodovan/fuzzinator/blob/master/docs/tutorial.rst)
> 3. [论文《Fuzzinator: An Open-Source Modular Random Testing Framework》](https://ieeexplore.ieee.org/document/8367070)

### [OSS-fuzz-2017](https://github.com/google/oss-fuzz)（google）

> OSS-Fuzz 的目的是利用更新的模糊测试技术与可扩展的分布式执行相结合，提高一般软件基础架构的安全性与稳定性。OSS-Fuzz结合了多种模糊测试技术/漏洞捕捉技术（即原来的libfuzzer）与清洗技术（即原来的AddressSanitizer），并且通过ClusterFuzz为大规模可分布式执行提供了测试环境。
>
> **相关资料：**
>
> 1. [论文–usenixsecurity17](<https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany>)

---

## **杂项**

其他的一些fuzzers，如内核fuzzers，通用型fuzzer等。

> 

### [gramfuzz](https://github.com/d0c-s4vage/gramfuzz)

> 一种基于语法的模糊器，可以让您定义复杂的语法来为文本和二进制数据格式建模。

### [Hodor Fuzzer](https://github.com/nccgroup/hodor)

> 另一种通用型fuzzer。

### [syzkaller ](https://github.com/google/syzkaller)

> 一款针对Linux内核进行模糊测试的开源工具。

### [ansvif](https://oxagast.github.io/ansvif/)

> 用于查找C/C++代码中的漏洞的高级跨平台模糊测试框架。

---

## 暂时未确认属于哪种类型的fuzzer



## **污点分析**

用户输入如何影响执行

### [PANDA](https://github.com/moyix/panda)

> 构建于顶级QEMU系统的新一代动态分析平台

### [QIRA](http://qira.me/)

> QEMU交互式运行时分析器

### [kfetch-toolkit](https://github.com/j00ru/kfetch-toolkit)

> 执行高级记录引用的工具

---

## **符号执行SAT和SMT求解器**

### [Z3](https://github.com/Z3Prover/z3)

> 属于SMT Solver，用于判定First Order Logic公式的可满足性。
>
>  **相关资料：**
>
> 1. Z3 – 指南](https://rise4fun.com/z3/tutorial/guide) – Z3入门指南：指南

### [SMT-LIB](http://smtlib.cs.uiowa.edu/)

> 旨在促进SMT研究与开发的国际计划。



## **辅助工具**

针对exploit开发人员和逆向工程师的工具。

### 调试工具

> [Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools) – windows平台下强大的用户态和内核态调试工具。
>
> [Immunity Debugger](http://debugger.immunityinc.com/)- 专门用于加速漏洞利用程序的开发，辅助漏洞挖掘以及恶意软件分析。
>
> [OllyDbg](http://www.ollydbg.de/) – 一个新的动态追踪工具。
>
> [Mona.py](https://github.com/corelan/mona/)（windbg和Immunity dbg的插件）
>
> [x64dbg](https://github.com/x64dbg/) – 用于Windows的开源x64/x32调试器。
>
> [Evan的调试器（EDB）](http://codef00.com/projects#debugger)- gdb前端。
>
> [GDB – Gnu调试器](http://www.sourceware.org/gdb/) – 最喜欢的Linux调试器。
>
> [PEDA](https://github.com/longld/peda) – 针对GDB的Python Exploit开发助手。
>
> [Radare2](http://www.radare.org/r/) – 用于逆向工程和二进制文件分析的框架。

### **反编译**

> [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml)- 最好的反编译软件
>
> [binnavi](https://github.com/google/binnavi) – 二进制分析IDE，注释控制流程图和调用反编译代码的图形。
>
> [Capstone](https://github.com/aquynh/capstone) – Capstone是一个轻量级的多平台，多架构反编译框架。

### **其它**

> [ltrace](http://ltrace.org/) – 用来跟踪进程调用库函数的情况。
>
> [strace](https://sourceforge.net/projects/strace/) – 跟踪系统调用和信号。

## 漏洞应用程序

> Exploit-DB -[ https://www.exploit-db.com](https://www.exploit-db.com/)（通过搜索相关的应用漏洞，并自行下载漏洞应用及EXP重现漏洞）
>
> PacketStorm - <https://packetstormsecurity.com/files/tags/exploit/>
>
> [Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - 用于测试fuzzers的漏洞C程序。

### 模糊测试样本文件：

> <https://files.fuzzing-project.org/>
>
> [来自Mozilla的PDF测试语料库](https://github.com/mozilla/pdf.js/tree/master/test/pdfs)
>
> [MS Office文件格式文档](https://www.microsoft.com/en-us/download/details.aspx?id=14565)
>
> [模糊测试套件](https://github.com/google/fuzzer-test-suite) – fuzzing引擎测试集。包括不同的已知bug，如Heartbleed， c-ares $100K bug等。

## 反Fuzzing

> [反Fuzzing介绍：纵深防御](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2014/january/introduction-to-anti-fuzzing-a-defence-in-depth-aid/)