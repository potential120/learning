
会用好各种工具。VIM ,GIT, SVN , LINUX,

方法论： 全都是自动化。 要有单元测试。

键盘是最重要的工具。告别鼠标流。

漫长的编译时间是大坑！

务必想尽一切办法缩短不必要的时间： 编译时间，部署时间，测试时间，合并代码时间，以及对业务的理解时间。（详见 如何与客户做需求分析）

英语要好。不要做汉语文档的奴隶。 英语好可以让你在平庸程序员中脱颖而出。

平庸程序员的特点： 不爱学习，英文差，容易自我满足，水平一般。

要善于表达自己。多写博客，多与非技术的人沟通。不要做闷骚男。

程序员如何处事？ 与人为善。

最终出路：只有30%的人会做跟技术相关的职位。其他70%的出路各有不同。 目前国内技术人员， 私企在33岁以下，外企在40岁左右。

如何带领团队？

西方： 管理学实践

东方： 中国式管理

对外：如何与人沟通需求，

对内：管理项目进度。  分配任务。 协调各个方面。

对于项目，什么样的人是催化剂，什么样的人是项目毒药。

项目必死的几个特点

沟通不够。 需求人员跟开发人员无法见面。常见于异地外包项目。难以见面聊需求。继而产生信任危机。

不要找兼职人员。 软件开发，需要的是频繁沟通。 可能一天碰面20次 ，

面对面是沟通的王道。 面对面 > 电话 > QQ > 邮件  . 所以，重要的问题，永远面对面解决。（记得不要傻呵呵的写表白信了）

成员不要有坏脾气。跟队友吵起来，这个项目不会成功

解决办法：项目的催化剂:  多鼓励，多沟通。有个脾气好的妹子做助理，特别重要。

需求变动频繁。 把做好的东西推翻重做，会极度扼杀士气。解决办法：保持好节奏。好的节奏是：小步快跑，跑之前想好。

一句话需求。

便宜到不可思议的项目，都是陷阱。比如说200块做个手机app.  一般都是外包公司把做好的东西，修改个标题，背景啥的，再扔给你。解决办法：要知道项目的成本。雇佣个程序员要多少钱，做个东西大约要多久。

人员变动频繁。 人永远是最重要的。代码次之 。 一个项目，无论怎么变动，都要留下一个资深者 。 （结对编程是个好办法），或者团队内要有个 这个项目的使用专家。

交付周期太长。 比如说6个月一交付。一年一交付。基本上这样的项目只有最后30%的阶段才能见到演示。而前面4,5个月都看不到成果。很危险。 解决办法：小步快跑，频繁交付。每次只做20% 的功能。忍痛割爱。

如何与人谈项目？

外包行业的市场很混乱，打价格战，受损的是客户。

谈需求三句话： 能不能做？ 多少钱？ 做多久？

价格要透明。

使用简笔画，先画出　操作界面。可视感比　表格和文字要好得多。

对于需求分析师，要善于引导，使用客户可以听懂的比喻，不要使用术语。

要善于引导客户说出需求。

客户都希望项目“明天就交付”.

作为客户，如何提出自己的需求？

不要用“一句话”来描述需求。 比如：我要做个卖啤酒的应用。

不要用“做成跟ＸＸ一样”。

不负责任的外包公司，会回答你：“可以做，肯定没问题”. 但一旦交了钱，就不是那回事了。

项目的估期

时间越短，越容易成功！

第一期只做最重要的功能（没有这个功能，项目就会挂掉）

可以带着缺点上线。

如何选择合适的技术（框架）

没有最好的，只有最合适的。

合适的技术的特点： 1. 要有良好的技术支持(open source )   2. 认同的人多。

未来技术的发展趋势

程序员门槛低。 想做好门槛高。

移动开发将来不会这么累。 看看当今的delphi, c++ 适用的领域。 再远一些，看看那些年的汇编。

Object C 迟早会退休，跟当年的 汇编一样。

很可能会出现一种语言或者框架 统一大部分的平台（例如目前的 hyperloop)

不要与其他程序员争论。多与国外的人接触，学习，如 github, stackoverflow

要持续不断的学习. 不要以为一招可以吃遍天下。

不要为了优化而优化。 lotus 为了节省运行时内存耗费了2年时间，直接导致 office 取代了它的位置。


## 关于程序的一点儿思考

1. 为什么行末尾要加分号？  为什么每个方法结束要放(), {} ?

2. 为什么 声明变量，常量，数组的方法不一样？

```php
var $apple = 'apple';

define('APPLE', 'an apple');

$apples = array('apple1', 'apple2', 'apple3');
```

像ruby, js 那样一个写法多好:

```ruby
$apple = 'apple'

APPLE= 'apple'

$apples = ['apple1', 'apple2']
```

3. 难道是我 MVC框架用多了？ 感觉不用MVC 就 没法干活。特别看不了这样的代码：

```php
<?php

  echo " ... "

?>
```
