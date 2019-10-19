# nanopore
NECAT是肖传乐老师团队开发的一个针对Nanopore数据组装的软件，目前该工具尚未发表，除了https://github.com/xiaochuanle/NECAT有软件的介绍外，暂时没有中文资料介绍NECAT的使用。

太长不看的结论: Nanopore的组装推荐用下NECAT。组装之后是先用MEDAKA做一遍三代polish，然后用NextPolish默认参数做二代polish。

这篇将会以一篇发表在Nature Communication上的拟南芥nanopore数据介绍如何使用NECAT进行组装，运行在CentOS Linux release 7.3.1611 (Core)，64G为内存， 20线程(Intel® Xeon® CPU E5-2640 v4 @ 2.40GHz)，下面是正文。
————————————————
版权声明：本文为CSDN博主「徐洲更hoptop」的原创文章，遵循 CC 4.0 BY-NC-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/u012110870/article/details/100171392
