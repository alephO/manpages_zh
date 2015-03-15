#基于列数的中文manpages手册

我希望借助开放和互助来持久的进行这个计划，在这个计划里没有什么限制，你可
以以你喜欢的方式工作，发布你喜欢的内容。只有在有一个起点的情况下，更多的
人才能够参与进来。

##中文manpages

中文manpages显然需要长久的维护，不仅现在留下来的上万的文档需要整理，程序
本身也在推陈出新，所以我希望更多的人能够参与进来，来维护一个长久更新，切
实能用的中文manpages,我本身非常乐观，因为我们现在有比之前更好更多的资源
，我使用ronn将兼容于markdown的ronn-format文件转换为漂亮的man手册，这个过
程也比之前那些项目要来的方便快捷，但你不用理会这个过程，你只需提交你的作
品，或者帮助改善中文文档，这些都是没有任何门槛的。

在man中显示汉字与英语杂排总是会有拉伸，同一个文件在每个人的显示屏上最终
显示效果也不同，为了解决这个问题，以前的中文manpages项目讨论过解决办法，
一种是采用固定列数的办法，manpages仅为这一种列数优化，在这种列数下显示一
般是正常的，其他列数下则有可能发生单词拉伸。还有一种办法就是每个汉字之间
放一个空格，把汉字当做英文单词来排版，这样做的缺点是不规范，也不好看。本
项目采用第一种方法，这样至少可以在特定列下显示是完整好看的。

##文件夹结构

`man/`下是中文manpages文档，`html/`下是中文manpages文档的网页文件，
`ronn/`下是用来生成man文档和网页的原始文件，`source/`下是翻译前可供参考
的文件，里面有LCTT计划和CMPP项目留下来的一些文件，您可以在此文件夹下设置
自己的工作目录。编辑显示和帮助请参考`help/`。

本项目在:<https://www.github.com/intetnet/manpages_zh>。

在线manpages文件可以在<http://intetnet.github.io/html/list.html>上查看。

##怎么安装？

manpages为文本文件，是不需要安装的。man使用特定的文件结构，类似于
`/home/youname/man/zh_CN/man1/man.1`这样子，你把下载的manpages手册放在硬
盘上你心仪的位置，然后保证manpath能找到即可。manpath可以通过设置环境变量
来实现，如果你使用的是bash,并且把本项目clone在用户根目录下manpages文件夹
,那么你可以在`.bashrc`加入下面语句：

	export MANPATH=/usr/man:/usr/share/man:～/manpages/man/zh_CN
	
不同的文件夹间使用分号隔开。

更多请参考help/文件夹。

##todo

参考TODO
 
##联系我

如果你有什么想法建议和申诉，可以跟我联系。

如果你要给我发送你翻译/整理的文章，可以跟我联系。

本项目托管于Github，如果你希望加入进来，我可以把你加入到Collaborators名
单中，这需要您有一个Github的账号。你也可以fork我的项目。

你可以发送电子邮件到yanpenn@outlook.com。

##我需要你的帮助

我希望能够有更多的人加入到这个项目，贡献自己的力量，你可以将你的作品发表
在此，让更多的人看到，也可以申诉文章引用不当之处。

现在这里只有我一个人在做排版，你可以帮助我来进行排版，排版请参考`help/`
文件夹中的相关内容。

我希望能有一个"快速行动小组"来追踪网友的反馈和一些重要软件的更新。

如果你希望贡献本项目，你可以任意选择已有或者未有的manpages来翻译提交，也
可以帮助我完成TODO里面的内容。

我需要你的帮助来完善版权信息和改善中文手册。

##版权

请参考COPYRIGHT
