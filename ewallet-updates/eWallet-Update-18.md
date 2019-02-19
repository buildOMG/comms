### [eWallet Update February 18, 2019: the “We're Vikings, it's an occupational hazard” edition](https://www.reddit.com/r/omise_go/comments/as8yn1/ewallet_update_february_18_2019_the_were_vikings/)

---

Before we get into the details, a quick note about version names. The version introducing blockchain integration was originally planned to be named 1.2. Although there’s no change in the order or speed of operations, we decided we wanted to get a couple of specific features into production ASAP, so we decided to sneak in an extra release with a very small scope, which will be called v1.2. The following release (with blockchain integration) will be called v2.0. Please note this reshuffling of names is also not yet reflected in the milestones page or tracker - as of this moment both still show Ethereum integration and many accompanying tasks and features under v1.2. Please bear with us until we get everything reorganized!

## Completed

Here are the main items we’ve knocked out since the  [last update](https://www.reddit.com/r/omise_go/comments/an5uzh/ewallet_update_february_04_2019_the_is_that_your/):

### Improvements:

-   Documentation and setup updates for v1.1  [#780](https://github.com/omisego/ewallet/pull/780)
-   Upgrade to Elixir 1.8 and Ecto 3.0  [#771](https://github.com/omisego/ewallet/pull/771)
-   Release v1.1.1 of iOS SDK with some improvements to the QR code scanner  [#115](https://github.com/omisego/ios-sdk/pull/115)
-   Add support for transaction request scanning in Point of Sale iOS app  [#45](https://github.com/omisego/pos-client-ios/pull/45)
    

### Bug fixes:

-   Fix various `/*.get` endpoints returning error 500 when not provided with `id`  [#773](https://github.com/omisego/ewallet/pull/773)
-   Fix missing BALANCE_CACHING_FREQUENCY config migration  [#777](https://github.com/omisego/ewallet/pull/777)
-   Fix settings being loaded before all settings are refreshed.  [#796](https://github.com/omisego/ewallet/pull/796)
-   Fix configurations loading order.  [#802](https://github.com/omisego/ewallet/pull/802) 
-   Fix deprecated `NODE_NAME` interfering with deploy.  [#792](https://github.com/omisego/ewallet/pull/792)
   
## In review

These tasks have been completed, pending review by wallet team admins:

### Improvements

-   Blockchain wallet schema  [#806](https://github.com/omisego/ewallet/pull/806)
    
## In progress

These are the tasks we’re focusing on right now:

-   Initial integration with Ethereum network
-   Ability to import ERC-20 token
-   New permission system  [#730](https://github.com/omisego/ewallet/pull/730)
-   Revamp Admin Panel  [#779](https://github.com/omisego/ewallet/pull/779)
    
As always, you can also follow our progress on the eWallet [Waffle board](https://waffle.io/omisego/ewallet)  and in our GitHub  [Milestones](https://github.com/omisego/ewallet/milestones) page.
