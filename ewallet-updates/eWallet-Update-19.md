#### Completed

Here are the main items we’ve knocked out since the [last update](https://www.reddit.com/r/omise_go/comments/as8yn1/ewallet_update_february_18_2019_the_were_vikings/):

-   Ethereum wallet generation ([#807](https://github.com/omisego/ewallet/pull/807)). This is the very beginning of wallet integration with the blockchain (!) - it generates a private/public key pair, which can be used to sign transactions and send them to Ethereum. The mechanism for actually sending transactions on the blockchain is a separate task, which we’ll tackle next.
-   Improve configuration validation [#812](https://github.com/omisego/ewallet/pull/812)

#### In review

These tasks have been completed, pending review by wallet team admins:

Improvements

-   Typo & deprecation fixes in EWalletDB and LocalLedgerDB namespaces [#815](https://github.com/omisego/ewallet/pull/815)

#### In progress

Following the previous week’s update on renaming v1.2 to v2.0, we’ve since split our development effort into 2 teams, one responsible for the specific features we intend to release to production ASAP, and the other focusing on blockchain integration.

For **v1.2**, we’re focusing on:

-   Continued working on the permissions & hierarchy removal [#730](https://github.com/omisego/ewallet/pull/730)
-   More descriptive error messages (thanks @jimpeebles!) [#810](https://github.com/omisego/ewallet/pull/810)
-   Admin panel redesign and change to user based [#779](https://github.com/omisego/ewallet/pull/779)

For **v2.0**, we’re focusing on:

-   Next steps in blockchain integration
-   Blockchain wallet schema [#806](https://github.com/omisego/ewallet/pull/806)
-   ERC-20 token import [#808](https://github.com/omisego/ewallet/pull/808)
-   Private key management for blockchain adapter [#689](https://github.com/omisego/ewallet/issues/689)

As always, you can also follow our progress on the eWallet[ Waffle board](https://waffle.io/omisego/ewallet) and in our GitHub [Milestones](https://github.com/omisego/ewallet/milestone/2) page.
