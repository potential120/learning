# 敏捷方法论

敏捷不是一个新鲜的词汇，10年前就有很多类似的书，请大家详细阅读。

给我的感觉，敏捷方法论就是一组最佳实践。跟截拳道的思想很像，不死板，什么方式好用，那就用它！

务实，灵活。

下面是我对敏捷开发的一些实践，实践证明，这些方法非常有效，能非常好的避免项目死掉：

## 要频繁交付，小步快跑

不要做项目时半年才交付一次。每个项目理想的情况下每天都要交付。下班之前做个部署，把每天的代码都放上去。
app的项目，每天晚上下班前发个包。

这样的话大家都知道你做到什么程度了，哪里做错了没。

好处多多：

- 增强了双方的沟通和新人
- 每天都能看到项目在进步，大家都对项目有信心
- 遇到问题也都能知道原因在哪里
- 需求方有变动的话，可以以最小的代价来实现。

## 能自动化的都自动化

自动化包括：

- 自动化部署
- 自动化的单元测试
- 自动化的集成测试
- 其他自动化的任务。

总之，如果你的工作当中存在很多人肉操作，可以替换成自动化的工具，那么赶紧动手~

## 有必要的测试

软件项目是非常复杂的，很多时候老板问起：“ 这个项目怎么样了？能发布吗？”，我们不应该心里跟老板一个疑问，
然后说，我们手动测试一下。

而是应该很潇洒的运行个测试命令，跑通所有的单元测试，然后告诉老板说：“当前项目有100个测试，跑通了92个，
问题不大，我把剩下的测试修改好，估计今晚就能上线了”。

做的更好的是（目前只看到国外有），在饮水机旁边放个红绿灯，哪个成员提交了代码，会触发持续集成服务器（CI) 自动运行所有的测试，
都通过的话给出绿灯，否则就是红灯，每个人打水的时候都可以看一眼。

国内的话，我周围的人很少有人写单元测试。web有成熟的框架，mobile应该也有，但是恐怕没人用。

## 队伍内部每天都要有例会

一般放在每天早上，开会时大家都站着，关手机，每人简洁明快的说下:

- 昨天做的事，
- 遇到的困难.
- 明确今天要做的事儿。（自己不知道的话问上级）

而上级只需要给大家解决问题和困难，再告诉大家要做的新任务，就可以了。

## 任务划分得当，精确到人

也就是，要把一个任务精确的细分。然后让每个人头上都有任务。并且，开会时要让所有人都知道谁在干什么。

## 整个团队，每个人都是学习狂

每个人每天都在进步，你今天学的慢明天就会被队友赶超，整个团队的学习氛围特别浓。
