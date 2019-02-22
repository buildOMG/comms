# Plasma Update 13
[Plasma Update #13 - February 11, 2019](https://www.reddit.com/r/omise_go/comments/appb1w/plasma_update_13_february_11_2019/)

## Research

The big news in the wider world of plasma research was Plasma Group’s first official  [announcement](https://medium.com/plasma-group/deployplasma-dd1cf0b2ab55), accompanying the release of a “toolbox for deploying, transacting on, building with, and developing on plasma chains.” They’ve spent the months since DevconIV putting together a Plasma Prime  [testnet](https://burner.plasma.group/#/)  (for anyone who doesn’t know, Plasma Prime is an iteration on the Plasma Cash design) and tools to help interested developers either interact with or deploy their own plasma chains.

Another cool thing here - in anticipation of a future where many plasma chains coexist, they’ve created a registry, where trusted deployment is verified via a contract so that users can be sure that funds are safe on the chain they’re using.

Plasma Group has published a thorough writeup of the design here:  [https://medium.com/plasma-group/plasma-spec-9d98d0f2fccf](https://medium.com/plasma-group/plasma-spec-9d98d0f2fccf)

## Production

We’re considering our current testnet, which has been running on Rinkeby since December, a release candidate of the OMG Network. We’ve been happy with the network’s performance over the last couple of weeks. We’ve merged the initial updates to  [omg-js](https://github.com/omisego/omg-js)  and have been testing these to ensure that things are going smoothly. We found and fixed a handful of bugs in the process, including addressing exceptions from the watcher when geth crashes, mitigating those crashes, and various improvements in syncing with geth.

Development continues on in-flight exits for ERC-20s and transaction metadata support. We also had some housekeeping to do, updating Elixir and our Exthereum dependency (Exthereum is an Ethereum client written in Elixir). To support testing in this phase, we’ve made it easier to adjust exit period times during deployment.

We are  excited  eager  preparing with zen-like composure to get wider involvement in testing in the coming weeks.
