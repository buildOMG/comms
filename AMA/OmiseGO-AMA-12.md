# OmiseGO AMA 12

**[OmiseGO AMA 12 - January 18, 2019](https://www.reddit.com/r/omise_go/comments/af715o/omisego_ama_12_january_18_2019/)**

----------

**How far along are you in the process of fiat on-ramp partnerships? Have some of these been locked down?**

Fiat on/off-ramp is still a work in progress and encompasses a wide spectrum of outlets - from Omise's own payment gateway, to banking partnerships for eWallet users, to dapps that let users spend crypto directly on real-world goods and services.

We don't have any partnerships to talk about right now; truthfully these types of partnerships mostly aren't going to be solidified until a bit further into the testnet phase when it becomes possible to create working prototypes incorporating the full tech stack.

----------

**After viewing both the positivity and negativity of the community’s discussions, what is one idea or concept you wish we understood better?**

It's important to understand that decentralization is not just a trope or a fad; it's at the core of our business model and it's the only way any of this actually works the way it was intended. We talk about this all the time, and people sometimes seem to tire of it. But it's such an integral part of what we're trying to do that not talking about it - and the attending implications - is not really an option.

To quote from AMA #1:

>Decentralization is an ideology that pervades technology, economic systems and mechanism design...We think about this when designing UX for the SDK, Plasma, the decentralized exchange as well as the projects we contribute to through the Ethereum Community Fund.

----------

**When will we have an updated roadmap for 2019/2020?**

The current and upcoming milestones as covered in [this post](https://blog.omisego.network/state-of-the-omg-ecosystem-75260c71a053) still stand. As far as anything specific to 2019, that would fall under the category of putting dates on things which we're [not doing anymore](https://www.reddit.com/r/omise_go/comments/9wi6ed/daily_discussion_november_13_2018/e9moe9x/?context=3). We do have timelines for 2019, but we have decided to keep those internal. You can keep track of what's ahead and watch step-by-step progress on what's being actively worked on [here](https://github.com/buildOMG/tracker/projects/1).

----------

**If transactions are inexpensive what is stopping someone with ulterior motives from flooding/crashing the network at a cheap cost if the system is only able to do 125 TPS? Or what happens if one app/game that is out of OmiseGO's hands connects its users to the network every 10 seconds since it would only take 1250 users of that app at the same time to create 125 TPS a second on the OMG network. I don't need to know how you plan on dealing with this but would like to know that you ARE dealing with this.**

Yes, we are aware of this and are dealing with it. Our main efforts are going toward increasing network capacity such that it can handle whatever comes its way.

There are also potential solutions such as throttling or queuing, in case of a DDOS attack or a functionally similar situation in which poor program design causes the network to be spammed with a volume of transactions that it can't handle - none of these measures are in use right now but it's worth mentioning that the possibility exists.

As a side note - an app connecting its users every 10 seconds would not necessarily equate to creating a transaction for every user every 10 seconds. An app that automatically created a transaction per user every 10 seconds would quickly become unreasonably expensive, no matter how cheap an individual transaction was (which is why we refer to poor program design above). But the fact that it would be a weird thing to do doesn't mean nobody will do it, so we're still taking this type of scenario into consideration.

----------

**What are the biggest challenges, if any, in implementing the MVP design you feel will work best as the result of your ongoing research?**

Some of the biggest challenges have actually come with moving from MVP to MoreVP, which is the design we feel will work best since you don't see it working in normal operations (unlike MVP, which required much more user interaction in order to perform basic operations).

MoreVP is an interactive protocol with multiple steps, considerably more complex than MVP. Looking ahead to launching MoreVP as our first external testnet, accounting for all the edge cases has been a pretty monumental task.
