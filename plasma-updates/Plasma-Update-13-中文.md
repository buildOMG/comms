# Plasma进展更新 #13
[Plasma进展更新 #13 -2019年2月11日](https://www.reddit.com/r/omise_go/comments/appb1w/plasma_update_13_february_11_2019/)

## 研发进度

我们在 Plasma 研究领域近期的大事件是，伴随着“在 Plasma 链上部署、交易、构建和开发专用工具箱”的发布，Plasma 团队发布了首个官方[公告]。(https://medium.com/plasma-group/deployplasma-dd1cf0b2ab55)。自 Devcon4 会议之后，团队成员一直致力于 Plasma Prime [测试网] (https://burner.plasma.group/#/) 以及其他一些工具的组件工作，以便帮助感兴趣的开发者与 Plasma 链进行交互，或者部署他们自己的 Plasma 链。（备注：Plasma Prime 是 Plasma Cash 设计架构的升级版本）

另外一件很酷的事情是--预计到未来会出现多条 Plasma 链共存的情况，开发团队设计了一个注册表 (registry)，其中受信任的部署会通过一个合约来进行验证，这样用户就能够确保资金在他们使用的那条链上是安全的。

[点击链接](https://medium.com/plasma-group/plasma-spec-9d98d0f2fccf)，查看 Plasma 团队公布的完整设计报告。

## 产品

我们一直在观测我们当前的测试网，该测试网从去年12月就一直在 Rinkeby 上运行，我们把它看作 OMG 网络的候选版本。在过去的几周中，该测试网络的表现令人满意。我们已经开始进行对 [omg-js] (https://github.com/omisego/omg-js) 的首次更新，并且一直测试更新情况，以保证一切能够顺利推进。我们在这个过程中能够发现并修复了一些问题，包括 geth 崩溃时观察站的处理异常情况，减少这类崩溃状况，此外，在与 geth 同步方面也做了改进。

针对 ERC-20 的 in-flight 退出和支持交易元数据的开发工作还在继续进行。
继续开发 ERC-20 的 in-flight 接口和交易元数据支持。我们还需要做一些日常管理相关的事情，例如更新 Elixir 和我们的 Exthereum 附属项目（Exthereum 是一个用 Elixir 编写的以太坊客户端）。为了支持这个阶段的测试工作，我们在部署时，实现了更容易地对退出周期进行调整。

在接下来几周中，我们将怀揣喜悦而又平和的心情准备迎接更大范围的测试工作。
