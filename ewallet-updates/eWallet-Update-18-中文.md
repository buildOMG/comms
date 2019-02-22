### [eWallet 技术更新 2019年2月18日](https://www.reddit.com/r/omise_go/comments/as8yn1/ewallet_update_february_18_2019_the_were_vikings/)

---

在我们讨论细节问题之前，先简要说明一下版本名称问题。我们最初计划把这个引入区块链集成的版本命名为1.2. 尽管在操作速度和顺序没有任何变化，但我们决定尽快将一些功能增加到产品中，所以我们决定小范围内发布一款额外的版本 v1.2。后续版本（能够集成到区块链中）将被命名为 v2.0。请注意，这次名称的调整并没有被记入里程碑或者追踪器中--因为从现在开始，两个版本依旧都能够集成到以太坊中，并且具有 v1.2 附带的功能和任务。请耐心等待，我们会将一切都处理好。

## 已完成事项

以下是[上次更新](https://www.reddit.com/r/omise_go/comments/an5uzh/ewallet_update_february_04_2019_the_is_that_your/) 之后我们攻破的事项。

### 改进:

-   文档和设置更新  [#780](https://github.com/omisego/ewallet/pull/780)
-   升级至 Exlixir 1.8 和 Ecto  [#771](https://github.com/omisego/ewallet/pull/771)
-   发布了 iOS SDK v1.1.1版本，改进二维码扫描器 [#115](https://github.com/omisego/ios-sdk/pull/115)
-   支持 iOS 端的 Point of Sale 交易扫码请求  [#45](https://github.com/omisego/pos-client-ios/pull/45)
    
### 修复漏洞:

- 修复各种 `/*.get` 端点在未提供 `id` 的情况下反馈错误的500的问题。 [#773](https://github.com/omisego/ewallet/pull/773)
- 修复 BALANCE_CACHING_FREQUENCY 的配置迁移问题。 [#777](https://github.com/omisego/ewallet/pull/777)
- 修复刷新之前加载的设置。  [#796](https://github.com/omisego/ewallet/pull/796)
- 修复配置加载顺序。 [#802](https://github.com/omisego/ewallet/pull/802) 
- 修复已经弃用的 `NODE_NAME` 对部署的干扰问题  [#792](https://github.com/omisego/ewallet/pull/792)
   
## 回顾总结

以下任务已经完成，等待钱包团队审查：

### 改进事项

-  区块链钱包模式  [#806](https://github.com/omisego/ewallet/pull/806)
    
## 正在进行的工作

以下是我们正在推进的任务：

-  与以太坊网络进行初始集成
-  导入 ERC-20 加密货币的功能
-  开发新权限系统  [#730](https://github.com/omisego/ewallet/pull/730)
-  修改控制面板  [#779](https://github.com/omisego/ewallet/pull/779)
    
像往常一样，您可以在 eWallet [Waffle board](https://waffle.io/omisego/ewallet) 和我们的 Github [Milestones](https://github.com/omisego/ewallet/milestones) 页面关注我们的进度。
