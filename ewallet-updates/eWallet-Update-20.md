After a 4 week sprint, we are now entering our 2 weeks buffer period. We are currently finishing up the last features for the 1.2 release. We’ll then test extensively and work on cleanup/refactoring tasks. We’ve begun work on the blockchain integration but made less progress than we wanted to in this cycle, due to the permissions system being way more complicated than expected. Once this buffer is up, the whole team will be fully focused on Ethereum integration.

Completed
---------

Here are the main items we’ve knocked out since the [last update](https://www.reddit.com/r/omise_go/comments/as8yn1/ewallet_update_february_18_2019_the_were_vikings/):

#### Improvements:

-   Permission listing endpoint [#857](https://github.com/omisego/ewallet/pull/857)
-   Remove 5-association limit from MatchParser [#858](https://github.com/omisego/ewallet/pull/858) Thanks [@enyan94](https://github.com/enyan94)!
-   Allow DB connection pool sharing between repos [#853](https://github.com/omisego/ewallet/pull/853)
-   Gather VM metrics and forward to AppSignal [#830](https://github.com/omisego/ewallet/pull/830) Thanks [@InoMurko](https://github.com/InoMurko)!
-   Big update for admin panel data hierarchy and design [#818](https://github.com/omisego/ewallet/pull/818)
-   Hierarchy removal and advanced permission system [#730](https://github.com/omisego/ewallet/pull/730)
-   Add ability to cancel transaction consumptions [#829](https://github.com/omisego/ewallet/pull/829)
-   Add a system to handle consumption intervals to requests [#825](https://github.com/omisego/ewallet/pull/825)

#### Bug Fixes:

-   Prevent creating new atoms from external sources [#820](https://github.com/omisego/ewallet/pull/820) Thanks [@InoMurko](https://github.com/InoMurko)!

In review
---------

-   Improve design for key management section [#855](https://github.com/omisego/ewallet/pull/855)

In progress
-----------

For **v1.2**, we’re focusing on:

-   Client keys without master account [#839](https://github.com/omisego/ewallet/issues/839)
-   Balance-viewing permission [#861](https://github.com/omisego/ewallet/issues/861)
-   Enforce dialyzer [#739](https://github.com/omisego/ewallet/issues/739)
-   Minor bug fixes [#804](https://github.com/omisego/ewallet/issues/804) [#811](https://github.com/omisego/ewallet/issues/811) [#814](https://github.com/omisego/ewallet/issues/814) [#831](https://github.com/omisego/ewallet/issues/831)

For **v2.0**, we’re focusing on:

-   Persist generated private key in Keychain DB [#863](https://github.com/omisego/ewallet/pull/863)
-   Blockchain wallet schema [#806](https://github.com/omisego/ewallet/pull/806)
-   ERC-20 token import [#808](https://github.com/omisego/ewallet/pull/808)

As always, you can also follow our progress on the eWallet [Waffle board](https://waffle.io/omisego/ewallet) and in our GitHub [Milestones](https://github.com/omisego/ewallet/milestone/2) page.
