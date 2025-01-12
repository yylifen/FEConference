# 第五届FEDAY参会总结

> PS: 本届FEDAY完整的话题信息以及PPT可前往[第五届REDAY官网 https://fequan.com/2019/](https://fequan.com/2019/)查阅。

![0.jpg](https://yylifen.github.io/FEConference/feday5/images/0.jpg)<br />![1.png](https://yylifen.github.io/FEConference/feday5/images/1.png)<br />
<br />本届FEDAY一共有9个主题，有些主题的分享内容和技术无关却和技术人息息相关，有些主题的解决方案充满争议，还有些主题的设计思想令人折服，不管是哪一种，都是一次非常有意义的回顾。今天主要和大家一起回顾以下3个主题。

### Vladimir Grinenko @Yandex《大型团队中开发的平衡性》
![1.1.jpg](https://yylifen.github.io/FEConference/feday5/images/1.1.jpg)<br />《大型团队中开发的平衡性》目前视频还没放出来，[ppt在这里可以查看](https://yylifen.github.io/FEConference/feday5/ppt/Grinenko_Balanced%20development%20in%20large%20teams.pdf)。这也是现场听得最费劲的一场，主要讲了Vladimir Grinenko在Yandex的团队管理方面遇到了角色分工职责和项目质量问题，而演讲的内容就是这个问题的解决方案。会场麦克风音量有点小，加上他讲话太温柔，再加上本来在外面休息质量会打折，差点睡着【尴尬】。

> Yandex是一家俄罗斯互联网企业，旗下的搜索引擎在俄国内拥有超过60%的市场占有率，同时也提供其他的一系列互联网产品和服务。根据数据显示，Yandex是当前世界上第五大搜索引擎。[摘自维基百科](https://zh.wikipedia.org/wiki/Yandex)

Yandex是一家类似于国内百度的公司，2017年我看过一篇全世界搜索引擎排名的文章，那时候Yandex好像是第9，百度第4，Google第一。由此可见，Yandex在俄罗斯的地位几乎可以和国内的百度同日而语。Vladimir Grinenko作为Yandex通用组件的leader，管理者分布在3个城市的五个团队，团队成员超过40人，管理难度之大不言而喻。如果你所在的团队成员小于5个人，可能真的可以像后面有位嘉宾说的“充分相信自己的每一位成员”，因为一般发生质变都是在量够大之后，质变则是失控的结果。讲师主要提出了两个问题，一个是项目的质量把控，另一个是项目中开发成员的角色分工职责。面对一个团队每个成员都有可能参与甚至直接作为多个项目的主力时，如何去把控项目质量和明确自己在团队在各个项目中的职责。他提出来一个虚拟团队（Virtual teams）的概念让人醍醐灌顶。小团队对中“开发”就是king，但是在大团队中，"产品"才是King。每个项目临时配置一个虚拟团队，根据敏捷开发原则，尽可能地让不同分工的前端、后端和设计师等不同角色专注自己的领域，从而实现不同角色成员为了一个共同的产品目标并行工作。这种虚拟团队根据需要灵活配置，可以有效地避免人员冗余，根据项目的复杂度调整人员，也简化了与其他团队的合作流程提高效率，重要的是虚拟团队的负责人不受自己的级别限制，是很多普通成员很好的锻炼机会，可以帮助员工快速成长，并且经验共享。
> 本主题的视频官方暂时还没放出

### 王泽@白鹭科技《框架开发中的基础设施搭建》
> Egret Engine白鹭引擎是一套开源免费的完整的HTML5游戏开发解决方案，用于构建二维游戏、演示程序和其他图形界面交互应用等。[摘自维基百科](https://zh.wikipedia.org/wiki/Egret)

<!-- ![2.1.jpg](https://yylifen.github.io/FEConference/feday5/images/2.1.jpg) -->
<iframe width="620" height="349" src="https://yylifen.github.io/FEConference/feday5/mp4/wangze.mp4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br />
《框架开发中的基础设施搭建》主要分享了白鹭引擎最新产品Egret Pro 在这方面的工程实践过程，为了解决框架代码的质量和可维护性，详细描述了他们是如何做模块拆分、单元测试和不同模块的版本控制。由于这几年一直在兼职开发和维护团队的公共工具，不管是模块开发还是不同模块的版本控制，踩过不少坑也深有体会，但目前团队的方案虽然够用，但是并非最佳。对这个话题的期待以及最佳方案的饥渴也是此行的目的之一。很多人知道白鹭引擎，可能和我一样，是从他们的一个爆款游戏《围住神经猫》开始的，去年还看过白鹭引擎广州沙龙上分享的《重度H5游戏性能优化技巧》，可以感受的出白鹭引擎的设计思想非常亮眼。前面是从什么是框架以及小团队是否有必要开发一个自己的框架引入话题的，这些PPT很详细这里不需要复述，具体的可以考虑[先回顾一下PPT内容](https://yylifen.github.io/FEConference/feday5/ppt/%E6%A1%86%E6%9E%B6%E5%BC%80%E5%8F%91%E4%B8%AD%E7%9A%84%E5%9F%BA%E7%A1%80%E8%AE%BE%E6%96%BD%E5%BB%BA%E8%AE%BE_%E7%8E%8B%E6%B3%BD.pdf)再回来看这里的小结。我们团队没有自己的框架，但是我自己定制了自己的CLI和构建工具，基本上很认同他认为小团队也有必要开发一个框架的结论，不仅仅能解决“通用型复用”，还能解决自己团队特定的“业务型复用”。在如何开发和维护一个自己团队的框架的分享中重点讲了他们的模块拆分和模块的本版管理。个人觉得他们为了解决版本控制上的痛点，牺牲了项目的独立性不是很合理。特别是项目繁多的业务团队，这种方式就像玩层层叠游戏一样，每一步可能带来惊喜也可能带来惊吓，一个不小心就很容易因为一个项目而影响了同在一个repo的其他项目。后面rush.js的解决版本关联升级等方案也是仁者见仁智者见智。我没有过相关实践，可能解耦思维对我影响太深，后面的部分忍不住加入了旁边人的讨论。现在重新回顾了视频和PPT，才发现他们这么做的合理性也是有的，毕竟他们可以做到“充分相信每一位团队成员”，这一点足以令每一个曾经被质疑过的人向往。
<!-- > 本主题的视频可以在这里观看[https://v.qq.com/x/page/w30023f5sew.html](https://v.qq.com/x/page/w30023f5sew.html) -->

### 刘帅@腾讯云《巨型小程序的分布式开发与自动化管理》
<!-- ![3.1.jpg](https://yylifen.github.io/FEConference/feday5/images/3.1.jpg) -->
<iframe width="620" height="349" style="margin: 0 auto" src="https://yylifen.github.io/FEConference/feday5/mp4/liushuai.mp4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br /> 
《巨型小程序的分布式开发与自动化管理》这个分享算是这届FEDAY的全场最佳，主要分享了开发巨型小程序分布式开发和自动化管理的工程框架Weshop的设计思想和实践经验。有点可惜，刚好这个点在会场外在线处理一些工作的事情，没有听到前面部分。回来后看了PPT和今天看了视频，才发现错过了很多，包括前面和分享主体无关的非诚勿扰和刺猬乐队，还有墨攻的故事引入。墨攻很早之前看过，但是基本忘得差不多了，非常巧合的是，第二天去金沙遗址看展，巡回特展正好是《中山国》。《墨攻》虽然是虚构的历史故事，但是里面凉城的范本就是中山国，是一个战略要冲，如果赵国要吞并北边的燕国，中山国就是个必取之地。主人公革离就是墨家派去守护中山国的侠客。嘉宾说自己当时接手这个项目时的处境差不多就像当时的革离，但是很多参会成员好像并没有get到任务艰巨的点。在一个月内设计并实现了Weshop，不仅解决了小程序矩阵体验不好的问题，还开创了一种全新的多团队协作开发小程序的模式，这可谓一壮举。现在几乎所有的APP都有自己的小程序，而且一般都不止一个。就拿KFC的小程序举个例子，你只想点个餐，发现他们肯德基+是个独立的小程序，会员活动也是一个独立的小程序，宅急送还是一个独立的小程序，V金商城也是一个独立的小程序，而且不同个小程序之间的交互跳转无法回退，一圈下来，微信下拉出来的小程序最近浏览记录全被KFC占满了。讲师这次的任务就是解决小程序的这个体验问题，目的是把这些独立的小程序合并成一个。合并看起来不是问题，把各个独立的小程序当做独立模块聚合，当然这里的聚合并不是上面提到的简单地把多个项目放到同一个仓库。那么问题来了，每个模块都是来自不同的供应商，合并之后如何保证每个独立的供应商可以有序地协同开发？似乎是为了解决一个小问题，开始了一个更大的坑啊？类比到我们日常的业务团队中的场景，像YY直播间分很多种模板，比如娱乐模板、约战模板、交友模板、游戏模板等等，不同模板的直播间需要加载各种不同业务的各种模块， 这些都是一个个独立的项目，那要怎么处理各个业务各个模块的配置和切换交互呢？所以这里的合并绝非简单的聚合，Weshop从架构层面利用了“总控和分治”的设计思想，PPT中详细地记载了整个Weshop工程框架每个决策的细节，[PPT可以到这里](https://yylifen.github.io/FEConference/feday5/ppt/%E5%A2%A8%E5%A4%AB%E5%BD%93%E5%85%B3%E2%80%94%E2%80%94%E5%B7%A8%E5%9E%8B%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%88%86%E5%B8%83%E5%BC%8F%E5%BC%80%E5%8F%91%E4%B8%8E%E8%87%AA%E5%8A%A8%E5%8C%96%E7%AE%A1%E7%90%86_%E5%88%98%E5%B8%85.pdf)细细品读，慢慢体会这种设计思想的伟大之处。一般的开发者，很难有如此大局观。和在中国延续了2000多年的中央集权制有着异曲同工之妙，中央集权，分郡治理。深刻反思了自己今年的活动平台项目进行不下去的根本原因，排斥积木，方案缺少对架构和设计模式的思考，自然经不起现实复杂的考验。
<!-- > 本主题的视频可以在这里观看[https://v.qq.com/x/page/j3007ls88f4.html](https://v.qq.com/x/page/j3007ls88f4.html) -->

靡不有初，鲜克有终。凡是过去，皆为序章。革命道路还很长，指尖颤抖，却对未来充满期待。感谢前端圈提供了本次的学习机会，祝福前端圈越来越好！

本次会议除了以上三个主题，还有以下6个主题，需要了解详情的可以直接查阅PPT和观看视频：

- 周俊鹏@腾讯云《从前端到全栈:依托云的Serverless落地实践》[[查阅PPT](https://yylifen.github.io/FEConference/feday5/ppt/Serverless%E8%90%BD%E5%9C%B0%E5%AE%9E%E8%B7%B5_%E5%91%A8%E4%BF%8A%E9%B9%8F.pdf)]  [[观看视频](https://v.qq.com/x/page/q3002q6gj81.html)]
- 吴亮(月影)@360《你不知道的GPU — 前端、图形系统与数据可视化》[[查阅PPT](https://yylifen.github.io/FEConference/feday5/ppt/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84GPU_%E6%9C%88%E5%BD%B1.pdf)]  [[观看视频](https://v.qq.com/x/page/t3002bcali1.html)]
- 谢传贵(贵重)@钉钉《服务亿级企业用户的前端团队演进之路》[[查阅PPT](https://yylifen.github.io/FEConference/feday5/ppt/%E6%9C%8D%E5%8A%A1%E4%BA%BF%E7%BA%A7%E4%BC%81%E4%B8%9A%E7%94%A8%E6%88%B7%E7%9A%84%E5%89%8D%E7%AB%AF%E5%9B%A2%E9%98%9F%E6%BC%94%E8%BF%9B%E4%B9%8B%E8%B7%AF_%E8%B4%B5%E9%87%8D.pdf)]  [[观看视频](https://v.qq.com/x/page/b3007mlwjwe.html)]
- Chris Fritz @ Vue《Visualizations using SVG, Canvas, and WebGL》[[查阅PPT](https://fritz.netlify.com/slides/viz-in-vue/1)] [[观看视频](https://v.qq.com/x/page/e3001fq1eg2.html)]
- Unbug Lee @Hulu《Rewrite with React Hooks》[[查阅PPT](https://yylifen.github.io/FEConference/feday5/ppt/Rewrite%20with%20%20React%20Hooks_unbug.pdf)]  [[观看视频](https://v.qq.com/x/page/a3002bud13q.html)]
- 崔红保@DCloud《基于weex实现的小程序引擎》[[查阅PPT](https://yylifen.github.io/FEConference/feday5/ppt/%E5%9F%BA%E4%BA%8Eweex%E5%AE%9E%E7%8E%B0%E7%9A%84%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%BC%95%E6%93%8E_%E5%B4%94%E7%BA%A2%E4%BF%9D.pdf)]  [[观看视频](https://v.qq.com/x/page/b3002tw9mgi.html)]

> 如有任何疑问，可以直接联系[freedom](https://github.com/yylifen)。


