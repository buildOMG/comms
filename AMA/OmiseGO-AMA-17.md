# OmiseGO AMA 17

**[OmiseGO AMA #17 - February 24, 2019](https://www.reddit.com/r/omise_go/comments/arw0et/omisego_ama_17_february_24_2019/)**

**How many transactions per second can the current test net at [https://quest.ari.omg.network](https://quest.ari.omg.network/) handle?**

We are still in active development, which means that code, libraries and such can change, resulting in variations in TPS values. We'll provide these numbers once we're confident that they are accurate. For what it's worth, we're happy with what we've seen so far. We'll be looking for your help to load-test the network in a more coordinated way in the near future - the best way to know for sure what the network can handle is to throw everything we can at it and see how it holds up!

**What are your thoughts on competing eWallet providers such as True Money, Alipay and Line. Does OmiseGO eWallet differentiate itself from these competitors?**

True Money, Alipay and Line aren't really competitors to OMG; they're the kinds of wallet providers who could benefit from what we're building. Those types of providers often use many rails concurrently (their own networks, settlement networks like Visa and Mastercard, ACH, connections with other payments platforms such as ApplePay). OMG would give them access to a new customer base and the potential to reduce costs and increase speed and security.

**Are staking pools getting any kind of resource allocation (development, research, etc) at the moment or is it too early? My concern is having a really great network built but having really sketchy non user-friendly UI/UX for interaction like pretty much all blockchain related nodes and networks.**

It's really too early to give any answer about this, although we agree it's important and we're certainly interested to see how staking pool research develops across the space over the coming months and years.

**Just using [this](https://medium.com/tokyo-fintech/rakuten-pay-app-gets-a-facelift-bfa16d35550f) as an example as it's quite alinged, not suggesting an affiliation. As it stands, could the eWallet suite be used to build an app like this? Allowing them (Rakuten in this case) to use all their existing payment channels, and manage their rewards points, etc, but with the option to utilise the OMG Network (to whatever degree they choose) when it goes live?**
> 
Yep! In the case of Rakuten or a similarly developed platform that would probably mean using the APIs or integration libraries rather than building out a full app using the eWallet suite. But as you said, the goal is to give potential implementers the optionality to use as much or as little of that tooling as they need in order to take advantage of OMG's capabilities.

**At what stage (or what are the remaining items left on the GitHub task tracker) will the OMG team be confident enough to start the Proof of Authority (PoA) phase to begin processing real transactions and perform the token burn process?**

The current testnet is already working on Proof of Authority. Proof of Authority (PoA) is just a type of consensus algorithm where a designated operator is responsible for validating transactions, and is basically the default state unless some other consensus mechanism is put into place. We've chosen to use PoA in our testnet and initial mainnet releases, to get the network up and running while we continue to work on implementing Proof of Stake.

As for when fees will be collected and burned: that process begins with mainnet launch. Following the public testnet, we'll release a production version of the PoA OMG Network onto the Ethereum mainnet, where it will process real transactions with real money. This is the part where we'll use the fees we collect as the single operator to buy and burn OMG. Prior to this, any "fees" collected on public testnet would not actually be worth anything.
