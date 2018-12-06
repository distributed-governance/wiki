# Use Case: Software Project

[Patreon](http://www.patreon.com/) is a highly successful service for supporting the creators with $12M monthly payouts for over 100k or creators. With that Patreon has some issues with [censorship](http://www.openlettertopatreon.com/) and [high pledge fees](https://www.reddit.com/r/patreon/comments/7i8pwa/new_pledge_fee_discussion/). Not saying that it’s easily solved, though there’s a place for similar services, like [Stake Tree](https://staketree.com/). So a potential organization with more than 1 creator can do a responsible crowdfunding. It can be a podcast, youtube show, book, research etc.

## Pando \(by Ryhope\)

**Case:** Pando \(software project\) is looking to do crowdfund the further development in a sustainable manner \(unlike usual ICOs\).

**Solution:**

1. Create an DAO fund \(e.g. Pando fund\) with e.g. 10M tokens
2. Setup the tap rule to the Pando operation account/wallet
3. Setup the exchange for ethereum \(other ERC20\) with the bonding curve

### Creating a Pando fund

Creating a separate fund is preferable as there could be additional sources of funding \(e.g. grants, private investments etc\) and their terms would differ, makes sense to govern them differently.

Also it’s more agile, dependent on the pando tokenomics. Pando can create a new token, that doesn’t influence the governance of org itself. Or can transfer some part of the existent token to the fund.

The fund can be created as an Aragon entity \(e.g. Pando Fund\), that will provide access for voting \(in case of changing the tap or instant liquidation\), financial reporting and info on tokenholders.

### Setup the tap rule to the Pando operation account/wallet

The fund initiator creates a payout rule e.g. $20k of value or 10% of ethereum collected will go to the wallet X, which is owned by Pando \(can be a simple wallet, multisig, Aragon DAO\).

### Setup the exchange for ethereum \(other ERC20\) with the bonding curve

Also with a new app for Aragon, the fund can open up the crowdsale/exchange. The fund initiator setups an initial price and pricing model \(flat, gradual or different types of curved\).

Investors can fund directly \(in case of ether\) or via some interface if other coins \(e.g. btc\). At any time they can exchange back with a rate setup by the bonding curve.

