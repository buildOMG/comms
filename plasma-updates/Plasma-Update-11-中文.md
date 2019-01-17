- [x] Replace english content below with CN translation;
- [x] Send translation to community manager.

***

# Plasma 技术进展更新 11
**[Plasma 技术进展更新 11 - 2019年1月14日](https://www.reddit.com/r/omise_go/comments/ag5btg/plasma_update_11_january_4_2019/)**

欢迎来到 [2019](https://en.wikipedia.org/wiki/2019)!

**产品介绍**
==========
经过不断的反馈和调试升级，我们全新的内部测试网终于在新年尹始之际面世。这版测试网实现了全面监控和持续部署，能够帮助我们更高效地验证和测试新发布的版本。新的测试网配备了遥测（旨在实现性能数据的记录和传输）、记录、以及异常预警检测功能。

当前，我们正在积极地对新的环境、部署工具和[ elixir-omg](https://github.com/omisego/elixir-omg) 的最新改进等方面进行测试。我们在逐渐对当前的环境进行稍加改变，接下来会克隆当前的环境用于合作伙伴进行测试。为了使搭环境的过程具备可复制性，我们花了很大的功夫，也就是说，以后我们能够更快速的搭建起新环境。

对于我们的 MVP 实现  ，我们将底层合约的退出整合到子链和观察站中。此外，我们也实现了新的 API 格式，此 API 将在子链、观测站和 eWallet 中都保持一致，因此兼具了简洁和更便于开发使用。目前我们已经拥有了能够兼容子链、观察站和 eWallet 的 API。接下来我们会升级我们的 JS 数据库来支撑 MVP 和 API 的高效运转。目前，我们即将为实现第一版的 MVP 的最后一步画上句号。一旦完成，我们就会进入大量测试和数据归档阶段。

**研发进度**
========
随着[以太坊君士坦丁堡升级](https://blog.ethereum.org/2019/01/11/ethereum-constantinople-upgrade-announcement/)会在本周稍晚时候进行，我们正考虑如何可以利用君士坦丁堡的 EIP (以太坊改进提案)来改善 OMG 网络。我们正对一系列可能性进行探索，包括：

使用 [EIP1052](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1052.md)：改进智能合约验证速度和能耗，从而更加有效地检查那些正在与根链合约进行交互的合约的任何内容。这对于我们处理取款操作将尤其有用，因为我们将能够轻松地查询到合约是否能够收到我们交易的资金。

使用 [EIP1014](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1014.md)：在退出更为复杂的状态时，可以借助 CREATE2 带来的可扩展性：我们正在研究一些反事实的退出操作，在这些操作中，用户访问某个可以在以太坊上部署的合约，但这个合约实际上不需要进行部署，除非出现什么差错。换句话说，某个状态可以从Plasma链中退出，而无需立即将该状态部署到以太坊上面。

最后，OMG 网络目前依赖于定期向以太坊主网提交区块根。目前我们正在研究通过使用[SSTORE 的全新 gas 定价](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1283.md)来优化当前区块根的存储方式。
