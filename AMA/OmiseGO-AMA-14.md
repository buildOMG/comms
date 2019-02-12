# OmiseGO AMA 14
**[OmiseGO AMA 14 - February 3, 2019]()**

***

**Can L1 and L2 Interaction be made seamless or is it in anyway possible for L1 projects (Augur, etc.) to directly utilize the L2 OMG Network (not having to withdraw) by having some mechanism in the OMG plasma contracts, etc?**

In short, yes, interactions between L1 and L2 projects are doable. Many of these contracts are simple enough they'd be able to be deployed directly on the plasma chain if someone felt so moved - although that still leaves funds on the plasma chain segregated from funds on the Ethereum main chain. Another way to have effective compatibility would be with a bridge that allows the two chains to watch and interact with each other - bridges are a different design space but could certainly be interesting to explore at some point. That said, we're focusing first on the payments use case (which we see as the one with by far the most volume potential) before looking into more complicated interactions.

---

**What sort of metrics were gathered from the running of Plasma Dog game (both during DevCon and the current iteration where Hoard is the PoA operator) and what kind of insights or 'Eureka!' moments have the data provided the OmiseGO team with?**

Between Plasma Dog’s launch on October 29 and its hibernation on November 28, we saw:

- 9000 users
- 12,900 sessions
- 23,607 total pageviews

The top 5 countries that users connected from were:

- 1 United States
- 2 Russia
- 3 Thailand
- 4 UK
- 5 Japan

The most valuable insights really came from working closely with Hoard on the integration; their input and our shared experience with using that first MVP version produced feedback that was directly applied in the testnet rebuild.

---

**With eCommerce platforms like Shopify projecting major growth in the coming years as more and more mom and pop stores move online, do you guys plan on marketing and making the tools easy for web merchants to add an OMG wallet/app onto their web stores?**

We’ve discussed possibilities for integration through the Omise plugins for WordPress, Shopify, and Magento. It shouldn’t be too complicated, but it is not top of the queue.

---

**What major developments are needed to switch from PoA to PoS down the road?**

Moving from PoA to PoS doesn't require restructuring of the network itself, it's a matter of designing and implementing a new mechanism for block production. So the development that's needed is a concerted research and engineering effort to take us from general concept to a fleshed-out, implementable design for distributed consensus.

---

**What other milestones need to be reached to deliver OMG Network/Plasma Public Testnet to everyone (except Plasma External testnet and eWallet 1.1)?**

The engineering team has gone through the tasks remaining on the tracker and have decided to move 13, 270 and 369 to a future sprint since they aren’t required for public testnet. The tracker has been [updated.](https://github.com/buildOMG/tracker/issues/28)

This leaves:

(172) Chain operator and wallet provider - minimally conforms to MoreVP semantics

(313) Notify about invalid piggybacking and challenge that (MoreVP)

(314) Make regular and in-flight exits never cross-spend/cross-exit funds (MoreVP)

And then we commence (303) throttled roll-out of external testnet.

Delivering the testnet doesn't require eWallet integration with Ethereum or plasma since these are separate components, not interdependent from a technical standpoint - although the integrated eWallet will make it much easier for a wider base to access the network. The eWallet team has already begun work on v1.2, which will introduce Ethereum integration. You can find the list of remaining v1.2 tasks [here.](https://github.com/buildOMG/tracker/issues/35)
