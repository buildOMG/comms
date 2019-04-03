**Completed**

Here are the main items we’ve knocked out since the [last update](https://www.reddit.com/r/omise_go/comments/b2nyg3/ewallet_update_march_18_2019_the_last_time_i/):

**Improvements:**

-   Get Account members and keys endpoints [#869](https://github.com/omisego/ewallet/pull/869)
    
-   Release iOS SDK [1.2.0.beta.1](https://cocoapods.org/pods/OmiseGO)
    
-   DB connection pool-sharing across database repositories [#853](https://github.com/omisego/ewallet/pull/853)
    
-   Detach client API keys from accounts and owner_app [#870](https://github.com/omisego/ewallet/pull/870)
    
-   Get paginated wallet’s balances endpoints [#822](https://github.com/omisego/ewallet/pull/822)
    
-   Update Android POS Client Wallet dependencies and refactor [#822](https://github.com/omisego/ewallet/pull/822)
    
-   Improve Key page style for Admin Panel [#867](https://github.com/omisego/ewallet/pull/867)
    

**Bug Fixes:**

-   Fixed an issue with the CORS config [#871](https://github.com/omisego/ewallet/pull/871)
    
-   Fixed a random test error in WalletControllerTest [#872](https://github.com/omisego/ewallet/pull/872)
    
-   Fix internal server error on missing filter params [#873](https://github.com/omisego/ewallet/pull/873)
    
-   Skip settings migration if the settings value has not been changed [#874](https://github.com/omisego/ewallet/pull/874)
    
-   Fix bug on Android POS Merchant Wallet [#46](https://github.com/omisego/pos-merchant-android/pull/46)
    

**In review**

These tasks have been completed, pending review by eWallet team admins:

Improvements:

-   Add a few new endpoints to retrieve memberships of accounts/admins/keys [#898](https://github.com/omisego/ewallet/pull/898)
    
-   Normalize ENV values before saving to settings [#875](https://github.com/omisego/ewallet/pull/875)
    
-   Add the ability to assign Key to Assign [#883](https://github.com/omisego/ewallet/pull/883)
    

**In progress**

-   Research and design of Potterhat, a multi-client Ethereum data service [OIP-15](https://github.com/omisego/OIP/issues/15)
    
-   Prevent balance leaks with new permission system [#861](https://github.com/omisego/ewallet/issues/861)
    

As always, you can also follow our progress on the eWallet[ Waffle board](https://waffle.io/omisego/ewallet) and in our GitHub [Milestones](https://github.com/omisego/ewallet/milestone/2) page.

Best,

The eWallet Suite Team
