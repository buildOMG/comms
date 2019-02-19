### [eWallet Update February 04, 2019: the “Is That Your Two Cents Worth, Worth?” edition](https://www.reddit.com/r/omise_go/comments/an5uzh/ewallet_update_february_04_2019_the_is_that_your/)

Here are the main items we’ve knocked out since the  [last update](https://www.reddit.com/r/omise_go/comments/aicztq/ewallet_update_january_21_2019_the_you_either_die/):

### Improvements:

-   Prepare release commands for v1.1  [#733](https://github.com/omisego/ewallet/pull/733)
-   Pin end-to-end tests to v1.1  [#749](https://github.com/omisego/ewallet/pull/749)
-   Merge authentications in one test for all admin api controller tests  [#722](https://github.com/omisego/ewallet/pull/722)
-   Remove sub-application dependencies from the `ewallet` sub-application  [#747](https://github.com/omisego/ewallet/pull/747)
-   Add a reset frequency configuration to the local ledger cached balances  [#738](https://github.com/omisego/ewallet/pull/738)
-   Release version `1.1.0` of the  [iOS SDK](https://github.com/omisego/ios-sdk/tree/1.1.0)
-   Improve readme for admin panel  [#687](https://github.com/omisego/ewallet/pull/687)
-   Planning and finalization of the scope and tasks for the  [1.2 cycle](https://github.com/omisego/ewallet/milestone/4)
    

### Bug fixes:

-   Fix various `/*.get` endpoints returning error 500 when not provided with `id`  [#773](https://github.com/omisego/ewallet/pull/773)
-   Fix incorrect association loading when records are filtered  [#681](https://github.com/omisego/ewallet/pull/681)
-   Fix setup script downloading saving to the wrong file name  [#745](https://github.com/omisego/ewallet/pull/745)
-   Fix assets path in build steps  [#763](https://github.com/omisego/ewallet/pull/763)
-   Fix Docker port expose in new Docker image  [#759](https://github.com/omisego/ewallet/pull/759)
-   Fix typo in AWS config  [#768](https://github.com/omisego/ewallet/pull/768)
-   Fix timezone format for the whole admin panel  [#762](https://github.com/omisego/ewallet/pull/762)
    

## In review

These tasks have been completed, pending review by wallet team admins:

### Improvements

-   Upgrade to Elixir 1.8 and Ecto 3.0  [#771](https://github.com/omisego/ewallet/pull/771)
-   Upgrade eWallet builder docker image to Elixir 1.8  [#1](https://github.com/omisego-images/docker-ewallet/pull/1)
    

## In progress

These are the tasks we’re focusing on right now:

-   Fix balance caching frequency not migrated with the config migration command  [#767](https://github.com/omisego/ewallet/issues/767)
-   Update the Point Of Sale demo iOS app to the latest SDK version  [#44](https://github.com/omisego/pos-client-ios/pull/44)  and  [#28](https://github.com/omisego/pos-merchant-ios/pull/28)
-   Permissions cleanup and improvements  [#730](https://github.com/omisego/ewallet/pull/730)
-   Update admin panel to be account based  [#570](https://github.com/omisego/ewallet/issues/570)
    

## To do

-   Add blockchain toggle settings  [#686](https://github.com/omisego/ewallet/issues/686)
-   Implement blockchain wallet schema  [#690](https://github.com/omisego/ewallet/issues/690)    
-   Add Ethereum wallet generation  [#689](https://github.com/omisego/ewallet/issues/689)

As always, you can also follow our progress on the eWallet [Waffle board](https://waffle.io/omisego/ewallet)  and in our GitHub  [Milestones](https://github.com/omisego/ewallet/milestone/2) page.
