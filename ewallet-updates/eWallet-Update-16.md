
# [eWallet Update 16 - January 21, 2019](https://www.reddit.com/r/omise_go/comments/aicztq/ewallet_update_january_21_2019_the_you_either_die/)

For the past two weeks, we have been focused on testing, debugging and fixing bugs in version 1.1. We’ve also spent time preparing and planning our next work cycle, which will include Ethereum integration.

## Completed

Here are the main items we’ve knocked out since the  [last update](https://www.reddit.com/r/omise_go/comments/adqkrk/ewallet_update_january_7_2019_the_as_long_as_you/):

### Improvements:

-   Allow the retrieval of balances for multiple wallets from local ledger  [#629](https://github.com/omisego/ewallet/pull/629)
    
-   E2E (end to end) storage setup  [#637](https://github.com/omisego/ewallet/pull/637)
    
-   Increase asynchronous tests and test coverage  [#630](https://github.com/omisego/ewallet/pull/630)  [#643](https://github.com/omisego/ewallet/pull/643)
    
-   Add Dialyzer in build steps  [#650](https://github.com/omisego/ewallet/pull/650)
    
-   Refactored URL Dispatcher and server tasks  [#656](https://github.com/omisego/ewallet/pull/656)
    
-   Improved Slack notifications  [#659](https://github.com/omisego/ewallet/pull/659)
    
-   Updated stale documentation  [#662](https://github.com/omisego/ewallet/pull/662)
    
-   Better handling for export failures  [#663](https://github.com/omisego/ewallet/pull/663)
    
-   Refactored config command to prevent double-argv parsing  [#665](https://github.com/omisego/ewallet/pull/665)
    

### Bug fixes:

-   Added missing `redirect_url` parameter for `me.update_email` doc endpoint  [#638](https://github.com/omisego/ewallet/pull/638)
    
-   Fixed {:error, noent} error in EWalletConfig.Storage.LocalTest  [#641](https://github.com/omisego/ewallet/pull/641)
    
-   Handle Goth supervisor properly (start/stop when needed)  [#642](https://github.com/omisego/ewallet/pull/642)
    
-   Fixed json validation for configuration  [#644](https://github.com/omisego/ewallet/pull/644)
    
-   Moved InvalidDateFormatError from EWallet.Errors to Utils.Errors  [#646](https://github.com/omisego/ewallet/pull/646)
    
-   Fixed error 500 when updating an email with an invalid email format  [#648](https://github.com/omisego/ewallet/pull/648)
    
-   Fixed a race condition while testing for simultaneous transfers on an insufficient fund  [#654](https://github.com/omisego/ewallet/pull/654)
    
-   Exclude soft-deleted API keys from /api_key.all  [#658](https://github.com/omisego/ewallet/pull/658)
    
-   Fixed test factory inserting roles with conflicting priorities  [#669](https://github.com/omisego/ewallet/pull/669)
    
-   Minor fix for user email update  [#670](https://github.com/omisego/ewallet/pull/670)
    
-   Corrected some bad grammar and typos within the application  [#671](https://github.com/omisego/ewallet/pull/671)
    
-   Changed Mix.env() to Application.get_env(:ewallet, :env)  [#675](https://github.com/omisego/ewallet/pull/675)
    

## In review

These tasks have been completed, pending review by wallet team admins:

-   Fixed configuration string splitting  [#672](https://github.com/omisego/ewallet/pull/672)
    
-   Cleaned up README  [#674](https://github.com/omisego/ewallet/pull/674)
    
-   Better wallet endpoints and retrieval in the admin panel  [#679](https://github.com/omisego/ewallet/pull/679)
    

## In progress

These are the tasks we’re focusing on right now:

-   Planning and design for the initial blockchain features!
    

We’re dealing with some last minute bugs, but the final release of 1.1 is well under way. We’re keeping it as a release candidate until we’re satisfied we are putting out a fully-tested version of the eWallet.

As always, you can also follow our progress on the eWallet [Waffle board](https://waffle.io/omisego/ewallet)  and in our GitHub  [Milestones](https://github.com/omisego/ewallet/milestone/2) page.
