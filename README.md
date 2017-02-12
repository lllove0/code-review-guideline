Code Review 规范说明
---------

# 目的
为了保证软件项目开发的代码实现质量，发现代码中的bug，保证项目组成员的沟通和对项目的了解，在实现功能的前提下，确保代码符合规范，同时保证代码的可读性和可维护性，因此需要进行阶段性Code Review（代码审查）

# Review 前准备工作
1. 确保代码已经通过 JSHint 检查，若出现违反规则的部分，应该针对指标进行说明。
1. 检查代码是否符合 JavaScript 规范 和 AngularJS 最佳实践。
1. 提前一天发出 Code Review 通告。
1. 通告内容包括：项目背景、时间、地点以及 Review 人员。
1. 确保程序可以正确执行，必要的时候需准备设备，进行产品演示。
1. 检查工作清单上的 TODO 和 FIXME 是否都被清楚了，诺没有，应简单说明下。

# Review 进行时
1. Review 前十分钟再次发通告，提醒大家做好准备，处理好手上的工作。
1. 调整 IDE 的字体大小，确保样式清晰。
1. 通过演示产品或者测试案例来说明需求。
1. 先 Review 程序的设计实现思路，然后 Review 设计模，接着 Review 成行的骨干代码，最后 Review 完成的代码。
1. 需要修改的部分，加上 FIXME 或者 TODO 相关注解，在 Webstorm 通过的 TODO 视窗可以快速找到该问题。

# 代码审核清单
1. 程序是否满足业务需求
1. 程序的体系结构和代码设计。例如：单一职责原则、代码复用、潜在的 bugs、错误处理等等。（这需要长期的累积在大脑形成一定的匹配模式）。
1. 程序架构是否满足未来扩充性（确定可能会增加的需求）
1. 程序的执行效率问题
1. 程序的安全问题
1. 程序的易读性

# Review 收尾
1. 当天出 Review 摘要，诺不能及时完成修改，需要标注说明
1. @全体人员 确认，确保正确理解 Reivew 过程中提出的问题以及是否有遗落或者其他意见。
1. 被 @ 的人员，都需要回复确认完毕。

# 参考
* [Code Review 礼仪 PPT ](http://lilin.me/share/CodeReview/index.html)
* [让 Code Review成为一种习惯](http://www.flickering.cn/uncategorized/2014/08/%E8%AE%A9-code-review%E6%88%90%E4%B8%BA%E4%B8%80%E7%A7%8D%E4%B9%A0%E6%83%AF/)
