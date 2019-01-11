# 电子钱包技术进展更新 #15 

**[2019年1月7日](https://www.reddit.com/r/omise_go/comments/adqkrk/ewallet_update_january_7_2019_the_as_long_as_you/)**

***

我们尽了最大的努力为假期抽出了一点时间，但随着 1.1.0-pre.0 版本的发布，我们在12月底仍然取得了巨大进展。这是一个先行版本，意味着在成为 1.1 稳定发行版本之前，这个候选发行版本将会进行测试和最终的调整。

**相关链接：**
1.1.0-pre.0版本：
https://github.com/omisego/ewallet/releases/tag/v1.1.0-pre.0

### 已经完成

以下是自上次更新以来我们改进的主要项目:

* “设置”从环境变量中移动到数据库 [\#578](https://github.com/omisego/ewallet/pull/578)
* 向监视系统报告内部服务器错误 [\#585](https://github.com/omisego/ewallet/pull/585)
* 修复随机DB连接. 连接错误 [\#584](https://github.com/omisego/ewallet/pull/584)
* 通过 AppSignal 执行可选的应用程序监控 [\#586](https://github.com/omisego/ewallet/pull/586), [\#608](https://github.com/omisego/ewallet/pull/608)
* 更严格的重定向URL前置代码验证 \(感谢[@jpopxfile](https://github.com/jpopxfile) f报告此问题\) [\#597](https://github.com/omisego/ewallet/pull/597)
* 完成完整的活动日志系统，记录所有的数据变更 [\#560](https://github.com/omisego/ewallet/pull/560)
* 添加端点(endpoints)来检索活动日志 [\#606](https://github.com/omisego/ewallet/pull/606)
* 为交易导出CSV [\#605](https://github.com/omisego/ewallet/pull/605)
* 切换到 Distllery 准备发布 [\#312](https://github.com/omisego/ewallet/pull/312)

### 审核中

这些任务已经被完成，等待钱包团队管理员的审核:

* 为 ActivityLogger 增加测试覆盖率 [\#618](https://github.com/omisego/ewallet/pull/618)

### 行进中

这些是我们正在专注的任务:

* 在管理面板中显示活动日志 [\#617](https://github.com/omisego/ewallet/pull/617)
* 在管理面板中添加导出 CSV 的功能 [\#613](https://github.com/omisego/ewallet/pull/613)
* 增加测试覆盖率 [\#611](https://github.com/omisego/ewallet/issues/611), [\#612](https://github.com/omisego/ewallet/issues/612), [\#614](https://github.com/omisego/ewallet/issues/614), [\#615](https://github.com/omisego/ewallet/issues/615)

### 即将到来:

为了将 v1.1 版本从候选版本引入到生产环境，我们将继续改进和添加，并进行大量的测试。我们从未停止过展望未来，所以我们将在未来几周开会，确定在 v1.1 版本发布之后的下一个版本的方法。

如往常一样，您也可以在我们的电子钱包 [ Waffle board](https://waffle.io/omisego/ewallet) 和 GitHub 里程碑 [Milestones](https://github.com/omisego/ewallet/milestone/2) 界面上关注我们的进展。

祝好，
电子钱包套件团队
