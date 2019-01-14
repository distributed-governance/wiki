# Continuous Token Model

Curation Markets is a set of protocol designs that aims to reduce information asymmetry through the use of tokenized signals. Tokens are minted as needed through a continuous token model.

## Continuous token model & Bonding curve \[[1](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5), [2](https://blog.relevant.community/how-to-make-bonding-curves-for-continuous-token-models-3784653f8b17), [3](https://medium.com/@justingoro/token-bonding-curves-explained-7a9332198e0e), [4](https://medium.com/thoughtchains/on-single-bonding-curves-for-continuous-token-models-a167f5ffef89)\]

Bonding curves is a core component of Curation Markets. It’s been interesting to see it adopted as the key feature from Curation Markets. It’s the opposite of the current ICO landscape, relying on once-off token sales that do not always provide the best incentives towards the teams and the buyers of the tokens.

The basic premise of curved bonding is as follows:

1. With a specific token \(eg ETH\), you can buy a new token \(eg \#projectToken\) through a smart contract. The ETH is kept as deposit within the smart contract. It’s not disbursed to any particular person or team.
2. The buy price is determined by the current supply of the new token \(\#projectToken\). The buy price is hardcoded according to some algorithmic curve.
3. At any point in time, someone can sell back their \#projectToken into the communal pool and get out an appropriate reward that is set by a sell curve.

### Linear

![](../../.gitbook/assets/image%20%288%29.png)

### Dynamic Token Bonding Curves \[[1](https://tokeneconomy.co/dynamic-token-bonding-curves-41d36e43befa), [2](https://medium.com/thoughtchains/on-single-bonding-curves-for-continuous-token-models-a167f5ffef89)\]

Communities could fund the tokens however they wanted, based on the stage or maturity of their community. For a community just starting out, there might be no funds backing the bonding curves, so tokens would not be worth anything _initially_, which would attract the core believers of what that community is trying to achieve \(these are the people you want in the beginning stages\). As a community matures, it could attract sponsorships, earn revenues from ticket sales, or accept donations. All of these revenue streams, or a portion of that revenue, could go directly into funding the dynamic bonding curve \(i.e. the contract would be _payable_ and accept ETH, but not mint tokens on funding events\).

Therefore the value of the funds underpinning the dynamic bonding curves _grows_ as the community ****grows \(in both size and revenues\), increasing the value of each community member’s token holdings.

![](../../.gitbook/assets/image%20%285%29.png)

  
As the ‘backing’ funds in the dynamic bonding curve increases \(purple\), the economic value of every person’s tokens also increases along their individual bonding curve. At close to t=0, there are no backing funds so the tokens have no economic value. At t=100, there are funds backing the dynamic bonding curve, so all tokens will have economic value, but with different prices depending on the person’s curve.

### The Commitment Curve \[[1](https://medium.com/@mrdavey/incentivising-participation-and-growth-in-communities-using-crypto-economics-5a369dd7f5fc)\]

A common tool for building communities is the ‘[Commitment Curve](https://cmxhub.com/article/the-cmx-community-engagement-cycle/)’. It helps community leaders map the level of commitment a member has and the effort they are willing to expend for the community. For example, a member with a low commitment level may be able to attend an event passively, whereas a member with a very high commitment level may be able to organise a community event in a different city. This is best visualised with a graph:

![](../../.gitbook/assets/image%20%284%29.png)

## Case studies

### Funding \[[1](https://medium.com/thoughtchains/on-bonding-curves-as-funding-mechanisms-a0812b22cc3d), [2](https://medium.com/incentivai/bonding-curve-simulation-using-incentivai-2b2bfe0c6400)\]

However, while these curves can incentivize participation, they are not designed to actually _fund_ projects; the amount bonded is effectively locked in. I can imagine that there are many applications where funding would benefit supporters of a project by enabling development, marketing, or whatnot — so we’re left with a question: _How might we use bonding curves to fund projects?_

### Distribution of IP \[[1](https://tokeneconomy.co/token-bonding-curves-in-practice-3eb904720cb8)\]

We outline how a combination of **Non-Fungible-Tokens \(NFTs\)** and **Token Bonding Curves \(TBCs\)** can create tokenised IP and how this could result in better innovation cycles. We also determine how a potential IP curve could look, as well as the actual utility of the issued tokens. This is rounded off by a practical example of the proposed mechanism in the pharmaceutical industry.

### Utility token \[[1](https://medium.com/collabs-io/can-we-save-the-utility-token-55ef639370cf)\]

We argue that in spite of the bad maths and hangover from the hubris that has gone before, there is merit to the idea of the utility token and that we can find models that better reflect their true value, discourage speculation, and result in an asset that can be programmed to incentivise desirable dynamics within a community built around open source software.

### Trade Popularity & Memes \[[1](https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881)\]

Each topic/meme/idea/goal has an associated token of value that is used to curate information inside it.

### Futarchy \[[1](https://ethresear.ch/t/futarchy-with-bonding-curve-tokens/3449)\]

A [bonding curve token 8](https://medium.com/@justingoro/token-bonding-curves-explained-7a9332198e0e) has a built in price-finding mechanism as well as a reserve pool of funds. This can be used to create a relatively simple and self-contained futarchy mechanism. 

## References:

* [https://medium.com/@mrdavey/dynamic-token-bonding-curves-41d36e43befa](https://medium.com/@mrdavey/dynamic-token-bonding-curves-41d36e43befa)
* [https://medium.com/thoughtchains/on-bonding-curves-as-funding-mechanisms-a0812b22cc3d](https://medium.com/thoughtchains/on-bonding-curves-as-funding-mechanisms-a0812b22cc3d)
* [https://medium.com/collabs-io/can-we-save-the-utility-token-55ef639370cf](https://medium.com/collabs-io/can-we-save-the-utility-token-55ef639370cf)
* [https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881](https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881)
* [https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5)
* [https://medium.com/incentivai/bonding-curve-simulation-using-incentivai-2b2bfe0c6400](https://medium.com/incentivai/bonding-curve-simulation-using-incentivai-2b2bfe0c6400)
* [https://ethresear.ch/t/futarchy-with-bonding-curve-tokens/3449](https://ethresear.ch/t/futarchy-with-bonding-curve-tokens/3449)
* [https://medium.com/thoughtchains/on-single-bonding-curves-for-continuous-token-models-a167f5ffef89](https://medium.com/thoughtchains/on-single-bonding-curves-for-continuous-token-models-a167f5ffef89)
* [https://medium.com/@thibauld/introducing-continuous-organizations-22ad9d1f63b7](https://medium.com/@thibauld/introducing-continuous-organizations-22ad9d1f63b7)
* [https://www.youtube.com/watch?v=ueoAroa8ePA](https://www.youtube.com/watch?v=ueoAroa8ePA)
* [https://medium.com/@Paul.Haas/token-bonding-curves-in-practice-3eb904720cb8](https://medium.com/@Paul.Haas/token-bonding-curves-in-practice-3eb904720cb8)



