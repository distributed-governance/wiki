# Public Network \(L1\) Governance Case Studies

Comparison?

## Bitcoin

There is a wide range of views regarding what the purpose of Bitcoin’s governance should be. What outcomes should governance optimize for?

* Matt Corallo [argues](http://bluematt.bitcoin.ninja/2017/02/28/bitcoin-trustlessness/) that trustlessness is the most important property of Bitcoin. Matt defines trustlessness as “the ability to use Bitcoin without trusting anything but the open-source software you run”. Without the property of trustlessness, all other positive outcomes are jeopardized.
* Daniel Krawisz [argues](https://nakamotoinstitute.org/mempool/who-controls-bitcoin/) that maximizing the value of a bitcoin is what governance de facto optimizes for. Daniel states that “the general rule about Bitcoin upgrades \[…\] is that upgrades which increase Bitcoin’s value will be adopted and those which do not will not.”

In the context of Bitcoin’s governance, these two views mirror the classic divide between [deontological](https://en.wikipedia.org/wiki/Deontological_ethics) and [consequentialist](https://en.wikipedia.org/wiki/Consequentialism) ethics respectively. I favor Matt’s deontological approach of focusing on trustlessness. Throughout monetary history, from ancient coin producers to modern central banks, trusting others to produce money has resulted in abuse of that trust. Compromising on trustlessness could help the Bitcoin price find a local maximum, at the expense of finding a much higher global maximum.Furthermore, there is no evidence that Bitcoin’s price has been correlated with upgrades to the Bitcoin protocol. Perhaps Bitcoin’s fundamental value is affected by upgrades, but Bitcoin is so illiquid and volatile that the price does not reliably reflect fundamental value. If we can’t observe the consequences of an upgrade on Bitcoin’s value, the consequentialist approach seems inadequate.

### Major Events:

* Segwit + new york agreement

### References:

* [https://medium.com/@pierre\_rochard/bitcoin-governance-37e86299470f](https://medium.com/@pierre_rochard/bitcoin-governance-37e86299470f)

## Ethereum

### What to govern?

* emergency fixes
* protocol upgrades \(PoS, Sharding, EVM, Opcode gas pricing, …\)
* Max

### Parties involved

| Party | On-chain verification / measurement |
| :--- | :--- |
| Miners | block.coinbase |
| Stakers / Ether owners | address.balance  |
| Users | msg.gas \* tx.gasPrice |
| Speculators/Traders \(daily price discovery\) | – |
| Client developers | identifiable through special key pair |
| Dapp developers | msg.sender of contract creation \* usage \(tx fees paid / ether balance\) |
| Foundation | foundation multisig |
| Researchers | – |
| Regulators | – |

\(c\) Christoph Jentzsch. [Source](https://edcon.io/2017/ppt/two/Christoph%20Jentzsch_Ethereum%20Governance%20Mechanism_EDCON.pdf)



![Source: https://github.com/ethereum/wiki/wiki/Governance-compendium](../.gitbook/assets/image%20%286%29.png)

###  Mechanisms

* Be-Weekly Ethereum Core Dev Calls
* EthResearch Forum Discussions
* Miners's right to vote on max gas limit
* EthMagicians initiative
* EIP0 Conf

### Major Events:

* The DAO fork
* EIP 999
* Miners fee reduction

### References:

* [Strange loop proposal](https://ethereum-magicians.org/t/strange-loop-an-ethereum-governance-framework-proposal/268)
* [https://www.ethnews.com/eip0-and-ethereums-challenges-for-collective-governance](https://www.ethnews.com/eip0-and-ethereums-challenges-for-collective-governance)
* EIP 0 conf
  * [https://www.youtube.com/watch?v=Xft6xlNtqkg](https://www.youtube.com/watch?v=Xft6xlNtqkg)
  * [https://www.youtube.com/watch?v=LcBqypKbYMA](https://www.youtube.com/watch?v=LcBqypKbYMA)
* [https://vitalik.ca/general/2017/12/17/voting.html](https://vitalik.ca/general/2017/12/17/voting.html)

## EOS

The launch of the EOS mainnet has not gone without problems, but how bad were these problems, and could they have been prevented?

It started off with stolen accounts, as a result of scams and theft, leaving 7 individuals without access to their EOS on the mainnet. The top 21 block producers at the time unanimously voted to freeze the accounts the affected accounts, without an official order from ECAF. This polarized the community, resulting in plenty of people questioning the integrity and level of decentralization of EOS governance. After the freeze of the accounts the block producers filed a dispute against themselves, in order to have their actions reviewed by ECAF. The actions were deemed just by an \(emergency\) arbitrator, and the freeze of 20 more accounts was ordered, sparking even more controversy, as no evidence that these accounts were in any way compromised was presented to the community.

This was followed by the sudden appearance of block producers not complying with the the block producer agreement. This raised another question: if a block producer is not even capable of hosting a website before registering themselves as a block producer, how did they get so many votes? Many of these block producers are still active today, seemingly untouchable, as long as the whales behind these block producers continue supporting them. The appearance of these block producers, and the inability to punish them for their non-compliance, has further divided the EOS community, with many prominent people in the community expressing their dissatisfaction with the current state of EOS.

There have also been various discussions about ‘vote buying’.

  
Digital Constitution + Vote Delegation

### Major Events:

* [Emergency Measure of Protection](https://cryptoslate.com/eos-governance-divides-crypto-community/) \(June 18\)

### References:

* [https://medium.com/coinmonks/a-deep-dive-into-eos-governance-49e892eeb4a2](https://medium.com/coinmonks/a-deep-dive-into-eos-governance-49e892eeb4a2)
* [https://cryptoslate.com/eos-governance-divides-crypto-community/](https://cryptoslate.com/eos-governance-divides-crypto-community/)

## Tezos

In [Tezos](https://www.tezos.com/), [anyone can submit a change to the governance structure](https://www.quora.com/How-is-Tezos-different-from-Ethereum?share=d5c26090&srid=OAAh) in the form of a code update. An on-chain vote occurs, and if passed, the update makes its way on to a test network. After a period of time on the test network, a confirmation vote occurs, at which point the change goes live on the main network. They call this concept a “self-amending ledger”.

### References:

* [https://medium.com/tezos/towards-futarchy-in-tezos-54a7b8926967](https://medium.com/tezos/towards-futarchy-in-tezos-54a7b8926967)
* [https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74](https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74)

## DFINITY

One step further would be a system which allows on-chain votes to the rules of the system like Tezos and direct, retroactive changes to the ledger itself. In other words, if something happens that tokenholders do not like \(ex: a hack, a marketplace selling drugs\), they can roll back or edit the ledger in addition to the rules of governance themselves. DFINITY, an in-development blockchain, is taking this approach. Proponents of this system point to events like hard fork caused by The DAO hack and the recent $150m Parity multi-sig bug and suggest such events would be much smoother if everyone could just vote to undo them. On the flip side, this system allows direct censorship and peoples’ tokens to be forcibly taken. As we saw with Ethereum’s hard fork to revert The DAO hack, this is possible with existing blockchains, but requires higher friction through off-chain coordination and hard forking instead of on-chain coordination with no forking. \[[https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74](https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74)\]

## Decred

* [Decred Investment Thesis](https://www.placeholder.vc/blog/2018/5/12/decred-investment-thesis) by Placeholder VC

## Lisk

Vote Delegation

## Polkadot

Digital Constitution

* [https://github.com/paritytech/polkadot/wiki/Governance](https://github.com/paritytech/polkadot/wiki/Governance)

## References:

* [https://blog.0xproject.com/blockchain-governance-7ff89e6ec383](https://blog.0xproject.com/blockchain-governance-7ff89e6ec383)
* [https://medium.com/polkadot-network/why-on-chain-governance-82ecf28f314c](https://medium.com/polkadot-network/why-on-chain-governance-82ecf28f314c)

