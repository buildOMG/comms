# Plasma Update 11
**[Plasma Update 11 - January 14, 2019](https://www.reddit.com/r/omise_go/comments/ag5btg/plasma_update_11_january_4_2019/)**

Welcome to [2019](https://en.wikipedia.org/wiki/2019)!

Production
==========

We kicked off the new year with a brand new internal testnet, with improvements based on feedback and observations from the initial iteration. This testnet is fully monitored and continuously deployed, making it much quicker for us to test and validate new releases. The new testnet is instrumented with telemetry (essentially, recording and transmission of performance data), logging, and exception reporting. We’re actively testing the new environment, the deployment tooling, and the most recent changes to [elixir-omg](https://github.com/omisego/elixir-omg). We’re changing our environment plans slightly and will be cloning this environment for partner testing. We’ve put in a lot of effort to make building the environment a repeatable process, so the next environment will happen much more quickly.

For our More Viable Plasma implementation, we’ve been integrating the in-flight exit support from the root contracts into the child chain and watcher. We’ve also implemented the new API format, which is consistent across the child chain, watcher, and eWallet so that it’s cleaner and more developer-friendly. We now have a consistent API format across the child chain, watcher, and eWallet. We’ll be updating our JS library to support MoreVP and the new API next. We’re finishing up the last pieces for our initial first implementation of More Viable Plasma. Once done, we’ll be entering a phase of heavy testing and documentation.

Research
========

With the [Constantinople upgrade](https://blog.ethereum.org/2019/01/11/ethereum-constantinople-upgrade-announcement/) coming to Ethereum later this week, we're considering how we might leverage the Constantinople EIP’s (Ethereum Improvement Proposals) to improve the OMG Network. We're exploring a number of possibilities, including:

-   Using [EIP 1052](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1052.md): Smart Contract Verification Speed & Energy to efficiently check the contents of any contracts that our root chain smart contract is interacting with. This is especially desirable when we’re dealing with withdrawals, as we’ll be able to easily check if a contract is able to receive the funds we’re transferring to it.
    
-   Taking advantage of [EIP 1014](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1014.md): CREATE2 Scalability when exiting more complex state: we're looking into counterfactual exits, in which users have access to a smart contract that could be deployed to Ethereum but don't actually need to deploy it unless something goes wrong. In other words, state could be exited from the plasma chain without having to deploy it to Ethereum right away.
    
-   Lastly, the OMG Network relies on periodically committing block roots to Ethereum. We’re looking into whether we can optimize how we’re currently storing block roots using [SSTORE’s new gas pricing](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1283.md).
