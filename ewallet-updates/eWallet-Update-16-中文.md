# [eWallet 第16次升级-2019年1月21日](https://www.reddit.com/r/omise_go/comments/aicztq/ewallet_update_january_21_2019_the_you_either_die/)

在过去的两周里，我们的工作重心是测试、调试以及修复1.1版本的漏洞。同时，我们也在花时间准备和筹划下一阶段的工作计划，其中包括了与以太坊的集成。

## 已经完成

上次升级之后，我们完成了以下 [主要事项](https://www.reddit.com/r/omise_go/comments/adqkrk/ewallet_update_january_7_2019_the_as_long_as_you/):

### 改进项:

-   允许从本地账本中检索多个钱包的余额  [#629](https://github.com/omisego/ewallet/pull/629)
    
-    E2E（端到端）的存储设置  [#637](https://github.com/omisego/ewallet/pull/637)
    
-   增加异步测试和测试覆盖率  [#630](https://github.com/omisego/ewallet/pull/630)  [#643](https://github.com/omisego/ewallet/pull/643)
    
-   在生成步骤环节增加 Dialyzer  [#650](https://github.com/omisego/ewallet/pull/650)
    
-   重构 URL 调度程序和服务器的任务  [#656](https://github.com/omisego/ewallet/pull/656)
    
-   改进 Slack 通知机制  [#659](https://github.com/omisego/ewallet/pull/659)
    
-   更新过时文档  [#662](https://github.com/omisego/ewallet/pull/662)
    
-   更好的处理导出故障 [#663](https://github.com/omisego/ewallet/pull/663)
    
-   重构配置命令以预防双参数析  [#665](https://github.com/omisego/ewallet/pull/665)
    
### 我们修复了以下 Bug:

-   为 me.update_email 文档端点添加了之前缺少的 redirect_url 参数  [#638](https://github.com/omisego/ewallet/pull/638)
    
-  解决了在 EWalletConfig.Storage.Local 测试中出现的 {:error, noent} 错误  [#641](https://github.com/omisego/ewallet/pull/641)
    
-  正确处理 Goth 监管问题（在需要时启动/停止）  [#642](https://github.com/omisego/ewallet/pull/642)
    
-   修复了配置中的 json 验证问题  [#644](https://github.com/omisego/ewallet/pull/644)
    
-  将 InvalidDateFormatError 从 eWallet 移到 Utils.Errors  [#646](https://github.com/omisego/ewallet/pull/646)
    
-   修复了使用无效电子邮件格式更新电子邮件时出现的500错误 [#648](https://github.com/omisego/ewallet/pull/648)
    
-   修复了在资金不足的条件下进行同步转账测试时出现的一个竞争状况  [#654](https://github.com/omisego/ewallet/pull/654)
    
-   移除 /api_key.all 中的 API 密钥  [#658](https://github.com/omisego/ewallet/pull/658)
    
-   解决插件测试过程中的优先级冲突问题  [#669](https://github.com/omisego/ewallet/pull/669)
    
-   针对用户邮箱进行了微调  [#670](https://github.com/omisego/ewallet/pull/670)
    
-   修改了应用程序的语法错误和拼写错误  [#671](https://github.com/omisego/ewallet/pull/671)
    
-   将 Mix.env() 修改为 Application.get_env(:ewallet, :env)  [#675](https://github.com/omisego/ewallet/pull/675)
    

## 处于审查阶段的事项：

下列任务已经完成，等待钱包团队审查：

-   解决了配置字符串拆分问题 [#672](https://github.com/omisego/ewallet/pull/672)
    
-   清除 README 自述文件  [#674](https://github.com/omisego/ewallet/pull/674)
    
-   更好的钱包端点和管理面板检索体验  [#679](https://github.com/omisego/ewallet/pull/679)
    
## 以下事项处于推进过程中：

以下是我们的工作重心：

-   初始区块链的功能规划和设计！

目前我们正在修复最后几个小bug，但1.1版本将会如期发布。我们会将它作为备选的发布版本，同时我们会持续改进以推出一个经过全面测试的 eWallet 版本。

一如既往，你可以在 [Waffle board](https://waffle.io/omisego/ewallet)  和我们的GitHub  [Milestones](https://github.com/omisego/ewallet/milestone/2) 上了解我们的项目进度。
