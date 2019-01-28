**[OmiseGO AMA 13 - January 27, 2019](https://www.reddit.com/r/omise_go/comments/ahtf13/omisego_ama_13_january_27_2019/)**

**What is one question/area that you think that people aren’t asking/focusing on, but yet critical and fundamental to the future of the OMG Network?**

The root of trust in computing is ultimately found at the hardware layer. We believe that the situation today, where chip design in particular is dictated by a few large companies, probably does not bode well for a cryptographic future. We want to see substantially more open hardware development, particularly around general-purpose and single-purpose chips. This will be important for OMG and every other decentralized project out there as well.

**Can you comment on the progress of the DEX and what work is being done to make it competitive with other leading exchanges in the crypto environment?**

A similar question was answered in [AMA #5](https://www.reddit.com/r/omise_go/comments/9wbfxe/omisego_ama_5_november_12_2018/e9y0q1r):

The DEX is not an exchange in the sense that most leading exchanges are. It's an infrastructure layer to which many venues (including other exchanges can connect (and add liquidity and volume) at the same time. You can read more about the general design and the "restricted custody" model [here](https://blog.omisego.network/omg-dex-update-6245812a7b2d).

**Regarding EIP1014 which has to do with Counterfactual states and contracts, you mentioned about researching it for exits. Is there any chance it can also help with finality?**

In short, not directly. Ethereum is currently a Proof-of-Work blockchain which grants us economic finality; cryptoeconomics can give us ways to reach finality faster than what's possible with PoW. However, EIP1014 specifically won't be much use for increasing the finality time of exits. So far we’ve being looking at it as both a gas reduction technique and as a way for other smart contracts on Ethereum interacting with the OMG Network’s smart contracts to have guarantees about what *will* be deployed, prior to actual deployment. That being said, anything that reduces gas costs allows more transactions to be included; which can in turn help said transactions to be finalized faster.

Keep in mind as well that processing a transaction does not necessarily require finality on the blockchain. A wallet provider could allow a transaction to process instantly and the customer to move on with their life - much the same way that a card transaction will usually process within a second or two, but the charge does not finalize in your account for up to several days (except that the blockchain doesn't require the same complicated system of intermediaries, so we reduce that several days to just the time between blocks).

**What do you think about adding a scripting facility to the eWallet in a future release?**

A very interesting idea with potential. Concerns would be the complexity and assuring security as this would be a vector for attack. We'd normally rely on a robust API to support this level of customization, but this is certainly something worth looking at down the road.

**Watchers don't receive transaction fees, what then are the incentives/motivations for people to run full nodes to provide security to the network?**

We anticipate early users of the OMG Network to be largely eWallet providers, who have a business relationship with their end users and so have an incentive to verify the security of the network on which that relationship depends. It's in their best interest to run a watcher in order to watch for any fraudulent activity related to their own funds. We are also researching other options to incentivize people to run watchers on the network during PoA, but nothing is certain in that area at this point.
