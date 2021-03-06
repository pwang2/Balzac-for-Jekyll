---
layout: post
title: "Agile is not now, nor was ever, Watererfall "
category: articles
author: Uncle Bob from 8thlight
tags: [Agile,中文,译文]
---

*译自http://blog.8thlight.com/uncle-bob/2015/10/16/agile-and-waterfall.html，所有版权和内容所有权归原作者所有*  


我最初读[《Agile is the new waterfall》](https://medium.com/swlh/agile-is-the-new-waterfall-f7baef5d026d)的时候是非常反感的，后来慢慢地怀有敬意，最终又了一些有限的认同。

作者自始至终都阐述着一个合理的论点；为了支持这个论点，他引述了一系列的虚假的论据，最终抹黑了Agile的哲学戒律认为它根本不值得遵守。他好比是把所有的东西都丢进了洗澡水里。

他从“没有正常人鼓吹Waterfall”的断言起文。我不知道作者生活在那个宇宙里，但是在我这个宇宙，还是有一些人在鼓吹Waterfall的。他们正常么？如果有一些法学标准来评估的话。那些认为Agile和Watefall的战斗结束了的人从来没有在一个正确的战壕里对战过。

如果你想要知道作者在这个问题上错的有多离谱的话，Google "Waterfall Software Teams"然后统计下那些试图达到一个平衡二者，或者混淆二者的文章的数目。在过去人们对放弃并不焦虑（译著：理解不了）。

接下来他引用了MacBeth的生活毫无意义的哀歌，使之等同于Agile的许诺。

> 嘈杂暴怒中，无所言表  
> "...full of sound and fury, signifying nothing."

我强烈反对事情的矛头被引到了敏捷宣言，说敏捷宣言本身是本身是毫无意义的噪声的例子。作者完全没有理解，作者也不知道。然而我同意从某种层面比起光热更多（译著：不懂，可能是圣经的段子？）；然而宣称整个运动是无足轻重忽视了软件行业漫长的历史。While I agree that in certain circles there is more heat than light; to claim that the entire movement is insignificant is to ignore a vast swath of software history.

我不打算逐点的驳斥作者。我只能说作者对软件行业的历史知之甚少，即便是他所知道的那点东西，他也搞错了，所以他妄自地对很多对整个行业做出巨大的共享的人不敬，一种对有着巨大正面意义的意识形态的不敬。

他反对那些帮助组织往敏捷迁移的Agile咨询师。他的有些抱怨是站得住脚的，但是绝大多数完全无从立足。改变一个组织是非常困难的。那些试图改变的公司，雇佣他们来帮助实现这种改变是勇气可嘉的。

那些Agile咨询师就比其他人出色么。是的当然。但是买者自慎，概不负责。但诽谤所有努力是完全不负责任的。

## 唯一的论点
作者关于Agile的理解几乎全盘是错的，但是他提出了很好的一点。不幸的事，他提出这点的上下文是错的，以致于从那些刺耳的胡说八道中，你找不到这一点。就是：

> 引入极为有限的流程

是的！当然！

难道每一个软件团队需要所有的敏捷实践么？当然不是。让我们看看这些实践：

1. 规划。长久以来针对怎么给牦牛剃胡子有很多反感。有些team需要比其它team更多的流程。对于有些team，一个简单的需求列表就足够了。对其它，看板可能就足够。然而，还是有一些人需要全套Story，Task，Release，Story points等等。你知道就好，明智的选择。

1. 客户测试。很多客户不希望被这些测试打扰。这是可悲的，因为客户测试明显是发掘需求的最好方式。对那些有了客户参与，通过Cucumber tests, 或者FitNesse tests 来明确需求的Team，你别无他求了。  其它没有这么幸运的Team可能不会从这个实践中受益。我个人的法则是：如果客户既不阅读也不编写测试用例，代码里面那些high level的单元测试就足够了。

1. 小版本发布。 很难想象一个Team不会从这个实践里面受益。让版本发布更小，你让客户等待新特性的时间越久，事情就越容易出错。

1. 团队。同样。很难想象一个team不会从和让开发人员和业务团队紧密合作中受益。当然不是所有的Team都这么幸运。

1. 共同所有。只要我一听到团队里面还存在这段代码是谁管的对话我就认为这个这个团队是失衡的。如果负责这部分代码的人离职，那么整个团队就会面临危机。有很多方式来实现共同所有，但是起码的底线是很简单的－－没有任何一个个人能把整个team扣为人质(译著：把控整个团队的生杀大权)。代码的任何一部分都应该有至少两个人负责，越多越好。

1. 代码标准。这个和共同所有是一脉相承的。代码应该看起来是一个team写的，不应该像是某个个人写的。团队成员应该在代码的表现形式上有认同。这个不是什么高科技。

1. 可持续的步调。这个是一个很简答的想法，软件项目是马拉松，不是短跑。你当然不应该用一个你无法长久持续的步伐前进。Murphy告诉我们任何违反这个法则的团队注定在某个时刻会引火上身。

1. 持续集成。当然有很多团队因为他们的项目太小，设置CI对他们来说可能是多余的。但是对于绝大多数team来说这是正面的。忽略这个即便不是不正常了，也是不道德的。

1. 结对编程。有些团队从这个实践受益良多，有些可能没有。对于后者，一定形式的代码审查是足够的。任何情况下，让每一行代码至少被多双眼睛看过是一个很好的想法。

1. 简单设计。如果说我们从90年代学到什么的话，那就是过度设计形同自杀。设计的水平每个team是不一样的，但是越简越好是一件值得褒奖的事情。

1. 代码重构。难道真会有人争辩说程序员让代码整洁不应该么？难道真有有人否认说持续改善代码质量是错的么？团队可能选择不同程度的重构实践。但是没有任何重构是绝对不可接受的。

1. 测试驱动开发。这个是Agile实践里面最有争议的一条。但是所有的争议都不是针对测试这个词。实际上，所有人都认同单元测试是重要的。我们中的有些人认为他们写测试的顺序是重要的。 有些团队会选择不同的策略。但是那些完全不屑测试的团队注定不会成功的。

## 结语
难道每一个team都需要所有的Agile实践么？当然不是，是不是每个team至少需要其中的一些呢？ 当然是。再次强调，要明智的选择。

我相信，原作者写的这片文章是写给那些正在被[flaccid
scrum](http://martinfowler.com/bliki/FlaccidScrum.html)所困扰并且认为所有的错误都归根与Agile本身的Team的。有一点他是对的。的确有些不称职的咨询公司正在教授一些变味的敏捷实践。从这个角度，他的这些抨击是可以理解的。即便如此，无知是没有借口的。如果你想要质疑一些好的人和好的想法的时候，你最多多做做功课。

