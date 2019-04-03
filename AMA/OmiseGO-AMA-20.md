**Regarding the team's reserve OMG tokens for staking. [This address](https://etherscan.io/address/0x2551d2357c8da54b7d330917e0e769d33f1f5b93) holds about 19% of the total supply - 26.77 M at the moment - which should be the team's reserve supply. How many OMG tokens will the team stake on the PoA period and also when public staking goes fully live?**

In PoA, staking is not required, and for public staking we are still working out the details. PoS Phase 2 involving the final selection and definition of PoS is in the pipeline, along with Tesuji Plasma Mainnet, Hybrid PoS and Full PoS. These items may not follow a chronological order of progression as they may be worked upon in tandem.

    
**Are you having any discussions with Coinbase regarding staking pools?**

PoS Design Phase 1 is ongoing and includes assessing other PoS mechanisms and variations. The focus on this has been eased to make way for other features that will generate greater network traffic before fully implementing PoS. With that in mind, we are not currently discussing staking pools with Coinbase.
    
**What are the uses of proof of existence mentioned by Pong in [this video](https://youtu.be/_AGCgLshXBQ) and how does it work (deposits, withdrawals, transfers, storage cost, data availability, etc.) and how is the OMG Network suitable for it rather than layer1?**

Depending on the actual use case, Proof of Existence, could be done the same way it was done in Bitcoin and in Layer 1 Blockchain. For example, if we want to prove integrity of a document using Bitcoin, we can simply hash the data, and store that hash in transaction metadata. Keeping in mind that you would need to pay for transaction fee. The API for that can be found [here](https://omisego.github.io/elixir-omg/docs-ui/?url=informational_api_swagger.json#/Transaction/createTransaction), however it is not yet available on Ari .

The potential benefit of Proof of Existence on Layer 2 would be a significant reduction of transaction fee and higher throughput. Storing hashes of 1000 documents would be a lot more efficient on the OMG network than on Bitcoin.

(Note that the PoE use case is still under exploration)

    
**Will PoA operator be a single node or will it be multiple nodes that arrive at a consensus and if it's multiple nodes, how many nodes and what consensus will be used (Tendermint, etc.)?**

The current design is single node.

    
**How much time do you think is required between beta and mainnet release? If you are unable to provide a precise estimate, would it be weeks or months in your estimation?**

We aren't giving estimates of dates for our releases, but an update to the roadmap is expected in the March newsletter to be delivered today. If you haven't yet subscribed, you can do so [here](https://omisego.network/).
