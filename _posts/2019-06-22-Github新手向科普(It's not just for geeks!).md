---
layout: post
title: Github新手向科普（It's not just for geeks!）
description: "
Github能怎好？除了用来管理代码，GitHub还能怎么玩？各种代码名词看起来很复杂？（也许它只是只傲娇的猫星人啦～"
modified: 2019-06-22
lang: zh
tags: [About Learning, Git]
image:
  path:# /images/abstract-3.jpg
  feature:# abstract-3.jpg
  credit:# dargadgetz
#  creditlink: # http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
---

![Otcocat]({{ site.url }}/images/Github-cat.webp)

## Github是什么？（能？）

GitHub最初是为开发者所创建的社区。在这里，程序员们可以进行代码的版本控制与协同工作。但如今，许多的非程序员们也将GitHub作为其创作平台，享受它管理项目与合作的便利。正如GitHub官方所说，GitHub是一个为所有“知识工作者”（knowledge worker）所提供的工具。

与其他的网络平台相比，GitHub更像是一个工具箱。它没有所谓的“正确”玩法，如何利用它来做自己想做的事，一切都靠想象力。推荐一些很有趣的非程序开发向GitHub repo：（repository 即仓库：用来管理项目。后文会有简单介绍）

* [Public Self](https://github.com/busterbenson/public)：作者的内心世界，他的三观（belief），他的生活准则（rule），他喜欢的思想等等。
* [Travel Plan](https://github.com/dylanegan/travel)：作者所去过的地方以及想要去的地方。可以看到很多人在这里提出了旅行建议。
* [The League of Moveable Type](https://github.com/theleagueof)：一个开源的字体设计组织，目前有18个仓库。任何人都能够下载字体，并提出设计意见。
* [A novel](https://github.com/JJ/hoborg)：一本完全利用GitHub写成的小说，已在amazon上架。任何人都能够提出修改建议，甚至基于此来写自己的小说。
* [DC Law](https://github.com/DCCouncil/dc-law-xml)：Columbia州的法律，很多人在这里找typo。（不少国家和地区都把法律公开在了GitHub上。甚至于有人传了这个([you-know-what done by you-know-who](https://github.com/mlouielu/cn_constitution_2018))
* [Organizing personal life](https://dev.to/jpcs369/organizing-your-life-using-github-6an)：一个私人项目（private repo，仅自己可见）利用GitHub来管理自己的生活，如各种文件，照片，to-do list 等等。


## 如何使用GitHub？（怎？）

当然首先你需要一个账号。（大部分功能免费。对于在校学生来说还有student pack，有兴趣可以自行研究。）接下来要怎么做？满屏幕的不明词语令人头秃？不用担心啦，只要大概理解GitHub的工作流程，这只傲娇的Octocat也只是一只傲娇的喵星人而已。

下图是一张简要的github工作流程：
人类1和人类2打算合作写一本小说。在写到第十章时，两人的思路发生了分歧，于是人类2创建了分支(branch)。但随后两人的故事实在无法融合，于是经过协商，他们决定从第十章重新开始写，于是将仓库滚回版本1.2。两人分别完成自己的部分后，将仓库融合(merge)。

![]({{ site.url }}/images/novel-1.webp)
![]({{ site.url }}/images/novel-2.webp)

除了上文提到的合作方式外，GitHub还提供了许多种与他人repo的互动方式，最常见的就是右上角的watch, star 和folk。

* watch：观察。当这个repo内容有任何的内容变化，包括收到pull request, issue（下文会讲）时，点了watch的人都会收到系统提醒。
* star: 类似于点赞+收藏功能。可以在自己的账户下看到所有自己点过star的repo。
* folk: 类似于复制功能。把当前版本的repo复制到自己的账户下，且做任何修改都不会对原repo有影响。

此外，他人（非合作者）也可以向repo提供自己的贡献：issue和pull request。（例如在上文提到的travel plan的仓库中，可以看到许多人在issue区进行讨论，以及通过pull request对作者的travel plan提出建议。）
* issue：即讨论区，可以和作者以及其他人在这里讨论这个repo的内容。
* pull request: 即提出要把自己对这个repo的修改部分合并入作者的分支中。

![]({{ site.url }}/images/coop.webp)


## 如何利用GitHub搭建个人blog？（怎？）
GitHub还有一个诱人的功能，就是可以免费host自己的blog。不需要买域名，不需要服务器，只要在自己的GitHub账户下建立一个以username.github.io 为名的仓库，然后将博客内容上传到这个仓库下，GitHub会自动为你生成该博客。

利用github搭建博客还有一个便利之处，就是可以利用github的folk功能来diy自己的blog样式。如果你看到喜欢的blog，便可以folk过来再改一改域名，变成自己的。也可以自己动手修改配置文件_config.yml 来修改样式。（比如把好几个blog的喜欢之处参考过来，搭建自己的blog。）

具体的搭建过程，网上有无数的教程，这里就不再叙述啦。

## GitHub的优势与缺点？（好？）
先说说优点：
1. 墙内可见。
2. 去中心化。（任何人都可以把仓库folk过来。举个例子：如果想要墙某一个仓库的内容，那必须把从这个仓库folk过来的所有仓库都墙了。）
3. 版本管理。
4. 十分便利多人协同工作。
5. 不重复造轮子。（开源的便利之一，大家可以使用并做出贡献。）

缺点：
1. 需要一点点时间来上手。（并不是学习代码，官方提供的git工具已经解放了命令行的使用。而是熟悉github的工作流程。）
2. 与其他社交网站相比，它不适合用来catch up with friends。（可能更适合用来做一些深入的事情。）

那么接下来？（what to go from here?）
推荐一些教程：

[How to use git and github?](https://www.classcentral.com/course/udacity-how-to-use-git-and-github-2661)  Udacity的一个online 课程。
[Git图形化工具介绍](https://www.cnblogs.com/jsonphp/articles/7760810.html)


感谢你看到这里。如果你有喜欢的（非开发向）github repo，或新手向的github教程十分欢迎留言，会更新在正文中。另外，如果本文有哪里描述不清楚，或错误，欢迎留言，会更正。
