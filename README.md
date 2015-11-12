## ZhiHuDailyDemo

前些日子在Github上看到了用Swift写的模仿知乎日报客户端,自己平时也比较喜欢看知乎、知乎日报，于是萌生了一个想法，用OC写一下这个客户端，刚学iOS开发的同学可以感受下，大神请忽略～<p>
很早以前在Github上看到了一篇分析知乎日报API的文章，在写这个项目的过程中给我带来了极大的方便，再也不用盯着Charles瞅半天了，在此感谢[izzyleung][7]同学的文章,原文:[知乎日报 API 分析][8],感兴趣的同学可以看一下,顺便star一下咯。之前clone了Swift版的模仿知乎日报客户端，学到了很多东西，在这里也要感谢一下作者Swift版作者,可是我找不到他的主页了...从他的代码里自己也收获颇多。

![启动页]

###项目说明
- 基本界面已经完成,在主页加载更多内容的时候tableview sectionHeaderView达不到原版客户端的效果,我这几天已经被NavigaitonBar 搞的快疯掉了,目前也没什么思路来解决这个问题,希望哪位大神可以提供一下思路。
效果图:
- 项目全部使用storyBoard加autolayout,因为我对手写各种界面,各种约束真的没爱。

- 目前仍没有完成的部分是点击任何地方的cell并不会进入详细页面，等待后续不断完善。
- 还有好多细节不是很完善。

  
  [6]: http://ww3.sinaimg.cn/bmiddle/6cee22c2jw1exyih2cavfg208w0gh4r1.gif
  [7]: https://github.com/izzyleung/ZhihuDailyPurify/wiki/知乎日报-API-分析
  [8]: https://github.com/izzyleung
