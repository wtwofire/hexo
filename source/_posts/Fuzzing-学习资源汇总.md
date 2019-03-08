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

## **fuzzing书籍：**

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

## fuzzing课程/培训视频：

### **免费**

> [纽约大学Poly（查看更多视频）](https://vimeo.com/5236104) – 由Dan Guido免费提供。
>
> [Samclass.info（检查项目部分和第17章）](https://samsclass.info/127/127_F15.shtml) – 由Sam提供。
>
> [现代二进制开发（RPISEC） – 第15章](https://github.com/RPISEC/MBE) – 由RPISEC提供。
>
> [攻击性计算机安全 – 第6周](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) – 由W. Owen Redwood和Xiuwen Liu教授提供。

**付费**

> [Offensive Security, ](https://www.offensive-security.com/information-security-training/)[CTP和高级Windows开发（AWE）](https://www.offensive-security.com/information-security-training/)
>
> [针对渗透测试的SANS 660/760高级Exploit开发](https://www.sans.org/course/advanced-exploit-development-penetration-testers)
>
> [Exodus Intelligence – 漏洞开发大师班](https://blog.exodusintel.com/2016/05/18/exodus-intelligence-2016-training-course/)

## 视频：

视频主要谈论fuzzing技术，工具以及最佳实践。

###  纽约大学Poly课程视频

> [Fuzzing 101 (Part 1)](https://vimeo.com/5236104) - Mike Zusman。
>
> [Fuzzing 101 (Part 2)](https://vimeo.com/5237484) - Mike Zusman。
>
> [Fuzzing 101 (2009)](https://vimeo.com/7574602) - Mike Zusman。
>
> [Fuzzing – Coursera软件安全课程](https://www.coursera.org/learn/software-security/lecture/VgyOn/fuzzing) – 由马里兰大学提供

### **会议讲座和教程**

> [Youtube上各种有关fuzzing的探讨](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD)[和演示文稿播放列表](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD) – 这些视频中有很多不错的内容
>
> [浏览器bug狩猎 – 最后一个人的回忆录](https://vimeo.com/109380793) – Atte Kettunen
>
> [将基于代码覆盖率的灰盒Fuzzing视为马尔科夫链](https://www.comp.nus.edu.sg/~mboehme/paper/CCS16.pdf)
>
> [DerbyCon 2016：Fuzzing基础知识……或如何破解软件](http://www.securitytube.net/video/16939)

## 教程和博客

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

### 从Fuzzing到利用：

> [从Fuzzing到0-day](https://blog.techorganic.com/2014/05/14/from-fuzzing-to-0-day/) - Harold Rodriguez(@superkojiman)。
>
> [从崩溃到利用](https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - Corelan团队。

### Peach Fuzzer相关教程：

> [开始使用Peach](http://community.peachfuzzer.com/v2/PeachQuickstart.html)
>
> [Peach Fuzzing第一部分](http://www.flinkd.org/fuzzing-with-peach-part-1/) – corelan团队Jason Kratzer
>
> [Peach Fuzzing第二部分 ](http://www.flinkd.org/fuzzing-with-peach-part-2-fixups-2/)- corelan团队Jason Kratzer
>
> [自动生成Peach pit文件/fuzzers ](http://doc.netzob.org/en/latest/tutorials/peach.html)- FrédéricGuihéry，Georges Bossert
>
> **peach使用介绍**：[1、peach语法介绍](<https://www.kanxue.com/chm.htm?id=12592&pid=node1001008>)、[2、peach语法实战](<https://www.kanxue.com/chm.htm?id=12593&pid=node1001008>)、[3、Peach 实战之 gif 文件格式](<https://www.kanxue.com/chm.htm?id=12594&pid=node1001008>)、[4、Peach Pit 模版调试技巧](<https://www.kanxue.com/chm.htm?id=12595&pid=node1001008>)

### AFL Fuzzer相关教程

> [Fuzzing工作流程； fuzz工作从开始到结束](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) – @BrandonPrry。
>
> [使用afl的persistent模式给capstone做模糊测试](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html) – @toasted_flakes。
>
> [RAM磁盘以及从AFL Fuzzing中保存你的SSD](http://cipherdyne.org/blog/2014/12/ram-disks-and-saving-your-ssd-from-afl-fuzzing.html)
>
> [使用American Fuzzy Lop狩猎Bug](https://josephg.com/blog/bug-hunting-with-american-fuzzy-lop/)
>
> [American Fuzzy Lop在真实案例中的高级使用](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)
>
> [使用afl-fuzz隔离Python](https://tomforb.es/segfaulting-python-with-afl-fuzz)
>
> [Fuzzing Perl： American Fuzzy Lops的故事](http://www.geeknik.net/71nvhf1fp)
>
> [使用AFL-Fuzz Fuzzing，一个练习示例（AFL vs Binutils）](https://www.evilsocket.net/2015/04/30/fuzzing-with-afl-fuzz-a-practical-example-afl-vs-binutils/)
>
> [Fuzzing的重要性？](https://mgba.io/2016/09/13/fuzzing-emulators/)
>
> [Heartbleed是如何被找到的](https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html)
>
> [使用American Fuzzy lop Fuzzing文件系统](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)
>
> [使用AFL Fuzzing Perl/XS模块](https://medium.com/@dgryski/fuzzing-perl-xs-modules-with-afl-4bfc2335dd90)
>
> [如何使用American Fuzzy Lop fuzz一个服务器 ](https://www.fastly.com/blog/how-fuzz-server-american-fuzzy-lop)- Jonathan Foote
>
> [AFL研讨会Fuzzing – 真正的漏洞带来的一系列挑战](https://github.com/ThalesIgnite/afl-training)

### libFuzzer Fuzzer相关教程

> [libFuzzer教程](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
>
> [libFuzzer研讨会：“C/C++项目的现代fuzzing”](https://github.com/Dor1s/libfuzzer-workshop)

### Spike Fuzzer相关教程

> [使用Spike Fuzzing查找溢出](https://null-byte.wonderhowto.com/how-to/hack-like-pro-build-your-own-exploits-part-3-fuzzing-with-spike-find-overflows-0162789/)
>
> [使用Spike Fuzzing](https://samsclass.info/127/proj/p18-spike.htm) – samclass.info

### FOE Fuzzer相关教程

> [使用FOE Fuzzing](https://samsclass.info/127/proj/p16-fuzz.htm) – Samclass.info
>
> SMT/SAT solver教程
>
> [Z3 – 指南](https://rise4fun.com/z3/tutorial/guide) – Z3入门指南：指南

## 工具

有助于fuzzing应用的工具

### Cloud Fuzzers

在云环境中帮助fuzzing测试的Fuzzers。

[Cloudfuzzer](https://github.com/ouspg/cloudfuzzer) – 云fuzzing框架，可以轻松在云环境中运行自动化模糊测试。

### 文件格式Fuzzers

可帮助fuzzing文件格式的Fuzzers，如PDF，MP3，SWF等

> [MiniFuzz – Wayback Machine链接](https://web.archive.org/web/20140512203517/http://download.microsoft.com/download/D/6/E/D6EDC908-A1D7-4790-AB0B-66A8B35CD931/MiniFuzzSetup.msi) – Microsoft提供的基本文件格式模糊测试工具。（Microsoft网站上不再提供）。
>
> [BFF from CERT](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=507974) - 用于文件格式的基本模糊测试框架。
>
> [AFL Fuzzer（仅适用于Linux）](http://lcamtuf.coredump.cx/afl/)- American Fuzzy Lop Fuzzer 由Michal Zalewski aka lcamtuf发布
>
> [Win AFL](https://github.com/ivanfratric/winafl)- Linux下的智能模糊测试神器afl-fuzz的Windows版本
>
> [Shellphish Fuzzer](https://github.com/shellphish/fuzzer)  – AFL的Python接口，允许注入测试用例和其他功能。
>
> [TriforceAFL](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/june/project-triforce-run-afl-on-everything/) – AFL的修改版本，它支持源代码不可用的应用程序的模糊测试。
>
> [Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/) –  一款智能模糊测试工具, 广泛用于发现软件中的漏洞和缺陷,它有两种主要模式,基于生长的模糊测试和基于变异的模糊测试。
>
> [MozPeach](https://github.com/MozillaSecurity/peach) - 由Mozilla Security提供的peach 2.7。
>
> [失败观察引擎（FOE）](https://github.com/secfigo/Awesome-Fuzzing/blob/master/www.cert.org/vulnerability-analysis/tools/foe.cfm) – 针对Windows应用程序的基于文件突变的fuzz测试工具。
>
> [rmadair ](http://rmadair.github.io/fuzzer/)- 基于文件突变的fuzz测试工具，使用PyDBG来监测感兴趣的信号。
>
> [honggfuzz](https://github.com/google/honggfuzz) - 一个易于使用的fuzzer以及有趣的分析选项。支持基于代码覆盖的feedback-driven fuzzing。同时支持GNU/Linux，FreeBSD，Mac OSX和Android系统。
>
> [zzuf](https://github.com/samhocevar/zzuf)  – 一个透明应用程序输入fuzzer。它通过拦截文件操作并更改程序输入中的随机位来工作。
>
> [radamsa](https://github.com/aoh/radamsa) – 通用型fuzzer和测试用例生成器。
>
> [binspector](https://github.com/binspector/binspector) - 二进制格式分析和模糊测试工具
>
> [grammarinator](https://github.com/renatahodovan/grammarinator) – 基于ANTLR v4语法的文件格式模糊测试工具（ANTLR项目中已有多种语法可用）。

### 网络协议Fuzzers

可帮助fuzzing使用基于网络协议（如HTTP, SSH, SMTP等）的应用程序Fuzzers。

> [Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/) –  一款智能模糊测试工具, 广泛用于发现软件中的漏洞和缺陷,它有两种主要模式,基于生长的模糊测试和基于变异的模糊测试。
>
> [Sulley](https://github.com/OpenRCE/sulley)- 由多个可扩展组件组成的fuzzer开发和模糊测试框架。
>
> [boofuzz](https://github.com/jtpereyda/boofuzz)- Sulley框架的分支和继承。
>
> [Spike](http://www.immunitysec.com/downloads/SPIKE2.9.tgz) – 一个fuzzer开发框架。
>
> Metasploit框架 – 通过辅助模块包含一些fuzzing功能的框架。
>
> [Nightmare](https://github.com/joxeankoret/nightmare) – 带有Web管理的分布式模糊测试套件，支持使用网络协议进行模糊测试。

### **杂项**

其他的一些fuzzers，如内核fuzzers，通用型fuzzer等。

> [Choronzon](https://github.com/CENSUS/choronzon) – 一个革命性的基于知识库的模糊测试。
>
> [QuickFuzz](https://github.com/CIFASIS/QuickFuzz) – 是一个语法模糊器，由QuickCheck，模板Haskell和Hackage的特定库生成许多复杂的文件格式，如Jpeg，Png，Svg，Xml，Zip，Tar等。
>
> [gramfuzz](https://github.com/d0c-s4vage/gramfuzz) – 一种基于语法的模糊器，可以让您定义复杂的语法来为文本和二进制数据格式建模。
>
> [KernelFuzzer](https://github.com/mwrlabs/KernelFuzzer) – 跨平台的内核Fuzzer框架。
>
> [honggfuzz](http://honggfuzz.com/) – 一个易于使用的fuzzer以及有趣的分析选项。支持基于代码覆盖的feedback-driven fuzzing。同时支持GNU/Linux，FreeBSD，Mac OSX和Android系统。
>
> [Hodor Fuzzer](https://github.com/nccgroup/hodor) - 另一种通用型fuzzer。
>
> [libFuzzer](http://llvm.org/docs/LibFuzzer.html)- C/C++编写的目标进程内覆盖引导渐进式fuzzing引擎。
>
> [syzkaller ](https://github.com/google/syzkaller)- 一款针对Linux内核进行模糊测试的开源工具。
>
> [ansvif](https://oxagast.github.io/ansvif/) – 用于查找C/C++代码中的漏洞的高级跨平台模糊测试框架。

### **污点分析**

用户输入如何影响执行

> [PANDA（构建于顶级QEMU系统上的新一代动态分析平台）](https://github.com/moyix/panda)
>
> [QIRA（QEMU交互式运行时分析器）](http://qira.me/)
>
> [kfetch-toolkit](https://github.com/j00ru/kfetch-toolkit) – 执行高级记录引用的工具

### **符号执行SAT和SMT求解器**

> [Z3](https://github.com/Z3Prover/z3) - 属于SMT Solver，用于判定First Order Logic公式的可满足性。
>
> [SMT-LIB](http://smtlib.cs.uiowa.edu/) - 旨在促进SMT研究与开发的国际计划。

## **参考**

点击链接了解更多信息：<https://www.ee.oulu.fi/research/ouspg/Fuzzers>

### **基本工具**

针对exploit开发人员和逆向工程师的工具。

### Debuggers

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

### **反编译以及更多**

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