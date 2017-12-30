# The-Little-Embedded-System

嵌入式系统学习小书

本小书，希望介绍自己对嵌入式系统软硬件方面的理解，将通过大学生智能汽车竞赛的实际案例展开，试图讲解嵌入式系统的一些基础，毕竟自己工作经验有限，所以如果不妥，还望斧正！

还记得大学学的自动化专业，当初学了一学期单片机居然从没摸过51单片机，也从来没做过实验，我现在想想都怀疑自己上的是假大学，后来在大三2017年参加飞思卡尔杯全国大学生智能汽车竞赛，才慢慢对单片机以及嵌入式方面的开发算是有了入门，因为做这个比赛需要对车速进行闭环控制，所以开始学PID控制器相关的知识，这时候发现其实《自动控制原理》那门课理论学术味太浓，距离解决实际问题还相差甚远，一点都不接地气。

大学毕业后，去了无锡一家小公司做电动自行车控制器相关的开发，主要用NEC单片机（因为便宜呀！！），工作后这才发现当时消费市场上的产品多数就是一简单的开环控制，PWM调节占空比调压调速，再做一个限流保护就可以了。那时候，总觉得，日了狗了，早知这样，还上毛学学那些艰深晦涩的狗屁理论呀。现在不一样了，像小米平衡车，DJI无人机，还有电动自行车都玩起了SVPWM矢量控制。

2009年，辞去工作开始读研，日子过得不要太潇洒，后来玩的不行了，觉得该搞点论文混毕业呀，于是恶补了一月，刷了PID控制相关的论文，写下了人生中的唯一一篇论文《A Multiple Tuning Method for PID Controllers Using Constrained Particle Swarm Optimization 》，这时候，才发现，原来控制理论不是那么枯燥无味，也可以深入研究很好玩。

内心里其实一直想做实时控制和嵌入式系统方面的工作，于是研究生一毕业，就去风电公司搞变频器开发了，在那里遇到了好多高手和大拿，学了很多控制，硬件，信号，还有嵌入式方面知识，也真的看到了Matlab/Simulink仿真真的可以验证系统，不是像大学在那凑数据糊弄实验报告，说实话，那段时间，真的开阔了自己在技术上的视野，与最优秀的一群人，一起工作和学习讨论问题真的是一种享受。

14年，回到廊坊，大学任教，开始认真做教育，接管创新实验室，给学生开公开课，和学生一起准备飞思卡尔杯大学生智能车竞赛，一切都是从零开始，做过了很多新的尝试，跟学生一起搭智能车比赛的整个软硬件平台，这中间也不断重新梳理自己所学的知识，同时也能看到学生们的不断成长，看着孩子们激动地调车，我自己也是开心得像个孩子一样。

这中间，出现了很多问题，学生们码代码不规范，完全没有版本控制，都是Ctrl C+Ctrl V，采集摄像头图像耗时严重，算法测试和验证极度效率低下，拖累整个开发进程。于是2016年，我自己重新梳理了一下，针对比赛中的摄像头组，做一个相对完备的开发平台，在山外K60库和硬件核心板的基础上完成，中间大量的核心工作都基于最简单的工具软件Maltab和串口完成，虽然是针对智能车比赛，但是里面的很多尝试和想法，在嵌入式系统和控制方面都是通用的，可以给大家做做一个借鉴和学习参考。

希望阅读完本小书，能够解答大家这些问题

* 不带RTOS的嵌入式系统如何更好地开发
* 嵌入式软件的分层设计怎么做
* 在设计控制器时，被控系统的简化动态模型怎么获得
* 传统的PID控制器设计在工程上到底怎么实施，如何仿真测试和写代码
* Matlab/Simulink怎么可以帮助提高嵌入式控制器的开发和测试效率
* 如何简单快速地做控制器故障分析和错误排查，等等

如果对小书中有问题，请邮件联系chenxiannn\#126.com

相约：[Github](https://github.com/chenxiannn)

[觅知圈](https://www.mizhiquan.com/)

##### ** 觅知圈公众号** {#觅知圈公众号}

![](https://www.mizhiquan.com/static/images/qrcode.jpg)



