### OmiseGO AMA 16 - February 17, 2019
[OmiseGO AMA 16 - February 17, 2019](https://www.reddit.com/r/omise_go/comments/apertx/omisego_ama_16_february_17_2019/)

---

**Approximately what are the major tasks that need to be done to go from external testnet to external mainnet?**

While running on testnet we will be logging issues and identifying bottlenecks. We will compile a more comprehensive list after a while when we start properly ramping up to mainnet.

**Have Synthetic Minds been auditing the code as its being written, or are they waiting until the code is complete?**

We will be receiving a report running against MVP from Synthetic Minds within the next week or two. It is a new system so there have been been some technical hurdles. Even though the MVP audit has become less relevant for feature development, we are still looking forward to seeing the results.

**Being a little more faster could enable more iterations and can make all the difference to steer OMG towards success. What is your opinion on this, can OmiseGO attain that speedup in the future and what can OmiseGO do to attain that necessary speedup?**

We do recognize the importance of moving rapidly, but security is our primary concern through our alpha release. As we advance towards beta release, community contributions and inputs will be essential. As we begin to whitelist and onboard developers to test the network, the iterative process will accelerate through community contributions.

**What specific aspect of the soonTM to be released testnet are you specifically interested in getting battle tested? Is there an aspect that has your specific interest when observing how things work?**

1. Usability for developers API. We would like to know if our integration library is simple to grasp and that it’s intuitive for developers to work with them. This involves documentation as well.
2. IRL network load, we want to observe different apps making concurrent transactions and queries on the child chain.
3. We don’t know what we don’t know, so having people interacting with Ari will give us better understanding of where things could fail.

**Will the testnet have various versions like for example the COSMOS testnet?**

Every time somebody commits code to `elixir-omg`, it gets reviewed. Once the code has passed peer review, lots of tests get run on it to make sure it doesn’t break anything. Then services are built up into a container, and deployed on our staging cluster, preserving the childchain blockchain data. We’ve done this over 100 times this month, and somewhere in the region of 500 times this year.
